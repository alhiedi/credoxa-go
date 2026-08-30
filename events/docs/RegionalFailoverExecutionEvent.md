# RegionalFailoverExecutionEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Sequence** | **int64** |  | 
**EventType** | [**RegionalFailoverExecutionEventEventTypeEnum**](RegionalFailoverExecutionEventEventTypeEnum.md) |  | 
**Actor** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Payload** | Pointer to **interface{}** |  | [optional] 
**OccurredAt** | **time.Time** |  | [readonly] 

## Methods

### NewRegionalFailoverExecutionEvent

`func NewRegionalFailoverExecutionEvent(id string, sequence int64, eventType RegionalFailoverExecutionEventEventTypeEnum, occurredAt time.Time, ) *RegionalFailoverExecutionEvent`

NewRegionalFailoverExecutionEvent instantiates a new RegionalFailoverExecutionEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverExecutionEventWithDefaults

`func NewRegionalFailoverExecutionEventWithDefaults() *RegionalFailoverExecutionEvent`

NewRegionalFailoverExecutionEventWithDefaults instantiates a new RegionalFailoverExecutionEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverExecutionEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverExecutionEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverExecutionEvent) SetId(v string)`

SetId sets Id field to given value.


### GetSequence

`func (o *RegionalFailoverExecutionEvent) GetSequence() int64`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *RegionalFailoverExecutionEvent) GetSequenceOk() (*int64, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *RegionalFailoverExecutionEvent) SetSequence(v int64)`

SetSequence sets Sequence field to given value.


### GetEventType

`func (o *RegionalFailoverExecutionEvent) GetEventType() RegionalFailoverExecutionEventEventTypeEnum`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *RegionalFailoverExecutionEvent) GetEventTypeOk() (*RegionalFailoverExecutionEventEventTypeEnum, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *RegionalFailoverExecutionEvent) SetEventType(v RegionalFailoverExecutionEventEventTypeEnum)`

SetEventType sets EventType field to given value.


### GetActor

`func (o *RegionalFailoverExecutionEvent) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *RegionalFailoverExecutionEvent) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *RegionalFailoverExecutionEvent) SetActor(v string)`

SetActor sets Actor field to given value.

### HasActor

`func (o *RegionalFailoverExecutionEvent) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetMessage

`func (o *RegionalFailoverExecutionEvent) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionalFailoverExecutionEvent) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionalFailoverExecutionEvent) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegionalFailoverExecutionEvent) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetPayload

`func (o *RegionalFailoverExecutionEvent) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *RegionalFailoverExecutionEvent) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *RegionalFailoverExecutionEvent) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *RegionalFailoverExecutionEvent) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *RegionalFailoverExecutionEvent) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *RegionalFailoverExecutionEvent) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetOccurredAt

`func (o *RegionalFailoverExecutionEvent) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *RegionalFailoverExecutionEvent) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *RegionalFailoverExecutionEvent) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


