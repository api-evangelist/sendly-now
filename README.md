# sendly-now

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

Sendly provides an Email API enhanced with AI capabilities for both transactional and marketing communications. It offers features such as scoped API keys, phishing screening, visual workflow builders, and integrations with Claude AI. Developers can send emails, manage campaigns, and verify domains through a unified API platform.

**Areas:** Email · API · Transactional Email · Marketing Campaigns · Workflow Automation · AI Integration · Developer Platform

## sendly-now on APIs.io

Everything profiled for sendly-now is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sendly-now/](https://apis.io/providers/sendly-now/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [sendly-now Account API](https://apis.io/apis/sendly-now/sendly-now-account-api/) — The signed-in person's own account: profile, notification channels, data export, deletion, and the project the dashboard opens on. For a session or an agent…
- [sendly-now Analytics API](https://apis.io/apis/sendly-now/sendly-now-analytics-api/) — Aggregate sending and engagement metrics. Every read is bounded to a window of at most 90 days and cached for 15 minutes.
- [sendly-now API Keys API](https://apis.io/apis/sendly-now/sendly-now-api-keys-api/) — Project-scoped sending/API credentials. All four operations are documented; minting and rotation answer with a one-time reveal link rather than the secret,…
- [sendly-now Billing API](https://apis.io/apis/sendly-now/sendly-now-billing-api/) — The project's plan, its metered Stripe subscription, and the two Stripe-hosted pages (Checkout and the billing portal). An agent gets a single-use `/go/`…
- [sendly-now Campaigns API](https://apis.io/apis/sendly-now/sendly-now-campaigns-api/) — Bulk sends to a list, segment, or filtered audience. Served by the `/api/v1` surface (bare payloads, RFC 9457 errors).
- [sendly-now Compatibility API](https://apis.io/apis/sendly-now/sendly-now-compatibility-api/) — Drop-in endpoints for the Resend, SendGrid, Postmark, Mailgun and Plunk send APIs, so an existing integration can switch by changing its base URL and key.…
- [sendly-now Connections API](https://apis.io/apis/sendly-now/sendly-now-connections-api/) — The services a project or a person is connected to: the project's Slack workspace, the domains whose DNS DoDomain manages, and the AI apps connected to a…
- [sendly-now Contacts API](https://apis.io/apis/sendly-now/sendly-now-contacts-api/) — Manage subscribers and per-contact custom data.
- [sendly-now Deliverability API](https://apis.io/apis/sendly-now/sendly-now-deliverability-api/) — Why mail from one of your domains is or is not arriving: DNS identity, recent delivery outcomes, and one recipient's suppression state, composed into findings.
- [sendly-now Domains API](https://apis.io/apis/sendly-now/sendly-now-domains-api/) — Register sending domains and manage SES verification.
- [sendly-now Emails API](https://apis.io/apis/sendly-now/sendly-now-emails-api/) — Send transactional email and inspect deliveries.
- [sendly-now Events API](https://apis.io/apis/sendly-now/sendly-now-events-api/) — Track custom contact events from your application.
- [sendly-now Lists API](https://apis.io/apis/sendly-now/sendly-now-lists-api/) — Self-serve list membership. These two endpoints accept sending-only keys so they can back a public subscribe/unsubscribe form; list management itself is…
- [sendly-now Mailboxes API](https://apis.io/apis/sendly-now/sendly-now-mailboxes-api/) — Real receiving mailboxes on your verified domains. Creating one changes how that domain's mail is routed; the messages a mailbox receives are not part of…
- [sendly-now Members API](https://apis.io/apis/sendly-now/sendly-now-members-api/) — A project's members and their roles. A project is the team: a member is added by the email of an existing Sendly account and joins at once, so there are no…
- [sendly-now Organizations API](https://apis.io/apis/sendly-now/sendly-now-organizations-api/) — The organizations a person belongs to, each a group of projects: their overview and the merged inbox across their mailboxes. An organization never widens…
- [sendly-now Projects API](https://apis.io/apis/sendly-now/sendly-now-projects-api/) — The project a credential is scoped to, and creating new ones. Configuring an existing project stays a dashboard action.
- [sendly-now Segments API](https://apis.io/apis/sendly-now/sendly-now-segments-api/) — Saved audiences — a `DYNAMIC` filter re-evaluated on read, or a `STATIC` membership list. Served by the `/api/v1` surface (bare payloads, RFC 9457 errors).
- [sendly-now Support API](https://apis.io/apis/sendly-now/sendly-now-support-api/) — Write to Sendly's support team and list what was written, and appeal a project's sending suspension. A ticket reaches the same inbox as the dashboard's…
- [sendly-now Suppression API](https://apis.io/apis/sendly-now/sendly-now-suppression-api/) — Project-scoped suppression list. Hard bounces and complaints land here automatically.
- [sendly-now Templates API](https://apis.io/apis/sendly-now/sendly-now-templates-api/) — Reusable email templates referenced by send operations.
- [sendly-now Topics API](https://apis.io/apis/sendly-now/sendly-now-topics-api/) — The subjects you mail about, and what each contact has said about them. A topic answer is a standing decision rather than an audience filter: it applies…
- [sendly-now Usage API](https://apis.io/apis/sendly-now/sendly-now-usage-api/) — Current email usage against the monthly and daily limits the platform enforces.
- [sendly-now Validation API](https://apis.io/apis/sendly-now/sendly-now-validation-api/) — Bulk email validation, billed per address: a bounded synchronous batch, and background runs over a whole list. Distinct from `Verify`, which is the one…
- [sendly-now Verify API](https://apis.io/apis/sendly-now/sendly-now-verify-api/) — Open email-validation endpoint (no auth required). Used by the marketing-site verifier.
- [sendly-now Webhooks API](https://apis.io/apis/sendly-now/sendly-now-webhooks-api/) — User-managed outbound webhooks for email and contact events.
- [sendly-now Workflows API](https://apis.io/apis/sendly-now/sendly-now-workflows-api/) — Event-triggered automations and the contact runs through them. Served by the `/api/v1` surface (bare payloads, RFC 9457 errors).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Sendly Now Webhooks](https://apis.io/asyncapis/sendly-now/sendly-now-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Sendly Now Agentic Access](https://apis.io/agentic-access/sendly-now/sendly-now-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [ComposeMailboxMessage](https://apis.io/schemas/sendly-now/sendly-now-compose-mailbox-message/)
- [Domain](https://apis.io/schemas/sendly-now/sendly-now-domain/)
- [DomainLogoReadinessV1](https://apis.io/schemas/sendly-now/sendly-now-domain-logo-readiness-v1/)
- [MailboxConversationReplyBody](https://apis.io/schemas/sendly-now/sendly-now-mailbox-conversation-reply-body/)
- [SendEmail](https://apis.io/schemas/sendly-now/sendly-now-send-email/)
- [SendEmailV1](https://apis.io/schemas/sendly-now/sendly-now-send-email-v1/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Sendly Now Context](https://apis.io/jsonld/sendly-now/sendly-now-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [sendly-now API Rules](https://apis.io/rules/sendly-now/sendly-now-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Sendly Now Authentication](https://apis.io/security/sendly-now/sendly-now-authentication/)
- [Sendly Now Domain Security](https://apis.io/security/sendly-now/sendly-now-domain-security/)
- [Sendly Now Vulnerability Disclosure](https://apis.io/security/sendly-now/sendly-now-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Sendly Now Scopes](https://apis.io/scopes/sendly-now/sendly-now-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sendly Now Plans Pricing](https://apis.io/plans/sendly-now/sendly-now-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sendly.now/)
- [Documentation](https://docs.sendly.now/)
- [API reference](https://sendly.now/changelog)
- [Pricing](https://sendly.now/pricing)
- [Support](https://app.sendly.now/support)
- [Trust centre](https://sendly.now/trust)
- [Terms of service](https://sendly.now/terms)
- [Privacy policy](https://sendly.now/privacy)
- [GitHub](https://github.com/DevinoSolutions)
- [Status](https://status.sendly.now/)

## API Evangelist rating

**Kin Score 67.6** — exemplar · rubric 0.25.0 · scored 2026-10-31

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 70.7 |
| Contract governance | 79.1 |
| Operational transparency | 39.5 |
| Developer ergonomics | 49.3 |
| Access clarity | 71.6 |

**Agent readiness 64.4** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | — |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sendly-now/](https://apis.io/providers/sendly-now/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for sendly-now: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sendly-now/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
