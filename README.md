# commercetools (commercetools)

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
