

# UpdateUserRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;Name of the user to update. If you&#39;re changing the name of the user, this is the original user name.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**newPath** | **String** | &lt;p&gt;New path for the IAM user. Include this parameter only if you&#39;re changing the user&#39;s path.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of either a forward slash (/) by itself or a string that must begin and end with forward slashes. In addition, it can contain any ASCII character from the ! (&lt;code&gt;\\u0021&lt;/code&gt;) through the DEL character (&lt;code&gt;\\u007F&lt;/code&gt;), including most punctuation characters, digits, and upper and lowercased letters.&lt;/p&gt; |  [optional] |
|**newUserName** | **String** | &lt;p&gt;New name for the user. Include this parameter only if you&#39;re changing the user&#39;s name.&lt;/p&gt; &lt;p&gt;IAM user, group, role, and policy names must be unique within the account. Names are not distinguished by case. For example, you cannot create resources named both \&quot;MyResource\&quot; and \&quot;myresource\&quot;.&lt;/p&gt; |  [optional] |



