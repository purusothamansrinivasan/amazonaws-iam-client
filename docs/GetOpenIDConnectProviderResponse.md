

# GetOpenIDConnectProviderResponse

Contains the response to a successful <a>GetOpenIDConnectProvider</a> request. 

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**url** | **String** | The URL that the IAM OIDC provider resource object is associated with. For more information, see &lt;a&gt;CreateOpenIDConnectProvider&lt;/a&gt;. |  [optional] |
|**clientIDList** | **List&lt;String&gt;** | A list of client IDs (also known as audiences) that are associated with the specified IAM OIDC provider resource object. For more information, see &lt;a&gt;CreateOpenIDConnectProvider&lt;/a&gt;. |  [optional] |
|**thumbprintList** | **List&lt;String&gt;** | A list of certificate thumbprints that are associated with the specified IAM OIDC provider resource object. For more information, see &lt;a&gt;CreateOpenIDConnectProvider&lt;/a&gt;.  |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time when the IAM OIDC provider resource object was created in the Amazon Web Services account. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the specified IAM OIDC provider. The returned list of tags is sorted by tag key. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



