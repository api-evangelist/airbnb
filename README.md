# Airbnb

Airbnb is the world's leading home-sharing and short-term rental marketplace, connecting hosts
who offer accommodations and experiences with guests worldwide. The Airbnb developer platform
provides connectivity partners — property management systems, channel managers, and experience
operators — with APIs to manage listings, reservations, calendars, messaging, reviews, and
webhook-based event notifications. Access is restricted to approved partners.

## APIs

- **Airbnb Homes API** — Manage property listings, calendars, reservations, messaging, and reviews
  - OpenAPI: [openapi/airbnb-homes-api-openapi.yml](openapi/airbnb-homes-api-openapi.yml)
  - Documentation: https://developer.withairbnb.com/

- **Airbnb Activities API** — Manage Experiences listings, scheduling, bookings, and host communications
  - OpenAPI: [openapi/airbnb-activities-api-openapi.yml](openapi/airbnb-activities-api-openapi.yml)
  - Documentation: https://developer.withairbnb.com/

- **Airbnb Webhooks API** — Receive real-time event notifications for reservations, messages, and reviews
  - AsyncAPI: [asyncapi/airbnb-webhooks-asyncapi.yml](asyncapi/airbnb-webhooks-asyncapi.yml)
  - Documentation: https://developer.withairbnb.com/

## Resources

- [Developer Portal](https://developer.withairbnb.com/)
- [Airbnb GitHub](https://github.com/airbnb)
- [Terms of Service](https://www.airbnb.com/terms)
- [Privacy Policy](https://www.airbnb.com/privacy)
- [Status](https://airbnb.statuspage.io/)

## Data Models

This repository includes 26 JSON Schema definitions extracted from the OpenAPI specifications,
covering listings, reservations, experiences, bookings, calendar days, messages, reviews, guests, and more.

- [json-schema/](json-schema/) — JSON Schema (draft/2020-12) definitions
- [json-structure/](json-structure/) — JSON Structure (json-structure.org) definitions
- [examples/](examples/) — Example instances of all data models
- [json-ld/airbnb-context.jsonld](json-ld/airbnb-context.jsonld) — JSON-LD 1.1 context with schema.org mappings

## Rules and Governance

- [rules/airbnb-spectral-rules.yml](rules/airbnb-spectral-rules.yml) — Spectral ruleset for API convention enforcement

## Capabilities

- [capabilities/shared/airbnb-api.yaml](capabilities/shared/airbnb-api.yaml) — Naftiko shared capability definition
- [capabilities/airbnb-listing-management.yaml](capabilities/airbnb-listing-management.yaml) — Workflow capability with 5 MCP tools

## Vocabulary

- [vocabulary/airbnb-vocabulary.yaml](vocabulary/airbnb-vocabulary.yaml) — 8 resources, 8 actions
