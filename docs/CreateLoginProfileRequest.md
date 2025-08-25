

# CreateLoginProfileRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the IAM user to create a password for. The user must already exist.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**password** | **String** | &lt;p&gt;The new password for the user.&lt;/p&gt; &lt;p&gt;The &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt; that is used to validate this parameter is a string of characters. That string can include almost any printable ASCII character from the space (&lt;code&gt;\\u0020&lt;/code&gt;) through the end of the ASCII character range (&lt;code&gt;\\u00FF&lt;/code&gt;). You can also include the tab (&lt;code&gt;\\u0009&lt;/code&gt;), line feed (&lt;code&gt;\\u000A&lt;/code&gt;), and carriage return (&lt;code&gt;\\u000D&lt;/code&gt;) characters. Any of these characters are valid in a password. However, many tools, such as the Amazon Web Services Management Console, might restrict the ability to type certain characters because they have special meaning within that tool.&lt;/p&gt; |  |
|**passwordResetRequired** | **Boolean** | Specifies whether the user is required to set a new password on next sign-in. |  [optional] |



