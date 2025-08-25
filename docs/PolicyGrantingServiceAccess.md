

# PolicyGrantingServiceAccess

<p>Contains details about the permissions policies that are attached to the specified identity (user, group, or role).</p> <p>This data type is an element of the <a>ListPoliciesGrantingServiceAccessEntry</a> object.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**policyName** | **String** | The policy name. |  |
|**policyType** | **PolicyType** | The policy type. For more information about these policy types, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html\&quot;&gt;Managed policies and inline policies&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  |
|**policyArn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN). ARNs are unique identifiers for Amazon Web Services resources.&lt;/p&gt; &lt;p&gt;For more information about ARNs, go to &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**entityType** | **PolicyOwnerEntityType** | &lt;p&gt;The type of entity (user or role) that used the policy to access the service to which the inline policy is attached.&lt;/p&gt; &lt;p&gt;This field is null for managed policies. For more information about these policy types, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html\&quot;&gt;Managed policies and inline policies&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**entityName** | **String** | &lt;p&gt;The name of the entity (user or role) to which the inline policy is attached.&lt;/p&gt; &lt;p&gt;This field is null for managed policies. For more information about these policy types, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html\&quot;&gt;Managed policies and inline policies&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |



