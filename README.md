# Trengo (trengo)

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
