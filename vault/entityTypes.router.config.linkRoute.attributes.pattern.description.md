---
id: auto-178daf63789964164
title: 'entityTypes.router.config.linkRoute.attributes.pattern.description'
desc: ''
updated: 1618581272457
created: 1618581272457
---
# entityTypes.router.config.linkRoute.attributes.pattern.description

A wildcarded pattern for address matching. Link addresses are matched against this pattern. Matching addresses use the configured settings. The pattern consists of one or more tokens separated by a forward slash &#39;/&#39;. A token can be one of the following: a * character, a # character, or a sequence of characters that do not include /, *, or #.  The * token matches any single token.  The # token matches zero or more tokens. * has higher precedence than #, and exact match has the highest precedence. Cannot be used with the prefix attribute.