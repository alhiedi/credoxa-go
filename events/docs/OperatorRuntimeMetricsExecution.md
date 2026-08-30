# OperatorRuntimeMetricsExecution

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestedConsumers** | **int32** |  | 
**CollectedConsumers** | **int32** |  | 
**FailedConsumers** | **int32** |  | 
**Failures** | [**[]OperatorRuntimeMetricsFailure**](OperatorRuntimeMetricsFailure.md) |  | 

## Methods

### NewOperatorRuntimeMetricsExecution

`func NewOperatorRuntimeMetricsExecution(requestedConsumers int32, collectedConsumers int32, failedConsumers int32, failures []OperatorRuntimeMetricsFailure, ) *OperatorRuntimeMetricsExecution`

NewOperatorRuntimeMetricsExecution instantiates a new OperatorRuntimeMetricsExecution object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsExecutionWithDefaults

`func NewOperatorRuntimeMetricsExecutionWithDefaults() *OperatorRuntimeMetricsExecution`

NewOperatorRuntimeMetricsExecutionWithDefaults instantiates a new OperatorRuntimeMetricsExecution object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestedConsumers

`func (o *OperatorRuntimeMetricsExecution) GetRequestedConsumers() int32`

GetRequestedConsumers returns the RequestedConsumers field if non-nil, zero value otherwise.

### GetRequestedConsumersOk

`func (o *OperatorRuntimeMetricsExecution) GetRequestedConsumersOk() (*int32, bool)`

GetRequestedConsumersOk returns a tuple with the RequestedConsumers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedConsumers

`func (o *OperatorRuntimeMetricsExecution) SetRequestedConsumers(v int32)`

SetRequestedConsumers sets RequestedConsumers field to given value.


### GetCollectedConsumers

`func (o *OperatorRuntimeMetricsExecution) GetCollectedConsumers() int32`

GetCollectedConsumers returns the CollectedConsumers field if non-nil, zero value otherwise.

### GetCollectedConsumersOk

`func (o *OperatorRuntimeMetricsExecution) GetCollectedConsumersOk() (*int32, bool)`

GetCollectedConsumersOk returns a tuple with the CollectedConsumers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectedConsumers

`func (o *OperatorRuntimeMetricsExecution) SetCollectedConsumers(v int32)`

SetCollectedConsumers sets CollectedConsumers field to given value.


### GetFailedConsumers

`func (o *OperatorRuntimeMetricsExecution) GetFailedConsumers() int32`

GetFailedConsumers returns the FailedConsumers field if non-nil, zero value otherwise.

### GetFailedConsumersOk

`func (o *OperatorRuntimeMetricsExecution) GetFailedConsumersOk() (*int32, bool)`

GetFailedConsumersOk returns a tuple with the FailedConsumers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedConsumers

`func (o *OperatorRuntimeMetricsExecution) SetFailedConsumers(v int32)`

SetFailedConsumers sets FailedConsumers field to given value.


### GetFailures

`func (o *OperatorRuntimeMetricsExecution) GetFailures() []OperatorRuntimeMetricsFailure`

GetFailures returns the Failures field if non-nil, zero value otherwise.

### GetFailuresOk

`func (o *OperatorRuntimeMetricsExecution) GetFailuresOk() (*[]OperatorRuntimeMetricsFailure, bool)`

GetFailuresOk returns a tuple with the Failures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailures

`func (o *OperatorRuntimeMetricsExecution) SetFailures(v []OperatorRuntimeMetricsFailure)`

SetFailures sets Failures field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


