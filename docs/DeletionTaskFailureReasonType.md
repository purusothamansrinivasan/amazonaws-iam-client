

# DeletionTaskFailureReasonType

<p>The reason that the service-linked role deletion failed.</p> <p>This data type is used as a response element in the <a>GetServiceLinkedRoleDeletionStatus</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**reason** | **String** | A short description of the reason that the service-linked role deletion failed. |  [optional] |
|**roleUsageList** | [**List&lt;RoleUsageType&gt;**](RoleUsageType.md) | A list of objects that contains details about the service-linked role deletion failure, if that information is returned by the service. If the service-linked role has active sessions or if any resources that were used by the role have not been deleted from the linked service, the role can&#39;t be deleted. This parameter includes a list of the resources that are associated with the role and the Region in which the resources are being used. |  [optional] |



