<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Enrico Schintu. Senior Software Engineer, Tech Lead, full stack. I turn business needs into production-ready software, hands-on at every stage, from analysis to delivery." src="assets/header-light.svg" width="100%">
</picture>
</p>

<p align="center">
  10+ years in fintech and travel · Italy, remote (CET)<br>
  <a href="https://enricoschintu.com">Website</a> ·
  <a href="https://www.linkedin.com/in/enrico-schintu-schengatto/">LinkedIn</a> ·
  <a href="https://codepress.it">Codepress</a> ·
  <a href="mailto:schintu.enrico@gmail.com">Email</a>
</p>

<p align="center">
  <i>Open to Senior / Staff Software Engineer and Forward Deployed Engineer roles, remote.</i>
</p>

---

## What I do

I'm a software engineer with hands-on team leadership experience, and I build the products the business needs. Alongside them, I build custom tools for the teams I work with, to improve their everyday work: higher productivity, better quality and a better place to work.

## How I work

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/workflow-dark.svg">
  <img alt="How I work: business requirements, functional and technical analysis, implementation and testing, delivery to production." src="assets/workflow-light.svg" width="100%">
</picture>
</p>

I started in 2015 as a backend developer, writing Java and Spring batch jobs for banks, and learned that data outlives every interface built on top of it. Yet the problem rarely ended at the API, so I crossed over to the frontend, and by 2018 I was leading the front-end team.

Being full stack was still not enough. A feature nobody can trust isn't done, so I took on QA and designed the integration and end-to-end strategy for my teams, with Playwright, Cucumber and real monitoring behind it. A feature nobody can deploy isn't done either, so I took on cloud ops too, from CI/CD pipelines to AWS and Terraform, and became the cloud-ops ambassador of my team at TUI Musement.

For me, building software means owning everything between the idea and the moment it runs in production for real users, with care for quality at every step. Today the team includes AI agents, and the principle hasn't changed. I ask the boring questions first, refuse complexity until it has earned its place, write the tests before I trust the code, and ship.

## Flagship: Codepress Workspace

**Jira, rebuilt for teams where humans and AI agents work side by side.** One board where work is planned, refined, built and reviewed in the same place, by people in the browser and by coding agents over MCP.

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/workspace-dark.svg">
  <img alt="People in the browser and coding agents over MCP share one Workspace board, linked to Archivist memory and to parallel agent runs." src="assets/workspace-light.svg" width="100%">
</picture>
</p>

