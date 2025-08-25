

# VirtualMFADevice

Contains information about a virtual MFA device.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**serialNumber** | **String** | The serial number associated with &lt;code&gt;VirtualMFADevice&lt;/code&gt;. |  |
|**base32StringSeed** | **String** |  The base32 seed defined as specified in &lt;a href&#x3D;\&quot;https://tools.ietf.org/html/rfc3548.txt\&quot;&gt;RFC3548&lt;/a&gt;. The &lt;code&gt;Base32StringSeed&lt;/code&gt; is base32-encoded.  |  [optional] |
|**qrCodePNG** | **String** |  A QR code PNG image that encodes &lt;code&gt;otpauth://totp/$virtualMFADeviceName@$AccountName?secret&#x3D;$Base32String&lt;/code&gt; where &lt;code&gt;$virtualMFADeviceName&lt;/code&gt; is one of the create call arguments. &lt;code&gt;AccountName&lt;/code&gt; is the user name if set (otherwise, the account ID otherwise), and &lt;code&gt;Base32String&lt;/code&gt; is the seed in base32 format. The &lt;code&gt;Base32String&lt;/code&gt; value is base64-encoded.  |  [optional] |
|**user** | [**User**](User.md) | The IAM user associated with this virtual MFA device. |  [optional] |
|**enableDate** | **OffsetDateTime** | The date and time on which the virtual MFA device was enabled. |  [optional] |
|**tags** | [**List&lt;Tag&gt;**](Tag.md) | A list of tags that are attached to the virtual MFA device. For more information about tagging, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\&quot;&gt;Tagging IAM resources&lt;/a&gt; in the &lt;i&gt;IAM User Guide&lt;/i&gt;. |  [optional] |



