

# SigningCertificate

<p>Contains information about an X.509 signing certificate.</p> <p>This data type is used as a response element in the <a>UploadSigningCertificate</a> and <a>ListSigningCertificates</a> operations. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name of the user the signing certificate is associated with. |  |
|**certificateId** | **String** | The ID for the signing certificate. |  |
|**certificateBody** | **String** | The contents of the signing certificate. |  |
|**status** | **StatusType** | The status of the signing certificate. &lt;code&gt;Active&lt;/code&gt; means that the key is valid for API calls, while &lt;code&gt;Inactive&lt;/code&gt; means it is not. |  |
|**uploadDate** | **OffsetDateTime** | The date when the signing certificate was uploaded. |  [optional] |



