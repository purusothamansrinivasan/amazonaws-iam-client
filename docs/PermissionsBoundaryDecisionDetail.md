

# PermissionsBoundaryDecisionDetail

Contains information about the effect that a permissions boundary has on a policy simulation when the boundary is applied to an IAM entity.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**allowedByPermissionsBoundary** | **Boolean** | Specifies whether an action is allowed by a permissions boundary that is applied to an IAM entity (user or role). A value of &lt;code&gt;true&lt;/code&gt; means that the permissions boundary does not deny the action. This means that the policy includes an &lt;code&gt;Allow&lt;/code&gt; statement that matches the request. In this case, if an identity-based policy also allows the action, the request is allowed. A value of &lt;code&gt;false&lt;/code&gt; means that either the requested action is not allowed (implicitly denied) or that the action is explicitly denied by the permissions boundary. In both of these cases, the action is not allowed, regardless of the identity-based policy. |  [optional] |



