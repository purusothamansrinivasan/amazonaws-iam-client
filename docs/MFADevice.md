

# MFADevice

<p>Contains information about an MFA device.</p> <p>This data type is used as a response element in the <a>ListMFADevices</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The user with whom the MFA device is associated. |  |
|**serialNumber** | **String** | The serial number that uniquely identifies the MFA device. For virtual MFA devices, the serial number is the device ARN. |  |
|**enableDate** | **OffsetDateTime** | The date when the MFA device was enabled for the user. |  |



