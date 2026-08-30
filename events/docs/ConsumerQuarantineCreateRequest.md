# ConsumerQuarantineCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | **string** |  | 
**ReasonCode** | **string** |  | 
**Reason** | **string** |  | 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**ExpectedRevision** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewConsumerQuarantineCreateRequest

`func NewConsumerQuarantineCreateRequest(consumerId string, reasonCode string, reason string, ) *ConsumerQuarantineCreateRequest`

NewConsumerQuarantineCreateRequest instantiates a new ConsumerQuarantineCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConsumerQuarantineCreateRequestWithDefaults

`func NewConsumerQuarantineCreateRequestWithDefaults() *ConsumerQuarantineCreateRequest`

NewConsumerQuarantineCreateRequestWithDefaults instantiates a new ConsumerQuarantineCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *ConsumerQuarantineCreateRequest) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *ConsumerQuarantineCreateRequest) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *ConsumerQuarantineCreateRequest) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetReasonCode

`func (o *ConsumerQuarantineCreateRequest) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *ConsumerQuarantineCreateRequest) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *ConsumerQuarantineCreateRequest) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.


### GetReason

`func (o *ConsumerQuarantineCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ConsumerQuarantineCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ConsumerQuarantineCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetEvidence

`func (o *ConsumerQuarantineCreateRequest) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *ConsumerQuarantineCreateRequest) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *ConsumerQuarantineCreateRequest) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *ConsumerQuarantineCreateRequest) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *ConsumerQuarantineCreateRequest) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *ConsumerQuarantineCreateRequest) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetExpectedRevision

`func (o *ConsumerQuarantineCreateRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *ConsumerQuarantineCreateRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *ConsumerQuarantineCreateRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.

### HasExpectedRevision

`func (o *ConsumerQuarantineCreateRequest) HasExpectedRevision() bool`

HasExpectedRevision returns a boolean if a field has been set.

### SetExpectedRevisionNil

`func (o *ConsumerQuarantineCreateRequest) SetExpectedRevisionNil(b bool)`

 SetExpectedRevisionNil sets the value for ExpectedRevision to be an explicit nil

### UnsetExpectedRevision
`func (o *ConsumerQuarantineCreateRequest) UnsetExpectedRevision()`

UnsetExpectedRevision ensures that no value is present for ExpectedRevision, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


