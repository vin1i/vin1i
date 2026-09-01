# Marcos Vinícius

**Software Engineer** — Full-Stack & Applied AI
TypeScript · Node.js/NestJS · React/Next.js · PHP/Laravel · Vue

Teresina, PI, Brazil · Open to remote

[![Portfolio](https://img.shields.io/badge/Portfolio-1A1A1A?style=for-the-badge&logo=vercel&logoColor=white)](https://www.vinideveloper.com.br/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mvini21/)
[![Email](https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marcosvinidev342@gmail.com)

---

### About

Software engineer with 3 years building **multi-tenant B2B SaaS** at scale. I cover the full cycle — data modeling, backend, real-time and frontend — with a bias toward reliability, application security and privacy by design.

Currently the top individual contributor on **BeeCRM**, an omnichannel CRM serving **108 client companies** and **88M+ messages** (peaks of 141k/day), where I shipped a voice-calling module from scratch on the Meta WhatsApp Cloud API and fixed **28 pentest vulnerabilities** before writing the security gate that became the project standard.

---

### What I work on

- **Multi-tenant SaaS at scale** — isolated databases, cross-tenant admin tooling, white-label architecture
- **Applied AI in product** — multi-provider architecture (OpenAI / Anthropic) swappable by config, SSE streaming, per-tenant cost accounting and rate limiting, automatic LGPD retention
- **Real-time systems** — WebSocket, WebRTC + Coturn, SDP signaling, live notifications
- **Queues & async processing** — BullMQ workers, high-volume exports, background pipelines
- **Application security** — IDOR, mass assignment, CSV/formula injection, HMAC webhooks with anti-replay, RBAC, LGPD
- **Performance** — N+1 elimination, query optimization, caching and request deduplication on active bases of millions of records

I treat AI as a dependency that can fail: deterministic fallback, usage accounting and per-tenant limits. A provider outage degrades a feature — it never takes down the screen.

---

### Selected work

**BeeLabs — BeeCRM** · omnichannel CRM & contact center (WhatsApp, Instagram, Messenger, RCS, SMS)
`Vue 3` `Laravel + Octane/Swoole` `MySQL` `Redis` `WebRTC`
Top individual contributor (2,261 of 8,445 commits). Built **Bee Voice** — voice calls over the Meta WhatsApp Cloud API with cascading routing, browser recording and signed S3 upload — for 1,500+ agents. Built the central admin panel consolidating 114 tenants across 5 database servers with AES-256-GCM credential encryption. Architected the per-card AI assistant and the AI call transcription/summary pipeline with per-tenant cost ceilings.

**Folheto Digital** · conversational marketing SaaS on WhatsApp, 150k+ leads
`Next.js 15` `React 19` `TypeScript` `BullMQ` `Socket.IO`
Lead frontend contributor (~69% of commits) across 14 domain modules. Cut average WhatsApp campaign cost by **R$300k (~US$60k) per supermarket chain** by replacing broadcast flows with digital flyer distribution. Led the i18n rollout of a live product to 3 locales over 7 planned phases and 18 namespaces. Built the reporting/BI module with async XLSX/CSV exports on queue.

**SIM — Sistemas Integrados de Melhoria** · occupational health & safety SaaS
`Turborepo` `Next.js 16` `NestJS 11` `Prisma 7` `PostgreSQL 16`
~25% of repository history, end to end. Designed the platform's table design system on TanStack Table (URL-synced faceted filters, batch actions, mobile card mode, dependency-free CSV export), adopted across 13 screens. Shipped white-labeling end to end — palette derivation with WCAG AA contrast validation, SSR theming without FOUC, brand propagation to 6 surfaces. Implemented frontend LGPD compliance (PII scrubbing in Sentry, consent-gated analytics) and recovered a months-stale Playwright e2e suite.

---

### Tech

| | |
|---|---|
| **Languages** | TypeScript, JavaScript, PHP 8, SQL |
| **Backend** | Node.js, NestJS, Laravel (Octane/Swoole), REST, WebSockets, Prisma, Eloquent, BullMQ, JWT/Passport, Zod, event-driven architecture |
| **Frontend** | React 19, Next.js (App Router, RSC, SSR), Vue 3, Tailwind CSS, shadcn/ui, Radix UI, TanStack Query/Table, Zustand, React Hook Form |
| **AI** | OpenAI API, Anthropic Claude API, provider abstraction, SSE streaming, per-tenant cost control, chatbot execution engines, agent orchestration (Claude Code, MCP) |
| **Data & Messaging** | PostgreSQL, MySQL, MongoDB, Redis, BullMQ, RabbitMQ, Socket.IO, Soketi, WebRTC + Coturn |
| **Cloud & DevOps** | Docker, Nginx, Caddy, AWS S3, Cloudflare R2, MinIO, Vercel, Linux VPS, Turborepo, pnpm workspaces, GitHub Actions |
| **Integrations** | Meta WhatsApp Cloud API, Evolution API, Baileys, Instagram/Messenger, RCS, SMS, Stripe, HMAC webhooks |
| **Quality & Security** | Vitest, Jest, PHPUnit, Playwright, Testing Library, Sentry, PostHog, pentest remediation, RBAC, LGPD, WCAG AA |

---

### Education

**Systems Analysis and Development** — Universidade Maurício de Nassau, 2025
Portuguese (native) · English (intermediate)

---

<img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vin1i&theme=github_dark&layout=compact&custom_title=Most%20used&langs_count=8" />
