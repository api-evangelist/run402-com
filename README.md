# run402-com

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Run402 provides open-source backend infrastructure for AI agents, offering services such as managed PostgreSQL databases, authentication, storage, serverless functions, and static/SSR hosting via a CLI. It enables agent-controlled prepaid usage through x402 (USDC on Base) or MPP (pathUSD on Tempo, or sats over Bitcoin Lightning). The platform is designed for developers to deploy full-stack applications without traditional cloud consoles or signup flows, emphasizing tool-native integration via MCP.

**Areas:** AI · Infrastructure · Backend · Open-source · Agents

## run402-com on APIs.io

Everything profiled for run402-com is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/run402-com/](https://apis.io/providers/run402-com/)** — or go straight to one of the APIs or properties below.

### APIs (43)

- run402-com Admin API — SQL migrations, RLS policies, usage, and schema introspection
- run402-com Agent API — Agent contact registration (wallet auth, free within tier)
- run402-com Agent Messaging API — The AgentMessaging API from run402-com — 11 operation(s) for agentmessaging.
- run402-com AI API — The AI API from run402-com — 4 operation(s) for ai.
- run402-com App Repos API — Plain, unencrypted git repositories owned by a project and written by its app (app-repos). Many per project, with an always-present `default`; linear…
- run402-com Apply API — Unified apply primitive — plan + commit + operations + resume.
- run402-com Auth API — User signup, login, token refresh, and logout
- run402-com Billing API — Prepaid allowance accounts and checkout
- run402-com Buzz Control Plane API — The Buzz Control Plane API from run402-com — 24 operation(s) for buzz control plane.
- run402-com CI Federation API — The CI Federation API from run402-com — 5 operation(s) for ci federation.
- run402-com Console API — The console for the person behind an agent (console spec). API-first: the reference web console is just a consumer of these endpoints.
- run402-com Content API — v1.34 generic CAS content plan/commit (used internally by the SDK for byte uploads).
- run402-com Contracts API — The Contracts API from run402-com — 11 operation(s) for contracts.
- run402-com Control Plane API — The ControlPlane API from run402-com — 30 operation(s) for controlplane.
- run402-com Control Plane Auth API — The ControlPlaneAuth API from run402-com — 1 operation(s) for controlplaneauth.
- run402-com Diagnostics API — The Diagnostics API from run402-com — 1 operation(s) for diagnostics.
- run402-com Escalations API — The Escalations API from run402-com — 7 operation(s) for escalations.
- run402-com Faucet API — Testnet USDC drip for development
- run402-com Feedback API — Feedback / contact endpoint (wallet auth, free within tier)
- run402-com Functions API — Serverless function deploy, invoke, logs, and secrets
- run402-com Health API — Health check and x402 discovery
- run402-com Identity Links API — The Identity Links API from run402-com — 7 operation(s) for identity links.
- run402-com Image API — AI image generation (x402-gated, per-call)
- run402-com Jobs API — The Jobs API from run402-com — 4 operation(s) for jobs.
- run402-com Live API — The Live API from run402-com — 2 operation(s) for live.
- run402-com Mailboxes API — Project-scoped email at slug@project-host.mail.run402.com, with ProjectDomain custom addresses and managed fallback
- run402-com Message API — The Message API from run402-com — 1 operation(s) for message.
- run402-com Org API — The Org API from run402-com — 28 operation(s) for org.
- run402-com Project Archives API — Portable archive export for the supported Run402 Core runtime slice of a Cloud project. This is the no-lock-in path, not a backup/SLA or allowance/spend-cap…
- run402-com Project Branches API — The Project Branches API from run402-com — 3 operation(s) for project branches.
- run402-com Project domains API — Project-scoped desired/observed/effective lifecycle for custom web and email domains
- run402-com Project Snapshots API — The Project Snapshots API from run402-com — 4 operation(s) for project snapshots.
- run402-com Project Transfers API — The Project Transfers API from run402-com — 7 operation(s) for project transfers.
- run402-com Projects API — Provision and manage database projects (wallet auth, free within tier)
- run402-com Publish API — Publish and fork app versions
- run402-com REST API — PostgREST proxy — full CRUD on your tables
- run402-com SSR Cache API — The SSR Cache API from run402-com — 2 operation(s) for ssr cache.
- run402-com Stable Hosts API — The Stable Hosts API from run402-com — 22 operation(s) for stable hosts.
- run402-com Storage API — Upload, download, delete, sign, and list files
- run402-com Subdomains API — Custom subdomain management for deployments
- run402-com Tiers API — Wallet-level tier lease — set (start, renew, upgrade) and check status
- run402-com Vault API — The vault API from run402-com — 45 operation(s) for vault.
- run402-com Vouchers API — Allowance vouchers: single-use promo codes redeemable by an authenticated wallet for allowance. A redeemed voucher spends like any other allowance (tiers,…

_These APIs get their own pages on APIs.io at the next catalog build, and this README is re-rendered with links when they do._

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://run402.com/)
- [Documentation](https://docs.run402.com/)
- [Getting started](https://run402.com/install.txt)
- [API reference](https://run402.com/openapi.json)
- [Pricing](https://run402.com/pricing)
- [Changelog](https://docs.run402.com/concepts/releases/)
- [Blog](https://blog.run402.com/)
- [Terms of service](https://run402.com/humans/terms.html)
- [Privacy policy](https://run402.com/humans/privacy.html)
- [GitHub](https://github.com/kychee-com)
- [Status](https://status.run402.com/)

## API Evangelist rating

Not yet rated. See [apis.io/providers/run402-com/](https://apis.io/providers/run402-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for run402-com: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/run402-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
