

# GetMFADeviceResponse


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The friendly name identifying the user. |  [optional] |
|**serialNumber** | **String** | Serial number that uniquely identifies the MFA device. For this API, we only accept FIDO security key &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/reference-arns.html\&quot;&gt;ARNs&lt;/a&gt;. |  |
|**enableDate** | **OffsetDateTime** | The date that a specified user&#39;s MFA device was first enabled. |  [optional] |
|**certifications** | **Map&lt;String, String&gt;** | The certifications of a specified user&#39;s MFA device. We currently provide FIPS-140-2, FIPS-140-3, and FIDO certification levels obtained from &lt;a href&#x3D;\&quot;https://fidoalliance.org/metadata/\&quot;&gt; FIDO Alliance Metadata Service (MDS)&lt;/a&gt;. |  [optional] |



