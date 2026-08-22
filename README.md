# Microsoft Outlook (microsoft-outlook)

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

Microsoft Outlook is a personal information manager and email client that is part of the Microsoft Office suite. It provides email, calendar, contact management, task management, and other productivity features.

**APIs.json:** [https://outlook.office.com](https://outlook.office.com)

## Tags

- Calendar
- Contacts
- Email
- Enterprise
- Microsoft
- Office 365
- Productivity

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Microsoft Graph Mail API

API for accessing Outlook email messages, folders, and mail settings through Microsoft Graph.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Email
- Folders
- Mail
- Messages

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-graph-mail-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/microsoft-outlook-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-outlook-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-mail-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)

### Microsoft Graph Calendar API

API for accessing Outlook calendar events, calendars, and meeting scheduling through Microsoft Graph.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Calendar
- Events
- Meetings
- Scheduling

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Code Examples](https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0#code-samples)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-calendar-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/calendar-overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Contacts API

API for accessing Outlook contacts and contact folders through Microsoft Graph.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Address Book
- Contacts
- People

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Tasks API

API for accessing Outlook tasks and to-do items through Microsoft Graph.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Task Management
- Tasks
- To-Do

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/todo-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Outlook Add-ins API

JavaScript API for building Outlook add-ins that extend Outlook functionality with custom features, using the Office.js library and the Mailbox requirement set.

- **Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/)
- **Base URL:** `https://appsforoffice.microsoft.com/lib/1/hosted/office.js`

#### Tags

- Add-Ins
- Extensions
- Office.js
- Plugins

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/)
- [Getting Started](https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/outlook-quickstart-yo)
- [API Reference](https://learn.microsoft.com/en-us/office/dev/add-ins/reference/javascript-api-for-office)
- [Authentication](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/microsoft-graph)
- [GitHub Organization](https://github.com/OfficeDev/office-js)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph People API

API for accessing people data relevant to the user, aggregating information from contacts, social networks, organization directory, and recent communications.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/people-insights-overview](https://learn.microsoft.com/en-us/graph/people-insights-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Contacts
- Directory
- People
- Social

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/people-insights-overview)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Change Notifications API

API for subscribing to changes in Outlook resources including mail, calendar events, and contacts via webhooks, enabling real-time notifications.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview](https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Events
- Notifications
- Subscriptions
- Webhooks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview)
- [Getting Started](https://learn.microsoft.com/en-us/graph/change-notifications-delivery-webhooks)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/change-notifications-api-overview?view=graph-rest-1.0)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Focused Inbox API

API for managing Focused Inbox overrides and message classification, allowing applications to control how incoming messages are categorized between Focused and Other tabs.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Classification
- Email Organization
- Focused Inbox

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Mail Rules API

API for managing Outlook inbox rules that automatically process incoming messages based on conditions, enabling actions like moving messages to folders, assigning categories, and forwarding.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Email Automation
- Filters
- Inbox Rules
- Rules

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-organize-messages)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Categories API

API for managing Outlook categories, allowing applications to create, read, update, and delete categories in a user's master category list for organizing messages, events, and contacts.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Categories
- Labels
- Organization

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Postman Collection](collections/microsoft-graph-mail-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-graph-mail-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.microsoft.com/en-us/graph)
- [Getting Started](https://learn.microsoft.com/en-us/graph/overview)
- [Documentation](https://learn.microsoft.com/en-us/outlook/)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/tag/outlook/)
- [GitHub Organization](https://github.com/microsoftgraph)
- [Sign Up](https://developer.microsoft.com/en-us/microsoft-365/dev-program)
- [Login](https://portal.azure.com)
- [Terms of Service](https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://developer.microsoft.com/en-us/graph/support)
- [Status Page](https://status.cloud.microsoft/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-graph)
- [Quickstart](https://developer.microsoft.com/en-us/graph/quick-start)
- [Training](https://learn.microsoft.com/en-us/training/paths/m365-msgraph-fundamentals/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
