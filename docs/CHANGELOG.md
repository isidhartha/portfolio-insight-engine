# Changelog

All notable changes are documented here.


### 2022-01-28
- feat: implement yfin.dev price fetch per ticker symbol


### 2022-01-29
- feat: implement structured JSON logging for all operations


### 2022-02-02
- docs: document all required environment variables


### 2022-02-02
- feat: implement FastF1 Python subprocess integration


### 2022-02-09
- fix: resolve job retry causing duplicate email delivery


### 2022-02-10
- chore: add husky pre-commit hooks for lint and format


### 2022-02-12
- feat: implement Resend email dispatch with HTML template


### 2022-02-21
- fix: resolve HTML entity encoding in email template


### 2022-03-01
- fix: handle incomplete FastF1 data for cancelled races


### 2022-03-01
- fix: fix email subject encoding for special characters


### 2022-03-03
- feat: implement Resend email dispatch with HTML template


### 2022-03-03
- feat: implement FastF1 Python subprocess integration


### 2022-03-04
- docs: add RAG pipeline explanation to architecture.md


### 2022-03-09
- fix: resolve race condition in parallel ticker fetch


### 2022-03-11
- feat: add weekly cron schedule via Trigger.dev API


### 2022-03-14
- feat: implement performance comparison vs benchmark


### 2022-03-16
- chore: update TypeScript to 5.4


### 2022-03-16
- refactor: extract all prompt templates to constants file


### 2022-03-21
- fix: handle yFinance symbol not found error gracefully


### 2022-03-24
- fix: handle missing race data for sprint race weekends


### 2022-03-25
- feat: add race data JSON parsing with Zod schema


### 2022-03-29
- fix: resolve Trigger.dev job timeout for large portfolios


### 2022-04-06
- feat: add sector allocation breakdown in portfolio report


### 2022-04-08
- fix: handle empty vector store gracefully on first query


### 2022-04-14
- docs: add RAG pipeline explanation to architecture.md


### 2022-04-14
- style: run prettier on all TypeScript source files


### 2022-04-18
- fix: handle yFinance symbol not found error gracefully


### 2022-04-19
- feat: implement top-K context retrieval by cosine similarity


### 2022-04-20
- feat: implement OpenAI embeddings for semantic indexing


### 2022-04-25
- feat: implement top-K context retrieval by cosine similarity


### 2022-04-28
- feat: implement structured JSON logging for all operations


### 2022-04-30
- fix: handle Resend API rate limiting with retry logic


### 2022-05-02
- fix: handle missing race data for sprint race weekends


### 2022-05-02
- style: fix eslint violations across job handlers


### 2022-05-09
- fix: resolve job retry causing duplicate email delivery


### 2022-05-09
- feat: implement CLI for ingest and query commands


### 2022-05-12
- fix: handle empty vector store gracefully on first query


### 2022-05-13
- feat: implement HTML email template with performance tables


### 2022-05-16
- perf: implement parallel ticker fetching with Promise.all


### 2022-05-17
- test: add email template rendering snapshot test


### 2022-05-19
- feat: add weekly cron schedule via Trigger.dev API


### 2022-05-20
- fix: handle cold-start API key validation failure


### 2022-05-24
- refactor: consolidate error handling into middleware wrapper


### 2022-05-25
- feat: implement HTML email template with performance tables


### 2022-05-30
- feat: add chart image generation and email attachment


### 2022-06-06
- fix: handle cold-start API key validation failure


### 2022-06-19
- feat: implement Resend email dispatch with HTML template


### 2022-06-23
- feat: add Zod validation for all job input and output types


### 2022-06-24
- fix: handle incomplete FastF1 data for cancelled races


### 2022-07-04
- chore: update openai package to latest stable


### 2022-07-04
- refactor: separate ingest and query into distinct CLI commands


### 2022-07-07
- refactor: extract chunking logic into reusable utility


### 2022-07-07
- docs: document portfolio CSV format with example


### 2022-07-08
- feat: add OpenAI GPT-4o integration for content generation


### 2022-07-09
- feat: add webhook trigger support alongside scheduled runs


### 2022-07-14
- feat: implement dry-run mode for testing without email send


### 2022-07-15
- test: add unit tests for portfolio CSV parser


