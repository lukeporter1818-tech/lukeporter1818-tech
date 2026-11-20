# Hi, I'm Luke 👋

I spent 12 years in the trades, running dispatch for a 30-technician commercial refrigeration division and managing design-build remodeling projects. Now I build AI software for the people who do that work.

I build with **Claude Code**, using Next.js, TypeScript, Supabase/Postgres and Vercel. I bring the domain knowledge and make the product decisions, and the AI writes most of the code.

## What I've built

**FROST**, a field service platform for commercial HVAC and refrigeration contractors (prototype)
- Work orders, dispatch, closeouts, equipment history, manuals, and an AI troubleshooting assistant, built from what I saw running dispatch
- A parts finder that reads a photo of a model/serial plate and checks it against equipment manuals before anything gets ordered
- An AI agent system with guardrails: allow/ask/never approval rules, an approved-send list, prompt-injection handling in its connectors, and an owner lock so customers can't change how the AI behaves
- Offline-first design, connectors (QuickBooks, ServiceChannel, Stripe, Twilio, Gmail/Outlook) and an MCP server so Claude and ChatGPT can work with it
- Tested by working refrigeration technicians. I'm the sole developer and product owner, building with AI-assisted development

**BrotherHood**, a men's community app I'm founding (pre-launch, live with a small group of early users)
- Topic Rooms, a daily check-in, opt-in one-on-one matching with private chat, and **Goose**, an AI companion with a risk classifier and a 988 crisis path. A "Get help" button is on every screen
- Privacy-first: anonymous handles, row-level security on every table, and AI tools scoped to the member's own data
- Next.js 16, React 19, TypeScript, Tailwind 4, Prisma 7, Supabase, Anthropic API, Vercel. About 100 test files, with secret scanning in CI
- I lead product, design and research, and direct AI coding agents through pull requests and review gates

**Halbrook**, design-build management for premium residential remodelers (prototype)
- Takes a home remodel from first lead to closeout. The owner talks, snaps a photo or drops a Chief Architect file, the app drafts the paperwork, and nothing goes out without his OK
- "Steps, not agents": each tap runs one bounded, owner-approved AI step, so behavior stays predictable and cheap to run
- 78 prototype versions in 12 days. I wrote the briefs, set the acceptance rules and approved every release, and Claude built it
- Built first for my family's design-build business. The earlier codebase uses Next.js, Supabase (row-level security, database tests) and Vercel, with branch protection and secret scanning

## How I work
- I start from a real problem I've seen in the field, not from a feature list
- I test with the people who'll use the software
- I lock down data and check my work before I ship

## What I'm looking for
Implementation, onboarding, customer success and support roles at AI and field-service software companies. Remote, or in the MD/DC area.

📫 [LinkedIn](https://www.linkedin.com/in/luke-porter)

*My project repos are private. I'm happy to give a live demo.*
