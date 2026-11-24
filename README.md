<div align="center">

# Wijoyo Raharjo (Joy)

**Software Engineer: Backend, Full-Stack, AI/LLM Integration** · Bandung, Indonesia (UTC+7) · open to remote

<img src="assets/badge-languages.svg" alt="Language-agnostic: TypeScript, C#, Go, Python, Java" />
<img src="assets/badge-ai.svg" alt="AI: LLM embeddings, pgvector, MCP" />

<a href="https://wiormiw-porto.wwijoyo2.workers.dev/"><img src="assets/badge-portfolio.svg" alt="Portfolio" /></a>
<a href="https://wiormiw-porto.wwijoyo2.workers.dev/Wijoyo_Raharjo_CV.pdf"><img src="assets/badge-cv.svg" alt="CV (PDF)" /></a>
<a href="https://www.linkedin.com/in/wiormiw"><img src="assets/badge-linkedin.svg" alt="LinkedIn" /></a>
<a href="mailto:wwijoyo2@gmail.com"><img src="assets/badge-email.svg" alt="Email" /></a>

</div>

---

## About

I pick the stack the system needs. I have shipped production code in **TypeScript, C#/.NET, Go, Python and
Java**. I like to turn slow manual processes, deep hierarchies
and large data flows into reliable, well-structured services.

- 🏦 **Banking systems**: full-time for banks since 2025. Today I connect a bank's back office to its **core
  banking system**, on flows of **hundreds of millions to billions of IDR**.
- 🤖 **AI and LLMs**: provider-agnostic embedding pipelines (Gemini, OpenAI, self-hosted Ollama), pgvector
  semantic search, MCP tool servers for LLM agents, and daily work with AI coding agents (Claude Code).
- 🧱 **Infrastructure**: air-gapped Linux production with replicated PostgreSQL, Redis and MinIO.

## Experience

| Role | Company | What was at stake |
| :-- | :-- | :-- |
| .NET Developer · 2026 to now | PT Talent Placement Consulting Indonesia | **Production banking.** Back office to core banking, flows of IDR hundreds of millions to billions. Automated 5+ manual processes and counting (160+ staff-hours a month saved), including a rule-driven case processor (one input file, many outputs set by layered case types and day-based rules) and per-product, per-merchant debit reports (processed, unprocessed, successful and failed amounts, with discounts). A background service streams 6M+ rows of balance roll-forwards. |
| Backend Developer · 2025 to 2026 | PT Fan Integrasi Teknologi | **A bank's internal employee platform** (3,000+ staff): internal mail, approvals and task delegation. Cut critical API response times by 80%; ran their air-gapped RHEL production servers. Found repmgr was the failover bottleneck (role switching only, no consensus, IP failover or load balancing) and designed the move to Patroni + etcd behind HAProxy. |
| Backend Developer (Intern) · 2023 | PT Len Industri (Persero), DEFEND ID | **Defense command-and-control map system.** Led 6 interns across three microservices; WebSocket sensor streaming (20% faster transfers). |
| IoT Developer (Intern) · 2019 | PT Adhim Aju Sejahtera | Industrial control panels: role-based access, ~30% faster queries. |

## Featured

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [**Akashic Records**](https://github.com/wiormiw/akashic-records) | Community platform of genre "realms" (TCG, cosplay, idol, VTuber) with jobs, events and a marketplace. **LLM embeddings** from Gemini, OpenAI or self-hosted Ollama check each post against its realm's learned centroid, and a model outage never blocks posting. Transactional outbox, fine-grained authorization, 670+ tests. | TypeScript, Bun, Hono, PostgreSQL + pgvector, OpenFGA, RabbitMQ, SvelteKit |
| [**LazyCVE**](https://github.com/wiormiw/lazy-cve) | Local-first vulnerability intelligence. An **MCP server** gives LLM agents CVE lookup, search and similar-advisory tools; **local embeddings** power pgvector semantic search with no paid API; calibrated XGBoost forecasts 30-day exploitation. | Python, FastAPI, pgvector, sentence-transformers, XGBoost, FastMCP, Bun, Hono, Nuxt |
| [**Old Country**](https://github.com/wiormiw/old-country) | Self-hosted music service for my offline library and YouTube Music: **one API, two native clients**. Desktop and Android builds are on GitHub Releases. | .NET 11 / C# 15 API, desktop (Tauri), Kotlin Android (Jetpack Compose) |
| [**SuggestMe 2.0**](https://github.com/wiormiw/suggestme-2.0) | Food recommendations by mood with the **Gemini API**, plus real-time ratings and comments. | TypeScript, ElysiaJS, Drizzle, PostgreSQL, React |
| [**wiormiw-porto**](https://wiormiw-porto.wwijoyo2.workers.dev/) | My portfolio, themed as a Pokemon battle log. | Astro, React, Tailwind, Cloudflare |
| [**GrowBaksAPI**](https://github.com/wiormiw/GrowBaksAPI) | E-commerce REST API for small businesses (UMKM). | Go, Fiber, PostgreSQL |

## Stack

**Languages**

<img src="assets/icons-languages.svg" alt="TypeScript, C#, Python, Go, Java, Kotlin" />

**Backend and data**

<img src="assets/icons-backend.svg" alt="Node.js, Bun, .NET, FastAPI, Express, PostgreSQL, Redis, RabbitMQ, Kafka" />

**Frontend and infrastructure**

<img src="assets/icons-frontend.svg" alt="React, Next.js, Svelte, Nuxt, Astro, Docker, NGINX, Linux, Cloudflare" />

**AI / LLM**: embeddings (Gemini, OpenAI, Ollama, sentence-transformers), pgvector semantic search, MCP servers
(FastMCP), XGBoost and scikit-learn, AI coding agents (Claude Code).

**Data and messaging**: PostgreSQL (replication, recursive CTEs, trigram and full-text search, PostGIS,
pgvector), SQL Server, Redis, Elasticsearch, RabbitMQ, Kafka, BullMQ, Celery; transactional outbox and
idempotent consumers.

**Systems**: RHEL, CentOS Stream, Rocky, Debian, Ubuntu, Arch and Windows Server; HAProxy, repmgr,
Patroni, etcd, GitHub Actions, OpenTelemetry.

---

<div align="center">

<sub>Based in Bandung · Indonesian and English · UTC+7 · open to remote roles</sub>

</div>
