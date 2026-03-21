# commercetools (commercetools)
commercetools is a cloud-native, headless commerce platform built on the Composable Commerce model, enabling businesses to build flexible retail and B2B solutions using microservices-based APIs. Their developer platform provides REST, GraphQL, and event-driven APIs for managing the full commerce lifecycle, along with SDKs, import tooling, and extensibility through the Merchant Center.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Commerce, E-Commerce, Composable Commerce, Headless, REST, GraphQL

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### commercetools HTTP API
The commercetools HTTP API is the core REST interface for programmatic access to all data and functionality within a Composable Commerce project. It covers a broad range of commerce resources including products, product types, categories, carts, orders, customers, payments, discounts, inventory, shipping methods, stores, and business units. All resources follow RESTful conventions using standard HTTP verbs and return JSON responses. Authentication is handled via OAuth 2.0 client credentials, and requests are scoped per project and resource type.

**Human URL:** [https://docs.commercetools.com/api](https://docs.commercetools.com/api)


#### Tags:

 - Commerce, E-Commerce, Composable Commerce, REST

#### Properties

- [Documentation](https://docs.commercetools.com/api)
- [OpenAPI](openapi/commercetools-http-api-openapi.yml)

### commercetools GraphQL API
The commercetools GraphQL API provides a flexible, network-efficient alternative to the HTTP API for querying and mutating Composable Commerce resources. It exposes a single endpoint and allows clients to request exactly the data they need, reducing over-fetching and minimizing round trips. The GraphQL API uses the same API clients, authentication tokens, and project scopes as the HTTP API. It is well-suited for frontend applications and headless commerce implementations where bandwidth and response shape control are important.

**Human URL:** [https://docs.commercetools.com/api/graphql](https://docs.commercetools.com/api/graphql)


#### Tags:

 - GraphQL, Commerce, E-Commerce, Composable Commerce

#### Properties

- [Documentation](https://docs.commercetools.com/api/graphql)

### commercetools Import API
The commercetools Import API enables bulk importing of commerce data into a Composable Commerce project. It supports importing categories, product types, products, product variants, prices, inventory entries, orders, and customers. Imports are processed asynchronously through import containers, and the API provides endpoints for monitoring import operation status and handling validation errors. The Import API is hosted on separate regional endpoints from the main HTTP API and uses the same OAuth 2.0 authorization model. It is commonly used for initial data migrations, catalog synchronization, and ongoing bulk data updates from external systems.

**Human URL:** [https://docs.commercetools.com/api/import-export/overview](https://docs.commercetools.com/api/import-export/overview)


#### Tags:

 - Import, Bulk Operations, Commerce, Data Migration

#### Properties

- [Documentation](https://docs.commercetools.com/api/import-export/overview)
- [OpenAPI](openapi/commercetools-import-api-openapi.yml)

### commercetools Change History API
The commercetools Change History API provides a queryable audit log of all changes made to resources within a Composable Commerce project. It records mutations applied to resources such as products, orders, customers, discounts, and carts, along with metadata about who made the change and when. The API is hosted on separate regional endpoints and supports filtering by resource type, date range, user, and client. It is useful for compliance workflows, debugging unexpected state changes, and building audit trails for regulated industries.

**Human URL:** [https://docs.commercetools.com/api/history/overview](https://docs.commercetools.com/api/history/overview)


#### Tags:

 - Audit Log, Change History, Compliance, Commerce

#### Properties

- [Documentation](https://docs.commercetools.com/api/history/overview)
- [OpenAPI](openapi/commercetools-change-history-api-openapi.yml)

### commercetools TypeScript SDK
The commercetools TypeScript SDK is the official client library for interacting with the Composable Commerce HTTP API, Import API, and GraphQL API from JavaScript and TypeScript applications. It provides full type safety, IDE autocompletion, and a fluent domain-specific language for constructing valid API requests. The SDK handles OAuth 2.0 token management, request building, and response deserialization. It is available as open source under the MIT License on GitHub and distributed via npm, making it suitable for both Node.js backend services and frontend applications.

**Human URL:** [https://docs.commercetools.com/sdk/typescript-sdk](https://docs.commercetools.com/sdk/typescript-sdk)


#### Tags:

 - TypeScript, JavaScript, SDK, Commerce

#### Properties

- [Documentation](https://docs.commercetools.com/sdk/typescript-sdk)

### commercetools Java SDK
The commercetools Java SDK is the official client library for accessing the Composable Commerce APIs from Java applications. It provides strongly typed request builders, automatic OAuth 2.0 token management, and support for all HTTP API and Import API endpoints. The SDK is compatible with standard Java development toolchains and is distributed via Maven Central. It is commonly used in enterprise backend systems and microservices that require JVM-based integration with the commercetools platform.

**Human URL:** [https://docs.commercetools.com/sdk/java-sdk](https://docs.commercetools.com/sdk/java-sdk)


#### Tags:

 - Java, SDK, Commerce, JVM

#### Properties

- [Documentation](https://docs.commercetools.com/sdk/java-sdk)

### commercetools Checkout API
The commercetools Checkout API provides programmatic control over Checkout application configurations within Composable Commerce. The Checkout Applications API allows developers to create, update, and manage Checkout applications without manual setup in the Merchant Center, enabling automated deployment and configuration across multiple stores, regions, and business units. Checkout integrates with payment connectors available through the Connect marketplace. It is designed for merchants that need a scalable, consistent checkout and payment experience managed through infrastructure-as-code workflows.

**Human URL:** [https://docs.commercetools.com/checkout](https://docs.commercetools.com/checkout)


#### Tags:

 - Checkout, Payments, Commerce, Embedded Components

#### Properties

- [Documentation](https://docs.commercetools.com/checkout)

### commercetools Merchant Center Customizations API
The commercetools Merchant Center Customizations API provides the programmatic interface for building custom applications and UI extensions within the Merchant Center. It exposes proxy endpoints to underlying REST and GraphQL APIs, allowing custom UIs to interact with Composable Commerce resources in a secure, scoped manner. Developers use this API when creating Custom Applications that extend the Merchant Center with business-specific tooling. The API handles authentication delegation and provides GraphQL targets for fetching project and organization-level data within the Merchant Center context.

**Human URL:** [https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api](https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api)


#### Tags:

 - Merchant Center, Customizations, Commerce, Extensions

#### Properties

- [Documentation](https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api)

## Common Properties

- [Portal](https://docs.commercetools.com/)
- [Documentation](https://docs.commercetools.com/)
- [Website](https://commercetools.com/)
- [PrivacyPolicy](https://commercetools.com/privacy)
- [TermsOfService](https://commercetools.com/terms-conditions)
- [Support](https://support.commercetools.com/)
- [Blog](https://commercetools.com/blog)
- [Login](https://mc.us-central1.gcp.commercetools.com/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
