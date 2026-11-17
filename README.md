<div align="center">

# Wijoyo Raharjo (Joy)

**Backend Engineer (TypeScript, .NET)** · Bandung, Indonesia (UTC+7) · open to remote

<img src="https://img.shields.io/badge/Core-TypeScript_%7C_.NET_%2B_C%23_%7C_PostgreSQL-FFD700?style=for-the-badge&labelColor=000000" alt="Core stacks: TypeScript, .NET with C#, PostgreSQL" />
<img src="https://img.shields.io/badge/CachyOS-daily_driver-00E5CE?style=for-the-badge&logo=cachyos&logoColor=black" alt="CachyOS daily driver" />

<a href="https://wiormiw-porto.wwijoyo2.workers.dev/"><img src="https://img.shields.io/badge/Portfolio-wiormiw--porto-DC2626?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/wiormiw"><img src="https://img.shields.io/badge/LinkedIn-wiormiw-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:wwijoyo2@gmail.com"><img src="https://img.shields.io/badge/Email-wwijoyo2%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## About

I have been programming since high school, and I like to turn slow manual processes, deep hierarchies and large
data flows into efficient, well-structured services.

- **TypeScript**: my first choice. Node.js (Express, Fastify) in production, and **Bun with Hono** for new
  services and side projects.
- **.NET with C#** (ASP.NET Core, EF Core, background services) for enterprise systems.
- **PostgreSQL** is my main database; I also work with SQL Server in enterprise projects.
- **Python with FastAPI** when a project needs it.

Outside work: daily Linux user (CachyOS) and hobby game development in Godot.

## Now

- 💼 **.NET Developer** at PT Talent Placement Consulting Indonesia: enterprise back-office automation, SFTP
  file pipelines, a Windows service that streams 6M+ rows in ~31 MB.
- 🐍 Building [**LazyCVE**](https://github.com/wiormiw/lazy-cve): local-first vulnerability intelligence with a Python and FastAPI core, machine learning
  for exploitation forecasts, and a Bun and Hono gateway.
- 🛠️ Building **Akashic Records**: a community platform in TypeScript, with a transactional outbox, OpenFGA
  authorization and a Dockerized deployment.
- 🎵 Building [**Old Country**](https://github.com/wiormiw/old-country): a self-hosted music player for my offline library and YouTube Music. The API is
  .NET 11 and C# 15 (minimal APIs, EF Core, PostgreSQL, vertical slices, union results), with yt-dlp for search,
  playback, downloads and playlist import; a Tauri and Leptos desktop app is next.
- 🌐 Open to **remote backend roles**.

## Experience

| Role | Company | Stack |
| :-- | :-- | :-- |
| .NET Developer · 2026 to now | PT Talent Placement Consulting Indonesia | .NET Framework, Windows Server, MSSQL, Windows Service, Docker |
| Backend Developer · 2025 to 2026 | PT Fan Integrasi Teknologi (Fanintek) | TypeScript, Express, Next.js, Go, PostgreSQL, Drizzle, Redis, BullMQ, Socket.IO, Firebase FCM, MinIO, NGINX, HAProxy, Patroni, etcd, RHEL, Docker, PM2, shadcn/ui, Tiptap, Zustand |
| Backend Developer (Intern) · 2023 | PT Len Industri (Persero) | TypeScript, Fastify, Prisma, Python, FastAPI, SQLAlchemy, Alembic, orjson, Poetry, pytest, Java, Quarkus, Rust with uWebSockets, RabbitMQ, Kafka, Memcached, Elasticsearch, PostgreSQL, PostGIS, GeoServer, Docker |
| IoT Developer (Intern) · 2019 | PT Adhim Aju Sejahtera | JavaScript, LabVIEW, REST, SQLite |

## Featured

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [**LazyCVE**](https://github.com/wiormiw/lazy-cve) | Local-first vulnerability intelligence: ingests CISA KEV and EPSS feeds, matches advisories to backend components, and forecasts 30-day exploitation with calibrated XGBoost. REST API, Nuxt dashboard and MCP tools. | Python, FastAPI, SQLAlchemy, Celery, XGBoost, PostgreSQL with pgvector, Kafka, Bun, Hono, Nuxt |
| [**Old Country**](https://github.com/wiormiw/old-country) | Self-hosted music server for my offline library and YouTube Music: library scanning, playlists, seekable streaming, and yt-dlp search, playback, downloads and playlist import. Vertical slices around a pure domain, C# 15 union results, explicit DI with hand-written decorators. | C#, .NET 11, ASP.NET Core, EF Core, PostgreSQL, FluentValidation, Aspire, yt-dlp |
| [**Akashic Records**](https://github.com/wiormiw/akashic-records) | Genre-specific "realms" (TCG, cosplay, idol, VTuber) with job listings, event RSVPs and a marketplace. Outbox pattern (PostgreSQL to RabbitMQ), realm-scoped authorization, typed SQL, 670+ tests. | TypeScript, Bun, Hono, PostgreSQL, Drizzle, OpenFGA, RabbitMQ, SvelteKit |
| [**wiormiw-porto**](https://wiormiw-porto.wwijoyo2.workers.dev/) | My portfolio, themed as a Pokemon battle log. | Astro, React, Tailwind, Cloudflare |
| [**SuggestMe 2.0**](https://github.com/wiormiw/suggestme-2.0) | Food recommendations by mood with Gemini, plus real-time ratings and comments. | ElysiaJS, Drizzle, PostgreSQL, React |
| [**GrowBaksAPI**](https://github.com/wiormiw/GrowBaksAPI) | E-commerce REST API for small businesses (UMKM). | Go, Fiber, PostgreSQL |

## Stack

**Core**

<img src="assets/core-stack.svg" alt="TypeScript, Node.js, Bun, Hono, .NET, C#, PostgreSQL, Redis, Docker" />

**Also in production work**

<img src="https://skillicons.dev/icons?i=express,py,fastapi,go,java,rabbitmq,kafka&perline=7" alt="Express, Python, FastAPI, Go, Java, RabbitMQ, Kafka" />

**Frontend and infrastructure**

<img src="https://skillicons.dev/icons?i=svelte,nextjs,nuxtjs,react,astro,nginx,linux,cloudflare&perline=8" alt="Svelte, Next.js, Nuxt, React, Astro, NGINX, Linux, Cloudflare" />

**Data and messaging**: PostgreSQL (recursive CTEs, GIN/trigram, full-text, PostGIS, pgvector), SQL Server,
Redis, Memcached, Elasticsearch, RabbitMQ, Kafka, BullMQ, Celery.

**Systems**: RHEL, CentOS Stream, Rocky, Debian, Ubuntu, Arch and Windows Server; air-gapped servers with
replicated PostgreSQL, Redis and MinIO.

---

<div align="center">

<sub>Based in Bandung · Indonesian and English · UTC+7</sub>

</div>
