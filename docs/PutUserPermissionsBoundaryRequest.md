

# PutUserPermissionsBoundaryRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name (friendly name, not ARN) of the IAM user for which you want to set the permissions boundary. |  |
|**permissionsBoundary** | **String** | &lt;p&gt;The ARN of the managed policy that is used to set the permissions boundary for the user.&lt;/p&gt; &lt;p&gt;A permissions boundary policy defines the maximum permissions that identity-based policies can grant to an entity, but does not grant permissions. Permissions boundaries do not define the maximum permissions that a resource-based policy can grant to an entity. To learn more, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM entities&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;For more information about policy types, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#access_policy-types\&quot;&gt;Policy types &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  |



