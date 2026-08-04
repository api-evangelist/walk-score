# Walk Score (walk-score)

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

Walk Score measures the walkability, transit accessibility, and bikeability of any address in the United States and Canada. The Walk Score API returns Walk Score, Transit Score, and Bike Score for any geographic location, supporting real estate platforms, commute calculators, urban planning tools, and location intelligence applications. The Public Transit API provides detailed transit data including nearby stops, route networks, and supported cities, enabling comprehensive transportation accessibility analysis.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Walkability
- Transit
- Bikeability
- Location
- Real Estate
- Urban Planning
- Transportation

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Walk Score API

Returns the Walk Score, Transit Score, and Bike Score for any location specified by latitude/longitude coordinates and address. Walk Score measures walkability on a scale from 0 (car-dependent) to 100 (walker's paradise). Optionally returns Transit Score and Bike Score in the same response. Supported in the United States and Canada. API calls must originate from server-side scripts.

- **Human URL:** [https://www.walkscore.com/professional/api.php](https://www.walkscore.com/professional/api.php)
- **Base URL:** `https://api.walkscore.com`

#### Tags

- Walkability
- Walk Score
- Transit Score
- Bike Score
- Location Intelligence

#### Properties

- [Documentation](https://www.walkscore.com/professional/api.php)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/json-schema/walk-score-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/walk-score-transit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/walk-score-transit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/walk-score.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/walk-score.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Walk Score Transit API

Provides detailed public transit data for locations in supported cities including Transit Scores, nearby transit stops with route information, complete transit network data, individual stop and route details, and a list of supported cities. Used for comprehensive transit accessibility analysis in real estate, city planning, and commute optimization applications.

- **Human URL:** [https://www.walkscore.com/professional/public-transit-api.php](https://www.walkscore.com/professional/public-transit-api.php)
- **Base URL:** `https://transit.walkscore.com`

#### Tags

- Public Transit
- Transit Data
- Transit Score
- Bus
- Rail
- Transportation

#### Properties

- [Documentation](https://www.walkscore.com/professional/public-transit-api.php)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/openapi/walk-score-transit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/walk-score-transit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/walk-score-transit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/walk-score.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/walk-score.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/walk-score)
- [Website](https://www.walkscore.com)
- [Portal](https://www.walkscore.com/professional/api.php)
- [Documentation](https://walkscore-api.readthedocs.io/en/latest/)
- [Sign Up](https://www.walkscore.com/professional/api-sign-up.php)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
