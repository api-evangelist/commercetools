# commercetools (commercetools)

commercetools is the leading composable, headless, API-first Commerce platform powering large-scale B2C, B2B, and marketplace digital commerce for enterprise brands. The platform exposes a broad API surface organized into the HTTP API (core REST interface), GraphQL API (flexible query and mutation alternative), Import API (bulk data ingestion), Change History API (audit log), Checkout API (managed checkout configuration), and Merchant Center Customizations API (custom UI extensions). It is complemented by official SDKs (TypeScript, Java, PHP, .NET, Python) and AsyncAPI-based subscriptions for event-driven integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Commerce
- Composable Commerce
- E-Commerce
- GraphQL
- REST
- SDK

## Timestamps

- **Created:** 2025-09-15
- **Modified:** 2026-05-19

## APIs

### Commercetools HTTP API

The commercetools HTTP API is the core REST interface for programmatic access to all data and functionality within a Composable Commerce project. It covers a broad range of commerce resources including products, product types, categories, carts, orders, customers, payments, discounts, inventory, shipping methods, stores, and business units. All resources follow RESTful conventions using standard HTTP verbs and return JSON responses.

- **Human URL:** [https://docs.commercetools.com/api](https://docs.commercetools.com/api)
- **Base URL:** `https://api.{region}.commercetools.com`

#### Tags

- Commerce
- Composable Commerce
- E-Commerce
- REST

#### Properties

- [Documentation](https://docs.commercetools.com/api)
- [OpenAPI](openapi/commercetools-http-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercetools-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/commercetools-subscriptions-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Commercetools GraphQL API

The commercetools GraphQL API provides a flexible, network-efficient alternative to the HTTP API for querying and mutating Composable Commerce resources. It exposes a single endpoint and allows clients to request exactly the data they need, reducing over-fetching and minimizing round trips. The GraphQL API uses the same API clients, authentication tokens, and project scopes as the HTTP API.

- **Human URL:** [https://docs.commercetools.com/api/graphql](https://docs.commercetools.com/api/graphql)
- **Base URL:** `https://api.{region}.commercetools.com`

#### Tags

- Commerce
- Composable Commerce
- E-Commerce
- GraphQL

#### Properties

- [Documentation](https://docs.commercetools.com/api/graphql)
- [Postman Collection](collections/commercetools-change-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-change-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-import-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-import-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commercetools Import API

The commercetools Import API enables bulk importing of commerce data into a Composable Commerce project. It supports importing categories, product types, products, product variants, prices, inventory entries, orders, and customers. Imports are processed asynchronously through import containers, and the API provides endpoints for monitoring import operation status and handling validation errors.

- **Human URL:** [https://docs.commercetools.com/api/import-export/overview](https://docs.commercetools.com/api/import-export/overview)
- **Base URL:** `https://import.{region}.commercetools.com`

#### Tags

- Bulk Operations
- Commerce
- Data Migration
- Import

#### Properties

- [Documentation](https://docs.commercetools.com/api/import-export/overview)
- [OpenAPI](openapi/commercetools-import-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercetools-import-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-import-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commercetools Change History API

The commercetools Change History API provides a queryable audit log of all changes made to resources within a Composable Commerce project. It records mutations applied to resources such as products, orders, customers, discounts, and carts, along with metadata about who made the change and when. The API is hosted on separate regional endpoints and supports filtering by resource type, date range, user, and client.

- **Human URL:** [https://docs.commercetools.com/api/history/overview](https://docs.commercetools.com/api/history/overview)
- **Base URL:** `https://history.{region}.commercetools.com`

#### Tags

- Audit Log
- Change History
- Commerce
- Compliance

#### Properties

- [Documentation](https://docs.commercetools.com/api/history/overview)
- [OpenAPI](openapi/commercetools-change-history-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercetools-change-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-change-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commercetools TypeScript SDK

The commercetools TypeScript SDK is the official client library for interacting with the Composable Commerce HTTP API, Import API, and GraphQL API from JavaScript and TypeScript applications. It provides full type safety, IDE autocompletion, and a fluent domain-specific language for constructing valid API requests. The SDK handles OAuth 2.0 token management, request building, and response deserialization.

- **Human URL:** [https://docs.commercetools.com/sdk/typescript-sdk](https://docs.commercetools.com/sdk/typescript-sdk)
- **Base URL:** `https://api.example.com`

#### Tags

- Commerce
- JavaScript
- SDK
- TypeScript

#### Properties

- [Documentation](https://docs.commercetools.com/sdk/typescript-sdk)
- [Postman Collection](collections/commercetools-change-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-change-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-import-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-import-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commercetools Java SDK

The commercetools Java SDK is the official client library for accessing the Composable Commerce APIs from Java applications. It provides strongly typed request builders, automatic OAuth 2.0 token management, and support for all HTTP API and Import API endpoints. The SDK is compatible with standard Java development toolchains and is distributed via Maven Central. It is commonly used in enterprise backend systems and microservices that require JVM-based integration with the commercetools platform.

- **Human URL:** [https://docs.commercetools.com/sdk/java-sdk](https://docs.commercetools.com/sdk/java-sdk)
- **Base URL:** `https://api.example.com`

#### Tags

- Commerce
- Java
- JVM
- SDK

#### Properties

- [Documentation](https://docs.commercetools.com/sdk/java-sdk)
- [Postman Collection](collections/commercetools-change-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-change-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-import-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-import-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commercetools Checkout API

The commercetools Checkout API provides programmatic control over Checkout application configurations within Composable Commerce. The Checkout Applications API allows developers to create, update, and manage Checkout applications without manual setup in the Merchant Center, enabling automated deployment and configuration across multiple stores, regions, and business units. Checkout integrates with payment connectors available through the Connect marketplace.

- **Human URL:** [https://docs.commercetools.com/checkout](https://docs.commercetools.com/checkout)
- **Base URL:** `https://api.example.com`

#### Tags

- Checkout
- Commerce
- Embedded Components
- Payments

#### Properties

- [Documentation](https://docs.commercetools.com/checkout)
- [Postman Collection](collections/commercetools-change-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-change-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-import-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-import-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commercetools Merchant Center Customizations API

The commercetools Merchant Center Customizations API provides the programmatic interface for building custom applications and UI extensions within the Merchant Center. It exposes proxy endpoints to underlying REST and GraphQL APIs, allowing custom UIs to interact with Composable Commerce resources in a secure, scoped manner. Developers use this API when creating Custom Applications that extend the Merchant Center with business-specific tooling.

- **Human URL:** [https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api](https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api)
- **Base URL:** `https://api.example.com`

#### Tags

- Commerce
- Customizations
- Extensions
- Merchant Center

#### Properties

- [Documentation](https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api)
- [Postman Collection](collections/commercetools-change-history-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-change-history-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/commercetools-import-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercetools-import-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/commercetools)
- [Website](https://commercetools.com/)
- [Documentation](https://docs.commercetools.com/)
- [Pricing](https://commercetools.com/pricing)
- [Status Page](https://status.commercetools.com/)
- [Git Hub](https://github.com/commercetools)
- [JSON-LD](json-ld/commercetools-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/commercetools-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/commercetools-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/commercetools-subscription-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/commercetools-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Features](undefined)
- [Integrations](https://commercetools.com/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
