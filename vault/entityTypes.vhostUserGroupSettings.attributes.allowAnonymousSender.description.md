---
id: auto-178daf6ce15764217
title: 'entityTypes.vhostUserGroupSettings.attributes.allowAnonymousSender.description'
desc: ''
updated: 1618581310997
created: 1618581310997
---
# entityTypes.vhostUserGroupSettings.attributes.allowAnonymousSender.description

Whether this connection is allowed to create sending links if the sender does not provide a target address. By prohibiting anonymous senders, the router only needs to verify once, when the link is created, that the sender is permitted to send messages to the target address. The router does not need to verify each message that is sent on the link. A value of &#39;true&#39; means that users may send messages to any address. Allowing anonymous senders can also decrease performance: if the sender does not specify a target address, then the router must parse each message to determine how to route it.