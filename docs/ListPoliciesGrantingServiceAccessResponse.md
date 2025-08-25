

# ListPoliciesGrantingServiceAccessResponse


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**policiesGrantingServiceAccess** | [**List&lt;ListPoliciesGrantingServiceAccessEntry&gt;**](ListPoliciesGrantingServiceAccessEntry.md) | A &lt;code&gt;ListPoliciesGrantingServiceAccess&lt;/code&gt; object that contains details about the permissions policies attached to the specified identity (user, group, or role). |  |
|**isTruncated** | **Boolean** | A flag that indicates whether there are more items to return. If your results were truncated, you can make a subsequent pagination request using the &lt;code&gt;Marker&lt;/code&gt; request parameter to retrieve more items. We recommend that you check &lt;code&gt;IsTruncated&lt;/code&gt; after every call to ensure that you receive all your results. |  [optional] |
|**marker** | **String** | When &lt;code&gt;IsTruncated&lt;/code&gt; is &lt;code&gt;true&lt;/code&gt;, this element is present and contains the value to use for the &lt;code&gt;Marker&lt;/code&gt; parameter in a subsequent pagination request. |  [optional] |



