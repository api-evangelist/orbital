# Orbital (orbital)
Orbital is a data gateway and integration platform that connects APIs, databases, event streams, and other data sources without requiring glue code or manual integration maintenance. The platform delivers self-repairing integrations through instant, on-the-fly orchestration that automatically adapts as APIs and schemas evolve, eliminating the need to write resolvers, generate API clients, or maintain YAML mapping files. Orbital works by having users embed semantic type metadata tags directly in their API specs (OpenAPI, Protobuf, databases), then use those tags in queries written in TaxiLang, a powerful query language that lets consumers define the schema they want while Orbital figures out where to fetch data from across multiple sources. Key features include universal scriptable field-level authorization policies applied everywhere, an automatic API and data catalog with interactive diagrams, end-to-end observability with lineage and call traces, and the ability to deploy custom APIs, event streams, and batch workflows in minutes with instant caching for performance. The platform supports git-based deployments where a simple git push instantly deploys endpoints that automatically migrate as APIs evolve, and enables use cases like microservices orchestration, event-based architectures, and rapid onboarding of external data feeds, making it ideal for engineering teams that would normally have to write extensive integration code.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/orbital/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Gateways, Data

## Timestamps

- **Created:** 2026-01-05 
- **Modified:** 2026-03-14 

## APIs

### Orbital Query API
The Orbital Query API allows developers to submit TaxiQL queries to the Orbital data gateway for integrating, transforming, and discovering data across APIs, databases, event streams, and other data sources. Queries are submitted to the /api/taxiql endpoint and results can be returned as JSON or streamed via Server-Sent Events. The API also provides endpoints for managing connections and caches.

**Human URL:** [https://orbitalhq.com/docs/querying/writing-queries](https://orbitalhq.com/docs/querying/writing-queries)


#### Tags:

 - Gateways, Data, Integration, Queries

#### Properties

- [Documentation](https://orbitalhq.com/docs/querying/writing-queries)
- [OpenAPI](openapi/orbital-query-api-openapi.yml)
- [JSONSchema](json-schema/query.json)
- [JSONSchema](json-schema/connection.json)
- [JSONSchema](json-schema/cache.json)
- [JSONLD](json-ld/orbital-context.jsonld)

### Orbital Schema Management API
The Orbital Schema Management API provides endpoints for managing schemas, types, and data source definitions within an Orbital workspace. It allows developers to register, update, and remove Taxi schemas and type definitions that Orbital uses to understand the semantic relationships between data across connected services. Schemas can originate from OpenAPI specs, Protobuf definitions, database schemas, or Taxi projects.

**Human URL:** [https://orbitalhq.com/docs/describing-data-sources/open-api](https://orbitalhq.com/docs/describing-data-sources/open-api)


#### Tags:

 - Gateways, Data, Schemas, Types

#### Properties

- [Documentation](https://orbitalhq.com/docs/describing-data-sources/open-api)
- [OpenAPI](openapi/orbital-schema-management-api-openapi.yml)
- [JSONSchema](json-schema/schema.json)
- [JSONSchema](json-schema/service.json)
- [JSONSchema](json-schema/type.json)
- [JSONLD](json-ld/orbital-context.jsonld)

## Common Properties

- [Website](https://orbitalhq.com/)
- [Documentation](https://orbitalhq.com/docs)
- [ChangeLog](https://orbitalhq.com/changelog)
- [Pricing](https://orbitalhq.com/pricing)
- [Blog](https://orbitalhq.com/blog)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
