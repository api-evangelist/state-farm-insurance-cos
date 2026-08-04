# State Farm Insurance Companies (state-farm-insurance-cos)

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

State Farm Insurance Companies is the collective name for the group of insurance subsidiaries operating under State Farm Mutual Automobile Insurance Company, the parent organization headquartered in Bloomington, Illinois. The group comprises fourteen property and casualty insurance companies and two life insurance companies including State Farm Mutual Automobile Insurance Company, State Farm Fire and Casualty Company, State Farm Indemnity Company, State Farm Life Insurance Company, State Farm General Insurance Company, State Farm Florida Insurance Company, and State Farm Lloyds, among others. This multi-entity structure allows State Farm to manage its business across different US state regulatory environments. As a group, State Farm Insurance Companies is the largest property and casualty insurer in the United States. The group shares the common digital infrastructure and developer platform operated at developer.statefarm.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/state-farm-insurance-cos/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Partner Gateway API

The State Farm Partner Gateway API serves as the unified integration layer for all State Farm Insurance Companies subsidiaries, enabling external partners to access insurance products across the State Farm family of companies through a single API entry point. The Partner Gateway supports embedded insurance workflows, lender integrations, real estate platforms, and third-party aggregators, routing requests to the appropriate State Farm subsidiary based on the product type and state jurisdiction.

- **Human URL:** [https://developer.statefarm.com](https://developer.statefarm.com)
- **Base URL:** `https://api.statefarm.com/v1`

#### Tags

- Insurance
- Partner
- Integration
- API Gateway
- Multi-line

#### Properties

- [Documentation](https://developer.statefarm.com)
- [F A Q](https://developer.statefarm.com/faq)
- [Postman Collection](collections/state-farm-insurance-cos-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-cos-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Renters Insurance API

The Renters Insurance API from State Farm Insurance Companies enables property management platforms, multifamily housing operators, and partner aggregators to embed State Farm renters insurance into their tenant onboarding flows. State Farm is the number one writer of renters insurance in the US. Partners can request quotes, bind policies, and retrieve policy status through this API. Coverage is underwritten by the appropriate State Farm subsidiary for each state jurisdiction.

- **Human URL:** [https://developer.statefarm.com/api/renters](https://developer.statefarm.com/api/renters)
- **Base URL:** `https://api.statefarm.com/v1`

#### Tags

- Insurance
- Renters Insurance
- Embedded Insurance
- Partner
- Multi-line

#### Properties

- [Documentation](https://developer.statefarm.com/api/renters)
- [OpenAPI](openapi/state-farm-insurance-cos-renters-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/state-farm-insurance-cos-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-cos-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### B2B Lender Services API

The State Farm B2B Lender Services API provides mortgage lenders and auto lenders with programmatic access to verify insurance coverage for collateral assets financed by their borrowers. Lenders can confirm active homeowners, auto, or property insurance policies written by any State Farm Insurance Companies subsidiary. This supports lender compliance, reduces force-placed insurance, and streamlines closing workflows.

- **Human URL:** [https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry](https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry)
- **Base URL:** `https://b2b.statefarm.com/api/v1`

#### Tags

- Insurance
- B2B
- Lenders
- Mortgage
- Verification

#### Properties

- [Documentation](https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry)
- [Postman Collection](collections/state-farm-insurance-cos-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-cos-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.statefarm.com)
- [Developer  Portal](https://developer.statefarm.com)
- [Git Hub](https://github.com/StateFarmIns)
- [Engineering  Blog](https://engineering.statefarm.com/blog)
- [B2 B  Portal](https://b2b.statefarm.com)
- [LinkedIn](https://www.linkedin.com/company/state-farm)
- [Newsroom](https://newsroom.statefarm.com)
- [Privacy Policy](https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy)
- [Terms of Service](https://www.statefarm.com/customer-care/legal-disclaimer)
- [OpenAPI](openapi/state-farm-insurance-cos-renters-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/state-farm-insurance-cos-renters-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/state-farm-insurance-cos-renters-policy-structure.json)
- [JSON-LD](json-ld/state-farm-insurance-cos-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/state-farm-insurance-cos-vocabulary.yml)
- [Spectral Rules](rules/state-farm-insurance-cos-rules.yml)
