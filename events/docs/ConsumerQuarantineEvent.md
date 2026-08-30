# ConsumerQuarantineEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Sequence** | **int64** |  | 
**EventType** | [**ConsumerQuarantineEventEventTypeEnum**](ConsumerQuarantineEventEventTypeEnum.md) |  | 
**Actor** | Pointer to **NullableString** |  | [optional] 
**ReasonCode** | Pointer to **NullableString** |  | [optional] 
**Payload** | Pointer to **interface{}** |  | [optional] 
**OccurredAt** | Pointer to **time.Time** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewConsumerQuarantineEvent

`func NewConsumerQuarantineEvent(id string, sequence int64, eventType ConsumerQuarantineEventEventTypeEnum, createdAt time.Time, ) *ConsumerQuarantineEvent`

NewConsumerQuarantineEvent instantiates a new ConsumerQuarantineEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConsumerQuarantineEventWithDefaults

`func NewConsumerQuarantineEventWithDefaults() *ConsumerQuarantineEvent`

NewConsumerQuarantineEventWithDefaults instantiates a new ConsumerQuarantineEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ConsumerQuarantineEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConsumerQuarantineEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConsumerQuarantineEvent) SetId(v string)`

SetId sets Id field to given value.


### GetSequence

`func (o *ConsumerQuarantineEvent) GetSequence() int64`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *ConsumerQuarantineEvent) GetSequenceOk() (*int64, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *ConsumerQuarantineEvent) SetSequence(v int64)`

SetSequence sets Sequence field to given value.


### GetEventType

`func (o *ConsumerQuarantineEvent) GetEventType() ConsumerQuarantineEventEventTypeEnum`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *ConsumerQuarantineEvent) GetEventTypeOk() (*ConsumerQuarantineEventEventTypeEnum, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *ConsumerQuarantineEvent) SetEventType(v ConsumerQuarantineEventEventTypeEnum)`

SetEventType sets EventType field to given value.


### GetActor

`func (o *ConsumerQuarantineEvent) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *ConsumerQuarantineEvent) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *ConsumerQuarantineEvent) SetActor(v string)`

SetActor sets Actor field to given value.

### HasActor

`func (o *ConsumerQuarantineEvent) HasActor() bool`

HasActor returns a boolean if a field has been set.

### SetActorNil

`func (o *ConsumerQuarantineEvent) SetActorNil(b bool)`

 SetActorNil sets the value for Actor to be an explicit nil

### UnsetActor
`func (o *ConsumerQuarantineEvent) UnsetActor()`

UnsetActor ensures that no value is present for Actor, not even an explicit nil
### GetReasonCode

`func (o *ConsumerQuarantineEvent) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *ConsumerQuarantineEvent) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *ConsumerQuarantineEvent) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.

### HasReasonCode

`func (o *ConsumerQuarantineEvent) HasReasonCode() bool`

HasReasonCode returns a boolean if a field has been set.

### SetReasonCodeNil

`func (o *ConsumerQuarantineEvent) SetReasonCodeNil(b bool)`

 SetReasonCodeNil sets the value for ReasonCode to be an explicit nil

### UnsetReasonCode
`func (o *ConsumerQuarantineEvent) UnsetReasonCode()`

UnsetReasonCode ensures that no value is present for ReasonCode, not even an explicit nil
### GetPayload

`func (o *ConsumerQuarantineEvent) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *ConsumerQuarantineEvent) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *ConsumerQuarantineEvent) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *ConsumerQuarantineEvent) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *ConsumerQuarantineEvent) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *ConsumerQuarantineEvent) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetOccurredAt

`func (o *ConsumerQuarantineEvent) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *ConsumerQuarantineEvent) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *ConsumerQuarantineEvent) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *ConsumerQuarantineEvent) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ConsumerQuarantineEvent) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ConsumerQuarantineEvent) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ConsumerQuarantineEvent) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


