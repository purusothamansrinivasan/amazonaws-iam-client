

# ListAccountAliasesRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**marker** | **String** | Use this parameter only when paginating results and only after you receive a response indicating that the results are truncated. Set it to the value of the &lt;code&gt;Marker&lt;/code&gt; element in the response that you received to indicate where the next call should start. |  [optional] |
|**maxItems** | **Integer** | &lt;p&gt;Use this only when paginating results to indicate the maximum number of items you want in the response. If additional items exist beyond the maximum you specify, the &lt;code&gt;IsTruncated&lt;/code&gt; response element is &lt;code&gt;true&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;If you do not include this parameter, the number of items defaults to 100. Note that IAM might return fewer results, even when there are more results available. In that case, the &lt;code&gt;IsTruncated&lt;/code&gt; response element returns &lt;code&gt;true&lt;/code&gt;, and &lt;code&gt;Marker&lt;/code&gt; contains a value to include in the subsequent call that tells the service where to continue from.&lt;/p&gt; |  [optional] |