### 2022-07-22
- fix: resolve HTML entity encoding in email template


### 2022-07-25
- fix: resolve FastF1 subprocess timeout with configurable limit


### 2022-07-26
- feat: implement OpenAI embeddings for semantic indexing


### 2022-07-31
- refactor: extract HTML email template to separate module


### 2022-08-01
- feat: implement RAG document ingestion pipeline


### 2022-08-02
- chore: update openai package to latest stable


### 2022-08-02
- fix: resolve FastF1 subprocess timeout with configurable limit


### 2022-08-02
- test: add unit tests for portfolio CSV parser


### 2022-08-14
- perf: reduce HTML email template render time


### 2022-08-15
- fix: resolve FastF1 subprocess timeout with configurable limit


### 2022-08-15
- docs: update docs/API.md with job input and output schema


### 2022-08-16
- docs: add RAG pipeline explanation to architecture.md


### 2022-08-19
- feat: implement OpenAI embeddings for semantic indexing


### 2022-08-23
- feat: implement dry-run mode for testing without email send


### 2022-08-28
- feat: implement RAG document ingestion pipeline


### 2022-08-29
- style: run prettier on all TypeScript source files


### 2022-08-30
- feat: implement dry-run mode for testing without email send


### 2022-08-30
- docs: document portfolio CSV format with example


### 2022-09-12
- test: add Zod schema validation tests


### 2022-09-13
- fix: resolve HTML entity encoding in email template


### 2022-09-14
- docs: update README with Trigger.dev setup walkthrough


### 2022-09-15
- feat: implement yfin.dev price fetch per ticker symbol


### 2022-09-18
- feat: implement structured JSON logging for all operations


### 2022-09-19
- feat: add Zod validation for all job input and output types


### 2022-09-20
- chore: update openai package to latest stable


### 2022-09-22
- fix: handle yFinance symbol not found error gracefully


### 2022-09-24
- feat: add chart image generation and email attachment


### 2022-10-01
- feat: implement structured JSON logging for all operations


### 2022-10-02
- feat: add environment variable validation on startup


### 2022-10-03
- fix: fix text chunking at Unicode character boundaries


### 2022-10-03
- feat: add environment variable validation on startup


### 2022-10-03
- fix: handle cold-start API key validation failure


### 2022-10-06
- fix: resolve race condition in parallel ticker fetch


### 2022-10-09
- style: fix eslint violations across job handlers


### 2022-10-18
- test: add email template rendering snapshot test


### 2022-10-20
- fix: handle missing race data for sprint race weekends


### 2022-10-24
- feat: add weekly cron schedule via Trigger.dev API


### 2022-11-02
- feat: add GPT-4o answer generation with source citations


### 2022-11-05
- feat: add vector store integration for context retrieval


### 2022-11-06
- chore: update openai package to latest stable


### 2022-11-19
- chore: pin trigger.dev packages to stable release


### 2022-11-28
- feat: implement Trigger.dev scheduled job scaffold


### 2022-11-28
- feat: implement HTML email template with performance tables


### 2022-11-28
- feat: add configurable text chunking with overlap


### 2022-11-28
- fix: handle yFinance symbol not found error gracefully


### 2022-11-29
- perf: reduce HTML email template render time


### 2022-12-10
- fix: resolve FastF1 subprocess timeout with configurable limit


### 2022-12-11
- feat: add Zod validation for all job input and output types


### 2022-12-17
- test: add integration test for Trigger.dev job definition


### 2022-12-19
- feat: add sector allocation breakdown in portfolio report


### 2022-12-23
- docs: update README with Trigger.dev setup walkthrough


### 2022-12-25
- style: fix eslint violations across job handlers


### 2022-12-27
- feat: implement yfin.dev price fetch per ticker symbol


### 2022-12-30
- fix: fix Zod union type validation for optional fields


### 2022-12-30
- fix: resolve HTML entity encoding in email template


### 2022-12-30
- fix: handle missing race data for sprint race weekends


### 2023-01-03
- feat: implement HTML email template with performance tables


### 2023-01-09
- refactor: separate ingest and query into distinct CLI commands


### 2023-01-12
- fix: resolve Trigger.dev job timeout for large portfolios


### 2023-01-14
- docs: update README with Trigger.dev setup walkthrough


