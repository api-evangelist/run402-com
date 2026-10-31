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

- [run402-com Admin API](https://apis.io/apis/run402-com/run402-com-admin-api/) — SQL migrations, RLS policies, usage, and schema introspection
- [run402-com Agent API](https://apis.io/apis/run402-com/run402-com-agent-api/) — Agent contact registration (wallet auth, free within tier)
- [run402-com Agent Messaging API](https://apis.io/apis/run402-com/run402-com-agentmessaging-api/) — The AgentMessaging API from run402-com — 11 operation(s) for agentmessaging.
- [run402-com AI API](https://apis.io/apis/run402-com/run402-com-ai-api/) — The AI API from run402-com — 4 operation(s) for ai.
- [run402-com App Repos API](https://apis.io/apis/run402-com/run402-com-app-repos-api/) — Plain, unencrypted git repositories owned by a project and written by its app (app-repos). Many per project, with an always-present `default`; linear…
- [run402-com Apply API](https://apis.io/apis/run402-com/run402-com-apply-api/) — Unified apply primitive — plan + commit + operations + resume.
- [run402-com Auth API](https://apis.io/apis/run402-com/run402-com-auth-api/) — User signup, login, token refresh, and logout
- [run402-com Billing API](https://apis.io/apis/run402-com/run402-com-billing-api/) — Prepaid allowance accounts and checkout
- [run402-com Buzz Control Plane API](https://apis.io/apis/run402-com/run402-com-buzz-control-plane-api/) — The Buzz Control Plane API from run402-com — 24 operation(s) for buzz control plane.
- [run402-com CI Federation API](https://apis.io/apis/run402-com/run402-com-ci-federation-api/) — The CI Federation API from run402-com — 5 operation(s) for ci federation.
- [run402-com Console API](https://apis.io/apis/run402-com/run402-com-console-api/) — The console for the person behind an agent (console spec). API-first: the reference web console is just a consumer of these endpoints.
- [run402-com Content API](https://apis.io/apis/run402-com/run402-com-content-api/) — v1.34 generic CAS content plan/commit (used internally by the SDK for byte uploads).
- [run402-com Contracts API](https://apis.io/apis/run402-com/run402-com-contracts-api/) — The Contracts API from run402-com — 11 operation(s) for contracts.
- [run402-com Control Plane API](https://apis.io/apis/run402-com/run402-com-controlplane-api/) — The ControlPlane API from run402-com — 30 operation(s) for controlplane.
- [run402-com Control Plane Auth API](https://apis.io/apis/run402-com/run402-com-controlplaneauth-api/) — The ControlPlaneAuth API from run402-com — 1 operation(s) for controlplaneauth.
- [run402-com Diagnostics API](https://apis.io/apis/run402-com/run402-com-diagnostics-api/) — The Diagnostics API from run402-com — 1 operation(s) for diagnostics.
- [run402-com Escalations API](https://apis.io/apis/run402-com/run402-com-escalations-api/) — The Escalations API from run402-com — 7 operation(s) for escalations.
- [run402-com Faucet API](https://apis.io/apis/run402-com/run402-com-faucet-api/) — Testnet USDC drip for development
- [run402-com Feedback API](https://apis.io/apis/run402-com/run402-com-feedback-api/) — Feedback / contact endpoint (wallet auth, free within tier)
- [run402-com Functions API](https://apis.io/apis/run402-com/run402-com-functions-api/) — Serverless function deploy, invoke, logs, and secrets
- [run402-com Health API](https://apis.io/apis/run402-com/run402-com-health-api/) — Health check and x402 discovery
- [run402-com Identity Links API](https://apis.io/apis/run402-com/run402-com-identity-links-api/) — The Identity Links API from run402-com — 7 operation(s) for identity links.
- [run402-com Image API](https://apis.io/apis/run402-com/run402-com-image-api/) — AI image generation (x402-gated, per-call)
- [run402-com Jobs API](https://apis.io/apis/run402-com/run402-com-jobs-api/) — The Jobs API from run402-com — 4 operation(s) for jobs.
- [run402-com Live API](https://apis.io/apis/run402-com/run402-com-live-api/) — The Live API from run402-com — 2 operation(s) for live.
- [run402-com Mailboxes API](https://apis.io/apis/run402-com/run402-com-mailboxes-api/) — Project-scoped email at slug@project-host.mail.run402.com, with ProjectDomain custom addresses and managed fallback
- [run402-com Message API](https://apis.io/apis/run402-com/run402-com-message-api/) — The Message API from run402-com — 1 operation(s) for message.
- [run402-com Org API](https://apis.io/apis/run402-com/run402-com-org-api/) — The Org API from run402-com — 28 operation(s) for org.
- [run402-com Project Archives API](https://apis.io/apis/run402-com/run402-com-project-archives-api/) — Portable archive export for the supported Run402 Core runtime slice of a Cloud project. This is the no-lock-in path, not a backup/SLA or allowance/spend-cap…
- [run402-com Project Branches API](https://apis.io/apis/run402-com/run402-com-project-branches-api/) — The Project Branches API from run402-com — 3 operation(s) for project branches.
- [run402-com Project domains API](https://apis.io/apis/run402-com/run402-com-project-domains-api/) — Project-scoped desired/observed/effective lifecycle for custom web and email domains
- [run402-com Project Snapshots API](https://apis.io/apis/run402-com/run402-com-project-snapshots-api/) — The Project Snapshots API from run402-com — 4 operation(s) for project snapshots.
- [run402-com Project Transfers API](https://apis.io/apis/run402-com/run402-com-project-transfers-api/) — The Project Transfers API from run402-com — 7 operation(s) for project transfers.
- [run402-com Projects API](https://apis.io/apis/run402-com/run402-com-projects-api/) — Provision and manage database projects (wallet auth, free within tier)
- [run402-com Publish API](https://apis.io/apis/run402-com/run402-com-publish-api/) — Publish and fork app versions
- [run402-com REST API](https://apis.io/apis/run402-com/run402-com-rest-api/) — PostgREST proxy — full CRUD on your tables
- [run402-com SSR Cache API](https://apis.io/apis/run402-com/run402-com-ssr-cache-api/) — The SSR Cache API from run402-com — 2 operation(s) for ssr cache.
- [run402-com Stable Hosts API](https://apis.io/apis/run402-com/run402-com-stable-hosts-api/) — The Stable Hosts API from run402-com — 22 operation(s) for stable hosts.
- [run402-com Storage API](https://apis.io/apis/run402-com/run402-com-storage-api/) — Upload, download, delete, sign, and list files
- [run402-com Subdomains API](https://apis.io/apis/run402-com/run402-com-subdomains-api/) — Custom subdomain management for deployments
- [run402-com Tiers API](https://apis.io/apis/run402-com/run402-com-tiers-api/) — Wallet-level tier lease — set (start, renew, upgrade) and check status
- [run402-com Vault API](https://apis.io/apis/run402-com/run402-com-vault-api/) — The vault API from run402-com — 45 operation(s) for vault.
- [run402-com Vouchers API](https://apis.io/apis/run402-com/run402-com-vouchers-api/) — Allowance vouchers: single-use promo codes redeemable by an authenticated wallet for allowance. A redeemed voucher spends like any other allowance (tiers,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Run402 Com Webhooks](https://apis.io/asyncapis/run402-com/run402-com-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Run402 Com Agentic Access](https://apis.io/agentic-access/run402-com/run402-com-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [DeployPlanResponse](https://apis.io/schemas/run402-com/run402-com-deploy-plan-response/)
- [Mailbox](https://apis.io/schemas/run402-com/run402-com-mailbox/)
- [ProjectEventFeedPage](https://apis.io/schemas/run402-com/run402-com-project-event-feed-page/)
- [ProjectTransferPreview](https://apis.io/schemas/run402-com/run402-com-project-transfer-preview/)
- [ReleaseInventory](https://apis.io/schemas/run402-com/run402-com-release-inventory/)
- [StableHostResolveResponse](https://apis.io/schemas/run402-com/run402-com-stable-host-resolve-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Run402 Com Context](https://apis.io/jsonld/run402-com/run402-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [run402-com API Rules](https://apis.io/rules/run402-com/run402-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Run402 Com Authentication](https://apis.io/security/run402-com/run402-com-authentication/)
- [Run402 Com Domain Security](https://apis.io/security/run402-com/run402-com-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Run402 Com Scopes](https://apis.io/scopes/run402-com/run402-com-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Run402 Com Plans Pricing](https://apis.io/plans/run402-com/run402-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Run402 Com Rate Limits](https://apis.io/rate-limits/run402-com/run402-com-rate-limits/)

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

**Kin Score 68.7** — exemplar · rubric 0.25.0 · scored 2026-10-29

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 68.6 |
| Contract governance | 79.1 |
| Operational transparency | 73.2 |
| Developer ergonomics | 61.2 |
| Access clarity | 60.0 |

**Agent readiness 58.3** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/run402-com/](https://apis.io/providers/run402-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for run402-com: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/run402-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
