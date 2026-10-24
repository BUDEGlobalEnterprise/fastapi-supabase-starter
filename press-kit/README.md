# Press and listing kit

Everything a directory, launch site or writer asks for about **FastAPI Supabase Starter**, ready to
copy. Logos and images are in this folder and in [`../screenshots`](../screenshots).

## At a glance

| | |
|---|---|
| **Name** | FastAPI Supabase Starter |
| **Website** | https://starter.budeglobal.in |
| **Pricing** | https://starter.budeglobal.in/pricing |
| **Try it** | https://starter.budeglobal.in/login?mode=signup (sign up with Google or email) |
| **Docs** | https://github.com/BUDEGlobalEnterprise/fastapi-supabase-starter |
| **Made by** | BUDE Global Enterprise, India |
| **Contact** | budemadeofficial@gmail.com · WhatsApp +91 93616 21891 |
| **Launched** | October 2026 |
| **Price** | One-time payment: Solo ₹1,999 · Pro ₹2,999 · Team ₹4,999 |
| **License** | Commercial, full source code, unlimited projects (not open source) |
| **Stack** | Python 3.12, FastAPI, Supabase (Auth, Postgres, Storage, Realtime), React 19, TanStack Start, Router and Query, Tailwind v4, shadcn/ui |

**Categories:** Developer Tools · SaaS Boilerplate / Starter Kit · Web Development

**Tags:** fastapi, supabase, python, saas boilerplate, saas starter kit, react, postgres, row level
security, stripe, razorpay, mcp, ai, tanstack, shadcn-ui

On forms that ask: pricing model **Paid / One-time**; open source **No**; platform **Web**;
price in USD: say "from ₹1,999 one-time" in the description, since prices are set in rupees.

## Taglines

Pick by the form's limit.

- **38 characters:** Ship your SaaS on FastAPI and Supabase
- **53 characters:** The Python-first SaaS starter on FastAPI and Supabase
- **58 characters:** FastAPI + Supabase SaaS starter, with the hard parts built

## Descriptions

**Short (110 characters)**

> The Python-first SaaS starter on FastAPI and Supabase, with auth, teams, roles, payments and AI already built.

