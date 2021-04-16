---
id: auto-178da80b0de4d69e5
title: 'entityTypes.connector.attributes.policyVhost.description'
desc: ''
updated: 1618573570270
created: 1618573570270
---
# entityTypes.connector.attributes.policyVhost.description

A connector may optionally define a policy to restrict the remote container to access only specific resources. This attribute defines the name of the policy vhost for this connector. Within the vhost the connector will use the vhost policy settings from user group &#39;&#39;. If the vhost policy is absent or if the user group &#39;&#39; within that policy is absent then the connector will fail to start.  In policy specified via connector attribute &#39;policyVhost&#39; the following vhostUserGroupSettings attributes are unused:  &#39;users&#39;