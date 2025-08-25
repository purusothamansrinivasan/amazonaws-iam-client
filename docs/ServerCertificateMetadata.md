

# ServerCertificateMetadata

<p>Contains information about a server certificate without its certificate body, certificate chain, and private key.</p> <p> This data type is used as a response element in the <a>UploadServerCertificate</a> and <a>ListServerCertificates</a> operations. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** |  The path to the server certificate. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.  |  |
|**serverCertificateName** | **String** | The name that identifies the server certificate. |  |
|**serverCertificateId** | **String** |  The stable and unique string identifying the server certificate. For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.  |  |
|**arn** | **String** |  The Amazon Resource Name (ARN) specifying the server certificate. For more information about ARNs and how to use them in policies, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.  |  |
|**uploadDate** | **OffsetDateTime** | The date when the server certificate was uploaded. |  [optional] |
|**expiration** | **OffsetDateTime** | The date on which the certificate is set to expire. |  [optional] |



