

# PolicyVersion

<p>Contains information about a version of a managed policy.</p> <p>This data type is used as a response element in the <a>CreatePolicyVersion</a>, <a>GetPolicyVersion</a>, <a>ListPolicyVersions</a>, and <a>GetAccountAuthorizationDetails</a> operations. </p> <p>For more information about managed policies, refer to <a href=\"https://docs.aws.amazon.com/IAM/latest/UserGuide/policies-managed-vs-inline.html\">Managed policies and inline policies</a> in the <i>IAM User Guide</i>. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**document** | **String** | &lt;p&gt;The policy document.&lt;/p&gt; &lt;p&gt;The policy document is returned in the response to the &lt;a&gt;GetPolicyVersion&lt;/a&gt; and &lt;a&gt;GetAccountAuthorizationDetails&lt;/a&gt; operations. It is not returned in the response to the &lt;a&gt;CreatePolicyVersion&lt;/a&gt; or &lt;a&gt;ListPolicyVersions&lt;/a&gt; operations. &lt;/p&gt; &lt;p&gt;The policy document returned in this structure is URL-encoded compliant with &lt;a href&#x3D;\&quot;https://tools.ietf.org/html/rfc3986\&quot;&gt;RFC 3986&lt;/a&gt;. You can use a URL decoding method to convert the policy back to plain JSON text. For example, if you use Java, you can use the &lt;code&gt;decode&lt;/code&gt; method of the &lt;code&gt;java.net.URLDecoder&lt;/code&gt; utility class in the Java SDK. Other languages and SDKs provide similar functionality.&lt;/p&gt; |  [optional] |
|**versionId** | **String** | &lt;p&gt;The identifier for the policy version.&lt;/p&gt; &lt;p&gt;Policy version identifiers always begin with &lt;code&gt;v&lt;/code&gt; (always lowercase). When a policy is created, the first policy version is &lt;code&gt;v1&lt;/code&gt;. &lt;/p&gt; |  [optional] |
|**isDefaultVersion** | **Boolean** | Specifies whether the policy version is set as the policy&#39;s default version. |  [optional] |
|**createDate** | **OffsetDateTime** | The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the policy version was created. |  [optional] |



