# SessionVault

SessionVault is a privacy-first SaaS for managing multiple work accounts, accounts, and workspaces from a single dashboard.

It is inspired by the workflow of tools like Janus, but rebuilt as a modern web application with a SaaS product structure.

---

**By Sebastian Horváth** — Creator of [CoreTrial Provider](https://github.com/horvathsebin220-sys/Collateral-Provider) and [giveme.my](https://giveme.my/)

---

## Why this exists

SessionVault gives teams a secure place to:

- manage multiple workspaces,
- track active accounts and session states,
- assign roles and permissions,
- monitor billing and seat usage,
- centralize operational context for teams.

## Stack

- Next.js 14
- TypeScript
- Tailwind CSS
- PostgreSQL-ready data model
- Stripe-ready billing layer
- Auth-ready layout

## Local development

1. Install dependencies:

```bash
npm install
```

2. Start the app:

```bash
npm run dev
```

3. Open http://localhost:3000

## Pricing model

- Starter: $0 / month
- Pro: $40 / user / month
- Enterprise: $120 / user / month

## Production readiness notes

This repo is a solid MVP foundation. For production, you should add:

- real authentication provider (Clerk or Supabase Auth),
- Stripe subscriptions and metering,
- PostgreSQL database schema and migrations,
- role-based permissions (RBAC),
- audit logs for compliance,
- secrets management (environment variables),
- deployment config for Vercel or Docker.

## Features roadmap

- [x] Landing page and pricing display
- [x] Dashboard skeleton
- [ ] User authentication
- [ ] Workspace creation and management
- [ ] Profile/account CRUD
- [ ] Stripe billing integration
- [ ] Team member management
- [ ] Audit logs
- [ ] API and webhooks
- [ ] SSO support

## Repo status

This is a starter SaaS foundation designed for building a real product rather than a finished production-ready app.

## License

MIT
