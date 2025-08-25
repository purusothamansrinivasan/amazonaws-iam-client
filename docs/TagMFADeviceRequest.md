

# TagMFADeviceRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serialNumber** | **String** | &lt;p&gt;The unique identifier for the IAM virtual MFA device to which you want to add tags. For virtual MFA devices, the serial number is the same as the ARN.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | The list of tags that you want to attach to the IAM virtual MFA device. Each tag consists of a key name and an associated value. |  |



