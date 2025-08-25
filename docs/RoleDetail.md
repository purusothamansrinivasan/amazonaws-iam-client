

# RoleDetail

<p>Contains information about an IAM role, including all of the role's policies.</p> <p>This data type is used as a response element in the <a>GetAccountAuthorizationDetails</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** | The path to the role. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**roleName** | **String** | The friendly name that identifies the role. |  [optional] |
|**roleId** | **String** | The stable and unique string identifying the role. For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**arn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN). ARNs are unique identifiers for Amazon Web Services resources.&lt;/p&gt; &lt;p&gt;For more information about ARNs, go to &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the role was created. |  [optional] |
|**assumeRolePolicyDocument** | **String** | The trust policy that grants permission to assume the role. |  [optional] |
|**instanceProfileList** | [**List&lt;InstanceProfile&gt;**](InstanceProfile.md) | A list of instance profiles that contain this role. |  [optional] |
|**rolePolicyList** | [**List&lt;PolicyDetail&gt;**](PolicyDetail.md) | A list of inline policies embedded in the role. These policies are the role&#39;s access (permissions) policies. |  [optional] |
|**attachedManagedPolicies** | [**List&lt;AttachedPolicy&gt;**](AttachedPolicy.md) | A list of managed policies attached to the role. These policies are the role&#39;s access (permissions) policies. |  [optional] |
|**permissionsBoundary** | [**AttachedPermissionsBoundary**](AttachedPermissionsBoundary.md) | &lt;p&gt;The ARN of the policy used to set the permissions boundary for the role.&lt;/p&gt; &lt;p&gt;For more information about permissions boundaries, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM identities &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the role. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**roleLastUsed** | [**RoleLastUsed**](RoleLastUsed.md) | Contains information about the last time that an IAM role was used. This includes the date and time and the Region in which the role was last used. Activity is only reported for the trailing 400 days. This period can be shorter if your Region began supporting these features within the last year. The role might have been used more than 400 days ago. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#access-advisor_tracking-period\&quot;&gt;Regions where data is tracked&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



