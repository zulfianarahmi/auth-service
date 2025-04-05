# Auth Service

Authentication service for our APAC Solution Challenge app.

## Stack

- Flutter (Backend & Frontend)
- PostgreSQL (via Neon)
- DevOps: Docker, GitHub Actions, Cloud Run

## Folder & File Structure

```text
auth-service/
├── .github/
│   └── workflows/
│       └── ci.yml           # CI/CD workflow (GitHub Actions) for auto build & deploy
├── .env.example             # Example env file – define DB_URL, JWT_SECRET, etc.
├── Dockerfile               # Docker config to containerize the backend
├── README.md                # This file – project overview & instructions
└── notes/
    └── devops-plan.md       # DevOps notes, sprint checklist, and planning docs
```

## Setup

```bash

git clone <repo-url>
cd auth-service

cp .env.example .env
```
