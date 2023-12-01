# Contributing to Portfolio Insight Engine

Thank you for your interest in contributing. This guide covers everything you need to get up and running and submit a quality pull request.

---

## Getting Started

1. **Fork** the repository on GitHub and clone your fork locally:

   ```bash
   git clone https://github.com/your-username/portfolio-insight-engine.git
   cd portfolio-insight-engine
   ```

2. **Create a feature branch** from `main`. Use a short, descriptive name:

   ```bash
   git checkout -b feat/your-feature-name
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Copy the environment file** and fill in your keys:

   ```bash
   cp .env.example .env
   ```

5. **Start the development server:**

   ```bash
   npm run dev
   ```

   This starts the TypeScript compiler in watch mode alongside the Trigger.dev local runner so you can test job changes in real time.

---

## Code Style

This project uses **Prettier** for formatting and **ESLint** for linting. Both run automatically on pre-commit via lint-staged (if configured), but you can also run them manually:

```bash
# Format all files
npm run format

# Lint and auto-fix where possible
npm run lint
```

Please ensure your code passes both checks before opening a pull request. PRs with linting errors will not be merged.

---

## Tests

Tests are written with **Jest** or **Vitest** (see `package.json` for the active runner). Run the full suite with:

```bash
npm test
```

- Add tests for any new logic in `src/`.
- Aim to keep coverage above 80 % for changed files.
- Mock external API calls (yfin.dev, OpenAI, Resend) — do not make live network requests in tests.

---

## Submitting a Pull Request

1. Push your branch to your fork:

   ```bash
   git push origin feat/your-feature-name
   ```

2. Open a pull request against `main` on the upstream repository.

3. Fill in the PR template — describe what you changed and why.

4. A maintainer will review your PR. Please be responsive to feedback and update your branch as needed.

---

## Reporting Issues

Open a GitHub Issue with a clear title and description. Include steps to reproduce, expected behaviour, and actual behaviour. Attach any relevant logs or screenshots.
