

# GetOrganizationsAccessReportResponse


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**jobStatus** | **JobStatusType** | The status of the job. |  |
|**jobCreationDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the report job was created. |  |
|**jobCompletionDate** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the generated report job was completed or failed.&lt;/p&gt; &lt;p&gt;This field is null if the job is still in progress, as indicated by a job status value of &lt;code&gt;IN_PROGRESS&lt;/code&gt;.&lt;/p&gt; |  [optional] |
|**numberOfServicesAccessible** | **Integer** | The number of services that the applicable SCPs allow account principals to access. |  [optional] |
|**numberOfServicesNotAccessed** | **Integer** | The number of services that account principals are allowed but did not attempt to access. |  [optional] |
|**accessDetails** | [**List&lt;AccessDetail&gt;**](AccessDetail.md) | An object that contains details about the most recent attempt to access the service. |  [optional] |
|**isTruncated** | **Boolean** | A flag that indicates whether there are more items to return. If your results were truncated, you can make a subsequent pagination request using the &lt;code&gt;Marker&lt;/code&gt; request parameter to retrieve more items. Note that IAM might return fewer than the &lt;code&gt;MaxItems&lt;/code&gt; number of results even when there are more results available. We recommend that you check &lt;code&gt;IsTruncated&lt;/code&gt; after every call to ensure that you receive all your results. |  [optional] |
|**marker** | **String** | When &lt;code&gt;IsTruncated&lt;/code&gt; is &lt;code&gt;true&lt;/code&gt;, this element is present and contains the value to use for the &lt;code&gt;Marker&lt;/code&gt; parameter in a subsequent pagination request. |  [optional] |
|**errorDetails** | [**ErrorDetails**](ErrorDetails.md) |  |  [optional] |



