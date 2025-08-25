

# CreatePolicyVersionRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**policyArn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN) of the IAM policy to which you want to add a new version.&lt;/p&gt; &lt;p&gt;For more information about ARNs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  |
|**policyDocument** | **String** | &lt;p&gt;The JSON policy document that you want to use as the content for this new version of the policy.&lt;/p&gt; &lt;p&gt;You must provide policies in JSON format in IAM. However, for CloudFormation templates formatted in YAML, you can provide the policy in JSON or YAML format. CloudFormation always converts a YAML policy to JSON format before submitting it to IAM.&lt;/p&gt; &lt;p&gt;The maximum length of the policy document that you can pass in this operation, including whitespace, is listed below. To view the maximum character counts of a managed policy with no whitespaces, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_iam-quotas.html#reference_iam-quotas-entity-length\&quot;&gt;IAM and STS character quotas&lt;/a&gt;.&lt;/p&gt; &lt;p&gt;The &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt; used to validate this parameter is a string of characters consisting of the following:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;Any printable ASCII character ranging from the space character (&lt;code&gt;\\u0020&lt;/code&gt;) through the end of the ASCII character range&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;The printable characters in the Basic Latin and Latin-1 Supplement character set (through &lt;code&gt;\\u00FF&lt;/code&gt;)&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;The special characters tab (&lt;code&gt;\\u0009&lt;/code&gt;), line feed (&lt;code&gt;\\u000A&lt;/code&gt;), and carriage return (&lt;code&gt;\\u000D&lt;/code&gt;)&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**setAsDefault** | **Boolean** | &lt;p&gt;Specifies whether to set this version as the policy&#39;s default version.&lt;/p&gt; &lt;p&gt;When this parameter is &lt;code&gt;true&lt;/code&gt;, the new policy version becomes the operative version. That is, it becomes the version that is in effect for the IAM users, groups, and roles that the policy is attached to.&lt;/p&gt; &lt;p&gt;For more information about managed policy versions, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/policies-managed-versions.html\&quot;&gt;Versioning for managed policies&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |



