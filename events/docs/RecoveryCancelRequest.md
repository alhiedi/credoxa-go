# RecoveryCancelRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedRevision** | **int32** |  | 
**Reason** | **string** |  | 
**CorrelationId** | Pointer to **string** |  | [optional] 

## Methods

### NewRecoveryCancelRequest

`func NewRecoveryCancelRequest(expectedRevision int32, reason string, ) *RecoveryCancelRequest`

NewRecoveryCancelRequest instantiates a new RecoveryCancelRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecoveryCancelRequestWithDefaults

`func NewRecoveryCancelRequestWithDefaults() *RecoveryCancelRequest`

NewRecoveryCancelRequestWithDefaults instantiates a new RecoveryCancelRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedRevision

`func (o *RecoveryCancelRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *RecoveryCancelRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *RecoveryCancelRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetReason

`func (o *RecoveryCancelRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RecoveryCancelRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RecoveryCancelRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetCorrelationId

`func (o *RecoveryCancelRequest) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *RecoveryCancelRequest) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *RecoveryCancelRequest) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *RecoveryCancelRequest) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


