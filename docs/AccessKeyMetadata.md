

# AccessKeyMetadata

<p>Contains information about an Amazon Web Services access key, without its secret key.</p> <p>This data type is used as a response element in the <a>ListAccessKeys</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name of the IAM user that the key is associated with. |  [optional] |
|**accessKeyId** | **String** | The ID for this access key. |  [optional] |
|**status** | **StatusType** | The status of the access key. &lt;code&gt;Active&lt;/code&gt; means that the key is valid for API calls; &lt;code&gt;Inactive&lt;/code&gt; means it is not. |  [optional] |
|**createDate** | **OffsetDateTime** | The date when the access key was created. |  [optional] |



