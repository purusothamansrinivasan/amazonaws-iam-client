

# ResyncMFADeviceRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the user whose MFA device you want to resynchronize.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**serialNumber** | **String** | &lt;p&gt;Serial number that uniquely identifies the MFA device.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**authenticationCode1** | **String** | &lt;p&gt;An authentication code emitted by the device.&lt;/p&gt; &lt;p&gt;The format for this parameter is a sequence of six digits.&lt;/p&gt; |  |
|**authenticationCode2** | **String** | &lt;p&gt;A subsequent authentication code emitted by the device.&lt;/p&gt; &lt;p&gt;The format for this parameter is a sequence of six digits.&lt;/p&gt; |  |



