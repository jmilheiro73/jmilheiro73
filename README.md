# Hi, I'm Juan 👋

AI Engineer in Rio de Janeiro. I build LLM systems for lawyers and keep them running.

Right now I'm the sole engineer behind an AI-driven legal platform: an LLM reads the court gazette every morning, classifies each publication, and a human confirms it in one click. Every decision is logged. The LLM never calculates a deadline — that's deterministic code.

### Things I've shipped

**Portal GX AI** — court gazette triage with structured output. Prompts are validated against the firm's expert-labeled answer key before any change goes live.

**PJe Agent** — logs into the labor court portal with a digital certificate and 2FA, pulls case updates, summarizes and ranks them by severity. Circuit breaker, throttling, heartbeat, cloud watchdog. Reverse-engineered the undocumented API to turn a full scan into a handful of requests.

**Baqui** — B2B agtech SaaS. Multi-tenant Postgres with Row Level Security; the permission matrix is tested against the database before every migration.

**Central 4CAP** — weekly production board for a creative studio.

**Pentest TechStore** — a deliberately vulnerable app I built to break, plus the report (OWASP Top 10:2025, CVSS 3.1).

### Stack

Python · TypeScript · React / React Native · PostgreSQL / Supabase · Claude API · LangChain / LangGraph · Playwright · Vercel

Security is not a separate skill for me — RBAC, row-level isolation, mTLS and JWT show up in everything above.

### Elsewhere

[LinkedIn](https://linkedin.com/in/juan-milheiro-b95a8631b) · jotta4bjj@gmail.com
