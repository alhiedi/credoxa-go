# OperatorRuntimeIncidentOccurrence

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Sequence** | **int64** |  | 
**Kind** | [**RuntimeIncidentOccurrenceKindEnum**](RuntimeIncidentOccurrenceKindEnum.md) |  | 
**Severity** | [**RuntimeIncidentSeverityEnum**](RuntimeIncidentSeverityEnum.md) |  | 
**ObservedValue** | Pointer to **NullableFloat64** |  | [optional] 
**AggregatedValue** | Pointer to **NullableFloat64** |  | [optional] 
**Threshold** | Pointer to **NullableFloat64** |  | [optional] 
**Actor** | Pointer to **string** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Context** | Pointer to **interface{}** |  | [optional] 
**OccurredAt** | **time.Time** |  | 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewOperatorRuntimeIncidentOccurrence

`func NewOperatorRuntimeIncidentOccurrence(id string, sequence int64, kind RuntimeIncidentOccurrenceKindEnum, severity RuntimeIncidentSeverityEnum, occurredAt time.Time, createdAt time.Time, ) *OperatorRuntimeIncidentOccurrence`

NewOperatorRuntimeIncidentOccurrence instantiates a new OperatorRuntimeIncidentOccurrence object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentOccurrenceWithDefaults

`func NewOperatorRuntimeIncidentOccurrenceWithDefaults() *OperatorRuntimeIncidentOccurrence`

NewOperatorRuntimeIncidentOccurrenceWithDefaults instantiates a new OperatorRuntimeIncidentOccurrence object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorRuntimeIncidentOccurrence) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorRuntimeIncidentOccurrence) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorRuntimeIncidentOccurrence) SetId(v string)`

SetId sets Id field to given value.


### GetSequence

`func (o *OperatorRuntimeIncidentOccurrence) GetSequence() int64`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *OperatorRuntimeIncidentOccurrence) GetSequenceOk() (*int64, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *OperatorRuntimeIncidentOccurrence) SetSequence(v int64)`

SetSequence sets Sequence field to given value.


### GetKind

`func (o *OperatorRuntimeIncidentOccurrence) GetKind() RuntimeIncidentOccurrenceKindEnum`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *OperatorRuntimeIncidentOccurrence) GetKindOk() (*RuntimeIncidentOccurrenceKindEnum, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *OperatorRuntimeIncidentOccurrence) SetKind(v RuntimeIncidentOccurrenceKindEnum)`

SetKind sets Kind field to given value.


### GetSeverity

`func (o *OperatorRuntimeIncidentOccurrence) GetSeverity() RuntimeIncidentSeverityEnum`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeIncidentOccurrence) GetSeverityOk() (*RuntimeIncidentSeverityEnum, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeIncidentOccurrence) SetSeverity(v RuntimeIncidentSeverityEnum)`

SetSeverity sets Severity field to given value.


### GetObservedValue

`func (o *OperatorRuntimeIncidentOccurrence) GetObservedValue() float64`

GetObservedValue returns the ObservedValue field if non-nil, zero value otherwise.

### GetObservedValueOk

`func (o *OperatorRuntimeIncidentOccurrence) GetObservedValueOk() (*float64, bool)`

GetObservedValueOk returns a tuple with the ObservedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedValue

`func (o *OperatorRuntimeIncidentOccurrence) SetObservedValue(v float64)`

SetObservedValue sets ObservedValue field to given value.

### HasObservedValue

`func (o *OperatorRuntimeIncidentOccurrence) HasObservedValue() bool`

HasObservedValue returns a boolean if a field has been set.

### SetObservedValueNil

`func (o *OperatorRuntimeIncidentOccurrence) SetObservedValueNil(b bool)`

 SetObservedValueNil sets the value for ObservedValue to be an explicit nil

### UnsetObservedValue
`func (o *OperatorRuntimeIncidentOccurrence) UnsetObservedValue()`

UnsetObservedValue ensures that no value is present for ObservedValue, not even an explicit nil
### GetAggregatedValue

`func (o *OperatorRuntimeIncidentOccurrence) GetAggregatedValue() float64`

GetAggregatedValue returns the AggregatedValue field if non-nil, zero value otherwise.

### GetAggregatedValueOk

`func (o *OperatorRuntimeIncidentOccurrence) GetAggregatedValueOk() (*float64, bool)`

GetAggregatedValueOk returns a tuple with the AggregatedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregatedValue

`func (o *OperatorRuntimeIncidentOccurrence) SetAggregatedValue(v float64)`

SetAggregatedValue sets AggregatedValue field to given value.

### HasAggregatedValue

`func (o *OperatorRuntimeIncidentOccurrence) HasAggregatedValue() bool`

HasAggregatedValue returns a boolean if a field has been set.

### SetAggregatedValueNil

`func (o *OperatorRuntimeIncidentOccurrence) SetAggregatedValueNil(b bool)`

 SetAggregatedValueNil sets the value for AggregatedValue to be an explicit nil

### UnsetAggregatedValue
`func (o *OperatorRuntimeIncidentOccurrence) UnsetAggregatedValue()`

UnsetAggregatedValue ensures that no value is present for AggregatedValue, not even an explicit nil
### GetThreshold

`func (o *OperatorRuntimeIncidentOccurrence) GetThreshold() float64`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *OperatorRuntimeIncidentOccurrence) GetThresholdOk() (*float64, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *OperatorRuntimeIncidentOccurrence) SetThreshold(v float64)`

SetThreshold sets Threshold field to given value.

### HasThreshold

`func (o *OperatorRuntimeIncidentOccurrence) HasThreshold() bool`

HasThreshold returns a boolean if a field has been set.

### SetThresholdNil

`func (o *OperatorRuntimeIncidentOccurrence) SetThresholdNil(b bool)`

 SetThresholdNil sets the value for Threshold to be an explicit nil

### UnsetThreshold
`func (o *OperatorRuntimeIncidentOccurrence) UnsetThreshold()`

UnsetThreshold ensures that no value is present for Threshold, not even an explicit nil
### GetActor

`func (o *OperatorRuntimeIncidentOccurrence) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *OperatorRuntimeIncidentOccurrence) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *OperatorRuntimeIncidentOccurrence) SetActor(v string)`

SetActor sets Actor field to given value.

### HasActor

`func (o *OperatorRuntimeIncidentOccurrence) HasActor() bool`

HasActor returns a boolean if a field has been set.

### GetMessage

`func (o *OperatorRuntimeIncidentOccurrence) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *OperatorRuntimeIncidentOccurrence) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *OperatorRuntimeIncidentOccurrence) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *OperatorRuntimeIncidentOccurrence) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetContext

`func (o *OperatorRuntimeIncidentOccurrence) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *OperatorRuntimeIncidentOccurrence) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *OperatorRuntimeIncidentOccurrence) SetContext(v interface{})`

SetContext sets Context field to given value.

### HasContext

`func (o *OperatorRuntimeIncidentOccurrence) HasContext() bool`

HasContext returns a boolean if a field has been set.

### SetContextNil

`func (o *OperatorRuntimeIncidentOccurrence) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *OperatorRuntimeIncidentOccurrence) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetOccurredAt

`func (o *OperatorRuntimeIncidentOccurrence) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *OperatorRuntimeIncidentOccurrence) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *OperatorRuntimeIncidentOccurrence) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.


### GetCreatedAt

`func (o *OperatorRuntimeIncidentOccurrence) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorRuntimeIncidentOccurrence) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorRuntimeIncidentOccurrence) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


