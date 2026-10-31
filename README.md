# Quay

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

Quay is a container image registry that enables you to build, store, distribute, and deploy container images with built-in security scanning, access controls, and automated build triggers. Available as a hosted service at Quay.io or as a self-hosted solution through Red Hat Quay.

**Areas:** Container Images · Containers · Red Hat · Registry · Security Scanning

## Quay on APIs.io

Everything profiled for Quay is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/quay/](https://apis.io/providers/quay/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Quay Build API](https://apis.io/apis/quay/quay-build-api/) — Manage Dockerfile builds, build logs, build triggers, and build configuration.
- [Quay Manifest API](https://apis.io/apis/quay/quay-manifest-api/) — Inspect image manifests, manifest layers, and labels associated with a pushed image.
- [Quay Organization API](https://apis.io/apis/quay/quay-organization-api/) — Manage Quay organizations, organization members, billing, application tokens, and organization-wide settings.
- [Quay Permission API](https://apis.io/apis/quay/quay-permission-api/) — Manage user and team permissions on repositories.
- [Quay Repository API](https://apis.io/apis/quay/quay-repository-api/) — Manage container image repositories including create, list, update, delete, visibility, descriptions, and metadata.
- [Quay Robot API](https://apis.io/apis/quay/quay-robot-api/) — Manage robot accounts used for automated repository access including credentials and permissions.
- [Quay Security API](https://apis.io/apis/quay/quay-security-api/) — Retrieve vulnerability scan results for repository images.
- [Quay Tag API](https://apis.io/apis/quay/quay-tag-api/) — Manage repository image tags including listing, restoring, expiring, and deleting tags.
- [Quay Team API](https://apis.io/apis/quay/quay-team-api/) — Manage organization teams, team membership, team roles, and team permissions on repositories.
- [Quay User API](https://apis.io/apis/quay/quay-user-api/) — Manage Quay user accounts, profile, starred repositories, and personal OAuth tokens.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/quay/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Quay Agentic Access](https://apis.io/agentic-access/quay/quay-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Quay Manifest Security Scan](https://apis.io/schemas/quay/quay-manifest-security/)
- [Quay Repository](https://apis.io/schemas/quay/quay-repository/)
- [Quay Tag](https://apis.io/schemas/quay/quay-tag/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Quay Context](https://apis.io/jsonld/quay/quay-context/)

#### Collections (11)

Postman and Open Collection request collections.

- [Quay Container Registry API](https://apis.io/collections/quay/open-quay/)
- [Quay Container Registry Build API](https://apis.io/collections/quay/open-quay-build-api/)
- [Quay Container Registry Build Manifest API](https://apis.io/collections/quay/open-quay-manifest-api/)
- [Quay Container Registry Build Organization API](https://apis.io/collections/quay/open-quay-organization-api/)
- [Quay Container Registry Build Permission API](https://apis.io/collections/quay/open-quay-permission-api/)
- [Quay Container Registry Build Repository API](https://apis.io/collections/quay/open-quay-repository-api/)
- [Quay Container Registry Build Robot API](https://apis.io/collections/quay/open-quay-robot-api/)
- [Quay Container Registry Build Security API](https://apis.io/collections/quay/open-quay-security-api/)
- [Quay Container Registry Build Tag API](https://apis.io/collections/quay/open-quay-tag-api/)
- [Quay Container Registry Build Team API](https://apis.io/collections/quay/open-quay-team-api/)
- [Quay Container Registry Build User API](https://apis.io/collections/quay/open-quay-user-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Quay — jsonschema rules](https://apis.io/rules/quay/quay-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Quay Authentication](https://apis.io/security/quay/quay-authentication/)
- [Quay Domain Security](https://apis.io/security/quay/quay-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Quay Scopes](https://apis.io/scopes/quay/quay-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Quay Plans Pricing](https://apis.io/plans/quay/quay-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Quay Rate Limits](https://apis.io/rate-limits/quay/quay-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Quay Finops](https://apis.io/finops/quay/quay-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://quay.io/)
- [Documentation](https://docs.quay.io/)
- [Getting started](https://docs.quay.io/guides/)
- [Pricing](https://quay.io/plans/)
- [Support](https://access.redhat.com/products/red-hat-quay/)
- [Blog](https://www.redhat.com/en/blog)
- [GitHub](https://github.com/quay)

## API Evangelist rating

**Kin Score 40.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 56.9 |
| Contract governance | 9.8 |
| Operational transparency | 10.5 |
| Developer ergonomics | 40.5 |
| Access clarity | 31.6 |

**Agent readiness 27.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/quay/](https://apis.io/providers/quay/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Quay: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/quay/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
