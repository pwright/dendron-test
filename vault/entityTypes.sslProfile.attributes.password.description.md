---
id: auto-178daf5c1e9600c18
title: 'entityTypes.sslProfile.attributes.password.description'
desc: ''
updated: 1618581242345
created: 1618581242345
---
# entityTypes.sslProfile.attributes.password.description

The password that unlocks the certificate key. You can specify the password by specifying an environment variable that stores the password, a file that stores the password, or by entering the password in clear text. To use an environment variable, specify &#39;password: env:&lt;var&gt;&#39;. Use this option with caution, because the environment of other processes is visible on certain platforms (for example, ps on certain Unix OSs). To use a file, specify &#39;password: file:&lt;absolute-path-to-file&gt;&#39;. This option is the most secure, because permissions can be set on the file that contains the password. To specify the password in clear text, specify &#39;password: pass:&lt;password&gt;&#39;, or &#39;password: literal:&lt;password&gt;&#39;, or &#39;password: &lt;password&gt;&#39;. This option is insecure, so it should only be used if security is not a concern. If both password and passwordFile are provided, the passwordFile is ignored.