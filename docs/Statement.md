

# Statement

<p>Contains a reference to a <code>Statement</code> element in a policy document that determines the result of the simulation.</p> <p>This data type is used by the <code>MatchedStatements</code> member of the <code> <a>EvaluationResult</a> </code> type.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**sourcePolicyId** | **String** | The identifier of the policy that was provided as an input. |  [optional] |
|**sourcePolicyType** | **PolicySourceType** | The type of the policy. |  [optional] |
|**startPosition** | [**Position**](Position.md) | The row and column of the beginning of the &lt;code&gt;Statement&lt;/code&gt; in an IAM policy. |  [optional] |
|**endPosition** | [**Position**](Position.md) | The row and column of the end of a &lt;code&gt;Statement&lt;/code&gt; in an IAM policy. |  [optional] |



