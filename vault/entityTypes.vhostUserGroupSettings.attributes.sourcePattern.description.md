---
id: auto-178daf6d53d28c7b9
title: 'entityTypes.vhostUserGroupSettings.attributes.sourcePattern.description'
desc: ''
updated: 1618581312829
created: 1618581312829
---
# entityTypes.vhostUserGroupSettings.attributes.sourcePattern.description

A wildcarded pattern for matching source addresses from which users in this group may receive messages. The pattern consists of one or more tokens separated by a forward slash &#39;/&#39;. A token can be one of the following: a * character, a # character, or a sequence of characters that do not include /, *, or #.  The * token matches any single token.  The # token matches zero or more tokens. * has higher precedence than #, and exact match has the highest precedence. To specify multiple addresses, separate the addresses with either a comma or a space. You can use the text string &#39;&#39; in a token to specify an address that contains a user&#39;s authenticated user name. If you do not specify any addresses, users in this group are not allowed to receive messages from any addresses. You may specify attributes &#39;sources&#39; or &#39;sourcePattern&#39; but not both at the same time.