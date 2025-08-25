

# ListPoliciesGrantingServiceAccessEntry

<p>Contains details about the permissions policies that are attached to the specified identity (user, group, or role).</p> <p>This data type is used as a response element in the <a>ListPoliciesGrantingServiceAccess</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serviceNamespace** | **String** | &lt;p&gt;The namespace of the service that was accessed.&lt;/p&gt; &lt;p&gt;To learn the service namespace of a service, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/service-authorization/latest/reference/reference_policies_actions-resources-contextkeys.html\&quot;&gt;Actions, resources, and condition keys for Amazon Web Services services&lt;/a&gt; in the &lt;i&gt;Service Authorization Reference&lt;/i&gt;. Choose the name of the service to view details for that service. In the first paragraph, find the service prefix. For example, &lt;code&gt;(service prefix: a4b)&lt;/code&gt;. For more information about service namespaces, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html#genref-aws-service-namespaces\&quot;&gt;Amazon Web Services service namespaces&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  [optional] |
|**policies** | [**List&lt;PolicyGrantingServiceAccess&gt;**](PolicyGrantingServiceAccess.md) | The &lt;code&gt;PoliciesGrantingServiceAccess&lt;/code&gt; object that contains details about the policy. |  [optional] |



