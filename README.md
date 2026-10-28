# Nadav Shtibel

**Full-Stack Software Engineer — AI Agents, Multi-Agent Systems & Production Web Architecture**

I design and ship full-stack web applications, data pipelines, and autonomous multi-agent systems across **TypeScript / Next.js / Angular**, **Node.js**, **Python**, and **.NET (C#)**.

---

### Core Focus Areas

- **AI Agents & Multi-Agent Orchestration**: Building autonomous tool-using agents, Model Context Protocol (**MCP**) servers, cross-device agent hubs, voice/messaging pipelines (ElevenLabs, Twilio, WhatsApp), and secure vault-backed execution workflows.
- **Full-Stack & E-Commerce Platforms**: Architecting high-scale web apps, multi-tenant SaaS backends, and RTL/Hebrew-first commerce systems with **Next.js (App Router)**, **React**, **Angular**, **ASP.NET Core**, **PostgreSQL / Supabase**, and **SQL Server**.
- **Data Engineering & Automation**: Automated scraping, entity resolution on noisy real-world feeds, XML/GZIP ingestion pipelines, and zero-ops static/edge delivery via **AWS Amplify** and **GitHub Actions**.

---

### Selected Public Repositories

| Repository | Stack | What It Does |
| :--- | :--- | :--- |
| [**Alex (סל חדרה)**](https://github.com/Shtibel1/Alex) | `Python` `Vanilla JS` `GitHub Actions` `AWS Amplify` | Israeli supermarket basket price-comparison engine across 10 retail chains (25 branches). Ingests official Price Transparency Law XML/GZIP feeds, resolves ~90 weighted fresh-produce items via token/unit heuristics, parses `PromoFull` deal structures, packs delta-encoded price indices into a single client-side bundle, and auto-publishes daily. |
| [**DunFlow**](https://github.com/Shtibel1/DunFlow) | `C#` `.NET 9` `EF Core` `Angular` | Metadata-driven task management and workflow state machine engine. Task categories, valid state transitions, and per-status required form schemas live entirely in the database (`WorkTaskTypes`, `WorkTaskStatuses`, `FormFields`) so new workflows ship without backend code changes. |
| [**InstallersApi2**](https://github.com/Shtibel1/InstallersApi2) & [**installers**](https://github.com/Shtibel1/installers) | `C#` `.NET 8` `EF Core` `WebSockets` `Angular` | Multi-tenant field-service dispatching, technician inventory/stock auditing, and automated contractor settlement platform. Uses JWT claim-based tenant routing (`CompanyMiddleware`), real-time WebSocket dispatch updates, and a full RTL Angular Material client. |
| [**detection-explorer**](https://github.com/Shtibel1/detection-explorer) | `TypeScript` `Next.js 14` `Tailwind` `AWS Amplify` | Static developer-experience & schema documentation tool mapping C# detection types, inheritance hierarchies, example payloads, and 3-way branch diffs (`Main-Next` ↔ `Main-Global` ↔ `CDMX`). |

---

### Technical Stack

- **Languages**: TypeScript, JavaScript, C#, Python, SQL
- **Frontend**: Next.js (App Router), React, Angular, Tailwind CSS, HTML/CSS (RTL & Hebrew UX)
- **Backend & Data**: Node.js, ASP.NET Core (.NET 8 / .NET 9), Entity Framework Core, PostgreSQL, Supabase, SQL Server, REST & WebSockets
- **AI & Tooling**: Model Context Protocol (MCP), LLM Agent Orchestration, ElevenLabs Voice AI, Playwright / Browser Automation
- **Cloud & CI/CD**: AWS (Amplify, S3, CloudFront), GitHub Actions, Docker, Linux
