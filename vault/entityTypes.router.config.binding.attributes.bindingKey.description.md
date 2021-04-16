---
id: auto-178da8108b3ee08d
title: 'entityTypes.router.config.binding.attributes.bindingKey.description'
desc: ''
updated: 1618573592756
created: 1618573592756
---
# entityTypes.router.config.binding.attributes.bindingKey.description

Pattern to compare against incoming message&#39;s subject.  The key is a string of zero or more tokens and wildcards. The format depends on the matchMethod configured for the exchange. For AMQP each token is delimited by the &#39;.&#39; character and wild-card tokens &#39;*&#39; matches a single token and &#39;#&#39; matches zero or more tokens. For MQTT each token is delimited by the &#39;/&#39; character and wildcard tokens &#39;+&#39; matches a single token and &#39;#&#39; matches zero or more tokens at the end of the topic. If a key is not provided the binding will match all messages arriving at the exchange (fanout behavior).