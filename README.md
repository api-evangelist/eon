# Eon

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

Eon is a next-generation cloud backup and data-protection platform that turns cloud backups into live, searchable, strategic assets across AWS, Google Cloud, and Azure. It provides agentless backup, cloud backup posture management, ransomware protection, global search over backups, live and granular file/resource restore, and a zero-ETL data-lake storage tier that makes old snapshots useful for analytics and AI. Eon exposes a REST API (OpenAPI 3.0, 99 operations) covering source/restore accounts, resources, vaults, snapshots, backup policies, restores, jobs, IAM, billing, and multi-party action approvals, with an official Go SDK and Terraform provider. Backed by BOND Capital and Lightspeed Venture Partners.

**Areas:** Company · Cloud Backup · Data Protection · Disaster Recovery · Ransomware Protection · Backup · Cloud Storage · Data Lake · Multi-Cloud · AWS · Microsoft Azure · Google Cloud

## Eon on APIs.io

Everything profiled for Eon is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/eon/](https://apis.io/providers/eon/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Eon Accounts API](https://apis.io/apis/eon/eon-accounts-api/) — Manage connected cloud accounts onboarded to Eon.
- [Eon Action Approvals API](https://apis.io/apis/eon/eon-actionapprovals-api/) — The actionApprovals API from Eon — 3 operation(s) for actionapprovals.
- [Eon Auth API](https://apis.io/apis/eon/eon-auth-api/) — Authentication and access token management.
- [Eon Backups API](https://apis.io/apis/eon/eon-backups-api/) — The backups API from Eon — 1 operation(s) for backups.
- [Eon Billing API](https://apis.io/apis/eon/eon-billing-api/) — Access billing and usage metering information.
- [Eon Dashboard API](https://apis.io/apis/eon/eon-dashboard-api/) — The dashboard API from Eon — 1 operation(s) for dashboard.
- [Eon Iam API](https://apis.io/apis/eon/eon-iam-api/) — The iam API from Eon — 8 operation(s) for iam.
- [Eon Jobs API](https://apis.io/apis/eon/eon-jobs-api/) — Track backup, restore, and other asynchronous jobs.
- [Eon Resources API](https://apis.io/apis/eon/eon-resources-api/) — Discover and manage protected cloud resources.
- [Eon Snapshots API](https://apis.io/apis/eon/eon-snapshots-api/) — Manage resource snapshots and point-in-time recovery points.
- [Eon Vaults API](https://apis.io/apis/eon/eon-vaults-api/) — Manage backup vaults that store snapshots.
- [Eon Backup Policies API](https://apis.io/apis/eon/eon-backup-policies-api/) — Define and manage backup policies and schedules.
- [Eon Database Snapshots API](https://apis.io/apis/eon/eon-database-snapshots-api/) — Manage database snapshots and their recovery points.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [eon](https://apis.io/servers/eon/eon/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Eon Agentic Access](https://apis.io/agentic-access/eon/eon-agentic-access/)

#### Collections (13)

Postman and Open Collection request collections.

- [Eon accounts API](https://apis.io/collections/eon/open-eon-accounts-api/)
- [Eon accounts actionApprovals API](https://apis.io/collections/eon/open-eon-actionapprovals-api/)
- [Eon accounts auth API](https://apis.io/collections/eon/open-eon-auth-api/)
- [Eon accounts backupPolicies API](https://apis.io/collections/eon/open-eon-backuppolicies-api/)
- [Eon accounts backups API](https://apis.io/collections/eon/open-eon-backups-api/)
- [Eon accounts billing API](https://apis.io/collections/eon/open-eon-billing-api/)
- [Eon accounts dashboard API](https://apis.io/collections/eon/open-eon-dashboard-api/)
- [Eon accounts databaseSnapshots API](https://apis.io/collections/eon/open-eon-databasesnapshots-api/)
- [Eon accounts iam API](https://apis.io/collections/eon/open-eon-iam-api/)
- [Eon accounts jobs API](https://apis.io/collections/eon/open-eon-jobs-api/)
- [Eon accounts resources API](https://apis.io/collections/eon/open-eon-resources-api/)
- [Eon accounts snapshots API](https://apis.io/collections/eon/open-eon-snapshots-api/)
- [Eon accounts vaults API](https://apis.io/collections/eon/open-eon-vaults-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Eon Openapi Overlay](https://apis.io/overlays/eon/eon-openapi-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Eon Authentication](https://apis.io/security/eon/eon-authentication/)
- [Eon Domain Security](https://apis.io/security/eon/eon-domain-security/)
- [Eon Trust Center](https://apis.io/security/eon/eon-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.eon.io)
- [Documentation](https://docs.eon.io)
- [Getting started](https://console.eon.io/global-management/api-credentials)
- [API reference](https://docs.eon.io)
- [Pricing](https://www.eon.io/pricing)
- [Sign up](https://www.eon.io/get-a-demo)
- [Blog](https://www.eon.io/resources)
- [Compliance](https://trust.eon.io)
- [Terms of service](https://www.eon.io/terms-of-use)
- [Privacy policy](https://www.eon.io/privacy-policy)
- [GitHub](https://github.com/eon-io)

## API Evangelist rating

**Kin Score 44.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 50.6 |
| Contract governance | 4.5 |
| Operational transparency | 2.6 |
| Developer ergonomics | 49.4 |
| Access clarity | 60.5 |

**Agent readiness 35.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/eon/](https://apis.io/providers/eon/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Eon: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/eon/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
