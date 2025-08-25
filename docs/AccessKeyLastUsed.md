

# AccessKeyLastUsed

<p>Contains information about the last time an Amazon Web Services access key was used since IAM began tracking this information on April 22, 2015.</p> <p>This data type is used as a response element in the <a>GetAccessKeyLastUsed</a> operation.</p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**lastUsedDate** | **OffsetDateTime** | &lt;p&gt;The date and time, in &lt;a href&#x3D;\&quot;http://www.iso.org/iso/iso8601\&quot;&gt;ISO 8601 date-time format&lt;/a&gt;, when the access key was most recently used. This field is null in the following situations:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;The user does not have an access key.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;An access key exists but has not been used since IAM began tracking this information.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;There is no sign-in data associated with the user.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**serviceName** | **String** | &lt;p&gt;The name of the Amazon Web Services service with which this access key was most recently used. The value of this field is \&quot;N/A\&quot; in the following situations:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;The user does not have an access key.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;An access key exists but has not been used since IAM started tracking this information.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;There is no sign-in data associated with the user.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; |  |
|**region** | **String** | &lt;p&gt;The Amazon Web Services Region where this access key was most recently used. The value for this field is \&quot;N/A\&quot; in the following situations:&lt;/p&gt; &lt;ul&gt; &lt;li&gt; &lt;p&gt;The user does not have an access key.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;An access key exists but has not been used since IAM began tracking this information.&lt;/p&gt; &lt;/li&gt; &lt;li&gt; &lt;p&gt;There is no sign-in data associated with the user.&lt;/p&gt; &lt;/li&gt; &lt;/ul&gt; &lt;p&gt;For more information about Amazon Web Services Regions, see &lt;a href&#x3D;\&quot;https://docs.aws.amazon.com/general/latest/gr/rande.html\&quot;&gt;Regions and endpoints&lt;/a&gt; in the Amazon Web Services General Reference.&lt;/p&gt; |  |