**Medium (249 characters, fits Product Hunt's 260)**

> A FastAPI + React SaaS starter on Supabase: sign-in, teams, roles, API keys, Stripe and Razorpay payments, a Gemini assistant and an MCP server. Postgres row-level security guards every table, even for API keys and AI clients. From ₹1,999, one-time.

**Long (about 190 words)**

> FastAPI Supabase Starter is the foundation every SaaS needs before its first real feature,
> finished, tested and documented, for Python developers.
>
> It's a fork of Tiangolo's Full-Stack FastAPI Template, rebuilt on Supabase Auth and Postgres
> row-level security. The API never connects to the database directly: it calls Supabase with the
> caller's own token, so the same RLS rules protect the web app, API keys and AI clients connecting
> over MCP. There are no ownership checks in the code to forget.
>
> Inside: sign-in with passwords, email codes, SMS or WhatsApp codes and any OAuth provider;
> organizations with invitations and roles; a permission matrix editable from the admin console;
> hashed API keys; Stripe and Razorpay checkout with verified webhooks and plan limits; a Gemini
> assistant whose tools are also served as an MCP server for Claude and Cursor; white-label
> branding; an audit log; and a public site pre-rendered for search engines, with a blog and help
> center.
>
> It ships ready for AI coding agents, with AGENTS.md, Claude Code skills and preconfigured MCP
> servers, so Claude Code, Codex or Cursor can add a feature end to end from the first prompt.
>
> One-time payment from ₹1,999, full source code, unlimited projects.

## Key features

- **Security in the database:** Postgres row-level security on every table, applied to the web app, API keys and MCP clients alike
- **Sign-in:** email and password, email codes, SMS or WhatsApp codes (MSG91), Google and any OAuth provider, Turnstile CAPTCHA
- **Teams:** organizations, invitations, owner/admin/member roles, ownership transfer
- **Permissions:** a role × resource × action matrix with expiring roles and per-user overrides, one `has_permission()` used by RLS, API and UI
- **Payments:** Stripe and Razorpay (UPI, cards, netbanking), USD and INR, verified webhooks, plans with usage limits
- **AI:** a Gemini assistant with tool calling, and the same tools as an MCP server with Supabase OAuth
- **Admin console:** users, roles, payments, feedback, analytics, messaging templates, audit log
- **Branding:** app name, logo and colors set from the admin UI, no deploy
- **Public site:** pre-rendered home, pricing, blog, help center and legal pages, sitemap and structured data
- **For coding agents:** AGENTS.md, Claude Code skills, MCP configs for Claude Code, Cursor and Codex
- **Quality:** API tests against a real Supabase, CI, Docker Compose, a typed client and Postman collection generated from OpenAPI

## Who it's for

- Python developers who want a SaaS foundation without switching to a Next.js stack
- Agencies and freelancers building client apps (every license covers unlimited projects)
- Founders in India who need Razorpay, UPI and SMS or WhatsApp sign-in codes
- Teams that build with Claude Code, Codex or Cursor

## Alternatives (for AlternativeTo, SaaSHub and comparison fields)

| Alternative | How this starter differs |
|---|---|
| Full Stack FastAPI Template (free) | This starter is a fork of it, rebuilt on Supabase, with teams, roles, payments, AI and an admin console added |
| Supastarter | Python and FastAPI backend instead of Next.js or Nuxt |
| MakerKit | Python and FastAPI backend instead of Next.js; Razorpay and INR built in |
| ShipFast | Python backend, Supabase RLS, teams and roles |
| SaaS Pegasus | FastAPI and Supabase instead of Django |

## Images

| File | Size | Use |
|---|---|---|
| [`logo-512.png`](logo-512.png) | 512 × 512 | Logo / icon on most directories |
| [`logo-240.png`](logo-240.png) | 240 × 240 | Product Hunt thumbnail |
| [`social-card-1200x630.png`](social-card-1200x630.png) | 1200 × 630 | Cover image, link previews |
| [`../screenshots/`](../screenshots) | 1440 × 900 (phones 390 × 844) | Galleries |

Gallery order that tells the story:

1. `dashboard.png`: the dashboard in the sidebar app shell
2. `admin-roles.png`: roles and the permission matrix
3. `billing.png`: plans in USD and INR, usage meters, payment history
4. `assistant.png`: the AI assistant and its MCP server URL
5. `branding.png`: name, logo and colors from the admin UI
6. `organization.png`: members and invitations
7. `command-menu.png`: the Ctrl+K command menu
8. `dashboard-dark.png`: dark mode
9. `mobile-dashboard.png`: on a phone

## Ready-made posts

### Product Hunt

- **Name:** FastAPI Supabase Starter
- **Tagline:** FastAPI + Supabase SaaS starter, with the hard parts built
- **Description:** the medium description above
- **Topics:** Developer Tools, SaaS, Artificial Intelligence
- **Launch:** Tuesday to Thursday, at 12:01 am Pacific (12:31 pm IST until 1 November, 1:31 pm after)

**Maker's first comment:**

> Hi Product Hunt! 👋
>
> Every SaaS I started began with the same three weeks: sign-in, teams, roles, payments, and making
> sure user A can never read user B's rows. Most starters that do this well are Next.js. I wanted
> one for Python.
>
> FastAPI Supabase Starter is a fork of Tiangolo's Full-Stack FastAPI Template rebuilt on Supabase.
> The part I'm proudest of: the API never talks to Postgres directly. It calls Supabase with the
> caller's own token, so row-level security covers the web app, API keys, and even Claude or Cursor
> connecting through the built-in MCP server. No ownership checks to forget.
>
> Also inside: Stripe and Razorpay (UPI), SMS and WhatsApp sign-in codes, a permission matrix, a
> Gemini assistant, white-label branding, and AGENTS.md plus Claude Code skills so coding agents can
> add features safely.
>
> You can sign up on the live app and click around. I'd love feedback, especially on the RLS
> approach.

### Hacker News (Show HN)

Rules: https://news.ycombinator.com/showhn.html. Post on a weekday morning US time; reply to every
comment; don't ask anyone to upvote.

**Title:** Show HN: FastAPI Supabase Starter – SaaS starter where RLS also guards API keys

**URL:** https://starter.budeglobal.in

**Text:**

> I built a paid SaaS starter for Python: FastAPI + React on Supabase, forked from Tiangolo's
> Full-Stack FastAPI Template.
>
> The design choice I'd like feedback on: the backend never connects to Postgres directly. Every
> request calls Supabase's REST API with the caller's own JWT, so row-level security decides what
> each query can see. That holds for the web app, for personal API keys (resolved to the owner,
> then run as them) and for the MCP server, so an AI client acting for a user can't read beyond
> that user's rows. The secret key is used only for work no user owns: verified payment webhooks,
> recording payments, resolving API keys.
>
> Permissions are (resource, action) pairs in one SQL function, has_permission(), which RLS
> policies, FastAPI dependencies and the UI all use. SQL error codes map to HTTP statuses, so a
> policy that raises 42501 becomes a 403 without code in the route.
>
> It also has organizations and invitations, Stripe and Razorpay with idempotent webhooks, a Gemini
> assistant whose tools double as MCP tools, and a public site pre-rendered with TanStack Start.
>
> Live app (sign up with Google or email): https://starter.budeglobal.in/login?mode=signup
> Docs: https://github.com/BUDEGlobalEnterprise/fastapi-supabase-starter
>
> It's ₹1,999 (about the price of a book) for the source. Happy to answer anything about the RLS
> setup, even if you build your own.

### Reddit (r/FastAPI, r/Supabase)

Read each subreddit's rules on self-promotion first, and say up front that it's paid.

**Title:** I built a FastAPI + Supabase SaaS starter where RLS protects API keys and MCP clients too (paid, feedback welcome)

> Disclosure: this is a paid product I made. Posting because the architecture might be useful even
> if you never buy it.
>
> The backend calls Supabase with each caller's own token instead of connecting to Postgres, so
> row-level security applies to everything: the web app, API keys, and AI clients over MCP.
> Permissions live in one SQL function used by RLS, the API and the UI.
>
> What's in it: sign-in (passwords, codes, OAuth, SMS/WhatsApp), organizations and roles, Stripe
> and Razorpay, a Gemini assistant plus MCP server, admin console, branding, and a pre-rendered
> public site.
>
> Live app: https://starter.budeglobal.in · Docs: https://github.com/BUDEGlobalEnterprise/fastapi-supabase-starter
>
> Questions and criticism about the RLS approach welcome.

### LinkedIn / X

> Launched: FastAPI Supabase Starter 🚀
>
> A Python-first SaaS starter: FastAPI + React on Supabase with auth, teams, roles, Stripe and
> Razorpay, a Gemini assistant and an MCP server, all behind Postgres row-level security.
>
> One-time from ₹1,999 · https://starter.budeglobal.in

## Where to submit

Free tiers on launch sites often come with a waiting line; the paid "skip the line" options are
optional. Tick each one off as it goes live.

**Launch sites**

| Done | Site | Submit at | Notes |
|:---:|---|---|---|
| ☑ | Product Hunt | https://www.producthunt.com/products/fastapi-supabase-starter | Live |
| ☐ | Hacker News (Show HN) | https://news.ycombinator.com/submit | Technical text above |
| ☐ | DevHunt | https://devhunt.org | Developer tools only; GitHub sign-in |
| ☐ | Uneed | https://www.uneed.best/submit-a-tool | |
| ☐ | Microlaunch | https://microlaunch.net | |
| ☐ | Peerlist Launchpad | https://peerlist.io/launchpad | Needs a Peerlist profile |
| ☐ | Fazier | https://fazier.com | |
| ☐ | TinyLaunch | https://www.tinylaunch.com | |
| ☐ | Launching Next | https://www.launchingnext.com/submit/ | |
| ☐ | Indie Hackers | https://www.indiehackers.com/products | Add a product page, then post a launch story |

**Directories**

| Done | Site | Submit at | Notes |
|:---:|---|---|---|
| ☐ | StarterIndex | https://starterindex.com/add-boilerplate | Has a FastAPI category and lists paid starters |
| ☐ | SaaS Boilerplates | https://saasboilerplates.dev/submit | Lists paid starters with prices |
| ☐ | Made with Supabase | https://www.madewithsupabase.com (Submit a project) | The live site runs on Supabase; sign in first |
| ☐ | SaaSHub | https://www.saashub.com/submit | Add the alternatives above |
| ☐ | AlternativeTo | https://alternativeto.net | Add it as an alternative to the starters above |
| ☐ | Twelve Tools | https://twelve.tools | |
| — | BoilerplateHub | https://boilerplatehub.com | Later: only accepts starters with an affiliate program |
| — | BetaList | https://betalist.com/submit | Skip: for products that haven't launched yet |

**Communities**

| Done | Where | Notes |
|:---:|---|---|
| ☐ | r/FastAPI, r/Supabase | Post above; check self-promotion rules |
| ☐ | r/SaaS, r/SideProject, r/developersIndia | Lead with the story, not the link |
| ☐ | dev.to, Hashnode | Re-post a blog article from the site with its canonical URL set to the original |

**GitHub lists**

| Done | List | Pull request |
|:---:|---|---|
| ☐ | xcomptek/awesome-saas-boilerplates (Python › FastAPI) | [#254](https://github.com/xcomptek/awesome-saas-boilerplates/pull/254), open |
| ☐ | lyqht/awesome-supabase (Community Starters) | [#86](https://github.com/lyqht/awesome-supabase/pull/86), open |
| ☐ | giovannism20/awesome-supabase (Tools and Extensions) | [#37](https://github.com/giovannism20/awesome-supabase/pull/37), open |
| — | mjhea0/awesome-fastapi | Later: needs a year of history and 100+ stars |
