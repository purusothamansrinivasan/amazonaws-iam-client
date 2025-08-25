

# GetSAMLProviderResponse

Contains the response to a successful <a>GetSAMLProvider</a> request. 

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**saMLMetadataDocument** | **String** | The XML metadata document that includes information about an identity provider. |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time when the SAML provider was created. |  [optional] |
|**validUntil** | **OffsetDateTime** | The expiration date and time for the SAML provider. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the specified IAM SAML provider. The returned list of tags is sorted by tag key. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



