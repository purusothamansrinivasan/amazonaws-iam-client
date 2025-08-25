

# UpdateServerCertificateRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serverCertificateName** | **String** | &lt;p&gt;The name of the server certificate that you want to update.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**newPath** | **String** | &lt;p&gt;The new path for the server certificate. Include this only if you are updating the server certificate&#39;s path.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of either a forward slash (/) by itself or a string that must begin and end with forward slashes. In addition, it can contain any ASCII character from the ! (&lt;code&gt;\\u0021&lt;/code&gt;) through the DEL character (&lt;code&gt;\\u007F&lt;/code&gt;), including most punctuation characters, digits, and upper and lowercased letters.&lt;/p&gt; |  [optional] |
|**newServerCertificateName** | **String** | &lt;p&gt;The new name for the server certificate. Include this only if you are updating the server certificate&#39;s name. The name of the certificate cannot contain any spaces.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  [optional] |



