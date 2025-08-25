

# EvaluationResult

<p>Contains the results of a simulation.</p> <p>This data type is used by the return parameter of <code> <a>SimulateCustomPolicy</a> </code> and <code> <a>SimulatePrincipalPolicy</a> </code>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**evalActionName** | **String** | The name of the API operation tested on the indicated resource. |  |
|**evalResourceName** | **String** | The ARN of the resource that the indicated API operation was tested on. |  [optional] |
|**evalDecision** | **PolicyEvaluationDecisionType** | The result of the simulation. |  |
|**matchedStatements** | [**List&lt;Statement&gt;**](Statement.md) | A list of the statements in the input policies that determine the result for this scenario. Remember that even if multiple statements allow the operation on the resource, if only one statement denies that operation, then the explicit deny overrides any allow. In addition, the deny statement is the only entry included in the result. |  [optional] |
|**missingContextValues** | **List&lt;String&gt;** | A list of context keys that are required by the included input policies but that were not provided by one of the input parameters. This list is used when the resource in a simulation is \&quot;*\&quot;, either explicitly, or when the &lt;code&gt;ResourceArns&lt;/code&gt; parameter blank. If you include a list of resources, then any missing context values are instead included under the &lt;code&gt;ResourceSpecificResults&lt;/code&gt; section. To discover the context keys used by a set of policies, you can call &lt;a&gt;GetContextKeysForCustomPolicy&lt;/a&gt; or &lt;a&gt;GetContextKeysForPrincipalPolicy&lt;/a&gt;. |  [optional] |
|**organizationsDecisionDetail** | [**OrganizationsDecisionDetail**](OrganizationsDecisionDetail.md) | A structure that details how Organizations and its service control policies affect the results of the simulation. Only applies if the simulated user&#39;s account is part of an organization. |  [optional] |
|**permissionsBoundaryDecisionDetail** | [**PermissionsBoundaryDecisionDetail**](PermissionsBoundaryDecisionDetail.md) | Contains information about the effect that a permissions boundary has on a policy simulation when the boundary is applied to an IAM entity. |  [optional] |
|**evalDecisionDetails** | **Map&lt;String, PolicyEvaluationDecisionType&gt;** | &lt;p&gt;Additional details about the results of the cross-account evaluation decision. This parameter is populated for only cross-account simulations. It contains a brief summary of how each policy type contributes to the final evaluation decision.&lt;/p&gt; &lt;p&gt;If the simulation evaluates policies within the same account and includes a resource ARN, then the parameter is present but the response is empty. If the simulation evaluates policies within the same account and specifies all resources (&lt;code&gt;*&lt;/code&gt;), then the parameter is not returned.&lt;/p&gt; &lt;p&gt;When you make a cross-account request, Amazon Web Services evaluates the request in the trusting account and the trusted account. The request is allowed only if both evaluations return &lt;code&gt;true&lt;/code&gt;. For more information about how policies are evaluated, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html#policy-eval-basics\&quot;&gt;Evaluating policies within a single account&lt;/a&gt;.&lt;/p&gt; &lt;p&gt;If an Organizations SCP included in the evaluation denies access, the simulation ends. In this case, policy evaluation does not proceed any further and this parameter is not returned.&lt;/p&gt; |  [optional] |
|**resourceSpecificResults** | [**List&lt;ResourceSpecificResult&gt;**](ResourceSpecificResult.md) | The individual results of the simulation of the API operation specified in EvalActionName on each resource. |  [optional] |



