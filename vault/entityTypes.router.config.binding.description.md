---
id: auto-178da8106e2f0a7e
title: 'entityTypes.router.config.binding.description'
desc: ''
updated: 1618573592290
created: 1618573592290
---
# entityTypes.router.config.binding.description

[EXPERIMENTAL] Defines a keyed next hop binding for a topic exchange. The subject field of the messages arriving at the exchange is compared against the binding&#39;s key value using the exchange&#39;s matchMethod.  If the subject matches the key the message is forwarded to the nextHopAddress. The nextHopAddress overrides the message&#39;s original destination.