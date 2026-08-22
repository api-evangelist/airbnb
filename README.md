# airbnb (airbnb)

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

Airbnb is the world's leading home-sharing and short-term rental marketplace, connecting hosts who offer accommodations and experiences with guests worldwide. The Airbnb developer platform provides connectivity partners — property management systems, channel managers, and experience operators — with APIs to manage listings, reservations, calendars, messaging, reviews, and webhook-based event notifications. Access is restricted to approved partners.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/airbnb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/airbnb/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Airbnb Homes API

The Airbnb Homes API provides partner developers with programmatic access to manage vacation rental listings on the Airbnb platform. It supports creating and updating property listings, managing descriptions, amenities, photos, pricing, and availability rules. The API also enables reservation management, calendar synchronization, guest messaging, and review handling.

- **Human URL:** [https://developer.withairbnb.com/](https://developer.withairbnb.com/)
- **Base URL:** `https://api.airbnb.com`

#### Tags

- Airbnb
- Calendar
- Channel Manager
- Hospitality
- Host
- Listings
- Lodging
- Photos
- Property Management
- Reservations
- Short-Term Rental
- Travel
- Vacation Rentals

#### Properties

- [Documentation](https://developer.withairbnb.com/)
- [OpenAPI](openapi/airbnb-homes-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airbnb-homes-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airbnb-homes-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Airbnb Activities API

The Airbnb Activities API allows approved partners to integrate with Airbnb Experiences, the platform's marketplace for hosted activities and tours. It provides endpoints for managing experience listings, handling bookings, and synchronizing availability for activities offered by local hosts.

- **Human URL:** [https://developer.withairbnb.com/](https://developer.withairbnb.com/)
- **Base URL:** `https://api.airbnb.com`

#### Tags

- Activities
- Airbnb
- Bookings
- Experiences
- Hospitality
- Tourism
- Travel

#### Properties

- [Documentation](https://developer.withairbnb.com/)
- [OpenAPI](openapi/airbnb-activities-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airbnb-activities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airbnb-activities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Airbnb Webhooks API

The Airbnb Webhooks API enables connectivity partners to receive real-time notifications when events occur on the Airbnb platform. It supports webhook subscriptions for reservation changes, message creation, review submissions, listing calendar updates, and other key events.

- **Human URL:** [https://developer.withairbnb.com/](https://developer.withairbnb.com/)
- **Base URL:** `https://api.airbnb.com`

#### Tags

- Airbnb
- Events
- Hospitality
- Notifications
- Real-Time
- Reservations
- Travel
- Webhooks

#### Properties

- [Documentation](https://developer.withairbnb.com/)
- [AsyncAPI](asyncapi/airbnb-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/airbnb-activities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airbnb-activities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/airbnb-homes-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airbnb-homes-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.airbnb.com/)
- [Portal](https://developer.withairbnb.com/)
- [JSON-LD](json-ld/airbnb-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/airbnb-listing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-webhook-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Blog](https://www.airbnb.com/resources/hosting-homes/a/airbnb-newsroom)
- [Git Hub](https://github.com/airbnb)
- [LinkedIn](https://www.linkedin.com/company/airbnb)
- [Twitter](https://twitter.com/airbnb)
- [Terms of Service](https://www.airbnb.com/terms)
- [Privacy Policy](https://www.airbnb.com/privacy)
- [Status Page](https://airbnb.statuspage.io/)
- [JSON Schema](json-schema/airbnb-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-booking-guest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-booking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-calendar-day-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-calendar-operation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-host-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-photo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-pricing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-experience-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-guest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-listing-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-listing-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-photo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-pricing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-review-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-schedule-create-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/airbnb-schedule-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/airbnb-address-structure.json)
- [JSON Structure](json-structure/airbnb-booking-guest-structure.json)
- [JSON Structure](json-structure/airbnb-booking-structure.json)
- [JSON Structure](json-structure/airbnb-calendar-day-structure.json)
- [JSON Structure](json-structure/airbnb-calendar-operation-structure.json)
- [JSON Structure](json-structure/airbnb-experience-create-structure.json)
- [JSON Structure](json-structure/airbnb-experience-host-structure.json)
- [JSON Structure](json-structure/airbnb-experience-location-structure.json)
- [JSON Structure](json-structure/airbnb-experience-message-structure.json)
- [JSON Structure](json-structure/airbnb-experience-photo-structure.json)
- [JSON Structure](json-structure/airbnb-experience-pricing-structure.json)
- [JSON Structure](json-structure/airbnb-experience-structure.json)
- [JSON Structure](json-structure/airbnb-experience-update-structure.json)
- [JSON Structure](json-structure/airbnb-guest-structure.json)
- [JSON Structure](json-structure/airbnb-listing-create-structure.json)
- [JSON Structure](json-structure/airbnb-listing-structure.json)
- [JSON Structure](json-structure/airbnb-listing-update-structure.json)
- [JSON Structure](json-structure/airbnb-message-structure.json)
- [JSON Structure](json-structure/airbnb-photo-structure.json)
- [JSON Structure](json-structure/airbnb-pricing-structure.json)
- [JSON Structure](json-structure/airbnb-reservation-structure.json)
- [JSON Structure](json-structure/airbnb-review-structure.json)
- [JSON Structure](json-structure/airbnb-schedule-create-structure.json)
- [JSON Structure](json-structure/airbnb-schedule-structure.json)
- [JSON Structure](json-structure/airbnb-schedule-update-structure.json)
- [JSON Structure](json-structure/airbnb-webhook-event-structure.json)
- [Example](examples/airbnb-address-example.json)
- [Example](examples/airbnb-booking-example.json)
- [Example](examples/airbnb-booking-guest-example.json)
- [Example](examples/airbnb-calendar-day-example.json)
- [Example](examples/airbnb-calendar-operation-example.json)
- [Example](examples/airbnb-experience-create-example.json)
- [Example](examples/airbnb-experience-example.json)
- [Example](examples/airbnb-experience-host-example.json)
- [Example](examples/airbnb-experience-location-example.json)
- [Example](examples/airbnb-experience-message-example.json)
- [Example](examples/airbnb-experience-photo-example.json)
- [Example](examples/airbnb-experience-pricing-example.json)
- [Example](examples/airbnb-experience-update-example.json)
- [Example](examples/airbnb-guest-example.json)
- [Example](examples/airbnb-listing-create-example.json)
- [Example](examples/airbnb-listing-example.json)
- [Example](examples/airbnb-listing-update-example.json)
- [Example](examples/airbnb-message-example.json)
- [Example](examples/airbnb-photo-example.json)
- [Example](examples/airbnb-pricing-example.json)
- [Example](examples/airbnb-reservation-example.json)
- [Example](examples/airbnb-review-example.json)
- [Example](examples/airbnb-schedule-create-example.json)
- [Example](examples/airbnb-schedule-example.json)
- [Example](examples/airbnb-schedule-update-example.json)
- [Example](examples/airbnb-webhook-event-example.json)
- [Spectral Rules](rules/airbnb-spectral-rules.yml)
- [Vocabulary](vocabulary/airbnb-vocabulary.yaml)
