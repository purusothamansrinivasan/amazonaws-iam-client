

# ResourceSpecificResult

<p>Contains the result of the simulation of a single API operation call on a single resource.</p> <p>This data type is used by a member of the <a>EvaluationResult</a> data type.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**evalResourceName** | **String** | The name of the simulated resource, in Amazon Resource Name (ARN) format. |  |
|**evalResourceDecision** | **PolicyEvaluationDecisionType** | The result of the simulation of the simulated API operation on the resource specified in &lt;code&gt;EvalResourceName&lt;/code&gt;. |  |
|**matchedStatements** | [**List&lt;Statement&gt;**](Statement.md) | A list of the statements in the input policies that determine the result for this part of the simulation. Remember that even if multiple statements allow the operation on the resource, if &lt;i&gt;any&lt;/i&gt; statement denies that operation, then the explicit deny overrides any allow. In addition, the deny statement is the only entry included in the result. |  [optional] |
|**missingContextValues** | **List&lt;String&gt;** | A list of context keys that are required by the included input policies but that were not provided by one of the input parameters. This list is used when a list of ARNs is included in the &lt;code&gt;ResourceArns&lt;/code&gt; parameter instead of \&quot;*\&quot;. If you do not specify individual resources, by setting &lt;code&gt;ResourceArns&lt;/code&gt; to \&quot;*\&quot; or by not including the &lt;code&gt;ResourceArns&lt;/code&gt; parameter, then any missing context values are instead included under the &lt;code&gt;EvaluationResults&lt;/code&gt; section. To discover the context keys used by a set of policies, you can call &lt;a&gt;GetContextKeysForCustomPolicy&lt;/a&gt; or &lt;a&gt;GetContextKeysForPrincipalPolicy&lt;/a&gt;. |  [optional] |
|**evalDecisionDetails** | **Map&lt;String, PolicyEvaluationDecisionType&gt;** | Additional details about the results of the evaluation decision on a single resource. This parameter is returned only for cross-account simulations. This parameter explains how each policy type contributes to the resource-specific evaluation decision. |  [optional] |
|**permissionsBoundaryDecisionDetail** | [**PermissionsBoundaryDecisionDetail**](PermissionsBoundaryDecisionDetail.md) | Contains information about the effect that a permissions boundary has on a policy simulation when that boundary is applied to an IAM entity. |  [optional] |



