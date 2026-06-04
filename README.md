# University of Cape Town (university-of-cape-town)

The University of Cape Town (UCT) is South Africa's leading public research university, ranked #96 in the QS World University Rankings 2025 and the highest-ranked university on the African continent. UCT does not publish a single consolidated developer portal, but several of its research and library units expose public, machine-readable interfaces — a NADA microdata catalog API, a DSpace OAI-PMH repository endpoint, and a Figshare-backed open data repository. This repository catalogs that public developer/API footprint as an APIs.json profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-cape-town/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-cape-town-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Data, Institutional Repository, OAI-PMH, South Africa, Africa

## APIs

- **DataFirst Microdata Catalog API (NADA)** — Public REST/JSON API over the DataFirst NADA data portal, returning survey and administrative microdata metadata. Docs: https://www.datafirst.uct.ac.za/dataportal/index.php/catalog (base: https://www.datafirst.uct.ac.za/dataportal/index.php/api)
- **OpenUCT Institutional Repository OAI-PMH** — DSpace OAI-PMH 2.0 metadata harvesting interface for UCT scholarly outputs. Docs: https://open.uct.ac.za/ (base: https://open.uct.ac.za/server/oai/request)
- **ZivaHub Open Data (Figshare API)** — UCT's institutional open data repository, powered by Figshare for Institutions and accessible via the public Figshare API. Docs: https://docs.figshare.com/ (base: https://api.figshare.com/v2)

## Plans

- plans/university-of-cape-town-plans-pricing.yml

## Rate Limits

- rate-limits/university-of-cape-town-rate-limits.yml

## FinOps

- finops/university-of-cape-town-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uct.ac.za/
- GitHub: https://github.com/uct-cbio
- LinkedIn: https://za.linkedin.com/school/university-of-cape-town/
- Plans: plans/university-of-cape-town-plans-pricing.yml
- Rate Limits: rate-limits/university-of-cape-town-rate-limits.yml
- FinOps: finops/university-of-cape-town-finops.yml
- Review: review.yml

## Notes

All APIs and URLs in this profile were verified live on 2026-06-03; no endpoints were fabricated. The DataFirst NADA catalog API returned valid JSON (573 surveys), OpenUCT served a valid OAI-PMH 2.0 Identify response, and ZivaHub is confirmed as a Figshare for Institutions repository reachable through the public Figshare API. UCT has multiple unofficial/departmental GitHub organizations (e.g. uct-cbio, UCT-MARiS, UCT-ICTS-HPC) rather than one institutional org; uct-cbio is listed as a representative public org. Operational, student-information (SIS), timetable, and identity/SSO systems are gated behind institutional authentication and are not publicly documented.

## Maintainers

- Kin Lane — kin@apievangelist.com
