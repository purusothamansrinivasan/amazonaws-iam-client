

# GenerateOrganizationsAccessReportRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**entityPath** | **String** | The path of the Organizations entity (root, OU, or account). You can build an entity path using the known structure of your organization. For example, assume that your account ID is &lt;code&gt;123456789012&lt;/code&gt; and its parent OU ID is &lt;code&gt;ou-rge0-awsabcde&lt;/code&gt;. The organization root ID is &lt;code&gt;r-f6g7h8i9j0example&lt;/code&gt; and your organization ID is &lt;code&gt;o-a1b2c3d4e5&lt;/code&gt;. Your entity path is &lt;code&gt;o-a1b2c3d4e5/r-f6g7h8i9j0example/ou-rge0-awsabcde/123456789012&lt;/code&gt;. |  |
|**organizationsPolicyId** | **String** | &lt;p&gt;The identifier of the Organizations service control policy (SCP). This parameter is optional.&lt;/p&gt; &lt;p&gt;This ID is used to generate information about when an account principal that is limited by the SCP attempted to access an Amazon Web Services service.&lt;/p&gt; |  [optional] |



