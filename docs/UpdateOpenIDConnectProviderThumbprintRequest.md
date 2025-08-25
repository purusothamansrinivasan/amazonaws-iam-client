

# UpdateOpenIDConnectProviderThumbprintRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**openIDConnectProviderArn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN) of the IAM OIDC provider resource object for which you want to update the thumbprint. You can get a list of OIDC provider ARNs by using the &lt;a&gt;ListOpenIDConnectProviders&lt;/a&gt; operation.&lt;/p&gt; &lt;p&gt;For more information about ARNs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  |
|**thumbprintList** | **List&lt;String&gt;** | A list of certificate thumbprints that are associated with the specified IAM OpenID Connect provider. For more information, see &lt;a&gt;CreateOpenIDConnectProvider&lt;/a&gt;.  |  |



