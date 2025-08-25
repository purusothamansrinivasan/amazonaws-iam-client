

# UploadSigningCertificateRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the user the signing certificate is for.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  [optional] |
|**certificateBody** | **String** | &lt;p&gt;The contents of the signing certificate.&lt;/p&gt; &lt;p&gt;The &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt; used to validate this parameter is a string of characters consisting of the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Any printable ASCII character ranging from the space character (&lt;code&gt;\\u0020&lt;/code&gt;) through the end of the ASCII character range&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;The printable characters in the Basic Latin and Latin-1 Supplement character set (through &lt;code&gt;\\u00FF&lt;/code&gt;)&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;The special characters tab (&lt;code&gt;\\u0009&lt;/code&gt;), line feed (&lt;code&gt;\\u000A&lt;/code&gt;), and carriage return (&lt;code&gt;\\u000D&lt;/code&gt;)&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |



