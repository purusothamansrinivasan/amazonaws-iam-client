

# UploadServerCertificateResponse

Contains the response to a successful <a>UploadServerCertificate</a> request. 

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serverCertificateMetadata** | [**ServerCertificateMetadata**](ServerCertificateMetadata.md) | The meta information of the uploaded server certificate without its certificate body, certificate chain, and private key. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the new IAM server certificate. The returned list of tags is sorted by tag key. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



