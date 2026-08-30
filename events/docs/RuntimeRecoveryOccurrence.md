# RuntimeRecoveryOccurrence

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Sequence** | **int64** |  | 
**EventType** | **string** |  | 
**Payload** | Pointer to **interface{}** |  | [optional] 
**CorrelationId** | **string** |  | 
**OccurredAt** | **time.Time** |  | 

## Methods

### NewRuntimeRecoveryOccurrence

`func NewRuntimeRecoveryOccurrence(id string, sequence int64, eventType string, correlationId string, occurredAt time.Time, ) *RuntimeRecoveryOccurrence`

NewRuntimeRecoveryOccurrence instantiates a new RuntimeRecoveryOccurrence object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeRecoveryOccurrenceWithDefaults

`func NewRuntimeRecoveryOccurrenceWithDefaults() *RuntimeRecoveryOccurrence`

NewRuntimeRecoveryOccurrenceWithDefaults instantiates a new RuntimeRecoveryOccurrence object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RuntimeRecoveryOccurrence) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RuntimeRecoveryOccurrence) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RuntimeRecoveryOccurrence) SetId(v string)`

SetId sets Id field to given value.


### GetSequence

`func (o *RuntimeRecoveryOccurrence) GetSequence() int64`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *RuntimeRecoveryOccurrence) GetSequenceOk() (*int64, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *RuntimeRecoveryOccurrence) SetSequence(v int64)`

SetSequence sets Sequence field to given value.


### GetEventType

`func (o *RuntimeRecoveryOccurrence) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *RuntimeRecoveryOccurrence) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *RuntimeRecoveryOccurrence) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetPayload

`func (o *RuntimeRecoveryOccurrence) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *RuntimeRecoveryOccurrence) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *RuntimeRecoveryOccurrence) SetPayload(v interface{})`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *RuntimeRecoveryOccurrence) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *RuntimeRecoveryOccurrence) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *RuntimeRecoveryOccurrence) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetCorrelationId

`func (o *RuntimeRecoveryOccurrence) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *RuntimeRecoveryOccurrence) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *RuntimeRecoveryOccurrence) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetOccurredAt

`func (o *RuntimeRecoveryOccurrence) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *RuntimeRecoveryOccurrence) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *RuntimeRecoveryOccurrence) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


