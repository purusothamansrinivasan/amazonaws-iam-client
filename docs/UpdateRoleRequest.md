

# UpdateRoleRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**roleName** | **String** | The name of the role that you want to modify. |  |
|**description** | **String** | The new description that you want to apply to the specified role. |  [optional] |
|**maxSessionDuration** | **Integer** | &lt;p&gt;The maximum session duration (in seconds) that you want to set for the specified role. If you do not specify a value for this setting, the default value of one hour is applied. This setting can have a value from 1 hour to 12 hours.&lt;/p&gt; &lt;p&gt;Anyone who assumes the role from the CLI or API can use the &lt;code&gt;DurationSeconds&lt;/code&gt; API parameter or the &lt;code&gt;duration-seconds&lt;/code&gt; CLI parameter to request a longer session. The &lt;code&gt;MaxSessionDuration&lt;/code&gt; setting determines the maximum duration that can be requested using the &lt;code&gt;DurationSeconds&lt;/code&gt; parameter. If users don&#39;t specify a value for the &lt;code&gt;DurationSeconds&lt;/code&gt; parameter, their security credentials are valid for one hour by default. This applies when you use the &lt;code&gt;AssumeRole*&lt;/code&gt; API operations or the &lt;code&gt;assume-role*&lt;/code&gt; CLI operations but does not apply when you use those operations to create a console URL. For more information, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use.html\&quot;&gt;Using IAM roles&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;.&lt;/p&gt; |  [optional] |



