# Friedrich-Alexander-Universität Erlangen-Nürnberg (friedrich-alexander-universitat-erlangen-nurnberg)

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
