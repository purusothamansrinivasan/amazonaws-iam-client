

# ListEntitiesForPolicyRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**policyArn** | **String** | &lt;p&gt;The Amazon Resource Name (ARN) of the IAM policy for which you want the versions.&lt;/p&gt; &lt;p&gt;For more information about ARNs, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/aws-arns-and-namespaces.html\&quot;&gt;Amazon Resource Names (ARNs)&lt;/a&gt; in the &lt;i&gt;Amazon Web Services General Reference&lt;/i&gt;.&lt;/p&gt; |  |
|**entityFilter** | **EntityType** | &lt;p&gt;The entity type to use for filtering the results.&lt;/p&gt; &lt;p&gt;For example, when &lt;code&gt;EntityFilter&lt;/code&gt; is &lt;code&gt;Role&lt;/code&gt;, only the roles that are attached to the specified policy are returned. This parameter is optional. If it is not included, all attached entities (users, groups, and roles) are returned. The argument for this parameter must be one of the valid values listed below.&lt;/p&gt; |  [optional] |
|**pathPrefix** | **String** | &lt;p&gt;The path prefix for filtering the results. This parameter is optional. If it is not included, it defaults to a slash (/), listing all entities.&lt;/p&gt; &lt;p&gt;This parameter allows (through its &lt;a href&#x3D;\&quot;http://wikipedia.org/wiki/regex\&quot;&gt;regex pattern&lt;/a&gt;) a string of characters consisting of either a forward slash (/) by itself or a string that must begin and end with forward slashes. In addition, it can contain any ASCII character from the ! (&lt;code&gt;\\u0021&lt;/code&gt;) through the DEL character (&lt;code&gt;\\u007F&lt;/code&gt;), including most punctuation characters, digits, and upper and lowercased letters.&lt;/p&gt; |  [optional] |
|**policyUsageFilter** | **PolicyUsageType** | &lt;p&gt;The policy usage method to use for filtering the results.&lt;/p&gt; &lt;p&gt;To list only permissions policies, set &lt;code&gt;PolicyUsageFilter&lt;/code&gt; to &lt;code&gt;PermissionsPolicy&lt;/code&gt;. To list only the policies used to set permissions boundaries, set the value to &lt;code&gt;PermissionsBoundary&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;This parameter is optional. If it is not included, all policies are returned. &lt;/p&gt; |  [optional] |
|**marker** | **String** | Use this parameter only when paginating results and only after you receive a response indicating that the results are truncated. Set it to the value of the &lt;code&gt;Marker&lt;/code&gt; element in the response that you received to indicate where the next call should start. |  [optional] |
|**maxItems** | **Integer** | &lt;p&gt;Use this only when paginating results to indicate the maximum number of items you want in the response. If additional items exist beyond the maximum you specify, the &lt;code&gt;IsTruncated&lt;/code&gt; response element is &lt;code&gt;true&lt;/code&gt;.&lt;/p&gt; &lt;p&gt;If you do not include this parameter, the number of items defaults to 100. Note that IAM might return fewer results, even when there are more results available. In that case, the &lt;code&gt;IsTruncated&lt;/code&gt; response element returns &lt;code&gt;true&lt;/code&gt;, and &lt;code&gt;Marker&lt;/code&gt; contains a value to include in the subsequent call that tells the service where to continue from.&lt;/p&gt; |  [optional] |



