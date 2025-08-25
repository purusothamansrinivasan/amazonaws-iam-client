

# GetUserResponse

Contains the response to a successful <a>GetUser</a> request. 

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**user** | [**User**](User.md) | &lt;p&gt;A structure containing details about the IAM user.&lt;/p&gt; &lt;important&gt; &lt;p&gt;Due to a service issue, password last used data does not include password use from May 3, 2018 22:50 PDT to May 23, 2018 14:08 PDT. This affects &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_finding-unused.html\&quot;&gt;last sign-in&lt;/a&gt; dates shown in the IAM console and password last used dates in the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_getting-report.html\&quot;&gt;IAM credential report&lt;/a&gt;, and returned by this operation. If users signed in during the affected time, the password last used date that is returned is the date the user last signed in before May 3, 2018. For users that signed in after May 23, 2018 14:08 PDT, the returned password last used date is accurate.&lt;/p&gt; &lt;p&gt;You can use password last used information to identify unused credentials for deletion. For example, you might delete users who did not sign in to Amazon Web Services in the last 90 days. In cases like this, we recommend that you adjust your evaluation window to include dates after May 23, 2018. Alternatively, if your users use access keys to access Amazon Web Services programmatically you can refer to access key last used information because it is accurate for all dates. &lt;/p&gt; &lt;/important&gt; |  |



