

# ServiceSpecificCredentialMetadata

Contains additional details about a service-specific credential.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name of the IAM user associated with the service-specific credential. |  |
|**status** | **StatusType** | The status of the service-specific credential. &lt;code&gt;Active&lt;/code&gt; means that the key is valid for API calls, while &lt;code&gt;Inactive&lt;/code&gt; means it is not. |  |
|**serviceUserName** | **String** | The generated user name for the service-specific credential. |  |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the service-specific credential were created. |  |
|**serviceSpecificCredentialId** | **String** | The unique identifier for the service-specific credential. |  |
|**serviceName** | **String** | The name of the service associated with the service-specific credential. |  |



