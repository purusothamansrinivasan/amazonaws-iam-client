

# UserDetail

<p>Contains information about an IAM user, including all the user's policies and all the IAM groups the user is in.</p> <p>This data type is used as a response element in the <a>GetAccountAuthorizationDetails</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** | The path to the user. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**userName** | **String** | The friendly name identifying the user. |  [optional] |
|**userId** | **String** | The stable and unique string identifying the user. For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**arn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN). ARNs are unique identifiers for Amazon Web Services resources.&lt;/p&gt; &lt;p&gt;For more information about ARNs, go to &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the user was created. |  [optional] |
|**userPolicyList** | [**List&lt;PolicyDetail&gt;**](PolicyDetail.md) | A list of the inline policies embedded in the user. |  [optional] |
|**groupList** | **List&lt;String&gt;** | A list of IAM groups that the user is in. |  [optional] |
|**attachedManagedPolicies** | [**List&lt;AttachedPolicy&gt;**](AttachedPolicy.md) | A list of the managed policies attached to the user. |  [optional] |
|**permissionsBoundary** | [**AttachedPermissionsBoundary**](AttachedPermissionsBoundary.md) | &lt;p&gt;The ARN of the policy used to set the permissions boundary for the user.&lt;/p&gt; &lt;p&gt;For more information about permissions boundaries, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM identities &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are associated with the user. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



