

# CreateUserRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** | &lt;p&gt; The path for the user name. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;This parameter is optional. If it is not included, it defaults to a slash (/).&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of either a forward slash (/) by itself or a string that must begin and end with forward slashes. In addition, it can contain any ASCII character from the ! (&lt;code&gt;\\u0021&lt;/code&gt;) through the DEL character (&lt;code&gt;\\u007F&lt;/code&gt;), including most punctuation characters, digits, and upper and lowercased letters.&lt;/p&gt; |  [optional] |
|**userName** | **String** | &lt;p&gt;The name of the user to create.&lt;/p&gt; &lt;p&gt;IAM user, group, role, and policy names must be unique within the account. Names are not distinguished by case. For example, you cannot create resources named both \&quot;MyResource\&quot; and \&quot;myresource\&quot;.&lt;/p&gt; |  |
|**permissionsBoundary** | **String** | &lt;p&gt;The ARN of the managed policy that is used to set the permissions boundary for the user.&lt;/p&gt; &lt;p&gt;A permissions boundary policy defines the maximum permissions that identity-based policies can grant to an entity, but does not grant permissions. Permissions boundaries do not define the maximum permissions that a resource-based policy can grant to an entity. To learn more, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM entities&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;For more information about policy types, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#access_policy-types\&quot;&gt;Policy types &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | &lt;p&gt;A list of tags that you want to attach to the new user. Each tag consists of a key name and an associated value. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; &lt;note&gt; &lt;p&gt;If any one of the tags is invalid or if you exceed the allowed maximum number of tags, then the entire request fails and the resource is not created.&lt;/p&gt; &lt;/note&gt; |  [optional] |



