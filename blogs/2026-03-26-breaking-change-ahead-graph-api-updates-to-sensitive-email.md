---
title: "Breaking Change Ahead: Graph API Updates to Sensitive Email Properties"
url: "https://devblogs.microsoft.com/microsoft365dev/graph-api-updates-to-sensitive-email-properties/"
date: "2026-03-26"
author: "Thomas Mechelke"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/tag/outlook/feed/"
---
We’re implementing a significant update in our service affecting applications that modify sensitive email properties on non-draft email messages. These sensitive email properties include the subject, body, recipients, and a number of other properties when changed using any of the message update methods on Graph API. Immutability of received email messages There’s a fundamental expectation that once you receive an email message, it should remain unchanged except for specific management-related properties such as read status, flags, and similar attributes.
