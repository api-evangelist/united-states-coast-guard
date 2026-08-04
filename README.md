# United States Coast Guard (united-states-coast-guard)

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
