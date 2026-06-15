# United States Coast Guard (united-states-coast-guard)

The United States Coast Guard is a branch of the military responsible for enforcing maritime laws, protecting the nation's waterways and coastlines, and ensuring the safety and security of seafarers. They conduct search and rescue operations, respond to environmental disasters, combat illegal drug trafficking and immigration, and conduct security patrols to thwart terrorism threats. The USCG provides public APIs and data services through the CGMIX Maritime Information Exchange, the Navigation Center (NAVCEN), and the National Vessel Documentation Center (NVDC).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/apis.yml)

## Scope

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
- **Modified:** 2026-05-19

## APIs

### CGMIX Maritime Information Exchange API

The Coast Guard Maritime Information Exchange (CGMIX) provides XML web services for accessing Coast Guard maritime information including vessel documentation, Port State Information Exchange (PSIX) data, equipment certifications, and Incident Investigation Reports (IIR). Data originates from the Marine Information for Safety and Law Enforcement (MISLE) system and is updated weekly.

- **Human URL:** [https://cgmix.uscg.mil/xml/default.aspx](https://cgmix.uscg.mil/xml/default.aspx)
- **Base URL:** `https://cgmix.uscg.mil`

#### Tags

- Maritime
- Vessel Documentation
- Safety
- Federal Government

#### Properties

- [Documentation](https://cgmix.uscg.mil/xml/default.aspx)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/openapi/cgmix-maritime-information-exchange-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/rules/cgmix-maritime-information-exchange-rules.yml)
- [Postman Collection](collections/cgmix-maritime-information-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cgmix-maritime-information-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NAVCEN AIS Vessel Information Verification Service

The Vessel Information Verification Service (VIVS) is a NAVCEN web service that allows retrieval of a vessel's broadcasted AIS static data, including Maritime Mobile Service Identity (MMSI), call sign, vessel name, official number, dimensions, draft, vessel type, and positioning source. Provided by the U.S. Coast Guard Navigation Center.

- **Human URL:** [https://www.navcen.uscg.gov/ais-vivs-home](https://www.navcen.uscg.gov/ais-vivs-home)
- **Base URL:** `https://www.navcen.uscg.gov`

#### Tags

- Maritime
- AIS
- Vessel Tracking
- Federal Government

#### Properties

- [Documentation](https://www.navcen.uscg.gov/ais-vivs-home)
- [Documentation](https://www.navcen.uscg.gov/ais-vessel-information-verification-service)
- [Postman Collection](collections/cgmix-maritime-information-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cgmix-maritime-information-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/uscoastguard)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
