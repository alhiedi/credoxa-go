# RecoveryRetryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedRevision** | **int32** |  | 
**IdempotencyKey** | **string** |  | 
**CorrelationId** | Pointer to **string** |  | [optional] 

## Methods

### NewRecoveryRetryRequest

`func NewRecoveryRetryRequest(expectedRevision int32, idempotencyKey string, ) *RecoveryRetryRequest`

NewRecoveryRetryRequest instantiates a new RecoveryRetryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecoveryRetryRequestWithDefaults

`func NewRecoveryRetryRequestWithDefaults() *RecoveryRetryRequest`

NewRecoveryRetryRequestWithDefaults instantiates a new RecoveryRetryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedRevision

`func (o *RecoveryRetryRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *RecoveryRetryRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *RecoveryRetryRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetIdempotencyKey

`func (o *RecoveryRetryRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *RecoveryRetryRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *RecoveryRetryRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetCorrelationId

`func (o *RecoveryRetryRequest) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *RecoveryRetryRequest) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *RecoveryRetryRequest) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *RecoveryRetryRequest) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


