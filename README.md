# Fırat Kıl

Full-stack developer in Ankara, Türkiye. I build AI-powered SaaS products end to end, from the data model and auth to billing, background jobs, tests and deployment. Mostly Next.js, TypeScript and PostgreSQL.

Since September 2025 I've been a full-stack developer at Vizio AI, an AI product studio, where I lead or solely build client products: a legal research assistant with cited answers, a recruiting platform, an AI customer-support suite, the backend of a live auction marketplace and an HVAC takeoff and quoting tool. That work lives in private client repositories; [firatkil.com](https://firatkil.com) describes it in more detail.

## What I work with

- **Frontend:** Next.js (App Router), React, TypeScript, Tailwind CSS, TanStack Query
- **Backend:** Node.js, NestJS, REST, SSE, WebSockets, Spring Boot
- **Data:** PostgreSQL and Supabase (row-level security, SQL functions), pgvector, Redis, MongoDB
- **AI:** OpenAI, Gemini, Vercel AI SDK, retrieval-augmented generation, streaming chat, text-to-speech
- **Shipping:** Stripe, BullMQ, Docker, Vercel, Azure, GitHub Actions, Playwright, Vitest, pgTAP
- 
## Public projects

| Project | What it is | Stack |
| --- | --- | --- |
| [bidlock](https://github.com/firatkill/bidlock) | A live auction engine that stays correct under load | Next.js, Supabase, PostgreSQL, Vitest, Playwright |
| [outbox](https://github.com/firatkill/outbox) | Transactional outbox, relay and inbox for PostgreSQL: at-least-once delivery with leases, retries, dead letters and per-key ordering | TypeScript, PostgreSQL, Vitest |
| [sourced](https://github.com/firatkill/sourced) | A small RAG app and starter kit over the PostgreSQL 17 docs; every citation is checked on the server before you see it | Next.js, Vercel AI SDK, OpenAI, pgvector, Drizzle |
| [rehearse](https://github.com/firatkill/rehearse) | Voice mock-interview coach: answer questions out loud in the browser and get rubric-based feedback on every answer | Next.js, Vercel AI SDK, Web Speech API, Upstash Redis |
| [erranderpy](https://github.com/firatkill/erranderpy) | Small personal agents you talk to on Telegram; add an agent by adding a folder and bring any LLM key | Python, python-telegram-bot, SQLite, Anthropic/OpenAI/Gemini |
| [markdownToPdf](https://github.com/firatkill/markdownToPdf) | Tiny native macOS app: drag and drop Markdown files, get clean PDFs | Swift, SwiftUI |

## How I work

I write most code with AI coding agents. I still own the data model, the security rules and the tests, and I read every change before it ships. I like putting rules where they can't be skipped: row-level security in the database, payment state changed only by verified webhooks, concurrency-sensitive logic inside Postgres functions.

## Contact

[firatkil.com](https://firatkil.com) · [LinkedIn](https://linkedin.com/in/firatkill) · firatkill.is@gmail.com
