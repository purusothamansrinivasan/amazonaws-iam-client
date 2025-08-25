

# Tag

A structure that represents user-provided metadata that can be associated with an IAM resource. For more information about tagging, see <a href=\"https://docs.aws.amazon.com/IAM/latest/UserGuide/id_tags.html\">Tagging IAM resources</a> in the <i>IAM User Guide</i>.

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**key** | **String** | The key name that can be used to look up or retrieve the associated value. For example, &lt;code&gt;Department&lt;/code&gt; or &lt;code&gt;Cost Center&lt;/code&gt; are common choices. |  |
|**value** | **String** | &lt;p&gt;The value associated with this tag. For example, tags with a key name of &lt;code&gt;Department&lt;/code&gt; could have values such as &lt;code&gt;Human Resources&lt;/code&gt;, &lt;code&gt;Accounting&lt;/code&gt;, and &lt;code&gt;Support&lt;/code&gt;. Tags with a key name of &lt;code&gt;Cost Center&lt;/code&gt; might have values that consist of the number associated with the different cost centers in your company. Typically, many resources have tags with the same key name but with different values.&lt;/p&gt; &lt;note&gt; &lt;p&gt;Amazon Web Services always interprets the tag &lt;code&gt;Value&lt;/code&gt; as a single string. If you need to store an array, you can store comma-separated values in the string. However, you must interpret the value in your code.&lt;/p&gt; &lt;/note&gt; |  |



