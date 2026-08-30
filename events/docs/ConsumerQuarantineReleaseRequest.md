# ConsumerQuarantineReleaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedRevision** | **int32** |  | 
**Reason** | **string** |  | 
**Force** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewConsumerQuarantineReleaseRequest

`func NewConsumerQuarantineReleaseRequest(expectedRevision int32, reason string, ) *ConsumerQuarantineReleaseRequest`

NewConsumerQuarantineReleaseRequest instantiates a new ConsumerQuarantineReleaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConsumerQuarantineReleaseRequestWithDefaults

`func NewConsumerQuarantineReleaseRequestWithDefaults() *ConsumerQuarantineReleaseRequest`

NewConsumerQuarantineReleaseRequestWithDefaults instantiates a new ConsumerQuarantineReleaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedRevision

`func (o *ConsumerQuarantineReleaseRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *ConsumerQuarantineReleaseRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *ConsumerQuarantineReleaseRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetReason

`func (o *ConsumerQuarantineReleaseRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ConsumerQuarantineReleaseRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ConsumerQuarantineReleaseRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetForce

`func (o *ConsumerQuarantineReleaseRequest) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *ConsumerQuarantineReleaseRequest) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *ConsumerQuarantineReleaseRequest) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *ConsumerQuarantineReleaseRequest) HasForce() bool`

HasForce returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


