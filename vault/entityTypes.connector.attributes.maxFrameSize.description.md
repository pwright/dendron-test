---
id: auto-178da80a69f44db1
title: 'entityTypes.connector.attributes.maxFrameSize.description'
desc: ''
updated: 1618573567647
created: 1618573567647
---
# entityTypes.connector.attributes.maxFrameSize.description

The maximum frame size in octets that will be used in the connection-open negotiation with a connected peer.  The frame size is the largest contiguous set of uninterrupted data that can be sent for a message delivery over the connection. Interleaving of messages on different links is done at frame granularity. Policy settings will not overwrite this value. Defaults to 16384.