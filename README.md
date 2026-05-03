# United States Coast Guard

The United States Coast Guard is a branch of the military responsible for enforcing maritime laws, protecting the nation's waterways and coastlines, and ensuring the safety and security of seafarers. They conduct search and rescue operations, respond to environmental disasters, combat illegal drug trafficking and immigration, and conduct security patrols to thwart terrorism threats. The Coast Guard also plays a crucial role in maintaining navigational aids, regulating maritime commerce, and conducting icebreaking operations in the polar regions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Maritime Safety
- Vessel Documentation
- Emergency Response
- Law Enforcement

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

---

## APIs

### CGMIX Maritime Information Exchange API

The Coast Guard Maritime Information Exchange (CGMIX) provides XML web services for accessing U.S. Coast Guard maritime information including vessel documentation, Port State Information Exchange (PSIX) data, equipment certifications, and Incident Investigation Reports (IIR). Data originates from the Marine Information for Safety and Law Enforcement (MISLE) system.

**Human URL:** https://cgmix.uscg.mil/xml/default.aspx

#### Tags

- Maritime, Vessel Documentation, Safety, Federal Government

#### Properties

- [Documentation](https://cgmix.uscg.mil/xml/default.aspx)
- [OpenAPI](openapi/cgmix-maritime-information-exchange-openapi.yml)
- [SpectralRules](rules/cgmix-maritime-information-exchange-rules.yml)
- [NaftikoCapability](capabilities/maritime-safety.yaml)

---

### NAVCEN AIS Vessel Information Verification Service

The Vessel Information Verification Service (VIVS) is a NAVCEN web service that allows retrieval of a vessel's broadcasted AIS static data, including MMSI, call sign, vessel name, official number, dimensions, draft, vessel type, and positioning source.

**Human URL:** https://www.navcen.uscg.gov/ais-vivs-home

#### Tags

- Maritime, AIS, Vessel Tracking, Federal Government

#### Properties

- [Documentation](https://www.navcen.uscg.gov/ais-vivs-home)

---

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [cgmix-maritime-information-exchange-openapi.yml](openapi/cgmix-maritime-information-exchange-openapi.yml) | CGMIX Maritime Information Exchange XML web services |

### Spectral Rules

| File | Description |
|------|-------------|
| [cgmix-maritime-information-exchange-rules.yml](rules/cgmix-maritime-information-exchange-rules.yml) | Spectral lint rules for CGMIX API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | APIs |
|------|------|
| [shared/cgmix-maritime-information-exchange.yaml](capabilities/shared/cgmix-maritime-information-exchange.yaml) | CGMIX Maritime Information Exchange (7 operations) |

#### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [maritime-safety.yaml](capabilities/maritime-safety.yaml) | Maritime safety and vessel compliance workflows | 7 tools |

### JSON Schemas

| File | Description |
|------|-------------|
| [cgmix-vessel-schema.json](json-schema/cgmix-vessel-schema.json) | Schema for USCG documented vessel records |
| [cgmix-vessel-case-schema.json](json-schema/cgmix-vessel-case-schema.json) | Schema for Port State Control inspection case records |

### JSON Structures

| File | Description |
|------|-------------|
| [cgmix-vessel-structure.json](json-structure/cgmix-vessel-structure.json) | Field-level structure documentation for vessel records |

### JSON-LD Context

| File | Description |
|------|-------------|
| [united-states-coast-guard-context.jsonld](json-ld/united-states-coast-guard-context.jsonld) | Linked data context mapping USCG maritime vocabulary to schema.org |

### Examples

| File | Operation |
|------|-----------|
| [cgmix-get-vessel-summary-example.json](examples/cgmix-get-vessel-summary-example.json) | Get Vessel Summary |
| [cgmix-get-equipment-details-example.json](examples/cgmix-get-equipment-details-example.json) | Get Equipment Details |
| [cgmix-get-vessel-cases-example.json](examples/cgmix-get-vessel-cases-example.json) | Get Vessel Cases |

### Vocabulary

| File | Description |
|------|-------------|
| [united-states-coast-guard-vocabulary.yml](vocabulary/united-states-coast-guard-vocabulary.yml) | Maritime safety domain vocabulary (AIS, PSIX, NVDC, CGMIX, VIVS, etc.) |

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
