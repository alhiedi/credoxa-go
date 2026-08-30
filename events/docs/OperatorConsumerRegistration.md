# OperatorConsumerRegistration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**Code** | **string** |  | 
**Name** | **string** |  | 
**OwnerService** | **string** |  | 
**Status** | **string** |  | 
**QueueName** | **string** |  | 
**DeadLetterExchange** | **string** |  | 
**DeadLetterQueue** | **string** |  | 
**MaxAttempts** | **int32** |  | 
**RetryBaseSeconds** | **int32** |  | 
**RetryMaxSeconds** | **int32** |  | 
**ProcessingTimeoutSeconds** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewOperatorConsumerRegistration

`func NewOperatorConsumerRegistration(id string, organizationId string, code string, name string, ownerService string, status string, queueName string, deadLetterExchange string, deadLetterQueue string, maxAttempts int32, retryBaseSeconds int32, retryMaxSeconds int32, processingTimeoutSeconds int32, createdAt time.Time, updatedAt time.Time, ) *OperatorConsumerRegistration`

NewOperatorConsumerRegistration instantiates a new OperatorConsumerRegistration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerRegistrationWithDefaults

`func NewOperatorConsumerRegistrationWithDefaults() *OperatorConsumerRegistration`

NewOperatorConsumerRegistrationWithDefaults instantiates a new OperatorConsumerRegistration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorConsumerRegistration) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorConsumerRegistration) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorConsumerRegistration) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *OperatorConsumerRegistration) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorConsumerRegistration) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorConsumerRegistration) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetCode

`func (o *OperatorConsumerRegistration) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OperatorConsumerRegistration) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OperatorConsumerRegistration) SetCode(v string)`

SetCode sets Code field to given value.


### GetName

`func (o *OperatorConsumerRegistration) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OperatorConsumerRegistration) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OperatorConsumerRegistration) SetName(v string)`

SetName sets Name field to given value.


### GetOwnerService

`func (o *OperatorConsumerRegistration) GetOwnerService() string`

GetOwnerService returns the OwnerService field if non-nil, zero value otherwise.

### GetOwnerServiceOk

`func (o *OperatorConsumerRegistration) GetOwnerServiceOk() (*string, bool)`

GetOwnerServiceOk returns a tuple with the OwnerService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerService

`func (o *OperatorConsumerRegistration) SetOwnerService(v string)`

SetOwnerService sets OwnerService field to given value.


### GetStatus

`func (o *OperatorConsumerRegistration) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorConsumerRegistration) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorConsumerRegistration) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetQueueName

`func (o *OperatorConsumerRegistration) GetQueueName() string`

GetQueueName returns the QueueName field if non-nil, zero value otherwise.

### GetQueueNameOk

`func (o *OperatorConsumerRegistration) GetQueueNameOk() (*string, bool)`

GetQueueNameOk returns a tuple with the QueueName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueueName

`func (o *OperatorConsumerRegistration) SetQueueName(v string)`

SetQueueName sets QueueName field to given value.


### GetDeadLetterExchange

`func (o *OperatorConsumerRegistration) GetDeadLetterExchange() string`

GetDeadLetterExchange returns the DeadLetterExchange field if non-nil, zero value otherwise.

### GetDeadLetterExchangeOk

`func (o *OperatorConsumerRegistration) GetDeadLetterExchangeOk() (*string, bool)`

GetDeadLetterExchangeOk returns a tuple with the DeadLetterExchange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetterExchange

`func (o *OperatorConsumerRegistration) SetDeadLetterExchange(v string)`

SetDeadLetterExchange sets DeadLetterExchange field to given value.


### GetDeadLetterQueue

`func (o *OperatorConsumerRegistration) GetDeadLetterQueue() string`

GetDeadLetterQueue returns the DeadLetterQueue field if non-nil, zero value otherwise.

### GetDeadLetterQueueOk

`func (o *OperatorConsumerRegistration) GetDeadLetterQueueOk() (*string, bool)`

GetDeadLetterQueueOk returns a tuple with the DeadLetterQueue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetterQueue

`func (o *OperatorConsumerRegistration) SetDeadLetterQueue(v string)`

SetDeadLetterQueue sets DeadLetterQueue field to given value.


### GetMaxAttempts

`func (o *OperatorConsumerRegistration) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorConsumerRegistration) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorConsumerRegistration) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetRetryBaseSeconds

`func (o *OperatorConsumerRegistration) GetRetryBaseSeconds() int32`

GetRetryBaseSeconds returns the RetryBaseSeconds field if non-nil, zero value otherwise.

### GetRetryBaseSecondsOk

`func (o *OperatorConsumerRegistration) GetRetryBaseSecondsOk() (*int32, bool)`

GetRetryBaseSecondsOk returns a tuple with the RetryBaseSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryBaseSeconds

`func (o *OperatorConsumerRegistration) SetRetryBaseSeconds(v int32)`

SetRetryBaseSeconds sets RetryBaseSeconds field to given value.


### GetRetryMaxSeconds

`func (o *OperatorConsumerRegistration) GetRetryMaxSeconds() int32`

GetRetryMaxSeconds returns the RetryMaxSeconds field if non-nil, zero value otherwise.

### GetRetryMaxSecondsOk

`func (o *OperatorConsumerRegistration) GetRetryMaxSecondsOk() (*int32, bool)`

GetRetryMaxSecondsOk returns a tuple with the RetryMaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryMaxSeconds

`func (o *OperatorConsumerRegistration) SetRetryMaxSeconds(v int32)`

SetRetryMaxSeconds sets RetryMaxSeconds field to given value.


### GetProcessingTimeoutSeconds

`func (o *OperatorConsumerRegistration) GetProcessingTimeoutSeconds() int32`

GetProcessingTimeoutSeconds returns the ProcessingTimeoutSeconds field if non-nil, zero value otherwise.

### GetProcessingTimeoutSecondsOk

`func (o *OperatorConsumerRegistration) GetProcessingTimeoutSecondsOk() (*int32, bool)`

GetProcessingTimeoutSecondsOk returns a tuple with the ProcessingTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTimeoutSeconds

`func (o *OperatorConsumerRegistration) SetProcessingTimeoutSeconds(v int32)`

SetProcessingTimeoutSeconds sets ProcessingTimeoutSeconds field to given value.


### GetCreatedAt

`func (o *OperatorConsumerRegistration) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorConsumerRegistration) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorConsumerRegistration) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorConsumerRegistration) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorConsumerRegistration) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorConsumerRegistration) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


