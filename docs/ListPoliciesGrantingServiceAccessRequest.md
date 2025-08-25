

# ListPoliciesGrantingServiceAccessRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | Use this parameter only when paginating results and only after you receive a response indicating that the results are truncated. Set it to the value of the &lt;code&gt;Marker&lt;/code&gt; element in the response that you received to indicate where the next call should start. |  [optional] |
|**arn** | **String** | The ARN of the IAM identity (user, group, or role) whose policies you want to list. |  |
|**serviceNamespaces** | **List&lt;String&gt;** | &lt;p&gt;The service namespace for the Amazon Web Services services whose policies you want to list.&lt;/p&gt; &lt;p&gt;To learn the service namespace for a service, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/service-authorization/latest/reference/reference_policies_actions-resources-contextkeys.html\&quot;&gt;Actions, resources, and condition keys for Amazon Web Services services&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. Choose the name of the service to view details for that service. In the first paragraph, find the service prefix. For example, &lt;code&gt;(service prefix: a4b)&lt;/code&gt;. For more information about service namespaces, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html#genref-aws-service-namespaces\&quot;&gt;Amazon Web Services service namespaces&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  |



