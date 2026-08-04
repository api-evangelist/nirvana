# Nirvana Health (nirvana)

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

Nirvana is a real-time insurance eligibility, benefits, and patient cost-estimation platform purpose-built for behavioral and mental health. Its Coverage API normalizes complex payer data into structured JSON, returning eligibility, plan-level benefits, patient cost-share, session limits, and prior authorization details, and can recover active coverage from only basic patient demographics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nirvana/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nirvana/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Insurance
- Eligibility
- Benefits
- Cost Estimation
- Behavioral Health

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Nirvana Eligibility & Coverage API

Real-time insurance eligibility and active-coverage discovery. The discover operation finds active coverage and plan-level details for a patient, including Cardless Verification that recovers coverage from only basic demographics (name, date of birth, ZIP).

- **Human URL:** [https://nirvana-docs.readme.io/docs/nirvana-overview-v2](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- **Base URL:** `https://coverage-api.meetnirvana.com/v1`

#### Tags

- Eligibility
- Coverage
- Discover

#### Properties

- [Documentation](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- [API Reference](https://nirvana-docs.readme.io/reference)
- [OpenAPI](openapi/nirvana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nirvana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nirvana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nirvana Coverage Scan API

Scans multiple payers to locate any active coverage a patient may have when the payer is unknown, returning matched coverage with normalized plan details.

- **Human URL:** [https://nirvana-docs.readme.io/docs/nirvana-overview-v2](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- **Base URL:** `https://coverage-api.meetnirvana.com/v1`

#### Tags

- Coverage
- Scan
- Discovery

#### Properties

- [Documentation](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- [API Reference](https://nirvana-docs.readme.io/reference)
- [OpenAPI](openapi/nirvana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nirvana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nirvana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nirvana Benefits API

Specialty-specific, payer-normalized benefit details returned within coverage and estimate responses - patient cost-share, copay, coinsurance, deductible, out-of-pocket maximum, session limits, telehealth coverage, and prior authorization requirements for behavioral health services.

- **Human URL:** [https://nirvana-docs.readme.io/docs/nirvana-overview-v2](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- **Base URL:** `https://coverage-api.meetnirvana.com/v1`

#### Tags

- Benefits
- Plan Details
- Behavioral Health

#### Properties

- [Documentation](https://www.meetnirvana.com/our-technology)
- [API Reference](https://nirvana-docs.readme.io/reference)
- [OpenAPI](openapi/nirvana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nirvana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nirvana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nirvana Cost Estimation API

Real-time per-session patient cost estimates. The estimate operation returns the patient's expected financial responsibility for an appointment based on provider session cost, network status, CPT/modality, and the patient's active benefits.

- **Human URL:** [https://nirvana-docs.readme.io/docs/nirvana-overview-v2](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- **Base URL:** `https://coverage-api.meetnirvana.com/v1`

#### Tags

- Cost Estimation
- Patient Responsibility
- Estimate

#### Properties

- [Documentation](https://www.meetnirvana.com/patient-intake)
- [API Reference](https://nirvana-docs.readme.io/reference)
- [OpenAPI](openapi/nirvana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nirvana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nirvana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nirvana Medicaid API

Finds active Medicaid coverage and Medicaid-level eligibility details for a patient, supporting Medicaid payers nationwide.

- **Human URL:** [https://nirvana-docs.readme.io/reference/medicaid_v1_medicaid_post](https://nirvana-docs.readme.io/reference/medicaid_v1_medicaid_post)
- **Base URL:** `https://coverage-api.meetnirvana.com/v1`

#### Tags

- Medicaid
- Eligibility
- Coverage

#### Properties

- [Documentation](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- [API Reference](https://nirvana-docs.readme.io/reference/medicaid_v1_medicaid_post)
- [OpenAPI](openapi/nirvana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nirvana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nirvana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/nirvana-hlth)
- [Website](https://www.meetnirvana.com)
- [Documentation](https://nirvana-docs.readme.io/docs/nirvana-overview-v2)
- [Plans](plans/nirvana-plans-pricing.yml)
- [Rate Limits](rate-limits/nirvana-rate-limits.yml)
- [Fin Ops](finops/nirvana-finops.yml)

## Authentication

The Nirvana Coverage API authenticates with a customer-specific API key passed in the `apikey` request header (not an OAuth Bearer token). Contact Nirvana to be provisioned a key.

## Notes

- No official Nirvana Health GitHub organization was found, so no GitHub Organization common property is listed.
- Pricing is sales-led and not publicly disclosed; plans, rate limits, and FinOps artifacts are marked unreconciled.
- "Claims" and "Webhooks" are not documented public HTTP APIs and are therefore not cataloged as APIs; see `review.yml` for disambiguation and scope notes (distinct from Nirvana trucking insurance and Nirvana Labs crypto).

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
