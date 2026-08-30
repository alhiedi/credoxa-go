# OperatorRuntimeMetricsCollectionState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumersWithErrors** | **int32** |  | 
**SourceErrorsTotal** | **int32** |  | 
**SourceErrorSources** | **map[string]int32** |  | 

## Methods

### NewOperatorRuntimeMetricsCollectionState

`func NewOperatorRuntimeMetricsCollectionState(consumersWithErrors int32, sourceErrorsTotal int32, sourceErrorSources map[string]int32, ) *OperatorRuntimeMetricsCollectionState`

NewOperatorRuntimeMetricsCollectionState instantiates a new OperatorRuntimeMetricsCollectionState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsCollectionStateWithDefaults

`func NewOperatorRuntimeMetricsCollectionStateWithDefaults() *OperatorRuntimeMetricsCollectionState`

NewOperatorRuntimeMetricsCollectionStateWithDefaults instantiates a new OperatorRuntimeMetricsCollectionState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumersWithErrors

`func (o *OperatorRuntimeMetricsCollectionState) GetConsumersWithErrors() int32`

GetConsumersWithErrors returns the ConsumersWithErrors field if non-nil, zero value otherwise.

### GetConsumersWithErrorsOk

`func (o *OperatorRuntimeMetricsCollectionState) GetConsumersWithErrorsOk() (*int32, bool)`

GetConsumersWithErrorsOk returns a tuple with the ConsumersWithErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumersWithErrors

`func (o *OperatorRuntimeMetricsCollectionState) SetConsumersWithErrors(v int32)`

SetConsumersWithErrors sets ConsumersWithErrors field to given value.


### GetSourceErrorsTotal

`func (o *OperatorRuntimeMetricsCollectionState) GetSourceErrorsTotal() int32`

GetSourceErrorsTotal returns the SourceErrorsTotal field if non-nil, zero value otherwise.

### GetSourceErrorsTotalOk

`func (o *OperatorRuntimeMetricsCollectionState) GetSourceErrorsTotalOk() (*int32, bool)`

GetSourceErrorsTotalOk returns a tuple with the SourceErrorsTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceErrorsTotal

`func (o *OperatorRuntimeMetricsCollectionState) SetSourceErrorsTotal(v int32)`

SetSourceErrorsTotal sets SourceErrorsTotal field to given value.


### GetSourceErrorSources

`func (o *OperatorRuntimeMetricsCollectionState) GetSourceErrorSources() map[string]int32`

GetSourceErrorSources returns the SourceErrorSources field if non-nil, zero value otherwise.

### GetSourceErrorSourcesOk

`func (o *OperatorRuntimeMetricsCollectionState) GetSourceErrorSourcesOk() (*map[string]int32, bool)`

GetSourceErrorSourcesOk returns a tuple with the SourceErrorSources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceErrorSources

`func (o *OperatorRuntimeMetricsCollectionState) SetSourceErrorSources(v map[string]int32)`

SetSourceErrorSources sets SourceErrorSources field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


