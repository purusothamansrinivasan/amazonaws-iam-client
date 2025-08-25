

# RemoveClientIDFromOpenIDConnectProviderRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**openIDConnectProviderArn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN) of the IAM OIDC provider resource to remove the client ID from. You can get a list of OIDC provider ARNs by using the &lt;a&gt;ListOpenIDConnectProviders&lt;/a&gt; operation.&lt;/p&gt; &lt;p&gt;For more information about ARNs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  |
|**clientID** | **String** | The client ID (also known as audience) to remove from the IAM OIDC provider resource. For more information about client IDs, see &lt;a&gt;CreateOpenIDConnectProvider&lt;/a&gt;. |  |



