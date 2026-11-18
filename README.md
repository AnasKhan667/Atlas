# Atlas

Multi-tenant AI knowledge platform: upload documents, chat with them, get cited answers.

## Status
Under active development. Currently on **Step 0: repo setup**.

## Planned stack
- **Frontend:** React, Vite, TypeScript, Redux Toolkit + Saga, Ant Design, Tailwind
- **Backend:** Node.js, Express, PostgreSQL + pgvector, pg-boss
- **AI:** Ollama / Gemini / Groq (swappable provider layer)

## Repo layout
- `backend/`  Express API and workers
- `frontend/` React app
- `docs/`     architecture notes and decisions

## Getting started
Coming in Step 1.

## Workflow
- `main`: always deployable
- `develop`: integration branch
- `feature/*`: one branch per task, merged into `develop` through a pull request
- Commits follow [Conventional Commits](https://www.conventionalcommits.org/)