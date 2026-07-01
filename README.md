# Jawg Maps (jawg-maps)

Jawg is a French location platform delivering customizable vector and raster map tiles, hosted map styles, geocoding and places search, routing, isochrones, distance matrices, and static maps. All surfaces are authenticated with a Jawg access token passed as an access-token query parameter (or header) and are served from tile.jawg.io and api.jawg.io.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jawg-maps/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jawg-maps/refs/heads/main/apis.yml)

## Tags

- Maps
- Geospatial
- Tiles
- Geocoding
- Routing
- Location

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Jawg Map Tiles & Styles API

Serves customizable slippy-map tiles in the XYZ scheme for both vector (Mapbox Vector Tile) and raster (PNG) formats using a hosted style ID, plus the style JSON and TileJSON metadata documents. Supports retina @2x tiles, language and worldview parameters, and a WMTS entrypoint.

- **Human URL:** [https://www.jawg.io/docs/apidocs/maps/](https://www.jawg.io/docs/apidocs/maps/)
- **Base URL:** `https://tile.jawg.io`

#### Tags

- Tiles
- Vector Tiles
- Raster Tiles
- Styles
- TileJSON

#### Properties

- [Documentation](https://www.jawg.io/docs/apidocs/maps/)
- [API Reference](https://www.jawg.io/docs/apidocs/maps/dynamic-maps/)
- [OpenAPI](openapi/jawg-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jawg-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jawg-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jawg Places / Geocoding API

Forward geocoding, autocomplete, reverse geocoding, and place-detail lookup returning GeoJSON features. Results can be biased and filtered by point, bounding box, layers, sources, and country.

- **Human URL:** [https://www.jawg.io/docs/apidocs/places/](https://www.jawg.io/docs/apidocs/places/)
- **Base URL:** `https://api.jawg.io/places/v1`

#### Tags

- Geocoding
- Places
- Search
- Autocomplete
- Reverse Geocoding

#### Properties

- [Documentation](https://www.jawg.io/docs/apidocs/places/)
- [API Reference](https://www.jawg.io/docs/apidocs/places/search/)
- [OpenAPI](openapi/jawg-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jawg-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jawg-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jawg Routing API

Valhalla-based turn-by-turn routing computing the shortest route or distance between locations across auto, bicycle, and pedestrian costing models, plus an optimized_route (traveling-salesman) endpoint. An OSRM-compatible routing surface is also available.

- **Human URL:** [https://www.jawg.io/docs/apidocs/routing/](https://www.jawg.io/docs/apidocs/routing/)
- **Base URL:** `https://api.jawg.io/routing`

#### Tags

- Routing
- Directions
- Valhalla
- Turn by Turn

#### Properties

- [Documentation](https://www.jawg.io/docs/apidocs/routing/)
- [API Reference](https://www.jawg.io/docs/apidocs/routing/osrm/)
- [OpenAPI](openapi/jawg-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jawg-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jawg-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jawg Matrix API

Valhalla sources_to_targets time-distance matrix service computing travel time and distance between every source and every target location for a given costing model.

- **Human URL:** [https://www.jawg.io/docs/apidocs/routing/](https://www.jawg.io/docs/apidocs/routing/)
- **Base URL:** `https://api.jawg.io/routing`

#### Tags

- Matrix
- Distance Matrix
- Valhalla

#### Properties

- [Documentation](https://www.jawg.io/docs/apidocs/routing/)
- [OpenAPI](openapi/jawg-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jawg-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jawg-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jawg Isochrone API

Valhalla isochrone service computing areas reachable within specified time or distance intervals from one or more locations, returned as GeoJSON polygon or line contours.

- **Human URL:** [https://www.jawg.io/docs/apidocs/routing/](https://www.jawg.io/docs/apidocs/routing/)
- **Base URL:** `https://api.jawg.io/routing`

#### Tags

- Isochrone
- Reachability
- Valhalla

#### Properties

- [Documentation](https://www.jawg.io/docs/apidocs/routing/)
- [OpenAPI](openapi/jawg-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jawg-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jawg-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jawg Static Maps API

Renders a standalone map image (PNG/JPEG) from a center, zoom, and size, or from an auto-fit set of features, with optional markers and paths - for display on web and mobile without JavaScript.

- **Human URL:** [https://www.jawg.io/docs/apidocs/maps/static-maps/](https://www.jawg.io/docs/apidocs/maps/static-maps/)
- **Base URL:** `https://api.jawg.io`

#### Tags

- Static Maps
- Images
- Markers

#### Properties

- [Documentation](https://www.jawg.io/docs/apidocs/maps/static-maps/)
- [OpenAPI](openapi/jawg-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jawg-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jawg-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/jawg)
- [LinkedIn](https://www.linkedin.com/company/jawg-maps)
- [Website](https://www.jawg.io/)
- [Documentation](https://www.jawg.io/docs/)
- [Plans](plans/jawg-maps-plans-pricing.yml)
- [Rate Limits](rate-limits/jawg-maps-rate-limits.yml)
- [Fin Ops](finops/jawg-maps-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
