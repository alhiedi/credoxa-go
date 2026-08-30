# FailoverSafetyDecisionEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sequence** | **int32** |  | 
**EventType** | **string** |  | 
**Actor** | **string** |  | 
**Reason** | **string** |  | 
**Payload** | **interface{}** |  | 
**OccurredAt** | **time.Time** |  | 

## Methods

### NewFailoverSafetyDecisionEvent

`func NewFailoverSafetyDecisionEvent(sequence int32, eventType string, actor string, reason string, payload interface{}, occurredAt time.Time, ) *FailoverSafetyDecisionEvent`

NewFailoverSafetyDecisionEvent instantiates a new FailoverSafetyDecisionEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFailoverSafetyDecisionEventWithDefaults

`func NewFailoverSafetyDecisionEventWithDefaults() *FailoverSafetyDecisionEvent`

NewFailoverSafetyDecisionEventWithDefaults instantiates a new FailoverSafetyDecisionEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSequence

`func (o *FailoverSafetyDecisionEvent) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *FailoverSafetyDecisionEvent) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *FailoverSafetyDecisionEvent) SetSequence(v int32)`

SetSequence sets Sequence field to given value.


### GetEventType

`func (o *FailoverSafetyDecisionEvent) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *FailoverSafetyDecisionEvent) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *FailoverSafetyDecisionEvent) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetActor

`func (o *FailoverSafetyDecisionEvent) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *FailoverSafetyDecisionEvent) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *FailoverSafetyDecisionEvent) SetActor(v string)`

SetActor sets Actor field to given value.


### GetReason

`func (o *FailoverSafetyDecisionEvent) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *FailoverSafetyDecisionEvent) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *FailoverSafetyDecisionEvent) SetReason(v string)`

SetReason sets Reason field to given value.


### GetPayload

`func (o *FailoverSafetyDecisionEvent) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *FailoverSafetyDecisionEvent) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *FailoverSafetyDecisionEvent) SetPayload(v interface{})`

SetPayload sets Payload field to given value.


### SetPayloadNil

`func (o *FailoverSafetyDecisionEvent) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *FailoverSafetyDecisionEvent) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetOccurredAt

`func (o *FailoverSafetyDecisionEvent) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *FailoverSafetyDecisionEvent) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *FailoverSafetyDecisionEvent) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


