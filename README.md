# Trengo (trengo)

Trengo is an omnichannel customer-engagement and shared-inbox platform that unifies email, WhatsApp, live chat, voice, SMS, and social channels into one team inbox with AI agents. The Trengo REST API (app.trengo.com/api/v2) lets you create and manage tickets, contacts, messages, channels, teams, users, labels, custom fields, webhooks, and WhatsApp templates programmatically with Bearer-token authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trengo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trengo/refs/heads/main/apis.yml)

## Tags

- Customer Engagement
- Omnichannel
- Shared Inbox
- Messaging
- WhatsApp
- Customer Support

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Trengo Tickets API

Create, list, assign, label, and close tickets (conversations) across every connected channel in the shared inbox, with filters for status, channel, user, label, and contact.

- **Human URL:** [https://developers.trengo.com/reference/list-all-tickets](https://developers.trengo.com/reference/list-all-tickets)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Tickets
- Conversations
- Inbox

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference/list-all-tickets)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo Contacts API

Manage contacts and contact profiles - create, fetch, list, update, and delete the people behind conversations, including identifiers and channel bindings used to route messages.

- **Human URL:** [https://developers.trengo.com/reference](https://developers.trengo.com/reference)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Contacts
- Profiles
- CRM

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo Messages API

List messages on a ticket and send outbound text or media messages to the contact's channel, including file uploads attached to outgoing replies.

- **Human URL:** [https://developers.trengo.com/reference/list-all-messages](https://developers.trengo.com/reference/list-all-messages)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Messages
- Send
- Media

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference/list-all-messages)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo Channels API

List the connected channels - email, WhatsApp, chat, voice, SMS, and social - that messages and tickets are bound to, including voice channels for telephony integrations.

- **Human URL:** [https://developers.trengo.com/reference](https://developers.trengo.com/reference)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Channels
- Voice
- Omnichannel

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo Teams and Users API

Manage teams and the agents (users) that handle conversations - list users, create teams, and use these identifiers when assigning tickets or filtering inbox views.

- **Human URL:** [https://developers.trengo.com/reference](https://developers.trengo.com/reference)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Teams
- Users
- Agents

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo Labels and Custom Fields API

Create and attach labels to tickets and define custom fields to store structured metadata on tickets and contacts for routing, reporting, and automation.

- **Human URL:** [https://developers.trengo.com/reference](https://developers.trengo.com/reference)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Labels
- Custom Fields
- Metadata

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo Webhooks API

Register, update, and delete webhooks so external systems receive real-time callbacks when tickets are created, assigned, closed, or messages are received.

- **Human URL:** [https://developers.trengo.com/docs/configuration](https://developers.trengo.com/docs/configuration)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://developers.trengo.com/docs/configuration)
- [API Reference](https://developers.trengo.com/reference)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trengo WhatsApp Templates API

Send pre-approved WhatsApp Business message templates to contacts to initiate or continue conversations outside the 24-hour customer-care window.

- **Human URL:** [https://developers.trengo.com/reference](https://developers.trengo.com/reference)
- **Base URL:** `https://app.trengo.com/api/v2`

#### Tags

- WhatsApp
- Templates
- Outbound

#### Properties

- [Documentation](https://developers.trengo.com/docs/welcome)
- [API Reference](https://developers.trengo.com/reference)
- [OpenAPI](openapi/trengo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trengo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trengo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/trengo)
- [Website](https://trengo.com/)
- [Documentation](https://developers.trengo.com/docs/welcome)
- [Plans](plans/trengo-plans-pricing.yml)
- [Rate Limits](rate-limits/trengo-rate-limits.yml)
- [Fin Ops](finops/trengo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
