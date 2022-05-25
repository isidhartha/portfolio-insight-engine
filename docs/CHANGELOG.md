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


