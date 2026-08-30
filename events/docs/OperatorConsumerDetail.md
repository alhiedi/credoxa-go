# OperatorConsumerDetail

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
**Bindings** | [**[]OperatorConsumerBinding**](OperatorConsumerBinding.md) |  | 

## Methods

### NewOperatorConsumerDetail

`func NewOperatorConsumerDetail(id string, organizationId string, code string, name string, ownerService string, status string, queueName string, deadLetterExchange string, deadLetterQueue string, maxAttempts int32, retryBaseSeconds int32, retryMaxSeconds int32, processingTimeoutSeconds int32, createdAt time.Time, updatedAt time.Time, bindings []OperatorConsumerBinding, ) *OperatorConsumerDetail`

NewOperatorConsumerDetail instantiates a new OperatorConsumerDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerDetailWithDefaults

`func NewOperatorConsumerDetailWithDefaults() *OperatorConsumerDetail`

NewOperatorConsumerDetailWithDefaults instantiates a new OperatorConsumerDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorConsumerDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorConsumerDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorConsumerDetail) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *OperatorConsumerDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorConsumerDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorConsumerDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetCode

`func (o *OperatorConsumerDetail) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OperatorConsumerDetail) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OperatorConsumerDetail) SetCode(v string)`

SetCode sets Code field to given value.


### GetName

`func (o *OperatorConsumerDetail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OperatorConsumerDetail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OperatorConsumerDetail) SetName(v string)`

SetName sets Name field to given value.


### GetOwnerService

`func (o *OperatorConsumerDetail) GetOwnerService() string`

GetOwnerService returns the OwnerService field if non-nil, zero value otherwise.

### GetOwnerServiceOk

`func (o *OperatorConsumerDetail) GetOwnerServiceOk() (*string, bool)`

GetOwnerServiceOk returns a tuple with the OwnerService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerService

`func (o *OperatorConsumerDetail) SetOwnerService(v string)`

SetOwnerService sets OwnerService field to given value.


### GetStatus

`func (o *OperatorConsumerDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorConsumerDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorConsumerDetail) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetQueueName

`func (o *OperatorConsumerDetail) GetQueueName() string`

GetQueueName returns the QueueName field if non-nil, zero value otherwise.

### GetQueueNameOk

`func (o *OperatorConsumerDetail) GetQueueNameOk() (*string, bool)`

GetQueueNameOk returns a tuple with the QueueName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueueName

`func (o *OperatorConsumerDetail) SetQueueName(v string)`

SetQueueName sets QueueName field to given value.


### GetDeadLetterExchange

`func (o *OperatorConsumerDetail) GetDeadLetterExchange() string`

GetDeadLetterExchange returns the DeadLetterExchange field if non-nil, zero value otherwise.

### GetDeadLetterExchangeOk

`func (o *OperatorConsumerDetail) GetDeadLetterExchangeOk() (*string, bool)`

GetDeadLetterExchangeOk returns a tuple with the DeadLetterExchange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetterExchange

`func (o *OperatorConsumerDetail) SetDeadLetterExchange(v string)`

SetDeadLetterExchange sets DeadLetterExchange field to given value.


### GetDeadLetterQueue

`func (o *OperatorConsumerDetail) GetDeadLetterQueue() string`

GetDeadLetterQueue returns the DeadLetterQueue field if non-nil, zero value otherwise.

### GetDeadLetterQueueOk

`func (o *OperatorConsumerDetail) GetDeadLetterQueueOk() (*string, bool)`

GetDeadLetterQueueOk returns a tuple with the DeadLetterQueue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetterQueue

`func (o *OperatorConsumerDetail) SetDeadLetterQueue(v string)`

SetDeadLetterQueue sets DeadLetterQueue field to given value.


### GetMaxAttempts

`func (o *OperatorConsumerDetail) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorConsumerDetail) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorConsumerDetail) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetRetryBaseSeconds

`func (o *OperatorConsumerDetail) GetRetryBaseSeconds() int32`

GetRetryBaseSeconds returns the RetryBaseSeconds field if non-nil, zero value otherwise.

### GetRetryBaseSecondsOk

`func (o *OperatorConsumerDetail) GetRetryBaseSecondsOk() (*int32, bool)`

GetRetryBaseSecondsOk returns a tuple with the RetryBaseSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryBaseSeconds

`func (o *OperatorConsumerDetail) SetRetryBaseSeconds(v int32)`

SetRetryBaseSeconds sets RetryBaseSeconds field to given value.


### GetRetryMaxSeconds

`func (o *OperatorConsumerDetail) GetRetryMaxSeconds() int32`

GetRetryMaxSeconds returns the RetryMaxSeconds field if non-nil, zero value otherwise.

### GetRetryMaxSecondsOk

`func (o *OperatorConsumerDetail) GetRetryMaxSecondsOk() (*int32, bool)`

GetRetryMaxSecondsOk returns a tuple with the RetryMaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryMaxSeconds

`func (o *OperatorConsumerDetail) SetRetryMaxSeconds(v int32)`

SetRetryMaxSeconds sets RetryMaxSeconds field to given value.


### GetProcessingTimeoutSeconds

`func (o *OperatorConsumerDetail) GetProcessingTimeoutSeconds() int32`

GetProcessingTimeoutSeconds returns the ProcessingTimeoutSeconds field if non-nil, zero value otherwise.

### GetProcessingTimeoutSecondsOk

`func (o *OperatorConsumerDetail) GetProcessingTimeoutSecondsOk() (*int32, bool)`

GetProcessingTimeoutSecondsOk returns a tuple with the ProcessingTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTimeoutSeconds

`func (o *OperatorConsumerDetail) SetProcessingTimeoutSeconds(v int32)`

SetProcessingTimeoutSeconds sets ProcessingTimeoutSeconds field to given value.


### GetCreatedAt

`func (o *OperatorConsumerDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorConsumerDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorConsumerDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorConsumerDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorConsumerDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorConsumerDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetBindings

`func (o *OperatorConsumerDetail) GetBindings() []OperatorConsumerBinding`

GetBindings returns the Bindings field if non-nil, zero value otherwise.

### GetBindingsOk

`func (o *OperatorConsumerDetail) GetBindingsOk() (*[]OperatorConsumerBinding, bool)`

GetBindingsOk returns a tuple with the Bindings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindings

`func (o *OperatorConsumerDetail) SetBindings(v []OperatorConsumerBinding)`

SetBindings sets Bindings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