- Agents read the board, pick up a ready task, update it as they go and hand it back for review with evidence. Definition of Ready and Done are gates, not decoration.
- Parallel agent runs across projects, each behind its own LLM gateway, with roadmaps, milestones and reports for the humans steering them.
- Shared agent memory ([Archivist](https://github.com/Schengatto/archivist)) linked per project, so every session starts from what the team already learned.
- Build-vs-buy decided on a benchmark: 20 concurrent agents at p95 100 ms, against 25.4 s for a git/markdown board.

<sub>Node.js 24 · TypeScript strict · SQLite · MCP · server-rendered UI · self-hosted · 600+ commits, sole author · runs my own teams' work every day</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/workspace-board-dark.png">
  <img alt="Codepress Workspace board: tasks across Backlog, To do, In progress, Parked and In review, with priority, points, effort, labels and assignees, humans and AI agents side by side." src="screenshots/workspace-board-light.png" width="100%">
</picture>
</p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/workspace-task-dark.png">
  <img alt="A task with Definition of Done, commit evidence, subtasks and comments from a teammate and a coding agent." src="screenshots/workspace-task-light.png" width="49%">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/workspace-run-dark.png">
  <img alt="An agent run narrated step by step: the agent asks a question, the human answers, the run resumes." src="screenshots/workspace-run-light.png" width="49%">
</picture>
</p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/workspace-roadmap-dark.png">
  <img alt="Roadmap with milestones, progress bars and estimated delivery dates." src="screenshots/workspace-roadmap-light.png" width="49%">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/workspace-report-dark.png">
  <img alt="Project report: points burned per day, velocity and breakdowns by status, type and priority." src="screenshots/workspace-report-light.png" width="49%">
</picture>
</p>

<p align="center"><sub>Invented demo dataset.</sub></p>

</details>

## Products I built

### [Fondamentix](https://fondamentix.com)

Free value-investing platform with screener, DCF/Graham/EPV fair-value models and 13F portfolios on 1,000+ US companies, refreshed nightly.<br>
<sub>Nuxt 4 · PostgreSQL</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/fondamentix-dark.png">
  <img alt="Fondamentix: fair value estimation with margin of safety and valuation methods for a US company." src="screenshots/fondamentix-light.png" width="100%">
</picture>
</p>

</details>

### [Soluzione Business](https://soluzione-business.codepress.it)

Management SaaS for Italian companies (e-invoicing, tax engine, payroll) with an AI advisor exposed over MCP.<br>
<sub>Next.js 16 · Prisma · PostgreSQL</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<img alt="Soluzione Business landing page with a dashboard preview." src="screenshots/soluzione-business.png" width="100%">
</p>

</details>

### Online gazette SaaS

A multi-tenant back-office CMS for running real online gazettes on any topic, each published through a white-label client. Editors define sources, taxonomy and branding, and Gemini reads, classifies and scores every article by sentiment and impact. Live gazettes include **[Markets Gazette](https://marketsgazette.cloud)**, with impact scored per asset and a daily consensus signal, and **[AI Gazette](https://ai.schengatto.com/)**, covering artificial intelligence.<br>
<sub>Nuxt · PostgreSQL · Gemini</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/markets-gazette-dark.png">
  <img alt="Markets Gazette: AI digest and sentiment-scored market news." src="screenshots/markets-gazette-light.png" width="100%">
</picture>
</p>

</details>

### [TubeToo](https://tube-too.netlify.app/)

Ad-free YouTube player as an installable PWA.<br>
<sub>TypeScript</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<img alt="TubeToo: ad-free YouTube player, search results for Technology." src="screenshots/tubetoo.jpg" width="100%">
</p>

</details>

## AI-native engineering

### [Archivist](https://github.com/Schengatto/archivist)

Shared long-term memory for teams of coding agents (Claude Code, Codex, Cursor), served as a remote MCP server. Append-only writes with merge-on-read compaction, hybrid full-text + vector search ranked with RRF, per-team isolation, no LLM on the server so cost stays flat and predictable. npm client: [`archivist-connect`](https://www.npmjs.com/package/archivist-connect).<br>
<sub>v1.2.0 · 570+ tests · in daily production since July 2026</sub>

### [Commercialista AI](https://commercialista-ai.codepress.it/login)

RAG assistant on Italian tax law, in production for accountants, with topic gating and role-based access.<br>
<sub>In production</sub>

### ai-assistant

White-label RAG framework extracted from Commercialista AI, on-premise and air-gappable, with a local-LLM provider. Powers the AI assistant of the Witzard portfolio-analytics platform.<br>
<sub>619 tests · installable release with CI</sub>

<sub>Stack: Python · FastAPI · Next.js · PostgreSQL + pgvector · Gemini · local LLMs · Docker · Kubernetes</sub>

## Open source

### [GitPress](https://github.com/Schengatto/git-press) · [site](https://schengatto.github.io/git-press/)

Cross-platform desktop Git GUI with a virtualized commit graph, hunk staging and drag-and-drop interactive rebase. 10 releases up to v1.0.0, installers for Windows, macOS and Linux.<br>
<sub>Electron · React · TypeScript</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/git-press-dark.png">
  <img alt="GitPress: commit graph, branches explorer, diff viewer and codebase statistics." src="screenshots/git-press-light.png" width="100%">
</picture>
</p>

</details>

### [trade-republic-analyzer](https://github.com/Schengatto/trade-republic-analyzer) · [live](https://schengatto.github.io/trade-republic-analyzer/)

Drop in a Trade Republic CSV and get realized P&L matched FIFO, monthly figures and a per-security breakdown. The file never leaves the browser.<br>
<sub>TypeScript · client-side only</sub>
<details>
<summary><sub>Screenshots</sub></summary>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="screenshots/trade-republic-analyzer-dark.png">
  <img alt="trade-republic-analyzer: realized profit, charges and annual return computed in the browser." src="screenshots/trade-republic-analyzer-light.png" width="100%">
</picture>
</p>

</details>

### More on GitHub

- **[mailstore-linux](https://github.com/Schengatto/mailstore-linux)**: read-only IMAP archiver, a deduplicated and full-text-searchable local archive in one relocatable folder. Never writes to the server. <sub>Electron · React · TypeScript · SQLite</sub>
- **[create-agentic-project](https://github.com/Schengatto/create-agentic-project)**: CLI that scaffolds agent-ready repos with instruction rules, agent memory, review, security and testing gates. <sub>TypeScript · Node.js</sub>
- **[libre-city](https://github.com/Schengatto/libre-city)**: multiplayer GTA-style sandbox in the browser, desktop and mobile, over WebSocket. <sub>JavaScript · Canvas 2D · Node.js · PWA</sub>

## Stack

**Backend**<br>
`TypeScript and Node.js (NestJS, Fastify, Hono)` `Python (FastAPI)` `Java and Spring` `C# and .NET`

**Data**<br>
`PostgreSQL` `MongoDB` `SQLite` `Elasticsearch` `Prisma`

**Frontend**<br>
`React` `Next.js` `Vue` `Nuxt` `Angular` `Electron` `WCAG accessibility`

**AI & LLM**<br>
`Claude models` `GPT models` `Gemini` `local LLMs` `AI gateways (OmniRoute)` `MCP servers` `RAG with pgvector, hybrid search and embeddings` `structured output` `AI cost control`

**Cloud & DevOps**<br>
`AWS (ECS, Lambda, API Gateway, CloudFront, RDS, Cognito)` `Docker` `Kubernetes` `Terraform` `GitHub Actions` `Datadog` `Grafana`

**Quality**<br>
`TDD` `BDD with Cucumber` `Playwright` `Vitest` `Jest` `pytest` `SAST in CI`

## Experience

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/experience-dark.svg">
  <img alt="2026 - present: Codepress, founder. Software house shipping fixed-scope products, audits, PoCs and enterprise RAG pilots, tests first and full code ownership for the client. 2026 - present: Witzard, technical collaboration. Senior technical advice and hands-on code on an AI portfolio-analytics platform (backtesting, VaR/CVaR, efficient frontier). Contributed the RSS-to-Gemini news pipeline and the white-label AI assistant. 2024 - present: KAIO, tech lead. Investor KYC on a schema-driven form engine, DocuSign subscription flows, Chainlink CCIP cross-chain integration, the encryption-key backup and rotation ceremony. Own QA (Playwright, Cucumber, Synpress), CI/CD and AWS monitoring. 2021 - 2023: TUI Musement, senior software engineer. Customer-facing tours and activities products for TUI Group. The team&#x27;s E2E and monitoring approach (Playwright, Cucumber, Datadog), cloud-ops ambassador on AWS and Terraform. 2020: Nivaura, senior full stack engineer. Fintech microservices on AWS (Java/Spring, NestJS, Vue). Infrastructure, security and architecture decisions, CI/CD and ELK observability. 2015 - 2020: Addvalue, backend developer, then full stack engineer and front-end team lead (2018 - 2020). Web and batch applications for banking, financial and e-commerce clients (Java/Spring, Angular, React, Elasticsearch, PostgreSQL)." src="assets/experience-light.svg" width="100%">
</picture>
</p>

---

<p align="center">
  Got a product to take to production, or a role where this fits? <a href="mailto:schintu.enrico@gmail.com">schintu.enrico@gmail.com</a>
</p>
