

# EntityDetails

<p>An object that contains details about when the IAM entities (users or roles) were last used in an attempt to access the specified Amazon Web Services service.</p> <p>This data type is a response element in the <a>GetServiceLastAccessedDetailsWithEntities</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**entityInfo** | [**EntityInfo**](EntityInfo.md) | The &lt;code&gt;EntityInfo&lt;/code&gt; object that contains details about the entity (user or role). |  |
|**lastAuthenticated** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the authenticated entity last attempted to access Amazon Web Services. Amazon Web Services does not report unauthenticated requests.&lt;/p&gt; &lt;p&gt;This field is null if no IAM entities attempted to access the service within the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#service-last-accessed-reporting-period\&quot;&gt;tracking period&lt;/a&gt;.&lt;/p&gt; |  [optional] |



