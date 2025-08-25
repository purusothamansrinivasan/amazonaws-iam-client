

# PasswordPolicy

<p>Contains information about the account password policy.</p> <p> This data type is used as a response element in the <a>GetAccountPasswordPolicy</a> operation. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**minimumPasswordLength** | **Integer** | Minimum length to require for IAM user passwords. |  [optional] |
|**requireSymbols** | **Boolean** | &lt;p&gt;Specifies whether IAM user passwords must contain at least one of the following symbols:&lt;/p&gt; &lt;p&gt;! @ # $ % ^ &amp;amp; * ( ) _ + - &#x3D; [ ] { } | &#39;&lt;/p&gt; |  [optional] |
|**requireNumbers** | **Boolean** | Specifies whether IAM user passwords must contain at least one numeric character (0 to 9). |  [optional] |
|**requireUppercaseCharacters** | **Boolean** | Specifies whether IAM user passwords must contain at least one uppercase character (A to Z). |  [optional] |
|**requireLowercaseCharacters** | **Boolean** | Specifies whether IAM user passwords must contain at least one lowercase character (a to z). |  [optional] |
|**allowUsersToChangePassword** | **Boolean** | Specifies whether IAM users are allowed to change their own password. Gives IAM users permissions to &lt;code&gt;iam:ChangePassword&lt;/code&gt; for only their user and to the &lt;code&gt;iam:GetAccountPasswordPolicy&lt;/code&gt; action. This option does not attach a permissions policy to each user, rather the permissions are applied at the account-level for all users by IAM. |  [optional] |
|**expirePasswords** | **Boolean** | Indicates whether passwords in the account expire. Returns true if &lt;code&gt;MaxPasswordAge&lt;/code&gt; contains a value greater than 0. Returns false if MaxPasswordAge is 0 or not present. |  [optional] |
|**maxPasswordAge** | **Integer** | The number of days that an IAM user password is valid. |  [optional] |
|**passwordReusePrevention** | **Integer** | Specifies the number of previous passwords that IAM users are prevented from reusing. |  [optional] |
|**hardExpiry** | **Boolean** | Specifies whether IAM users are prevented from setting a new password via the Amazon Web Services Management Console after their password has expired. The IAM user cannot access the console until an administrator resets the password. IAM users with &lt;code&gt;iam:ChangePassword&lt;/code&gt; permission and active access keys can reset their own expired console password using the CLI or API. |  [optional] |



