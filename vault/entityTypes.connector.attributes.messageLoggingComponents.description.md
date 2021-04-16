---
id: auto-178daf5f925527f5a
title: 'entityTypes.connector.attributes.messageLoggingComponents.description'
desc: ''
updated: 1618581256485
created: 1618581256485
---
# entityTypes.connector.attributes.messageLoggingComponents.description

A comma separated list that indicates which components of the message should be logged (no spaces allowed between list components). Defaults to &#39;none&#39; (log nothing). If you want all properties and application properties of the message logged use &#39;all&#39;. Specific components of the message can be logged by indicating the components via a comma separated list. The components are message-id, user-id, to, subject, reply-to, correlation-id, content-type, content-encoding, absolute-expiry-time, creation-time, group-id, group-sequence, reply-to-group-id, app-properties. The application-data part of the bare message will not be logged. This log message is written to the MESSAGE logging module. In the &#39;log&#39; entity, set &#39;module&#39; property to MESSAGE or DEFAULT and &#39;enable&#39; to trace+ to see this log message