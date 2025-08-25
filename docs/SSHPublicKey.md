

# SSHPublicKey

<p>Contains information about an SSH public key.</p> <p>This data type is used as a response element in the <a>GetSSHPublicKey</a> and <a>UploadSSHPublicKey</a> operations. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name of the IAM user associated with the SSH public key. |  |
|**ssHPublicKeyId** | **String** | The unique identifier for the SSH public key. |  |
|**fingerprint** | **String** | The MD5 message digest of the SSH public key. |  |
|**ssHPublicKeyBody** | **String** | The SSH public key. |  |
|**status** | **StatusType** | The status of the SSH public key. &lt;code&gt;Active&lt;/code&gt; means that the key can be used for authentication with an CodeCommit repository. &lt;code&gt;Inactive&lt;/code&gt; means that the key cannot be used. |  |
|**uploadDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the SSH public key was uploaded. |  [optional] |



