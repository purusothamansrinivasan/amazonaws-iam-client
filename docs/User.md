

# User

<p>Contains information about an IAM user entity.</p> <p>This data type is used as a response element in the following operations:</p> <ul> <li> <p> <a>CreateUser</a> </p> </li> <li> <p> <a>GetUser</a> </p> </li> <li> <p> <a>ListUsers</a> </p> </li> </ul>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**path** | **String** | &lt;p&gt;The path to the user. For more information about paths, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; &lt;p&gt;The ARN of the policy used to set the permissions boundary for the user.&lt;/p&gt; |  |
|**userName** | **String** | The friendly name identifying the user. |  |
|**userId** | **String** | The stable and unique string identifying the user. For more information about IDs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  |
|**arn** | **String** | The Amazon Resource Name (ARN) that identifies the user. For more information about ARNs and how to use ARNs in policies, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/Using_Identifiers.html\&quot;&gt;IAM Identifiers&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.  |  |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the user was created. |  |
|**passwordLastUsed** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the user&#39;s password was last used to sign in to an Amazon Web Services website. For a list of Amazon Web Services websites that capture a user&#39;s last sign-in time, see the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/credential-reports.html\&quot;&gt;Credential reports&lt;/a&gt; topic in the &lt;i&gt;IAM User Guide&lt;/i&gt;. If a password is used more than once in a five-minute span, only the first use is returned in this field. If the field is null (no value), then it indicates that they never signed in with a password. This can be because:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;The user never had a password.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;A password exists but has not been used since IAM started tracking this information on October 20, 2014.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;A null value does not mean that the user &lt;i&gt;never&lt;/i&gt; had a password. Also, if the user does not currently have a password but had one in the past, then this field contains the date and time the most recent password was used.&lt;/p&gt; &lt;p&gt;This value is returned only in the &lt;a&gt;GetUser&lt;/a&gt; and &lt;a&gt;ListUsers&lt;/a&gt; operations. &lt;/p&gt; |  [optional] |
|**permissionsBoundary** | [**AttachedPermissionsBoundary**](AttachedPermissionsBoundary.md) | For more information about permissions boundaries, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html\&quot;&gt;Permissions boundaries for IAM identities &lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are associated with the user. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



