# Nirvana Health (nirvana)

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
