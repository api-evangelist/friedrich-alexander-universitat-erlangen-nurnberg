# Friedrich-Alexander-Universität Erlangen-Nürnberg (friedrich-alexander-universitat-erlangen-nurnberg)

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

Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU) is a public research university in Bavaria, Germany, ranked #224 in the QS World University Rankings 2025. FAU does not run a single consolidated developer portal, but several central services expose public, machine-readable interfaces — most notably the OPEN FAU institutional repository (DSpace 7.4) and the FAU CRIS research information system (Clarivate Converis). This repository catalogs that public developer/API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/friedrich-alexander-universitat-erlangen-nurnberg/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=friedrich-alexander-universitat-erlangen-nurnberg-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Repository, Library, Germany

## APIs

- **OPEN FAU DSpace REST API** — DSpace 7.4 REST/HAL API for FAU's open-access repository (communities, collections, items, discovery). Base URL: `https://open.fau.de/server/api`. Docs: https://ub.fau.de/en/research/open-fau/
- **OPEN FAU OAI-PMH Interface** — OAI-PMH metadata harvesting for the OPEN FAU repository. Base URL: `https://open.fau.de/server/oai/request`. Docs: https://ub.fau.de/en/research/open-fau/
- **FAU CRIS Converis Public Web Service** — Converis research-information web service under `/converis/ws/public`; access-restricted (HTTP 403) on FAU's instance. Docs: https://www.fau.eu/research/services-for-researchers/research-information-system/

## Plans

[plans/friedrich-alexander-universitat-erlangen-nurnberg-plans-pricing.yml](plans/friedrich-alexander-universitat-erlangen-nurnberg-plans-pricing.yml)

## Rate Limits

[rate-limits/friedrich-alexander-universitat-erlangen-nurnberg-rate-limits.yml](rate-limits/friedrich-alexander-universitat-erlangen-nurnberg-rate-limits.yml)

## FinOps

[finops/friedrich-alexander-universitat-erlangen-nurnberg-finops.yml](finops/friedrich-alexander-universitat-erlangen-nurnberg-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.fau.eu/
- GitHub (RRZE central IT web team): https://github.com/RRZE-Webteam
- GitHub (Competence Center Research Data and Information): https://github.com/FAU-CDI
- Source Code (GitLab): https://gitlab.rrze.fau.de/
- LinkedIn: https://www.linkedin.com/school/fau-erlangen-n%C3%BCrnberg/
- Authentication (RRZE Shibboleth/SAML SSO): https://www.rrze.fau.de/2009/10/zentraler-anmeldedienst-fur-web-anwendungen-mein-campus-stud-on-und-uniportal/

## Notes

All endpoints in this profile were probed live on 2026-06-03 and their HTTP status recorded in `review.yml`. The OPEN FAU DSpace REST API and OAI-PMH interface respond publicly (200); the DSpace items endpoint returns 401 for write/management operations, and the CRIS Converis public web-service path returns 403 (gated). The legacy OPUS FAU OAI endpoint now redirects to OPEN FAU. No endpoints were fabricated; FAU exposes no single unified, openly documented public API portal.

## Maintainers

- Kin Lane — kin@apievangelist.com
