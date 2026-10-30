# Friedrich-Alexander-Universität Erlangen-Nürnberg

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

Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU) is a public research university in Erlangen and Nuremberg, Bavaria, Germany, founded in 1743 and one of Germany's largest, with around 39,000 students across five faculties. FAU operates no central developer portal and publishes no OpenAPI definition of its own — but unlike most of this cohort its programmable footprint is real, and every surface in it runs on FAU's own infrastructure: every host recorded below resolves inside FAU's own 131.188.0.0/16 network, and not one of them CNAMEs to a vendor. The institution-operated, publicly readable surfaces verified live on 2026-08-30 are the OPEN FAU institutional repository on DSpace 7.4, which serves both a REST/HAL API and a fully functional OAI-PMH 2.0 harvesting endpoint with eight metadata crosswalks; a Matrix (Synapse 1.159.0) homeserver at matrix.fau.de, correctly delegated from .well-known/matrix/server and .well-known/matrix/client on fau.de, which makes FAU's chat service reachable by any standards-conformant Matrix client; the WordPress REST API behind the RRZE-operated FAU web platform, where the /wp-json index and search route are restricted but the wp/v2 content collections return real JSON on www.fau.de and a complete route index on ub.fau.de; and anonymous read access to the GitLab v4 REST API on FAU's self-hosted GitLab at gitlab.rrze.fau.de, which reports 132 public projects. Three further surfaces are live but gated: the FAU API gateway at api.fau.de, which fronts an authenticated API router behind SSO; the ClusterCockpit HPC job-monitoring REST API at monitoring.nhr.fau.de, run by NHR@FAU, the national high-performance computing centre FAU hosts; and the Clarivate Converis web service on cris.fau.de, which is FAU's research information system and returns HTTP 403 on its public web-service paths. FAU also operates a SAML 2.0 identity provider registered in the DFN-AAI federation, mints DOIs under its own DataCite prefix 10.25593, and maintains three active public GitHub organisations plus a self-hosted GitLab. No vendor contract is saved in this repository under FAU's name: where the software beneath a surface is someone else's product, the profile says so and keeps no copy of that product's specification.

**Areas:** University · Higher Education · Education · Research · Research Repository · Open Access · OAI-PMH · Identity Federation · Research Computing · Matrix · Germany · Bavaria

## Friedrich-Alexander-Universität Erlangen-Nürnberg on APIs.io

Everything profiled for Friedrich-Alexander-Universität Erlangen-Nürnberg is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/friedrich-alexander-universitat-erlangen-nurnberg/](https://apis.io/providers/friedrich-alexander-universitat-erlangen-nurnberg/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [OPEN FAU OAI-PMH Metadata Service](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/open-fau-oai/) — Open Archives Initiative Protocol for Metadata Harvesting 2.0 service for OPEN FAU, the university's open-access publication repository. Verified live on…
- [OPEN FAU DSpace REST API](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/open-fau-rest/) — The REST/HAL API of OPEN FAU, FAU's DSpace 7.4 institutional repository, run by the University Library on FAU's own host. Verified live on 2026-08-30: the…
- [FAU Matrix Homeserver](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/matrix-homeserver/) — FAU operates a Matrix homeserver — Synapse 1.159.0 at matrix.fau.de — with a hosted Element web client at chat.fau.de. It is properly delegated: both…
- [FAU WebSSO SAML 2.0 Identity Provider](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/websso-saml/) — FAU's central web single sign-on, operated by RRZE, publishes SAML 2.0 identity provider metadata as a machine-readable document at…
- [Friedrich-Alexander-Universität Erlangen-Nürnberg Website (WordPress REST)](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/fau-de-website-wordpress-rest/) — The public WordPress REST API (wp-json) of the Friedrich-Alexander-Universität Erlangen-Nürnberg website at www.fau.de: the route index of the site's…
- [RRZE GitLab REST API (FAU self-hosted)](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/gitlab-api/) — RRZE runs FAU's self-hosted GitLab at gitlab.rrze.fau.de, and its v4 REST API answers anonymous reads. Verified live on 2026-08-30:…
- [FAU API Gateway (api.fau.de)](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/fau-api-gateway/) — api.fau.de is an FAU-operated API portal — the browser title is "FAU API", the single-page application is served from FAU's own network, and its footer…
- [NHR@FAU ClusterCockpit Job Monitoring API](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/clustercockpit-nhr/) — NHR@FAU — the Erlangen National High Performance Computing Center, hosted by FAU — runs ClusterCockpit at monitoring.nhr.fau.de as the job-specific…
- [Clarivate Converis Web Service — FAU CRIS deployment](https://apis.io/apis/friedrich-alexander-universitat-erlangen-nurnberg/cris-converis-ws/) — FAU CRIS is the university's research information system, holding 146,000+ publications and 5,200+ projects and syndicating data to more than a thousand FAU…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Friedrich Alexander Universitat Erlangen Nurnberg Context](https://apis.io/jsonld/friedrich-alexander-universitat-erlangen-nurnberg/friedrich-alexander-universitat-erlangen-nurnberg-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Friedrich Alexander Universitat Erlangen Nurnberg Domain Security](https://apis.io/security/friedrich-alexander-universitat-erlangen-nurnberg/friedrich-alexander-universitat-erlangen-nurnberg-domain-security/)
- [Friedrich Alexander Universitat Erlangen Nurnberg Vulnerability Disclosure](https://apis.io/security/friedrich-alexander-universitat-erlangen-nurnberg/friedrich-alexander-universitat-erlangen-nurnberg-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Friedrich Alexander Universitat Erlangen Nurnberg Plans Pricing](https://apis.io/plans/friedrich-alexander-universitat-erlangen-nurnberg/friedrich-alexander-universitat-erlangen-nurnberg-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Friedrich Alexander Universitat Erlangen Nurnberg Rate Limits](https://apis.io/rate-limits/friedrich-alexander-universitat-erlangen-nurnberg/friedrich-alexander-universitat-erlangen-nurnberg-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Friedrich Alexander Universitat Erlangen Nurnberg Finops](https://apis.io/finops/friedrich-alexander-universitat-erlangen-nurnberg/friedrich-alexander-universitat-erlangen-nurnberg-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.fau.de/)
- [Documentation](https://doc.nhr.fau.de/)
- [Support](https://www.rrze.fau.de/)
- [Terms of service](https://www.fau.de/impressum/)
- [Privacy policy](https://www.fau.de/datenschutz/)

## API Evangelist rating

**Kin Score 26.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
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
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/friedrich-alexander-universitat-erlangen-nurnberg/](https://apis.io/providers/friedrich-alexander-universitat-erlangen-nurnberg/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Friedrich-Alexander-Universität Erlangen-Nürnberg: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/friedrich-alexander-universitat-erlangen-nurnberg/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
