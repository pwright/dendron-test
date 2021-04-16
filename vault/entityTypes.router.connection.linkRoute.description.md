---
id: auto-178daf6ddb5421639
title: 'entityTypes.router.connection.linkRoute.description'
desc: ''
updated: 1618581314997
created: 1618581314997
---
# entityTypes.router.connection.linkRoute.description

[EXPERIMENTAL] A linkRoute that is scoped to the connection that created it. Connection linkRoutes only exist within the context of a connection and when the connection is closed, they vanish. This differs from configured linkRoutes (router.config.linkRoute) which remain configured should their associated connection restart. Connection linkRoutes may be used by a client to create link-routed message flows that are automatically removed when the client disconnects.  Note well that connection.linkRoute cannot be declared in a configuration file - they must be created at run time via management operations over the connection which they are to be used. Connection linkRoutes are only visible to management access that is via the containing connection.