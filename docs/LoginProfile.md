

# LoginProfile

<p>Contains the user name and password create date for a user.</p> <p> This data type is used as a response element in the <a>CreateLoginProfile</a> and <a>GetLoginProfile</a> operations. </p>

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**userName** | **String** | The name of the user, which can be used for signing in to the Amazon Web Services Management Console. |  |
|**createDate** | **OffsetDateTime** | The date when the password for the user was created. |  |
|**passwordResetRequired** | **Boolean** | Specifies whether the user is required to set a new password on next sign-in. |  [optional] |



