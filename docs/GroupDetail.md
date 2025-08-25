

# GroupDetail

<p>Contains information about an IAM group, including all of the group's policies.</p> <p>This data type is used as a response element in the <a>GetAccountAuthorizationDetails</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** | The path to the group. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**groupName** | **String** | The friendly name that identifies the group. |  [optional] |
|**groupId** | **String** | The stable and unique string identifying the group. For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**arn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN). ARNs are unique identifiers for Amazon Web Services resources.&lt;/p&gt; &lt;p&gt;For more information about ARNs, go to &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the group was created. |  [optional] |
|**groupPolicyList** | [**List&lt;PolicyDetail&gt;**](PolicyDetail.md) | A list of the inline policies embedded in the group. |  [optional] |
|**attachedManagedPolicies** | [**List&lt;AttachedPolicy&gt;**](AttachedPolicy.md) | A list of the managed policies attached to the group. |  [optional] |



