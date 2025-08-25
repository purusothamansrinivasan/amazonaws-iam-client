

# Role

Contains information about an IAM role. This structure is returned as a response element in several API operations that interact with roles.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** |  The path to the role. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.  |  |
|**roleName** | **String** | The friendly name that identifies the role. |  |
|**roleId** | **String** |  The stable and unique string identifying the role. For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.  |  |
|**arn** | **String** |  The Amazon Resource Name (ARN) specifying the role. For more information about ARNs and how to use them in policies, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt; guide.  |  |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the role was created. |  |
|**assumeRolePolicyDocument** | **String** | The policy that grants an entity permission to assume the role. |  [optional] |
|**description** | **String** | A description of the role that you provide. |  [optional] |
|**maxSessionDuration** | **Integer** | The maximum session duration (in seconds) for the specified role. Anyone who uses the CLI, or API to assume the role can specify the duration using the optional &lt;code&gt;DurationSeconds&lt;/code&gt; API parameter or &lt;code&gt;duration-seconds&lt;/code&gt; CLI parameter. |  [optional] |
|**permissionsBoundary** | [**AttachedPermissionsBoundary**](AttachedPermissionsBoundary.md) | &lt;p&gt;The ARN of the policy used to set the permissions boundary for the role.&lt;/p&gt; &lt;p&gt;For more information about permissions boundaries, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM identities &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the role. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**roleLastUsed** | [**RoleLastUsed**](RoleLastUsed.md) | Contains information about the last time that an IAM role was used. This includes the date and time and the Region in which the role was last used. Activity is only reported for the trailing 400 days. This period can be shorter if your Region began supporting these features within the last year. The role might have been used more than 400 days ago. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#access-advisor_tracking-period\&quot;&gt;Regions where data is tracked&lt;/a&gt; in the &lt;i&gt;IAM user Guide&lt;/i&gt;. |  [optional] |



