

# CreateServiceLinkedRoleRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**awSServiceName** | **String** | &lt;p&gt;The service principal for the Amazon Web Services service to which this role is attached. You use a string similar to a URL but without the http:// in front. For example: &lt;code&gt;elasticbeanstalk.amazonaws.com&lt;/code&gt;. &lt;/p&gt; &lt;p&gt;Service principals are unique and case-sensitive. To find the exact service principal for your service-linked role, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_aws-services-that-work-with-iam.html\&quot;&gt;Amazon Web Services services that work with IAM&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. Look for the services that have &lt;b&gt;Yes &lt;/b&gt;in the &lt;b&gt;Service-Linked Role&lt;/b&gt; column. Choose the &lt;b&gt;Yes&lt;/b&gt; link to view the service-linked role documentation for that service.&lt;/p&gt; |  |
|**description** | **String** | The description of the role. |  [optional] |
|**customSuffix** | **String** | &lt;p/&gt; &lt;p&gt;A string that you provide, which is combined with the service-provided prefix to form the complete role name. If you make multiple requests for the same service, then you must supply a different &lt;code&gt;CustomSuffix&lt;/code&gt; for each request. Otherwise the request fails with a duplicate role name error. For example, you could add &lt;code&gt;-1&lt;/code&gt; or &lt;code&gt;-debug&lt;/code&gt; to the suffix.&lt;/p&gt; &lt;p&gt;Some services do not support the &lt;code&gt;CustomSuffix&lt;/code&gt; parameter. If you provide an optional suffix and the operation fails, try the operation again without the suffix.&lt;/p&gt; |  [optional] |



