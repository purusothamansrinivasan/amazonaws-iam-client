

# AccessDetail

<p>An object that contains details about when a principal in the reported Organizations entity last attempted to access an Amazon Web Services service. A principal can be an IAM user, an IAM role, or the Amazon Web Services account root user within the reported Organizations entity.</p> <p>This data type is a response element in the <a>GetOrganizationsAccessReport</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serviceName** | **String** | The name of the service in which access was attempted. |  |
|**serviceNamespace** | **String** | &lt;p&gt;The namespace of the service in which access was attempted.&lt;/p&gt; &lt;p&gt;To learn the service namespace of a service, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/service-authorization/latest/reference/reference_policies_actions-resources-contextkeys.html\&quot;&gt;Actions, resources, and condition keys for Amazon Web Services services&lt;/a&gt; in the &lt;i&gt;Service Authorization Reference&lt;/i&gt;. Choose the name of the service to view details for that service. In the first paragraph, find the service prefix. For example, &lt;code&gt;(service prefix: a4b)&lt;/code&gt;. For more information about service namespaces, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html#genref-aws-service-namespaces\&quot;&gt;Amazon Web Services service namespaces&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  |
|**region** | **String** | &lt;p&gt;The Region where the last service access attempt occurred.&lt;/p&gt; &lt;p&gt;This field is null if no principals in the reported Organizations entity attempted to access the service within the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#service-last-accessed-reporting-period\&quot;&gt;tracking period&lt;/a&gt;.&lt;/p&gt; |  [optional] |
|**entityPath** | **String** | &lt;p&gt;The path of the Organizations entity (root, organizational unit, or account) from which an authenticated principal last attempted to access the service. Amazon Web Services does not report unauthenticated requests.&lt;/p&gt; &lt;p&gt;This field is null if no principals (IAM users, IAM roles, or root user) in the reported Organizations entity attempted to access the service within the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#service-last-accessed-reporting-period\&quot;&gt;tracking period&lt;/a&gt;.&lt;/p&gt; |  [optional] |
|**lastAuthenticatedTime** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when an authenticated principal most recently attempted to access the service. Amazon Web Services does not report unauthenticated requests.&lt;/p&gt; &lt;p&gt;This field is null if no principals in the reported Organizations entity attempted to access the service within the &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html#service-last-accessed-reporting-period\&quot;&gt;tracking period&lt;/a&gt;.&lt;/p&gt; |  [optional] |
|**totalAuthenticatedEntities** | **Integer** | The number of accounts with authenticated principals (root user, IAM users, and IAM roles) that attempted to access the service in the tracking period. |  [optional] |



