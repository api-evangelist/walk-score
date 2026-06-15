# Walk Score (walk-score)

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
