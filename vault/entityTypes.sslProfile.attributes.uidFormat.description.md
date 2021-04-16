---
id: auto-178da80793d52edc1
title: 'entityTypes.sslProfile.attributes.uidFormat.description'
desc: ''
updated: 1618573556029
created: 1618573556029
---
# entityTypes.sslProfile.attributes.uidFormat.description

A list of x509 client certificate fields that will be used to build a string that will uniquely identify the client certificate owner. For e.g. a value of &#39;cou&#39; indicates that the uid will consist of c - common name concatenated with o - organization-company name concatenated with u - organization unit; or a value of &#39;o2&#39; indicates that the uid will consist of o (organization name) concatenated with 2 (the sha256 fingerprint of the entire certificate) . Allowed values can be any combination of &#39;c&#39;( ISO3166 two character country code)