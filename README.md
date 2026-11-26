# Hi, I'm Nilish 👋

Software developer in Melbourne working mainly in **Python** and **TypeScript**.
I build backend APIs, data pipelines, search tools and small AI-powered apps, and I
deploy and run them myself on Linux with Docker.

🔎 **Open to:** backend, full-stack and AI/LLM engineering roles in Melbourne or remote (AU).

## 🛠️ Tech I use

- **Languages:** Python · TypeScript · JavaScript · SQL
- **Backend:** FastAPI · SQLAlchemy · Alembic · pytest · ReportLab
- **Frontend:** Next.js · React
- **Data:** PostgreSQL · SQLite · BM25 / hybrid search
- **AI:** Claude API · OpenAI API · LLM tool-calling · retrieval (RAG) · embeddings · MCP
- **Ops:** Docker Compose · nginx · systemd · Linux VPS · GitHub Actions
- **Microsoft:** Power Apps Component Framework (PCF) · Dynamics 365

## 🚀 Selected projects

| Project | What it is | Stack |
|---|---|---|
| **CareHub** ([live demo](https://carehub.imisstech.com.au)) | Open-source document hub for aged-care admin teams, built on Paperless-ngx. Role-based access across four staff groups, OCR search, and AI chat (Claude) that only answers from documents the signed-in user may view. Fictional demo facility; idempotent setup script with stable import keys and 87 tests in CI. Demo login on request | Paperless-ngx · Claude API · Python · Docker · nginx |
| [**melbourne-tech-jobs**](https://github.com/Nilish1994/melbourne-tech-jobs) | Live dashboard of the Melbourne tech job market: a daily Adzuna collector with a quota ledger and advisory locks, deterministic skill extraction, and analytics for skill demand, trends, salaries and locations | FastAPI · PostgreSQL · Next.js · Docker |
| [**ask-my-docs**](https://github.com/Nilish1994/ask-my-docs) | Documentation Q&A with Claude: answers cite the exact docs passage. Hybrid BM25 + embedding retrieval, measured by a 42-question eval in CI (hit@5 0.93 vs 0.86 for BM25 alone) | Claude API · FastAPI · Next.js · RAG |
| [**JobPilot**](https://github.com/Nilish1994/job-match-agent) ([live](https://jobpilot.imisstech.com.au)) | Multi-user AI job-search copilot (invite-only beta): users upload a CV, Claude scores new jobs against their profile weekly, and Telegram approvals produce tailored CV and cover-letter PDFs. Encrypted profiles, per-user isolation, budget guards, 45 tests; it never applies on its own | Claude API · Python · Telegram · SQLite |
| [**ai-playground**](https://github.com/Nilish1994/ai-playground) | Backend for a personal AI assistant: OpenAI Responses API, async Postgres, dependency injection, structured logging and a tool registry built for extension | FastAPI · SQLAlchemy · Docker |
| [**crypto-market-research-engine**](https://github.com/Nilish1994/crypto-market-research-engine) | Collects Binance futures data every 5 minutes, detects support/resistance levels, logs outcomes and writes daily/weekly scorecards. It runs unattended under systemd, has pytest suites, and live trading is deliberately disabled | Python · SQLite · systemd |
| **Facilities services website** | Production Next.js marketing site for a Melbourne facilities business, with suburb landing pages, visit tracking, and a Docker/nginx deploy | Next.js · TypeScript · Docker |
| **Staff allocation PDF generator** | Internal tool that turns staffing-sheet CSV exports into A3 daily allocation PDFs using documented allocation rules | FastAPI · ReportLab · Next.js · PostgreSQL |
| **Roster pattern viewer** | Imports aged-care roster workbooks and analyses fortnightly staff, location and shift patterns | FastAPI · PostgreSQL · React |
| [**retrieval-lab**](https://github.com/Nilish1994/retrieval-lab) | BM25 search engine written from scratch, with optional stemming and a CLI | Python · pytest |

<sub>Some projects are private because they contain client or business data. I'm happy to walk through the code in an interview.</sub>

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/nilish-aluthwatta-a8579a192)
