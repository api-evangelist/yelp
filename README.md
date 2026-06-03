# Yelp (yelp)
Yelp connects people with great local businesses. The Yelp Fusion API gives developers programmatic access to Yelp's database of millions of local businesses, ratings, reviews, photos, events, and category taxonomy, plus the Yelp Fusion AI conversational search endpoint. Core public capabilities include business search and discovery, business details, review excerpts, autocomplete, phone and address matching, and local event search. Partner-tier APIs add reviews response, leads, advertising, reservations, waitlist, checkout, and reporting. Authentication uses a Yelp API key passed as a bearer token.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/yelp/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

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

**Human URL:** [https://docs.developer.yelp.com/](https://docs.developer.yelp.com/)

**Base URL:** `https://api.yelp.com`

#### Tags:

 - Restaurant
 - Local Search
 - Reviews

#### Properties

- [Documentation](https://docs.developer.yelp.com/)
- [APIReference](https://docs.developer.yelp.com/reference/v3_business_search)
- [OpenAPI](openapi/yelp-openapi.yml)
- 14 [JSONSchema](json-schema/) files
- 6 [JSONStructure](json-structure/) files
- 6 [Example](examples/) files
- 5 [NaftikoCapability](capabilities/) files

## Common Properties

- [Documentation](https://docs.developer.yelp.com/)
- [GettingStarted](https://docs.developer.yelp.com/docs/getting-started)
- [APIReference](https://docs.developer.yelp.com/reference/v3_business_search)
- [Authentication](https://docs.developer.yelp.com/docs/oauth-authorization)
- [DeveloperPortal](https://www.yelp.com/developers)
- [SignUp](https://www.yelp.com/developers/v3/manage_app)
- [Console](https://www.yelp.com/developers/fusion-ai/chat)
- [Pricing](https://docs.developer.yelp.com/docs/plans)
- [RateLimits](https://docs.developer.yelp.com/docs/places-rate-limiting)
- [Errors](https://docs.developer.yelp.com/docs/api-errors)
- [FAQ](https://docs.developer.yelp.com/docs/places-faq)
- [ChangeLog](https://docs.developer.yelp.com/changelog)
- [TermsOfService](https://docs.developer.yelp.com/docs/policies)
- [GitHubOrganization](https://github.com/Yelp)
- [GitHubRepository](https://github.com/Yelp/yelp-fusion)
- [LinkedIn](https://www.linkedin.com/company/yelp-com)
- [LLMsTxt](https://docs.developer.yelp.com/llms.txt)
- [SDK — Yelp Fusion Code Samples](https://github.com/Yelp/yelp-fusion)
- [SDK — Python (yelp-python)](https://github.com/Yelp/yelp-python)
- [SDK — Ruby (yelp-ruby)](https://github.com/Yelp/yelp-ruby)
- [SDK — Android (yelp-android)](https://github.com/Yelp/yelp-android)
- [SDK — iOS (yelp-ios)](https://github.com/Yelp/yelp-ios)
- [Tools — MCP Server (Fusion AI)](https://github.com/Yelp/yelp-mcp)
- [SpectralRules](rules/yelp-spectral-rules.yml)
- [Vocabulary](vocabulary/yelp-vocabulary.yaml)
- [JSONLD](json-ld/yelp-fusion-api-context.jsonld)
- [Plans](plans/yelp-plans-pricing.yml)
- [RateLimits](rate-limits/yelp-rate-limits.yml)
- [FinOps](finops/yelp-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Business Search | Search up to 240 businesses by location, term, category, price, and attributes. |
| Business Details | Retrieve rich detail for a business by id or alias, including hours, photos, and attributes. |
| Reviews | Retrieve review excerpts, ratings, and reviewer details for a business. |
| Autocomplete | Return search-term, business, and category suggestions as the user types. |
| Phone and Address Match | Resolve a phone number or postal address to Yelp businesses. |
| Events | Search and retrieve local events with timing, location, cost, and ticketing. |
| Category Taxonomy | Access the full Yelp business category list and per-category details. |
| Fusion AI | Natural language, multi-turn conversational search and business questions. |

## Use Cases

| Name | Description |
|------|-------------|
| Restaurant Discovery | Power restaurant and food discovery experiences with search, ratings, and photos. |
| Location-Aware Recommendations | Surface nearby, open, and highly-rated businesses based on user coordinates. |
| Reputation Monitoring | Track ratings and review excerpts for a portfolio of businesses. |
| Conversational Concierge | Build AI agents that answer natural language questions about local businesses. |
| Local Events Listings | Embed curated local event listings into apps and sites. |

## Integrations

| Name | Description |
|------|-------------|
| Zapier | Yelp Leads and Conversions APIs offer Zapier integrations for no-code workflows. |
| Model Context Protocol | Official Yelp MCP server exposes Fusion AI as an agent tool over MCP. |
| Webhooks | Reviews and Leads webhooks push real-time events to partner endpoints. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Yelp Fusion API](openapi/yelp-openapi.yml) — 11 operations across Businesses, Reviews, Events, Categories, and AI

### JSON Schema

14 JSON Schema files extracted from the Yelp Fusion API components in [json-schema/](json-schema/).

### JSON Structure

14 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [Yelp Fusion API Context](json-ld/yelp-fusion-api-context.jsonld) — 98 terms with schema.org alignments

### Examples

14 example payloads in [examples/](examples/).

## Capabilities

Naftiko capabilities, one self-contained file per Yelp Fusion business surface. Each declares an inline `consumes` block plus REST and MCP exposers.

| Capability | API | Tools | Persona |
|------------|-----|-------|---------|
| [Business Discovery](capabilities/yelp-businesses.yaml) | Yelp Fusion API | 5 | Local Search Developer / Restaurant Concierge Agent |
| [Reviews](capabilities/yelp-reviews.yaml) | Yelp Fusion API | 1 | Reputation Analyst |
| [Local Events](capabilities/yelp-events.yaml) | Yelp Fusion API | 2 | Events Curator |
| [Category Taxonomy](capabilities/yelp-categories.yaml) | Yelp Fusion API | 2 | Local Search Developer |
| [Conversational AI](capabilities/yelp-ai.yaml) | Yelp Fusion API | 1 | Restaurant Concierge Agent |

## Vocabulary

- [Yelp Vocabulary](vocabulary/yelp-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 6 actions, 5 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Yelp Spectral Rules](rules/yelp-spectral-rules.yml) — 32 rules across info, paths, operations, tags, parameters, responses, schemas, security, and HTTP method categories enforcing Yelp Fusion API conventions

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/yelp-plans-pricing.yml) — Starter, Base, Enhanced, Premium, and Enterprise tiers
- [Rate Limits](rate-limits/yelp-rate-limits.yml) — Daily call cap, QPS throttling, and RateLimit headers
- [FinOps](finops/yelp-finops.yml) — FOCUS-aligned cost and usage mapping

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
