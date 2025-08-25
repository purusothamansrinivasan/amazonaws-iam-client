

# GetSSHPublicKeyRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the IAM user associated with the SSH public key.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**ssHPublicKeyId** | **String** | &lt;p&gt;The unique identifier for the SSH public key.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters that can consist of any upper or lowercased letter or digit.&lt;/p&gt; |  |
|**encoding** | **EncodingType** | Specifies the public key encoding format to use in the response. To retrieve the public key in ssh-rsa format, use &lt;code&gt;SSH&lt;/code&gt;. To retrieve the public key in PEM format, use &lt;code&gt;PEM&lt;/code&gt;. |  |



