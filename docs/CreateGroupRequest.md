

# CreateGroupRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** | &lt;p&gt; The path to the group. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;This parameter is optional. If it is not included, it defaults to a slash (/).&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of either a forward slash (/) by itself or a string that must begin and end with forward slashes. In addition, it can contain any ASCII character from the ! (&lt;code&gt;\\u0021&lt;/code&gt;) through the DEL character (&lt;code&gt;\\u007F&lt;/code&gt;), including most punctuation characters, digits, and upper and lowercased letters.&lt;/p&gt; |  [optional] |
|**groupName** | **String** | &lt;p&gt;The name of the group to create. Do not include the path in this value.&lt;/p&gt; &lt;p&gt;IAM user, group, role, and policy names must be unique within the account. Names are not distinguished by case. For example, you cannot create resources named both \&quot;MyResource\&quot; and \&quot;myresource\&quot;.&lt;/p&gt; |  |



