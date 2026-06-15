# Orbital (orbital)

Orbital is a data gateway and integration platform that connects APIs, databases, event streams, and other data sources without requiring glue code or manual integration maintenance. The platform delivers self-repairing integrations through instant, on-the-fly orchestration that automatically adapts as APIs and schemas evolve, eliminating the need to write resolvers, generate API clients, or maintain YAML mapping files.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Data
- Gateways

## Timestamps

- **Created:** 2026-01-05
- **Modified:** 2026-05-19

## APIs

### Orbital Query API

The Orbital Query API allows developers to submit TaxiQL queries to the Orbital data gateway for integrating, transforming, and discovering data across APIs, databases, event streams, and other data sources. Queries are submitted to the /api/taxiql endpoint and results can be returned as JSON or streamed via Server-Sent Events. The API also provides endpoints for managing connections and caches.

- **Human URL:** [https://orbitalhq.com/docs/querying/writing-queries](https://orbitalhq.com/docs/querying/writing-queries)

#### Tags

- Data
- Gateways
- Integration
- Queries

#### Properties

- [Documentation](https://orbitalhq.com/docs/querying/writing-queries)
- [OpenAPI](openapi/orbital-query-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/orbital-query-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/orbital-query-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/query.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/connection.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cache.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/orbital-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Orbital Schema Management API

The Orbital Schema Management API provides endpoints for managing schemas, types, and data source definitions within an Orbital workspace. It allows developers to register, update, and remove Taxi schemas and type definitions that Orbital uses to understand the semantic relationships between data across connected services. Schemas can originate from OpenAPI specs, Protobuf definitions, database schemas, or Taxi projects.

- **Human URL:** [https://orbitalhq.com/docs/describing-data-sources/open-api](https://orbitalhq.com/docs/describing-data-sources/open-api)

#### Tags

- Data
- Gateways
- Schemas
- Types

#### Properties

- [Documentation](https://orbitalhq.com/docs/describing-data-sources/open-api)
- [OpenAPI](openapi/orbital-schema-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/orbital-schema-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/orbital-schema-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/service.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/type.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/orbital-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/orbital-finance)
- [Website](https://orbitalhq.com/)
- [Documentation](https://orbitalhq.com/docs)
- [Changelog](https://orbitalhq.com/changelog)
- [Pricing](https://orbitalhq.com/pricing)
- [Blog](https://orbitalhq.com/blog)
- [L L Ms Txt](https://orbitalhq.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
