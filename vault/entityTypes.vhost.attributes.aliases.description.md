---
id: auto-178daf6bcac41638c
title: 'entityTypes.vhost.attributes.aliases.description'
desc: ''
updated: 1618581306540
created: 1618581306540
---
# entityTypes.vhost.attributes.aliases.description

Alternate hostnames that share this vhost configuration. Hosts named in this attribute are treated as if this vhost was defined with the alias name in the vhost &#39;hostname&#39; attribute. This attribute is implemented to help with multitenant configurations where multiple vhosts share a common configuration. The string is a comma- or space-separated list of literal hostnames or hostname patterns. A vhost aliases hostname must be unique across all vhost hostnames and all of their aliases.