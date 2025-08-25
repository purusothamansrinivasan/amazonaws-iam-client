

# ManagedPolicyDetail

<p>Contains information about a managed policy, including the policy's ARN, versions, and the number of principal entities (users, groups, and roles) that the policy is attached to.</p> <p>This data type is used as a response element in the <a>GetAccountAuthorizationDetails</a> operation.</p> <p>For more information about managed policies, see <a href=\"https://docs.aws.amazon.com/IAM/latest/UserGuide/policies-managed-vs-inline.html\">Managed policies and inline policies</a> in the <i>IAM User Guide</i>. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**policyName** | **String** | The friendly name (not ARN) identifying the policy. |  [optional] |
|**policyId** | **String** | &lt;p&gt;The stable and unique string identifying the policy.&lt;/p&gt; &lt;p&gt;For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**arn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN). ARNs are unique identifiers for Amazon Web Services resources.&lt;/p&gt; &lt;p&gt;For more information about ARNs, go to &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**path** | **String** | &lt;p&gt;The path to the policy.&lt;/p&gt; &lt;p&gt;For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**defaultVersionId** | **String** | &lt;p&gt;The identifier for the version of the policy that is set as the default (operative) version.&lt;/p&gt; &lt;p&gt;For more information about policy versions, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/policies-managed-versions.html\&quot;&gt;Versioning for managed policies&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**attachmentCount** | **Integer** | The number of principal entities (users, groups, and roles) that the policy is attached to. |  [optional] |
|**permissionsBoundaryUsageCount** | **Integer** | &lt;p&gt;The number of entities (users and roles) for which the policy is used as the permissions boundary. &lt;/p&gt; &lt;p&gt;For more information about permissions boundaries, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM identities &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**isAttachable** | **Boolean** | Specifies whether the policy can be attached to an IAM user, group, or role. |  [optional] |
|**description** | **String** | A friendly description of the policy. |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the policy was created. |  [optional] |
|**updateDate** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the policy was last updated.&lt;/p&gt; &lt;p&gt;When a policy has only one version, this field contains the date and time when the policy was created. When a policy has more than one version, this field contains the date and time when the most recent policy version was created.&lt;/p&gt; |  [optional] |
|**policyVersionList** | [**List&lt;PolicyVersion&gt;**](PolicyVersion.md) | A list containing information about the versions of the policy. |  [optional] |



