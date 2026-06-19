# git-test-api

A barebones Node.js API service used to test a PR code-review service.

## Requirements

- Node.js >= 22 (developed on v24)
- pnpm

## Setup

```bash
pnpm install
```

## Run

```bash
pnpm start    # start the server
pnpm dev      # start with file watching
```

The server listens on `PORT` (default `3000`).

## Endpoints

- `GET /health` — returns `{ "status": "ok" }`
