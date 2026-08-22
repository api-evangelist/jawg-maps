# Jawg Maps (jawg-maps)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
