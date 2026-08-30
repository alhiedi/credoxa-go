# OperatorConsumerDeliveryFailure

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveryId** | **string** |  | 
**OrganizationId** | **string** |  | 
**ConsumerId** | **string** |  | 
**ConsumerCode** | **string** |  | 
**ConsumerName** | **string** |  | 
**Status** | **string** |  | 
**AttemptCount** | **int32** |  | 
**MaxAttempts** | **int32** |  | 
**Retryable** | **bool** |  | 
**LastError** | **string** |  | 
**AvailableAt** | **NullableTime** |  | 
**CompletedAt** | **NullableTime** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewOperatorConsumerDeliveryFailure

`func NewOperatorConsumerDeliveryFailure(deliveryId string, organizationId string, consumerId string, consumerCode string, consumerName string, status string, attemptCount int32, maxAttempts int32, retryable bool, lastError string, availableAt NullableTime, completedAt NullableTime, createdAt time.Time, ) *OperatorConsumerDeliveryFailure`

NewOperatorConsumerDeliveryFailure instantiates a new OperatorConsumerDeliveryFailure object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerDeliveryFailureWithDefaults

`func NewOperatorConsumerDeliveryFailureWithDefaults() *OperatorConsumerDeliveryFailure`

NewOperatorConsumerDeliveryFailureWithDefaults instantiates a new OperatorConsumerDeliveryFailure object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveryId

`func (o *OperatorConsumerDeliveryFailure) GetDeliveryId() string`

GetDeliveryId returns the DeliveryId field if non-nil, zero value otherwise.

### GetDeliveryIdOk

`func (o *OperatorConsumerDeliveryFailure) GetDeliveryIdOk() (*string, bool)`

GetDeliveryIdOk returns a tuple with the DeliveryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryId

`func (o *OperatorConsumerDeliveryFailure) SetDeliveryId(v string)`

SetDeliveryId sets DeliveryId field to given value.


### GetOrganizationId

`func (o *OperatorConsumerDeliveryFailure) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorConsumerDeliveryFailure) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorConsumerDeliveryFailure) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetConsumerId

`func (o *OperatorConsumerDeliveryFailure) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorConsumerDeliveryFailure) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorConsumerDeliveryFailure) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetConsumerCode

`func (o *OperatorConsumerDeliveryFailure) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorConsumerDeliveryFailure) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorConsumerDeliveryFailure) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.


### GetConsumerName

`func (o *OperatorConsumerDeliveryFailure) GetConsumerName() string`

GetConsumerName returns the ConsumerName field if non-nil, zero value otherwise.

### GetConsumerNameOk

`func (o *OperatorConsumerDeliveryFailure) GetConsumerNameOk() (*string, bool)`

GetConsumerNameOk returns a tuple with the ConsumerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerName

`func (o *OperatorConsumerDeliveryFailure) SetConsumerName(v string)`

SetConsumerName sets ConsumerName field to given value.


### GetStatus

`func (o *OperatorConsumerDeliveryFailure) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorConsumerDeliveryFailure) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorConsumerDeliveryFailure) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAttemptCount

`func (o *OperatorConsumerDeliveryFailure) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *OperatorConsumerDeliveryFailure) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *OperatorConsumerDeliveryFailure) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.


### GetMaxAttempts

`func (o *OperatorConsumerDeliveryFailure) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorConsumerDeliveryFailure) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorConsumerDeliveryFailure) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetRetryable

`func (o *OperatorConsumerDeliveryFailure) GetRetryable() bool`

GetRetryable returns the Retryable field if non-nil, zero value otherwise.

### GetRetryableOk

`func (o *OperatorConsumerDeliveryFailure) GetRetryableOk() (*bool, bool)`

GetRetryableOk returns a tuple with the Retryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryable

`func (o *OperatorConsumerDeliveryFailure) SetRetryable(v bool)`

SetRetryable sets Retryable field to given value.


### GetLastError

`func (o *OperatorConsumerDeliveryFailure) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *OperatorConsumerDeliveryFailure) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *OperatorConsumerDeliveryFailure) SetLastError(v string)`

SetLastError sets LastError field to given value.


### GetAvailableAt

`func (o *OperatorConsumerDeliveryFailure) GetAvailableAt() time.Time`

GetAvailableAt returns the AvailableAt field if non-nil, zero value otherwise.

### GetAvailableAtOk

`func (o *OperatorConsumerDeliveryFailure) GetAvailableAtOk() (*time.Time, bool)`

GetAvailableAtOk returns a tuple with the AvailableAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableAt

`func (o *OperatorConsumerDeliveryFailure) SetAvailableAt(v time.Time)`

SetAvailableAt sets AvailableAt field to given value.


### SetAvailableAtNil

`func (o *OperatorConsumerDeliveryFailure) SetAvailableAtNil(b bool)`

 SetAvailableAtNil sets the value for AvailableAt to be an explicit nil

### UnsetAvailableAt
`func (o *OperatorConsumerDeliveryFailure) UnsetAvailableAt()`

UnsetAvailableAt ensures that no value is present for AvailableAt, not even an explicit nil
### GetCompletedAt

`func (o *OperatorConsumerDeliveryFailure) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *OperatorConsumerDeliveryFailure) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *OperatorConsumerDeliveryFailure) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *OperatorConsumerDeliveryFailure) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *OperatorConsumerDeliveryFailure) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *OperatorConsumerDeliveryFailure) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorConsumerDeliveryFailure) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorConsumerDeliveryFailure) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


