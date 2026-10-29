# Chulalongkorn University

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

Chulalongkorn University is Thailand's oldest public research university, founded in 1917 in Bangkok. Its programmable footprint is small, real, and almost entirely undeclared: there is no developer portal, no open data portal, no published specification of any kind, and no self-service registration anywhere in the estate. What it does operate are two genuine institution-run surfaces. Chula SSO at account.it.chula.ac.th has been in production since January 2017 and is documented endpoint-by-endpoint on a public wiki — a modified CAS 1.0 protocol with an added application-authentication step, backed by the university LDAP directory, with keys issued by email rather than by a console. The Office of the Registrar's CU-REG Course Schedule application answers unauthenticated JSON at cas.reg.chula.ac.th/class/api for its curriculum register and build version, though the thirteen further endpoints its own client declares return 404 from outside the campus network. Everything else that looks like a Chulalongkorn API belongs to somebody else: Chula Digital Collections, which serves the university's only working OAI-PMH endpoint, is a bepress Digital Commons tenancy (digital.car.chula.ac.th is a CNAME to dcchula.bepress.com, adminEmail dc-support@elsevier.com); federated login is a Microsoft Entra ID tenant; DOIs are registered through DataCite and, faculty by faculty, through eleven separate Crossref member records. The institution's own DigiVerse repository publishes no machine-readable interface at all, and the previously recorded claim that it is a DSpace deployment exposing DSpace REST and OAI-PMH does not survive probing. The central data exchange, CU Data Gateway, is restricted to assigned university personnel and unreachable from outside the campus network.

**Areas:** Education · Higher Education · University · Research · Thailand · Bangkok · Identity Federation · SSO · Course Catalog · Research Repository · Library · Open Access

## Chulalongkorn University on APIs.io

Everything profiled for Chulalongkorn University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/chulalongkorn/](https://apis.io/providers/chulalongkorn/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Chula DigiVerse — Institutional Digital Repository](https://apis.io/apis/chulalongkorn/digiverse/) — The university's digital preservation platform for theses, dissertations, rare books, multimedia and digitised manuscripts, operated by the Office of…
- [Chula Digital Collections (bepress Digital Commons tenant)](https://apis.io/apis/chulalongkorn/digital-collections/) — The university's open-access journals, theses and ETD platform, and the only working OAI-PMH endpoint in the estate. The Identify response names "Chula…
- [Chulalongkorn University Identity Federation (Microsoft Entra ID tenant)](https://apis.io/apis/chulalongkorn/entra-federation/) — The university's cloud identity, and the most complete machine-readable contract anywhere in this profile. Entra tenant 271d5e7b-1350-4b96-ab84-52dbda4cf40c…
- [DataCite Membership (consortium organization lygd)](https://apis.io/apis/chulalongkorn/datacite/) — Chulalongkorn University is a DataCite consortium organization, provider id lygd, country TH, with one registered repository — lygd.aguxul, "Chula…
- [Crossref Membership (eleven faculty and institute member records)](https://apis.io/apis/chulalongkorn/crossref/) — Chulalongkorn registers Crossref DOIs through eleven separate member records, one per faculty, institute or office, each with its own prefix — Engineering…
- [ROR Registration (https://ror.org/028wp3y58)](https://apis.io/apis/chulalongkorn/ror/) — Chulalongkorn University's Research Organization Registry record, carrying the Thai and English names, the acronym CU, ten Crossref Funder IDs, GRID…
- [Chula Library Discovery (EBSCO tenant)](https://apis.io/apis/chulalongkorn/library-discovery/) — The Office of Academic Resources fronts its licensed-content discovery through EBSCO, under the named customer account chulalun. The links published on…
- [CU Data Gateway](https://apis.io/apis/chulalongkorn/data-gateway/) — The university's central data exchange, consolidating and sharing data across departments in two connection modes — batch over SFTP and online over an API.…
- [Chulalongkorn University Authentication API](https://apis.io/apis/chulalongkorn/chulalongkorn-authentication-api/) — Session establishment and teardown
- [Chulalongkorn University Curriculum API](https://apis.io/apis/chulalongkorn/chulalongkorn-curriculum-api/) — Degree programs and fields of study
- [Chulalongkorn University Meta API](https://apis.io/apis/chulalongkorn/chulalongkorn-meta-api/) — Service metadata
- [Chulalongkorn University Validation API](https://apis.io/apis/chulalongkorn/chulalongkorn-validation-api/) — Ticket validation for relying applications

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [CU-REG Course Study (Degree Program)](https://apis.io/schemas/chulalongkorn/chulalongkorn-course-study/)
- [Chula SSO Authenticated User](https://apis.io/schemas/chulalongkorn/chulalongkorn-sso-user/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Chulalongkorn Context](https://apis.io/jsonld/chulalongkorn/chulalongkorn-context/)

#### Examples (2)

Example requests and responses.

- [Chulalongkorn Course Studies Example](https://apis.io/examples/chulalongkorn/chulalongkorn-course-studies-example/)
- [Chulalongkorn Sso Servicevalidation Example](https://apis.io/examples/chulalongkorn/chulalongkorn-sso-servicevalidation-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Chulalongkorn Authentication](https://apis.io/security/chulalongkorn/chulalongkorn-authentication/)
- [Chulalongkorn Domain Security](https://apis.io/security/chulalongkorn/chulalongkorn-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Chulalongkorn Plans Pricing](https://apis.io/plans/chulalongkorn/chulalongkorn-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Chulalongkorn Rate Limits](https://apis.io/rate-limits/chulalongkorn/chulalongkorn-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Chulalongkorn Finops](https://apis.io/finops/chulalongkorn/chulalongkorn-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.chula.ac.th/en/)
- [Documentation](https://account.it.chula.ac.th/wiki/doku.php)
- [API reference](https://account.it.chula.ac.th/wiki/doku.php?id=how_does_it_work)
- [Support](https://portal.it.chula.ac.th/home)

## API Evangelist rating

**Kin Score 25.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 44.1 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 33.3 |
| Access clarity | 5.3 |

**Agent readiness 21.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/chulalongkorn/](https://apis.io/providers/chulalongkorn/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Chulalongkorn University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/chulalongkorn/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
