# Airbnb GraphQL Schema

## Overview

This is a conceptual GraphQL schema for the Airbnb platform, covering the core domains of the Airbnb partner API: listings, reservations, calendars, pricing, guests, hosts, messaging, reviews, experiences, and payments. Airbnb does not publish a public GraphQL API; this schema is derived from the documented REST partner API capabilities at https://developer.withairbnb.com/ and represents the data model in GraphQL SDL form.

## Schema Source

- **Derived from**: Airbnb Homes API and Activities API (REST)
- **Partner portal**: https://developer.withairbnb.com/
- **Access model**: Approved connectivity partners only (property management systems, channel managers)

## Domains Covered

### Listings
Core property listing types including `Listing`, `ListingDetails`, `Room`, `EntireHome`, `SharedRoom`, `HotelRoom`, and supporting types for amenities, photos, check-in/check-out, and location data.

### Availability and Calendar
`Calendar`, `BlockedDate`, `Availability`, `HostCalendar`, and `HostAvailability` types covering date-based availability and synchronization.

### Pricing
`Price`, `PricingRule`, `WeekendPrice`, `WeeklyPrice`, `MonthlyPrice`, and `LongTermPrice` types supporting Airbnb's flexible pricing model.

### Reservations and Bookings
`Booking`, `Reservation`, and supporting workflow types for the full reservation lifecycle.

### Guests and Hosts
`Guest`, `Host`, `Profile`, `HostResponse`, `Verification`, and `HostConfig` types covering user identity and partner management.

### Reviews
`Review`, `ReviewFrom`, `ReviewTo`, and `LookupRating` types for the Airbnb two-way review system.

### Messaging
`Message` and `Thread` types for guest-host communication within reservation contexts.

### Experiences
`Experience`, `ExperienceType`, `ExperienceActivity`, and `ExperiencePhoto` types for the Airbnb Experiences marketplace.

### Search
`Search`, `SearchFilter`, and `SearchResult` types for listing and experience discovery.

### Wishlists
`Wishlist` and `WishlistItem` types for guest saved collections.

### Payments and Payouts
`Payment`, `Payout`, `PayoutAccount`, and `PayoutMethod` types for financial transaction management.

### Localization
`LocaleCurrency` and `ExchangeRate` types for multi-currency support.

### Referrals
`Invite` and `Referral` types for the Airbnb referral program.

### Protection
`AirCover` and `InsuranceCoverage` types for Airbnb's host protection program.

## File

- `airbnb-schema.graphql` — Full GraphQL SDL with 60+ named types
