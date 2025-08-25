

# GetAccessKeyLastUsedResponse

Contains the response to a successful <a>GetAccessKeyLastUsed</a> request. It is also returned as a member of the <a>AccessKeyMetaData</a> structure returned by the <a>ListAccessKeys</a> action.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the IAM user that owns this access key.&lt;/p&gt; &lt;p/&gt; |  [optional] |
|**accessKeyLastUsed** | [**AccessKeyLastUsed**](AccessKeyLastUsed.md) | Contains information about the last time the access key was used. |  [optional] |



