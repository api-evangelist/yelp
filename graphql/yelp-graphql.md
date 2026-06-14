# Yelp GraphQL API

Yelp exposes a GraphQL endpoint alongside its REST Fusion API, available at `https://api.yelp.com/v3/graphql`. The same bearer-token authentication used for the REST API applies here. The GraphQL surface mirrors the core Fusion REST capabilities — business search, business details, reviews, phone and address matching, events, autocomplete, and category taxonomy — but lets clients request exactly the fields they need in a single round trip.

## Endpoint

```
POST https://api.yelp.com/v3/graphql
Content-Type: application/json
Authorization: Bearer <YELP_API_KEY>
```

## Reference

- Official GraphQL reference: https://docs.developer.yelp.com/reference/v3_graphql
- Yelp developer portal: https://www.yelp.com/developers
- GitHub organization: https://github.com/Yelp

## Root Queries

| Query | Description |
|---|---|
| `search` | Search for businesses by keyword, location, coordinates, category, price, attributes, and more. Returns a `Businesses` response with pagination. |
| `business` | Fetch full details for a single business by Yelp ID or alias. |
| `reviews` | Retrieve review excerpts, ratings, and reviewer details for a business. |
| `phone_search` | Resolve a phone number to matching Yelp businesses. |
| `business_match` | Match a business by name and address to a Yelp business record. |
| `event` | Retrieve details for a single Yelp event by ID. |
| `search_event` | Search for local events by location, category, and time range. |
| `featured_event` | Return the featured event for a given location. |
| `categories` | List all Yelp business categories or filter by alias. |
| `category` | Retrieve a single category by alias. |
| `autocomplete` | Return business, category, and search-term suggestions for a partial query string. |
| `transaction_search` | Search for businesses that support a transaction type such as food delivery or restaurant reservations. |

## Schema File

See `yelp-schema.graphql` in this directory for the full type definitions.

## Example Query

```graphql
{
  search(term: "sushi", location: "San Francisco, CA", limit: 5) {
    total
    business {
      id
      name
      rating
      review_count
      price
      location {
        address1
        city
        state
        zip_code
      }
      coordinates {
        latitude
        longitude
      }
      categories {
        alias
        title
      }
      hours {
        hours_type
        is_open_now
        open {
          day
          start
          end
          is_overnight
        }
      }
    }
  }
}
```

## Authentication

Pass your Yelp API key as an `Authorization: Bearer <key>` header. All GraphQL requests are POST to the single endpoint above; the query or mutation is supplied in the request body as JSON with a `query` field and optionally a `variables` field.

## Rate Limits

The GraphQL endpoint shares the same rate-limit pool as the REST Fusion API. See https://docs.developer.yelp.com/docs/places-rate-limiting for current limits by plan tier.
