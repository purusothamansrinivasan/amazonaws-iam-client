

# UntagMFADeviceRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serialNumber** | **String** | &lt;p&gt;The unique identifier for the IAM virtual MFA device from which you want to remove tags. For virtual MFA devices, the serial number is the same as the ARN.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**tagKeys** | **List&lt;String&gt;** | A list of key names as a simple array of strings. The tags with matching keys are removed from the specified instance profile. |  |



