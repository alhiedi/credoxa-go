# OperatorRuntimeMetricsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Collection** | [**OperatorRuntimeMetricsExecution**](OperatorRuntimeMetricsExecution.md) |  | 
**Metrics** | [**OperatorRuntimeMetricsAggregate**](OperatorRuntimeMetricsAggregate.md) |  | 

## Methods

### NewOperatorRuntimeMetricsResponse

`func NewOperatorRuntimeMetricsResponse(collection OperatorRuntimeMetricsExecution, metrics OperatorRuntimeMetricsAggregate, ) *OperatorRuntimeMetricsResponse`

NewOperatorRuntimeMetricsResponse instantiates a new OperatorRuntimeMetricsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsResponseWithDefaults

`func NewOperatorRuntimeMetricsResponseWithDefaults() *OperatorRuntimeMetricsResponse`

NewOperatorRuntimeMetricsResponseWithDefaults instantiates a new OperatorRuntimeMetricsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCollection

`func (o *OperatorRuntimeMetricsResponse) GetCollection() OperatorRuntimeMetricsExecution`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *OperatorRuntimeMetricsResponse) GetCollectionOk() (*OperatorRuntimeMetricsExecution, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *OperatorRuntimeMetricsResponse) SetCollection(v OperatorRuntimeMetricsExecution)`

SetCollection sets Collection field to given value.


### GetMetrics

`func (o *OperatorRuntimeMetricsResponse) GetMetrics() OperatorRuntimeMetricsAggregate`

GetMetrics returns the Metrics field if non-nil, zero value otherwise.

### GetMetricsOk

`func (o *OperatorRuntimeMetricsResponse) GetMetricsOk() (*OperatorRuntimeMetricsAggregate, bool)`

GetMetricsOk returns a tuple with the Metrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetrics

`func (o *OperatorRuntimeMetricsResponse) SetMetrics(v OperatorRuntimeMetricsAggregate)`

SetMetrics sets Metrics field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


