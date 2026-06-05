# Community Health Systems (community-health-systems)

Community Health Systems (CHS) is a Fortune 500 hospital operator that owns, leases, and operates general acute care hospitals across the United States. In compliance with the CMS Interoperability and Patient Access Final Rule (CMS-9115-F), CHS publishes FHIR R4 healthcare interoperability APIs that allow third-party applications to access patient demographics and clinical data, adjudicated claims and encounters, formulary information, and provider directory data. The APIs use the HL7 FHIR R4 standard and SMART-on-FHIR authorization for patient-scoped access.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS-9115-F
- FHIR
- Healthcare
- Hospitals
- Interoperability
- Patient Access
- Provider Directory
- SMART-on-FHIR

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Community Health Systems Patient Access API

FHIR R4 API published pursuant to the CMS Interoperability and Patient Access Final Rule (CMS-9115-F). Allows third-party applications, with the patient's authorization, to retrieve adjudicated claims and encounters (ExplanationOfBenefit), formulary and medication data (MedicationKnowledge), and clinical data (Patient and related resources). Authentication uses SMART-on-FHIR OAuth2 with patient/launch scopes.

- **Human URL:** [https://www.chs.net](https://www.chs.net)
- **Base URL:** `https://api.chs.net/fhir/r4`

#### Tags

- CMS-9115-F
- FHIR
- Healthcare
- Interoperability
- Patient Access
- SMART-on-FHIR

#### Properties

- [Documentation](https://www.chs.net)
- [C M S Final Rule](https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index)
- [OpenAPI](openapi/chs-patient-access-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chs-patient-access-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chs-patient-access-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Community Health Systems Provider Directory API

FHIR R4 read API exposing provider and pharmacy directory data in compliance with CMS interoperability requirements. Third-party applications can search Practitioner, Organization, and Location resources without patient consent (no PHI is exposed by these directory endpoints).

- **Human URL:** [https://www.chs.net](https://www.chs.net)
- **Base URL:** `https://api.chs.net/fhir/r4`

#### Tags

- CMS-9115-F
- FHIR
- Healthcare
- Interoperability
- Provider Directory

#### Properties

- [Documentation](https://www.chs.net)
- [C M S Final Rule](https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index)
- [Postman Collection](collections/chs-patient-access-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chs-patient-access-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/community-health-systems)
- [Website](https://www.chs.net)
- [Patient Portal](https://www.chs.net/patients-visitors/)
- [Investors](https://www.chs.net/investors/)
- [Privacy Policy](https://www.chs.net/privacy-statement/)
- [C M S Interoperability](https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index)
- [H L7 F H I R R4](https://hl7.org/fhir/R4/)
- [JSON-LD](json-ld/community-health-systems-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/chs-fhir-bundle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/community-health-systems-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
