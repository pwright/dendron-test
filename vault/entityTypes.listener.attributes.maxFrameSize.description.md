---
id: auto-178daf5d6e02f9e8c
title: 'entityTypes.listener.attributes.maxFrameSize.description'
desc: ''
updated: 1618581247712
created: 1618581247712
---
# entityTypes.listener.attributes.maxFrameSize.description

The maximum frame size in octets that will be used in the connection-open negotiation with a connected peer.  The frame size is the largest contiguous set of uninterrupted data that can be sent for a message delivery over the connection. Interleaving of messages on different links is done at frame granularity. Policy settings, if specified, will overwrite this value. Defaults to 16384.