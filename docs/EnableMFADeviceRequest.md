

# EnableMFADeviceRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | &lt;p&gt;The name of the IAM user for whom you want to enable the MFA device.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: _+&#x3D;,.@-&lt;/p&gt; |  |
|**serialNumber** | **String** | &lt;p&gt;The serial number that uniquely identifies the MFA device. For virtual MFA devices, the serial number is the device ARN.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of upper and lowercase alphanumeric characters with no spaces. You can also include any of the following characters: &#x3D;,.@:/-&lt;/p&gt; |  |
|**authenticationCode1** | **String** | &lt;p&gt;An authentication code emitted by the device. &lt;/p&gt; &lt;p&gt;The format for this parameter is a string of six digits.&lt;/p&gt; &lt;important&gt; &lt;p&gt;Submit your request immediately after generating the authentication codes. If you generate the codes and then wait too long to submit the request, the MFA device successfully associates with the user but the MFA device becomes out of sync. This happens because time-based one-time passwords (TOTP) expire after a short period of time. If this happens, you can &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_sync.html\&quot;&gt;resync the device&lt;/a&gt;.&lt;/p&gt; &lt;/important&gt; |  |
|**authenticationCode2** | **String** | &lt;p&gt;A subsequent authentication code emitted by the device.&lt;/p&gt; &lt;p&gt;The format for this parameter is a string of six digits.&lt;/p&gt; &lt;important&gt; &lt;p&gt;Submit your request immediately after generating the authentication codes. If you generate the codes and then wait too long to submit the request, the MFA device successfully associates with the user but the MFA device becomes out of sync. This happens because time-based one-time passwords (TOTP) expire after a short period of time. If this happens, you can &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_sync.html\&quot;&gt;resync the device&lt;/a&gt;.&lt;/p&gt; &lt;/important&gt; |  |



