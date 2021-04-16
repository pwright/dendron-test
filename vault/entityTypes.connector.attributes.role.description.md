---
id: auto-178daf5ea231b03f4
title: 'entityTypes.connector.attributes.role.description'
desc: ''
updated: 1618581252643
created: 1618581252643
---
# entityTypes.connector.attributes.role.description

The role of an established connection. In the normal role, the connection is assumed to be used for AMQP clients that are doing normal message delivery over the connection.  In the inter-router role, the connection is assumed to be to another router in the network.  Inter-router discovery and routing protocols can only be used over inter-router connections. route-container role can be used for router-container connections, for example, a router-broker connection.  In the edge role, the connection is assumed to be between and edge router and an interior router.