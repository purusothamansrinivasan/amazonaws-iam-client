

# GenerateServiceLastAccessedDetailsRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**arn** | **String** | The ARN of the IAM resource (user, group, role, or managed policy) used to generate information about when the resource was last used in an attempt to access an Amazon Web Services service. |  |
|**granularity** | **AccessAdvisorUsageGranularityType** | The level of detail that you want to generate. You can specify whether you want to generate information about the last attempt to access services or actions. If you specify service-level granularity, this operation generates only service data. If you specify action-level granularity, it generates service and action data. If you don&#39;t include this optional parameter, the operation generates service data. |  [optional] |



