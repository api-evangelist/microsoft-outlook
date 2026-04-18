# Microsoft Outlook (microsoft-outlook)
Microsoft Outlook is a personal information manager and email client that is part of the Microsoft Office suite. It provides email, calendar, contact management, task management, and other productivity features.

**URL:** [Visit APIs.json URL](https://outlook.office.com)

## Tags

 - Calendar, Contacts, Email, Enterprise, Microsoft, Office 365, Productivity

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Microsoft Graph Mail API
API for accessing Outlook email messages, folders, and mail settings through Microsoft Graph.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0)

#### Tags

 - Email, Folders, Mail, Messages

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-graph-mail-api-openapi.yml)
- [JSON Schema](json-schema/microsoft-outlook-message-schema.json)
- [JSON-LD](json-ld/microsoft-outlook-context.jsonld)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-mail-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Change Log](https://developer.microsoft.com/en-us/graph/changelog)

### Microsoft Graph Calendar API
API for accessing Outlook calendar events, calendars, and meeting scheduling through Microsoft Graph.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0)

#### Tags

 - Calendar, Events, Meetings, Scheduling

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Code Examples](https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0#code-samples)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-calendar-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/calendar-overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Change Log](https://developer.microsoft.com/en-us/graph/changelog)

### Microsoft Graph Contacts API
API for accessing Outlook contacts and contact folders through Microsoft Graph.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0)

#### Tags

 - Address Book, Contacts, People

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Getting Started](https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Change Log](https://developer.microsoft.com/en-us/graph/changelog)

### Microsoft Graph Tasks API
API for accessing Outlook tasks and to-do items through Microsoft Graph.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0)

#### Tags

 - Task Management, Tasks, To-Do

### Outlook Add-ins API
JavaScript API for building Outlook add-ins that extend Outlook functionality with custom features.

**Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/)

#### Tags

 - Add-Ins, Extensions, Office.js, Plugins

### Microsoft Graph People API
API for accessing people data relevant to the user, aggregating information from contacts, social networks, organization directory, and recent communications.

**Human URL:** [https://learn.microsoft.com/en-us/graph/people-insights-overview](https://learn.microsoft.com/en-us/graph/people-insights-overview)

#### Tags

 - Contacts, Directory, People, Social

### Microsoft Graph Change Notifications API
API for subscribing to changes in Outlook resources including mail, calendar events, and contacts via webhooks.

**Human URL:** [https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview](https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview)

#### Tags

 - Events, Notifications, Subscriptions, Webhooks

### Microsoft Graph Focused Inbox API
API for managing Focused Inbox overrides and message classification.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0)

#### Tags

 - Classification, Email Organization, Focused Inbox

### Microsoft Graph Mail Rules API
API for managing Outlook inbox rules that automatically process incoming messages based on conditions.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0)

#### Tags

 - Email Automation, Filters, Inbox Rules, Rules

### Microsoft Graph Categories API
API for managing Outlook categories for organizing messages, events, and contacts.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0)

#### Tags

 - Categories, Labels, Organization

## Capabilities

### Workflow Capabilities

| Capability | Description | File |
|---|---|---|
| Email Productivity | Unified capability for Microsoft Outlook email productivity combining mail operations, folder management, and attachment handling via Microsoft Graph. | [email-productivity.yaml](capabilities/email-productivity.yaml) |

### Shared Definitions

| API | File |
|---|---|
| Microsoft Graph Mail API | [graph-mail.yaml](capabilities/shared/graph-mail.yaml) |

## Common Properties

- [Portal](https://developer.microsoft.com/en-us/graph)
- [Getting Started](https://learn.microsoft.com/en-us/graph/overview)
- [Documentation](https://learn.microsoft.com/en-us/outlook/)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [SDK](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Change Log](https://developer.microsoft.com/en-us/graph/changelog)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/tag/outlook/)
- [GitHub Organization](https://github.com/microsoftgraph)
- [Sign Up](https://developer.microsoft.com/en-us/microsoft-365/dev-program)
- [Login](https://portal.azure.com)
- [Terms of Service](https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://developer.microsoft.com/en-us/graph/support)
- [Status](https://status.cloud.microsoft/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-graph)
- [Training](https://learn.microsoft.com/en-us/training/paths/m365-msgraph-fundamentals/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
