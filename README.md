<div align="center">

# Georgy Pevchikh

### AI Product & Automation Engineer · Product Systems Designer

I turn product ideas and AI-generated prototypes into structured, secure and usable applications — from product discovery and interaction design to data models, permissions, automation, testing and deployment.

[![Upwork](https://img.shields.io/badge/Upwork-Profile-14A800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01c6b4199075060eea)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/georgy-pevchikh-b84967406/)
[![X](https://img.shields.io/badge/X-@georgypevchikh-111111?style=for-the-badge&logo=x)](https://x.com/georgypevchikh)

**Product judgment stays human-owned. AI accelerates execution.**

</div>

## What I build

My background is in visual design, but my work spans the complete product system. I define the problem, model the workflow, design the interface and data boundary, integrate managed services, and build a delivery process that keeps decisions and implementation traceable.

| Product engineering | Backend and automation | Product systems |
|---|---|---|
| React, Next.js, TypeScript, React Native, Expo | Supabase, PostgreSQL, Auth, RLS, SQL, APIs, webhooks, n8n | Product discovery, UX architecture, data modeling, roles, permissions, design systems |

## Flagship work

### Restamenu Console — executable multi-tenant proof

<a href="https://github.com/georgypevchikh/restamenu-console-demo">
  <img src="https://raw.githubusercontent.com/georgypevchikh/restamenu-console-demo/main/docs/images/requests-dashboard.png" alt="Restamenu purchase-request dashboard" />
</a>

A public restaurant operations console built to prove that tenant isolation lives in Postgres rather than in client-side filters.

- **Next.js 16 + React 19 + TypeScript strict** on Vercel.
- **Supabase Auth + Postgres Row Level Security** across two live restaurant tenants.
- Manager/team roles with read- and write-side tenant-isolation tests.
- Urgent request → Postgres trigger → `pg_net` → n8n → Telegram.
- Webhook secret in Supabase Vault; no privileged database credential in n8n.
- Typecheck, ESLint, production build and **7/7 integration tests** in GitHub Actions.

[Live demo](https://restamenu-console-demo.vercel.app) · [Technical case study](https://github.com/georgypevchikh/restamenu-console-demo) · [CI](https://github.com/georgypevchikh/restamenu-console-demo/actions)

### StuffSycle — research-to-shipped marketplace

<a href="https://github.com/georgypevchikh/stuff-sycle-case-study">
  <img src="https://raw.githubusercontent.com/georgypevchikh/stuff-sycle-case-study/main/assets/screenshots/catalog.jpg" alt="StuffSycle university marketplace catalog" />
</a>

A peer-to-peer marketplace for a university community, built independently from the research question through product strategy, UX/UI, application architecture, backend integration and public deployment.

- React 18, TypeScript, Vite, React Router and Tailwind CSS.
- Supabase Auth, PostgreSQL, Storage and Realtime.
- Catalog, search, filters, listings, profiles, item-linked messaging, support and administration.
- Structured AI-assisted workflow across Obsidian, Linear, Figma Make, Cursor and Claude Code.
- **43-page bachelor project** documenting the research, product decisions, architecture and implemented interface.

[Live product](https://stuff-sycle-web-4.vercel.app/) · [Product + engineering case study](https://github.com/georgypevchikh/stuff-sycle-case-study) · [Bachelor project](https://github.com/georgypevchikh/stuff-sycle-case-study/blob/main/docs/StuffSycle-bachelor-project.pdf)

## How I work with AI

AI is an implementation accelerator, not the owner of architecture or product judgment.

```text
Research and decisions   → Obsidian
Scope and acceptance     → Linear
Interface exploration    → Figma / Figma Make
Implementation workspace → Cursor / Codex / Claude Code
Versioned source         → GitHub
Backend and data         → Supabase / PostgreSQL
Automation               → Postgres triggers / n8n / APIs
Deployment               → Vercel / Expo EAS
```

I keep durable decisions outside chat, break work into reviewable outcomes, inspect generated output, and make authorization, secrets and release boundaries explicit.

## Engineering principles

- Product decisions before framework decisions.
- Database permissions before client-side assumptions.
- Migrations and code in version control; runtime secrets outside Git.
- Implemented, planned and exploratory work are labeled separately.
- Managed infrastructure first when it reduces surface area without weakening the data model.
- Every public claim should have an artifact behind it.
- A green local command is not finished until CI and the deployed result agree.

## All public repositories

This section is generated daily from the GitHub API. New public repositories appear automatically; the workflow commits only when repository metadata changes.

<!-- PUBLIC-REPOS:START -->
<!-- Generated by scripts/update_public_projects.py. Do not edit this block manually. -->
| Repository | What it demonstrates | Stack / topics | Links |
|---|---|---|---|
| **[restamenu-console-demo](https://github.com/georgypevchikh/restamenu-console-demo)** | Multi-tenant restaurant operations demo — Next.js, Supabase RLS, CI, n8n, and Telegram automation | TypeScript · multi tenant · n8n · nextjs · postgresql | [Repository](https://github.com/georgypevchikh/restamenu-console-demo) · [Live](https://restamenu-console-demo.vercel.app) |
| **[stuff-sycle-case-study](https://github.com/georgypevchikh/stuff-sycle-case-study)** | Research-to-shipped university marketplace — product, UX, React, Supabase, and AI-assisted delivery case study | ai assisted development · case study · marketplace · product design | [Repository](https://github.com/georgypevchikh/stuff-sycle-case-study) · [Live](https://stuff-sycle-web-4.vercel.app/) |
<!-- PUBLIC-REPOS:END -->

## Availability

Open to scoped product builds, AI-generated prototype productionization, React/Next.js/Supabase work, workflow automation, architecture and codebase audits, and long-term product engineering partnerships.

<div align="center">

[Upwork](https://www.upwork.com/freelancers/~01c6b4199075060eea) · [LinkedIn](https://www.linkedin.com/in/georgy-pevchikh-b84967406/) · [X](https://x.com/georgypevchikh)

</div>
