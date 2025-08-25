

# ListPoliciesRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**scope** | **PolicyScopeType** | &lt;p&gt;The scope to use for filtering the results.&lt;/p&gt; &lt;p&gt;To list only Amazon Web Services managed policies, set &lt;code&gt;Scope&lt;/code&gt; to &lt;code&gt;AWS&lt;/code&gt;. To list only the customer managed policies in your Amazon Web Services account, set &lt;code&gt;Scope&lt;/code&gt; to &lt;code&gt;Local&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;This parameter is optional. If it is not included, or if it is set to &lt;code&gt;All&lt;/code&gt;, all policies are returned.&lt;/p&gt; |  [optional] |
|**onlyAttached** | **Boolean** | &lt;p&gt;A flag to filter the results to only the attached policies.&lt;/p&gt; &lt;p&gt;When &lt;code&gt;OnlyAttached&lt;/code&gt; is &lt;code&gt;true&lt;/code&gt;, the returned list contains only the policies that are attached to an IAM user, group, or role. When &lt;code&gt;OnlyAttached&lt;/code&gt; is &lt;code&gt;false&lt;/code&gt;, or when the parameter is not included, all policies are returned.&lt;/p&gt; |  [optional] |
|**pathPrefix** | **String** | The path prefix for filtering the results. This parameter is optional. If it is not included, it defaults to a slash (/), listing all policies. This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of either a forward slash (/) by itself or a string that must begin and end with forward slashes. In addition, it can contain any ASCII character from the ! (&lt;code&gt;\\u0021&lt;/code&gt;) through the DEL character (&lt;code&gt;\\u007F&lt;/code&gt;), including most punctuation characters, digits, and upper and lowercased letters. |  [optional] |
|**policyUsageFilter** | **PolicyUsageType** | &lt;p&gt;The policy usage method to use for filtering the results.&lt;/p&gt; &lt;p&gt;To list only permissions policies, set &lt;code&gt;PolicyUsageFilter&lt;/code&gt; to &lt;code&gt;PermissionsPolicy&lt;/code&gt;. To list only the policies used to set permissions boundaries, set the value to &lt;code&gt;PermissionsBoundary&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;This parameter is optional. If it is not included, all policies are returned. &lt;/p&gt; |  [optional] |
|**marker** | **String** | Use this parameter only when paginating results and only after you receive a response indicating that the results are truncated. Set it to the value of the &lt;code&gt;Marker&lt;/code&gt; element in the response that you received to indicate where the next call should start. |  [optional] |
|**maxItems** | **Integer** | &lt;p&gt;Use this only when paginating results to indicate the maximum number of items you want in the response. If additional items exist beyond the maximum you specify, the &lt;code&gt;IsTruncated&lt;/code&gt; response element is &lt;code&gt;true&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;If you do not include this parameter, the number of items defaults to 100. Note that IAM might return fewer results, even when there are more results available. In that case, the &lt;code&gt;IsTruncated&lt;/code&gt; response element returns &lt;code&gt;true&lt;/code&gt;, and &lt;code&gt;Marker&lt;/code&gt; contains a value to include in the subsequent call that tells the service where to continue from.&lt;/p&gt; |  [optional] |



