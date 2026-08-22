# Yelp (yelp)

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
