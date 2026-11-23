# Rial

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

Rial provides a photo verification platform that authenticates images at the moment of capture. It offers APIs, SDKs, and a CLI for businesses to verify photos, detect AI‑generated images, and manage credit balances. The service includes sandbox testing, detailed error handling, and tools for integrating verification into web, mobile, and AI agent workflows.

**Areas:** PhotoVerification · API · SDK · AIDetection · Security · Company

## Rial on APIs.io

Everything profiled for Rial is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rial-io/](https://apis.io/providers/rial-io/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Rial Audits API](https://apis.io/apis/rial-io/rial-io-audits-api/) — Check a photo you already have. `POST /v1/audits/sync` answers AI detection in the same call; every other audit is a verification in `audit` mode.
- [Rial Credits API](https://apis.io/apis/rial-io/rial-io-credits-api/) — Prepaid photo credits at US$0.20 a photo, bought in packs by an agent with the card a person saved, under a monthly spend cap. Through the API every feature…
- [Rial Databases API](https://apis.io/apis/rial-io/rial-io-databases-api/) — Create, update, inspect and synchronize tenant-scoped databases used by reusable verification templates. Callable with a dashboard session or secret API key.
- [Rial Templates API](https://apis.io/apis/rial-io/rial-io-templates-api/) — Publish, update, revoke and inspect link templates — the reusable capture links behind `/l/{token}` (a compact JWT carrying the org and template slugs; the…
- [Rial Verifications API](https://apis.io/apis/rial-io/rial-io-verifications-api/) — Create, fetch, list, and finalize verifications. The core of the API — every tenant integration starts here.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Rial Agentic Access](https://apis.io/agentic-access/rial-io/rial-io-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AuditVerification](https://apis.io/schemas/rial-io/rial-io-audit-verification/)
- [CreateVerificationRequest](https://apis.io/schemas/rial-io/rial-io-create-verification-request/)
- [Credits](https://apis.io/schemas/rial-io/rial-io-credits/)
- [DeveloperVerification](https://apis.io/schemas/rial-io/rial-io-developer-verification/)
- [LinkTemplate](https://apis.io/schemas/rial-io/rial-io-link-template/)
- [OperatorDatabase](https://apis.io/schemas/rial-io/rial-io-operator-database/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Rial Io Context](https://apis.io/jsonld/rial-io/rial-io-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Rial API Rules](https://apis.io/rules/rial-io/rial-io-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Rial Authentication](https://apis.io/security/rial-io/rial-io-authentication/)
- [Rial Domain Security](https://apis.io/security/rial-io/rial-io-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://rial.io/)
- [Documentation](https://docs.rial.io/)
- [Getting started](https://docs.rial.io/quickstart.md)
- [API reference](https://docs.rial.io/api-reference/)
- [Trust centre](https://trust.rial.io/)
- [Privacy policy](https://www.rial.io/privacy)
- [Status](https://status.rial.io)

## API Evangelist rating

**Kin Score 50.9** — developing · rubric 0.28.0 · scored 2026-11-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 64.7 |
| Contract governance | 79.1 |
| Operational transparency | 23.8 |
| Developer ergonomics | 54.8 |
| Access clarity | 14.9 |

**Agent readiness 64.2** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 25.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rial-io/](https://apis.io/providers/rial-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rial: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rial-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
