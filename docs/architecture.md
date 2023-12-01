# Architecture — Portfolio Insight Engine

## Overview

A serverless job pipeline that runs on a weekly schedule to produce an AI-powered stock portfolio report delivered by email.

## Components

### Trigger.dev Scheduled Job
The core job is registered with Trigger.dev and fires every Monday morning. Trigger.dev provides reliable execution with automatic retries, dead-letter logging, and a dashboard for monitoring job runs.

### Data Fetch Layer
The job fetches current prices and portfolio metadata from yfin.dev's REST API. Each holding in the user's CSV is looked up individually. Sector, market cap, and 52-week high/low data is included.

### AI Analysis (GPT-4o)
Structured portfolio data is formatted into a system prompt describing the analysis task (performance vs benchmark, diversification, concentration risk). GPT-4o returns a natural language assessment with specific actionable suggestions.

### Email Dispatch (Resend)
A responsive HTML email template wraps the AI narrative, a holdings performance table, and a simple chart image. The email is dispatched via Resend's API with the configured sender domain.

## Data Flow

```
Portfolio CSV → Trigger.dev Job → yfin.dev API (per ticker)
                                        ↓
                              Price + Metadata Object
                                        ↓
                               GPT-4o Analysis
                                        ↓
                              HTML Email Template
                                        ↓
                               Resend → Inbox
```

## Scheduling

The job runs weekly using Trigger.dev's `schedules.cron` API. The cron expression is configurable via the job definition file. Trigger.dev handles timezone normalisation and missed-run recovery.
