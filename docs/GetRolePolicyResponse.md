

# GetRolePolicyResponse

Contains the response to a successful <a>GetRolePolicy</a> request. 

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**roleName** | **String** | The role the policy is associated with. |  |
|**policyName** | **String** | The name of the policy. |  |
|**policyDocument** | **String** | &lt;p&gt;The policy document.&lt;/p&gt; &lt;p&gt;IAM stores policies in JSON format. However, resources that were created using CloudFormation templates can be formatted in YAML. CloudFormation always converts a YAML policy to JSON format before submitting it to IAM.&lt;/p&gt; |  |



