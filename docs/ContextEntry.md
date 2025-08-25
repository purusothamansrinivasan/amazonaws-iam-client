

# ContextEntry

<p>Contains information about a condition context key. It includes the name of the key and specifies the value (or values, if the context key supports multiple values) to use in the simulation. This information is used when evaluating the <code>Condition</code> elements of the input policies.</p> <p>This data type is used as an input parameter to <a>SimulateCustomPolicy</a> and <a>SimulatePrincipalPolicy</a>.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**contextKeyName** | **String** | The full name of a condition context key, including the service prefix. For example, &lt;code&gt;aws:SourceIp&lt;/code&gt; or &lt;code&gt;s3:VersionId&lt;/code&gt;. |  [optional] |
|**contextKeyValues** | **List&lt;String&gt;** | The value (or values, if the condition context key supports multiple values) to provide to the simulation when the key is referenced by a &lt;code&gt;Condition&lt;/code&gt; element in an input policy. |  [optional] |
|**contextKeyType** | **ContextKeyTypeEnum** | The data type of the value (or values) specified in the &lt;code&gt;ContextKeyValues&lt;/code&gt; parameter. |  [optional] |



