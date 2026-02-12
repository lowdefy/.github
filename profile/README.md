# Lowdefy — The Config-First Web Stack for AI and Humans

With [Lowdefy](https://lowdefy.com/) you can build web apps that AI can generate, humans can review, and teams can maintain. Config that works between code and natural language.

#### Why config-first matters in the age of AI

AI writes code fast, but the maintenance doesn't scale. LLMs generate thousands of lines that are hard to review, inconsistent across sessions, and full of hidden vulnerabilities. Lowdefy solves this:

- **50 lines of config vs 500 lines of code** — AI generates concise, reviewable config instead of sprawling React components.
- **Schema-validated, no arbitrary code paths** — Every property validated against a schema. No arbitrary code paths.
- **One framework update upgrades all your apps** — Config is stable. Lowdefy updates benefits all apps. No fixing each AI-generated codebase individually.
- **Config is interpreted, not executed** — No code injection possible. Auth, permissions, and data validation built into the runtime.

#### Full-stack, production-ready

- **Built on [Next.js](https://nextjs.org/) and [Auth.js](https://authjs.dev/)** — Deploy anywhere you host Next.js.
- **70+ UI components** — Forms, tables, charts, markdown, and more out of the box.
- **50+ logic operators** — `_if`, `_get`, `_js`, `_state` for dynamic UIs without writing code.
- **10+ data connectors** — MongoDB, PostgreSQL, MySQL, REST APIs, Google Sheets, S3, Elasticsearch, Stripe.
- **Auth & RBAC** — 75+ auth providers, public and private pages, role-based access control.

#### Extend with npm plugins

Blocks, Connections, Operators, Actions, Auth Providers, and Adapters can all be extended with plugins. Declare them in config — Lowdefy handles the rest.   

Tree-shaking bundles only what you use. Build custom plugins with npm packages and publish them for the community.
  
- https://docs.lowdefy.com/plugins-introduction
- https://github.com/lowdefy/lowdefy-example-plugins (pnpm monorepo setup)
- https://github.com/lowdefy/community-plugins

Get started

Visit our https://docs.lowdefy.com/introduction or run:

```
npx lowdefy@latest init && npx lowdefy@latest dev
```

Examples:

- https://github.com/lowdefy/lowdefy-example-crud
- https://github.com/lowdefy/lowdefy-example-case-management
- https://github.com/lowdefy/lowdefy-example-reporting
- https://github.com/lowdefy/lowdefy-example-auth-email
- https://github.com/lowdefy/lowdefy-example-auth0-mongo
- https://github.com/lowdefy/lowdefy-example-business-card

---
## 🌱 Lowdefy is built and maintained by Resonancy

🚀 Too many apps? https://resonancy.io builds it for you.

Most teams run 10+ business apps that don't talk to each other. https://resonancy.io replaces them with one purpose-built solution on Lowdefy — delivered in days, not months.

- Consolidate your stack — Replace disconnected apps with one unified solution.
- Streamline workflows — Seamlessly integrated systems that free up your team.
- Ship in days — Custom apps built fast with Lowdefy.
- Connect everything — Real-time data across your business for reliable insights.

✅ One unified app replacing your SaaS dependency · ✅ Custom solution tailored to your business · ✅ AI, data science & integrations included · ✅ Ongoing support & managed hosting

10+ years building business apps. 50+ internal tools deployed. Built on open source.

https://resonancy.io

---
Questions or suggestions?

We use https://github.com/lowdefy/lowdefy/discussions and https://discord.gg/WmcJgXt for help, bug reports, and feature ideas.
