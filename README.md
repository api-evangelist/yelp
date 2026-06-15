# Yelp (yelp)

Yelp connects people with great local businesses. The Yelp Fusion API gives developers programmatic access to Yelp's database of millions of local businesses, ratings, reviews, photos, events, and category taxonomy, plus the Yelp Fusion AI conversational search endpoint. Core public capabilities include business search and discovery, business details, review excerpts, autocomplete, phone and address matching, and local event search. Partner-tier APIs add reviews response, leads, advertising, reservations, waitlist, checkout, and reporting. Authentication uses a Yelp API key passed as a bearer token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/yelp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/yelp/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Restaurant
- Local Search
- Reviews
- Business Data
- Location

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-06-03

## APIs

### Yelp Fusion API

The public Yelp Fusion REST API for business search and discovery, business details, reviews, autocomplete, phone and address matching, local events, category taxonomy, and the Yelp Fusion AI conversational chat endpoint. Authenticated with a Yelp API key passed as a bearer token.

- **Human URL:** [https://docs.developer.yelp.com/](https://docs.developer.yelp.com/)
- **Base URL:** `https://api.yelp.com`

#### Tags

- Restaurant
- Local Search
- Reviews

#### Properties

- [Documentation](https://docs.developer.yelp.com/)
- [API Reference](https://docs.developer.yelp.com/reference/v3_business_search)
- [OpenAPI](openapi/yelp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yelp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yelp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/yelp-business-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-business-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-business-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-coordinates-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-category-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-review-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-reviews-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-autocomplete-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-business-hours-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-event-search-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-ai-chat-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/yelp-ai-chat-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/yelp-business-structure.json)
- [JSON Structure](json-structure/yelp-business-detail-structure.json)
- [JSON Structure](json-structure/yelp-business-search-response-structure.json)
- [JSON Structure](json-structure/yelp-review-structure.json)
- [JSON Structure](json-structure/yelp-event-structure.json)
- [JSON Structure](json-structure/yelp-category-structure.json)
- [Example](examples/yelp-business-search-response-example.json)
- [Example](examples/yelp-business-detail-example.json)
- [Example](examples/yelp-reviews-response-example.json)
- [Example](examples/yelp-event-search-response-example.json)
- [Example](examples/yelp-autocomplete-response-example.json)
- [Example](examples/yelp-ai-chat-response-example.json)

## Common Properties

- [Documentation](https://docs.developer.yelp.com/)
- [Getting Started](https://docs.developer.yelp.com/docs/getting-started)
- [API Reference](https://docs.developer.yelp.com/reference/v3_business_search)
- [Authentication](https://docs.developer.yelp.com/docs/oauth-authorization)
- [Developer Portal](https://www.yelp.com/developers)
- [Sign Up](https://www.yelp.com/developers/v3/manage_app)
- [Console](https://www.yelp.com/developers/fusion-ai/chat)
- [Pricing](https://docs.developer.yelp.com/docs/plans)
- [Rate Limits](https://docs.developer.yelp.com/docs/places-rate-limiting)
- [Errors](https://docs.developer.yelp.com/docs/api-errors)
- [F A Q](https://docs.developer.yelp.com/docs/places-faq)
- [Changelog](https://docs.developer.yelp.com/changelog)
- [Terms of Service](https://docs.developer.yelp.com/docs/policies)
- [GitHub Organization](https://github.com/Yelp)
- [GitHub Repository](https://github.com/Yelp/yelp-fusion)
- [LinkedIn](https://www.linkedin.com/company/yelp-com)
- [L L Ms Txt](https://docs.developer.yelp.com/llms.txt)
- [SDK](https://github.com/Yelp/yelp-fusion)
- [SDK](https://github.com/Yelp/yelp-python)
- [SDK](https://github.com/Yelp/yelp-ruby)
- [SDK](https://github.com/Yelp/yelp-android)
- [SDK](https://github.com/Yelp/yelp-ios)
- [Tools](https://github.com/Yelp/yelp-mcp)
- [Spectral Rules](rules/yelp-spectral-rules.yml)
- [Vocabulary](vocabulary/yelp-vocabulary.yaml)
- [JSON-LD](json-ld/yelp-fusion-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/yelp-plans-pricing.yml)
- [Rate Limits](rate-limits/yelp-rate-limits.yml)
- [Fin Ops](finops/yelp-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
