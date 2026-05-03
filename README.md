# Walk Score

Walk Score measures the walkability, transit accessibility, and bikeability of any address in the United States and Canada. The Walk Score API returns Walk Score, Transit Score, and Bike Score for any geographic location, supporting real estate platforms, commute calculators, urban planning tools, and location intelligence applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/walk-score/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-03

## APIs

| API | Description |
|---|---|
| [Walk Score API](https://www.walkscore.com/professional/api.php) | Returns Walk Score, Transit Score, and Bike Score for any location |
| [Walk Score Transit API](https://www.walkscore.com/professional/public-transit-api.php) | Detailed transit data including stops, routes, network, and Transit Scores |

## OpenAPI Specifications

- [walk-score-openapi.yml](openapi/walk-score-openapi.yml) — Walk Score, Transit Score, and Bike Score endpoint
- [walk-score-transit-openapi.yml](openapi/walk-score-transit-openapi.yml) — Transit Score, stops, routes, network, and supported cities

## JSON Schemas

- [walk-score-score-schema.json](json-schema/walk-score-score-schema.json) — Walk Score API response schema with status codes
- [walk-score-transit-stop-schema.json](json-schema/walk-score-transit-stop-schema.json) — Transit stop and route data model

## JSON Structure

- [walk-score-score-structure.json](json-structure/walk-score-score-structure.json) — Walk Score response structure documentation

## JSON-LD Context

- [walk-score-context.jsonld](json-ld/walk-score-context.jsonld) — Linked data context mapping to schema.org and GTFS vocabulary

## Examples

- [walk-score-get-walk-score-example.json](examples/walk-score-get-walk-score-example.json) — Get Walk Score with Transit and Bike Scores for Seattle address
- [walk-score-get-transit-score-example.json](examples/walk-score-get-transit-score-example.json) — Get Transit Score for a city location
- [walk-score-search-transit-stops-example.json](examples/walk-score-search-transit-stops-example.json) — Search nearby transit stops with route details

## Spectral Rules

- [walk-score-rules.yml](rules/walk-score-rules.yml) — Spectral ruleset enforcing Walk Score API conventions

## Naftiko Capabilities

### Shared Definitions

- [capabilities/shared/walk-score.yaml](capabilities/shared/walk-score.yaml) — Walk Score API consumed definitions (1 operation)
- [capabilities/shared/walk-score-transit.yaml](capabilities/shared/walk-score-transit.yaml) — Transit API consumed definitions (6 operations)

### Workflow Capabilities

- [capabilities/location-intelligence.yaml](capabilities/location-intelligence.yaml) — Unified location intelligence workflow combining Walk Score and Transit APIs (7 REST endpoints, 7 MCP tools)

## Vocabulary

- [walk-score-vocabulary.yml](vocabulary/walk-score-vocabulary.yml) — Walkability, transit, bikeability, and location intelligence vocabulary

## Common Properties

- [API Documentation](https://www.walkscore.com/professional/api.php)
- [Transit API](https://www.walkscore.com/professional/public-transit-api.php)
- [API Reference Docs](https://walkscore-api.readthedocs.io/en/latest/)
- [Sign Up](https://www.walkscore.com/professional/api-sign-up.php)
- [Website](https://www.walkscore.com)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
