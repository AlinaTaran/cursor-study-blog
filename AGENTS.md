# StudySprint Agent Guide

Monorepo: React 19 + Vite + **Ant Design 6** client, Express 5 + MongoDB server.

## Conventions

Rules live in `.cursor/rules/`. Key points:

- Start **server** before **client**
- API source of truth: `server/src/routes/`
- UI: **Ant Design 6** — theme in `client/src/App.jsx`
- Reuse existing helpers, hooks, and constants

## Quick Start

```bash
cd server && cp .env.example .env && npm install && npm run setup && npm run server
cd client && cp .env.example .env && npm install && npm run dev
```

See README files for credentials and seed data.
