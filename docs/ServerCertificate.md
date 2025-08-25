

# ServerCertificate

<p>Contains information about a server certificate.</p> <p> This data type is used as a response element in the <a>GetServerCertificate</a> operation. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serverCertificateMetadata** | [**ServerCertificateMetadata**](ServerCertificateMetadata.md) | The meta information of the server certificate, such as its name, path, ID, and ARN. |  |
|**certificateBody** | **String** | The contents of the public key certificate. |  |
|**certificateChain** | **String** | The contents of the public key certificate chain. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the server certificate. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



