# Chulalongkorn University (chulalongkorn)

Chulalongkorn University is Thailand's oldest and a leading public research university, located in Bangkok and ranked #229 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. The footprint is limited and largely gated: a campus single sign-on (Chula SSO) authentication API, an institutional repository (CUIR / Chula Digiverse on DSpace) with OAI-PMH and REST interfaces, and a staff-only central data exchange (CU Data Gateway) offering an online API mode. There is no unified, openly documented public developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/chulalongkorn/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=chulalongkorn-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Thailand, Identity, Single Sign-On, Institutional Repository, Open Access, OAI-PMH

## APIs

- **Chula SSO Authentication API** — Single sign-on for authenticating Chula students/staff; integration requires an appid/appsecret requested by email (not self-service). Docs: https://account.it.chula.ac.th/wiki/doku.php — sample code: https://github.com/krerk/ChulaSSO.Android
- **CUIR / Chula Digiverse Repository (OAI-PMH & DSpace REST)** — DSpace-based institutional repository of theses, papers, and archives, exposing standard OAI-PMH and REST interfaces. Docs: https://digiverse.chula.ac.th/
- **CU Data Gateway API** — Central campus data exchange with Batch (SFTP) and Online (API) modes; restricted to assigned university personnel, no public docs. Docs: https://www.it.chula.ac.th/service/data-gateway/

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/chulalongkorn-plans-pricing.yml](plans/chulalongkorn-plans-pricing.yml)
- Rate Limits: [rate-limits/chulalongkorn-rate-limits.yml](rate-limits/chulalongkorn-rate-limits.yml)
- FinOps: [finops/chulalongkorn-finops.yml](finops/chulalongkorn-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.chula.ac.th/en/
- GitHub: https://github.com/ChulalongkornUniversity
- LinkedIn: https://www.linkedin.com/school/chulalongkorn-university/
- Developer/IT Services: https://www.it.chula.ac.th/
- Review: [review.yml](review.yml)

## Notes

All APIs and URLs were verified against public pages where possible. The Chula SSO and CU Data Gateway APIs require credentials/keys granted on request and are not self-service. The DSpace OAI-PMH and REST endpoints returned HTTP 500 to external probes, and the Data Gateway portal (datagateway.chula.ac.th) did not resolve from outside the campus network; these are documented honestly in [review.yml](review.yml). No endpoints were fabricated — base/doc URLs derive from confirmed pages or standard DSpace conventions.

## Maintainers

- Kin Lane — kin@apievangelist.com
