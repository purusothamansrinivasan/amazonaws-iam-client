

# ListEntitiesForPolicyResponse

Contains the response to a successful <a>ListEntitiesForPolicy</a> request. 

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**policyGroups** | [**List&lt;PolicyGroup&gt;**](PolicyGroup.md) | A list of IAM groups that the policy is attached to. |  [optional] |
|**policyUsers** | [**List&lt;PolicyUser&gt;**](PolicyUser.md) | A list of IAM users that the policy is attached to. |  [optional] |
|**policyRoles** | [**List&lt;PolicyRole&gt;**](PolicyRole.md) | A list of IAM roles that the policy is attached to. |  [optional] |
|**isTruncated** | **Boolean** | A flag that indicates whether there are more items to return. If your results were truncated, you can make a subsequent pagination request using the &lt;code&gt;Marker&lt;/code&gt; request parameter to retrieve more items. Note that IAM might return fewer than the &lt;code&gt;MaxItems&lt;/code&gt; number of results even when there are more results available. We recommend that you check &lt;code&gt;IsTruncated&lt;/code&gt; after every call to ensure that you receive all your results. |  [optional] |
|**marker** | **String** | When &lt;code&gt;IsTruncated&lt;/code&gt; is &lt;code&gt;true&lt;/code&gt;, this element is present and contains the value to use for the &lt;code&gt;Marker&lt;/code&gt; parameter in a subsequent pagination request. |  [optional] |



