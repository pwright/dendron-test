---
id: auto-178daf6d38d49d55a
title: 'entityTypes.vhostUserGroupSettings.attributes.sources.description'
desc: ''
updated: 1618581312397
created: 1618581312397
---
# entityTypes.vhostUserGroupSettings.attributes.sources.description

A list of source addresses from which users in this group may receive messages. To specify multiple addresses, separate the addresses with either a comma or a space. If you do not specify any addresses, users in this group are not allowed to receive messages from any addresses. You can use the substitution token &#39;&#39; to specify an address that contains a user&#39;s authenticated user name. You can use an asterisk (&#39;*&#39;) wildcard to match one or more characters in an address. However, this wildcard is only recognized if it is the last character in the address name. You may specify attributes &#39;sources&#39; or &#39;sourcePattern&#39; but not both at the same time.