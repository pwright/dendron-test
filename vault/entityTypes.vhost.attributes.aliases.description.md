---
id: auto-178da8172486c4ff0
title: 'entityTypes.vhost.attributes.aliases.description'
desc: ''
updated: 1618573619784
created: 1618573619784
---
# entityTypes.vhost.attributes.aliases.description

Alternate hostnames that share this vhost configuration. Hosts named in this attribute are treated as if this vhost was defined with the alias name in the vhost &#39;hostname&#39; attribute. This attribute is implemented to help with multitenant configurations where multiple vhosts share a common configuration. The string is a comma- or space-separated list of literal hostnames or hostname patterns. A vhost aliases hostname must be unique across all vhost hostnames and all of their aliases.