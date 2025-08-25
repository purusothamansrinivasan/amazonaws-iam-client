

# UpdateSigningCertificateRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the IAM user the signing certificate belongs to.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  [optional] |
|**certificateId** | **String** | &lt;p&gt;The ID of the signing certificate you want to update.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters that can consist of any upper or lowercased letter or digit.&lt;/p&gt; |  |
|**status** | **StatusType** |  The status you want to assign to the certificate. &lt;code&gt;Active&lt;/code&gt; means that the certificate can be used for programmatic calls to Amazon Web Services &lt;code&gt;Inactive&lt;/code&gt; means that the certificate cannot be used. |  |



