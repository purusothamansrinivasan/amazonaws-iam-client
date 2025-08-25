

# TrackedActionLastAccessed

<p>Contains details about the most recent attempt to access an action within the service.</p> <p>This data type is used as a response element in the <a>GetServiceLastAccessedDetails</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**actionName** | **String** | The name of the tracked action to which access was attempted. Tracked actions are actions that report activity to IAM. |  [optional] |
|**lastAccessedEntity** | **String** | &lt;p&gt;The Amazon Resource Name (ARN). ARNs are unique identifiers for Amazon Web Services resources.&lt;/p&gt; &lt;p&gt;For more information about ARNs, go to &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;. &lt;/p&gt; |  [optional] |
|**lastAccessedTime** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when an authenticated entity most recently attempted to access the tracked service. Amazon Web Services does not report unauthenticated requests.&lt;/p&gt; &lt;p&gt;This field is null if no IAM entities attempted to access the service within the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#service-last-accessed-reporting-period\&quot;&gt;tracking period&lt;/a&gt;.&lt;/p&gt; |  [optional] |
|**lastAccessedRegion** | **String** | &lt;p&gt;The Region from which the authenticated entity (user or role) last attempted to access the tracked action. Amazon Web Services does not report unauthenticated requests.&lt;/p&gt; &lt;p&gt;This field is null if no IAM entities attempted to access the service within the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#service-last-accessed-reporting-period\&quot;&gt;tracking period&lt;/a&gt;.&lt;/p&gt; |  [optional] |



