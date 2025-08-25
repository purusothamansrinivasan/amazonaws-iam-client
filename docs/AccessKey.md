

# AccessKey

<p>Contains information about an Amazon Web Services access key.</p> <p> This data type is used as a response element in the <a>CreateAccessKey</a> and <a>ListAccessKeys</a> operations. </p> <note> <p>The <code>SecretAccessKey</code> value is returned only in response to <a>CreateAccessKey</a>. You can get a secret access key only when you first create an access key; you cannot recover the secret access key later. If you lose a secret access key, you must create a new access key.</p> </note>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name of the IAM user that the access key is associated with. |  |
|**accessKeyId** | **String** | The ID for this access key. |  |
|**status** | **StatusType** | The status of the access key. &lt;code&gt;Active&lt;/code&gt; means that the key is valid for API calls, while &lt;code&gt;Inactive&lt;/code&gt; means it is not.  |  |
|**secretAccessKey** | **String** | The secret key used to sign requests. |  |
|**createDate** | **OffsetDateTime** | The date when the access key was created. |  [optional] |



