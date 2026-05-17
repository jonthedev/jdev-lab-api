# jdev-lab-api

Personal backend built to develop and demonstrate full-stack product engineering skills. This is a living project — each technology is integrated progressively as it's learned, rather than scaffolded all at once.

Part of the [JDev Online](https://j-dev.online) lab: backend architecture, data modeling, and AI-ready APIs.

---

## What This Is

A NestJS REST API that grows with the stack. The goal is to build a real, working backend from first principles — understanding every layer rather than generating it.

**Stack (progressive)**

| Layer | Technology | Status |
|---|---|---|
| API framework | NestJS + TypeScript | In progress |
| Database | PostgreSQL | Pending |
| Containerisation | Docker + Compose | Pending |
| Analytics | DuckDB | Pending |
| AI integration | Ollama (local) | Pending |

---

## Running Locally

```bash
pnpm install
pnpm run start:dev
```

API runs on `http://localhost:3000` by default.

---

## Project Structure

```
src/
├── main.ts               # Entry point
├── app.module.ts         # Root module
├── app.controller.ts     # Root route handler
└── app.service.ts        # Root service
```

Modules will be added to `src/` as each new technology is integrated.

---

## Milestones

- `v0.1` — NestJS foundations: modules, controllers, services, routing
- `v0.2` — PostgreSQL: database module, TypeORM, migrations
- `v0.3` — Docker: containerised API + Postgres via Compose
- `v0.4` — DuckDB: analytics module alongside Postgres
- `v0.5` — Ollama: local AI integration via REST

---

*Jonathan Kaonga — [j-dev.online](https://j-dev.online)*
