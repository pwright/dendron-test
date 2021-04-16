---
id: auto-178daf5f836f2f17
title: 'entityTypes.connector.attributes.saslPassword.description'
desc: ''
updated: 1618581256246
created: 1618581256246
---
# entityTypes.connector.attributes.saslPassword.description

The password that the connector is using to connect to a peer. You can specify the password by specifying an environment variable that stores the password, a file that stores the password, or by entering the password in clear text. To use an environment variable, specify &#39;saslPassword: env:&lt;var&gt;&#39;. Use this option with caution, because the environment of other processes is visible on certain platforms (for example, ps on certain Unix OSs). To use a file, specify &#39;saslPassword: file:&lt;absolute-path-to-file&gt;&#39;. This option is the most secure, because permissions can be set on the file that contains the password. To specify the password in clear text, specify &#39;saslPassword: pass:&lt;password&gt;&#39; or &#39;saslPassword: &lt;password&gt;&#39;. This option is insecure, so it should only be used if security is not a concern.