# Community Health Systems (community-health-systems)

Community Health Systems (CHS) is a Fortune 500 hospital operator that owns, leases, and operates general acute care hospitals across the United States. In compliance with the CMS Interoperability and Patient Access Final Rule (CMS-9115-F), CHS publishes FHIR R4 healthcare interoperability APIs that allow third-party applications to access patient demographics and clinical data, adjudicated claims and encounters, formulary information, and provider directory data. The APIs use the HL7 FHIR R4 standard and SMART-on-FHIR authorization for patient-scoped access.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

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
- **Modified:** 2026-04-26

## APIs

### Community Health Systems Patient Access API
FHIR R4 API published pursuant to the CMS Interoperability and Patient Access Final Rule (CMS-9115-F). Allows third-party applications, with the patient's authorization, to retrieve adjudicated claims and encounters (ExplanationOfBenefit), formulary and medication data (MedicationKnowledge), and clinical data (Patient and related resources). Authentication uses SMART-on-FHIR OAuth2 with patient/launch scopes.

**Base URL:** `https://api.chs.net/fhir/r4`

**Human URL:** [https://www.chs.net](https://www.chs.net)

#### Tags

- CMS-9115-F, FHIR, Healthcare, Interoperability, Patient Access, SMART-on-FHIR

#### Properties

- [Documentation](https://www.chs.net)
- [CMS Final Rule](https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index)
- [OpenAPI](openapi/chs-patient-access-api-openapi.yml)

### Community Health Systems Provider Directory API
FHIR R4 read API exposing provider and pharmacy directory data in compliance with CMS interoperability requirements. Third-party applications can search Practitioner, Organization, and Location resources without patient consent.

**Base URL:** `https://api.chs.net/fhir/r4`

**Human URL:** [https://www.chs.net](https://www.chs.net)

#### Tags

- CMS-9115-F, FHIR, Healthcare, Interoperability, Provider Directory

## Common Properties

- [Website](https://www.chs.net)
- [Patient Portal](https://www.chs.net/patients-visitors/)
- [Investors](https://www.chs.net/investors/)
- [Privacy Statement](https://www.chs.net/privacy-statement/)
- [CMS Interoperability](https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index)
- [HL7 FHIR R4](https://hl7.org/fhir/R4/)
- [JSON-LD Context](json-ld/community-health-systems-context.jsonld)
- [FHIR Bundle JSON Schema](json-schema/chs-fhir-bundle-schema.json)
- [Spectral Ruleset](rules/community-health-systems-rules.yml)
- [Naftiko Capabilities](capabilities/community-health-systems-fhir-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
