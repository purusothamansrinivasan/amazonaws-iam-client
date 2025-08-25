

# RoleUsageType

<p>An object that contains details about how a service-linked role is used, if that information is returned by the service.</p> <p>This data type is used as a response element in the <a>GetServiceLinkedRoleDeletionStatus</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**region** | **String** | The name of the Region where the service-linked role is being used. |  [optional] |
|**resources** | **List&lt;String&gt;** | The name of the resource that is using the service-linked role. |  [optional] |



