# jdev-lab-api

The NestJS REST API powering the lab section of [j-dev.online](https://j-dev.online). Built progressively — each technology is integrated as it's learned, with every milestone adding a real capability to the running system.

The end goal is a **RAG-powered chat assistant**: a small chat window where visitors can ask questions about me as a developer, with answers grounded in my CV and project data stored in PostgreSQL. In production, inference runs via a hosted LLM API (provider TBD after completing the unlearn.dev RAG track).

---

## Stack

| Layer | Technology | Status |
|---|---|---|
| API framework | NestJS + TypeScript | v0.1 ✓ |
| Database + ORM | PostgreSQL + Prisma | v0.2 |
| Containerisation | Docker + Compose | v0.3 |
| RAG knowledge base | Knowledge module | v0.4 |
| Chat endpoint | Hosted LLM API (TBD) | v0.5 |

---

## Running Locally

```bash
pnpm install
pnpm run start:dev
```

API runs on `http://localhost:3000` by default.

---

## Milestones

- `v0.1` — NestJS foundations: modules, controllers, services, routing ✓
- `v0.2` — PostgreSQL + Prisma: projects module with full CRUD
- `v0.3` — Docker: containerised API + Postgres via Compose
- `v0.4` — Knowledge module: ingest CV and project data into Postgres as RAG chunks
- `v0.5` — Chat module: retrieve relevant chunks, pass to hosted LLM, return answer

---

*Jonathan Kaonga — [j-dev.online](https://j-dev.online)*
