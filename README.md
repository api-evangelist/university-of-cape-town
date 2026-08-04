# University of Cape Town (university-of-cape-town)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
