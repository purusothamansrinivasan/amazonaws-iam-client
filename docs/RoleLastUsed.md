

# RoleLastUsed

<p>Contains information about the last time that an IAM role was used. This includes the date and time and the Region in which the role was last used. Activity is only reported for the trailing 400 days. This period can be shorter if your Region began supporting these features within the last year. The role might have been used more than 400 days ago. For more information, see <a href=\"https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#access-advisor_tracking-period\">Regions where data is tracked</a> in the <i>IAM user Guide</i>.</p> <p>This data type is returned as a response element in the <a>GetRole</a> and <a>GetAccountAuthorizationDetails</a> operations.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**lastUsedDate** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt; that the role was last used.&lt;/p&gt; &lt;p&gt;This field is null if the role has not been used within the IAM tracking period. For more information about the tracking period, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#access-advisor_tracking-period\&quot;&gt;Regions where data is tracked&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**region** | **String** | The name of the Amazon Web Services Region in which the role was last used. |  [optional] |



