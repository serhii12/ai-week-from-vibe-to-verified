# Prerequisites

- [Node.js](https://nodejs.org/) v22+
- [pnpm](https://pnpm.io/) v9+ (enabled via `corepack enable`)
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) CLI installed
- A Claude Pro or Max subscription

## Getting Started

```bash
# Install dependencies
pnpm install

# Run database migrations and seed data
pnpm db:migrate
pnpm db:seed

# Start the dev server
pnpm dev
```

The app will be running at `http://localhost:5173`.

## Scripts

| Command                     | Description                            |
| --------------------------- | -------------------------------------- |
| `pnpm dev`                  | Start the development server           |
| `pnpm build`                | Build for production                   |
| `pnpm test`                 | Run tests with Vitest                  |
| `pnpm test:watch`           | Run tests in watch mode                |
| `pnpm typecheck`            | Type-check the project                 |
| `pnpm db:migrate`           | Run database migrations                |
| `pnpm db:seed`              | Seed the database                      |
| `pnpm reset <commit>`       | Reset your repo to a lesson checkpoint |
| `pnpm cherry-pick <commit>` | Cherry-pick a lesson's solution        |
