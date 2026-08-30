# OperatorRuntimeIncidentOccurrenceSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**LatestSequence** | **NullableInt32** |  | 
**LatestKind** | [**NullableRuntimeIncidentOccurrenceKindEnum**](RuntimeIncidentOccurrenceKindEnum.md) |  | 

## Methods

### NewOperatorRuntimeIncidentOccurrenceSummary

`func NewOperatorRuntimeIncidentOccurrenceSummary(total int32, latestSequence NullableInt32, latestKind NullableRuntimeIncidentOccurrenceKindEnum, ) *OperatorRuntimeIncidentOccurrenceSummary`

NewOperatorRuntimeIncidentOccurrenceSummary instantiates a new OperatorRuntimeIncidentOccurrenceSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentOccurrenceSummaryWithDefaults

`func NewOperatorRuntimeIncidentOccurrenceSummaryWithDefaults() *OperatorRuntimeIncidentOccurrenceSummary`

NewOperatorRuntimeIncidentOccurrenceSummaryWithDefaults instantiates a new OperatorRuntimeIncidentOccurrenceSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OperatorRuntimeIncidentOccurrenceSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OperatorRuntimeIncidentOccurrenceSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OperatorRuntimeIncidentOccurrenceSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetLatestSequence

`func (o *OperatorRuntimeIncidentOccurrenceSummary) GetLatestSequence() int32`

GetLatestSequence returns the LatestSequence field if non-nil, zero value otherwise.

### GetLatestSequenceOk

`func (o *OperatorRuntimeIncidentOccurrenceSummary) GetLatestSequenceOk() (*int32, bool)`

GetLatestSequenceOk returns a tuple with the LatestSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestSequence

`func (o *OperatorRuntimeIncidentOccurrenceSummary) SetLatestSequence(v int32)`

SetLatestSequence sets LatestSequence field to given value.


### SetLatestSequenceNil

`func (o *OperatorRuntimeIncidentOccurrenceSummary) SetLatestSequenceNil(b bool)`

 SetLatestSequenceNil sets the value for LatestSequence to be an explicit nil

### UnsetLatestSequence
`func (o *OperatorRuntimeIncidentOccurrenceSummary) UnsetLatestSequence()`

UnsetLatestSequence ensures that no value is present for LatestSequence, not even an explicit nil
### GetLatestKind

`func (o *OperatorRuntimeIncidentOccurrenceSummary) GetLatestKind() RuntimeIncidentOccurrenceKindEnum`

GetLatestKind returns the LatestKind field if non-nil, zero value otherwise.

### GetLatestKindOk

`func (o *OperatorRuntimeIncidentOccurrenceSummary) GetLatestKindOk() (*RuntimeIncidentOccurrenceKindEnum, bool)`

GetLatestKindOk returns a tuple with the LatestKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestKind

`func (o *OperatorRuntimeIncidentOccurrenceSummary) SetLatestKind(v RuntimeIncidentOccurrenceKindEnum)`

SetLatestKind sets LatestKind field to given value.


### SetLatestKindNil

`func (o *OperatorRuntimeIncidentOccurrenceSummary) SetLatestKindNil(b bool)`

 SetLatestKindNil sets the value for LatestKind to be an explicit nil

### UnsetLatestKind
`func (o *OperatorRuntimeIncidentOccurrenceSummary) UnsetLatestKind()`

UnsetLatestKind ensures that no value is present for LatestKind, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


