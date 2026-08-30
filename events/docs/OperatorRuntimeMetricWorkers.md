# OperatorRuntimeMetricWorkers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Observed** | **int32** |  | 
**Live** | **int32** |  | 
**Running** | **int32** |  | 
**Starting** | **int32** |  | 
**Stale** | **int32** |  | 
**Failed** | **int32** |  | 
**Draining** | **int32** |  | 
**CapacitySatisfied** | **bool** |  | 
**ProcessedTotal** | **int32** |  | 
**FailureTotal** | **int32** |  | 

## Methods

### NewOperatorRuntimeMetricWorkers

`func NewOperatorRuntimeMetricWorkers(observed int32, live int32, running int32, starting int32, stale int32, failed int32, draining int32, capacitySatisfied bool, processedTotal int32, failureTotal int32, ) *OperatorRuntimeMetricWorkers`

NewOperatorRuntimeMetricWorkers instantiates a new OperatorRuntimeMetricWorkers object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricWorkersWithDefaults

`func NewOperatorRuntimeMetricWorkersWithDefaults() *OperatorRuntimeMetricWorkers`

NewOperatorRuntimeMetricWorkersWithDefaults instantiates a new OperatorRuntimeMetricWorkers object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetObserved

`func (o *OperatorRuntimeMetricWorkers) GetObserved() int32`

GetObserved returns the Observed field if non-nil, zero value otherwise.

### GetObservedOk

`func (o *OperatorRuntimeMetricWorkers) GetObservedOk() (*int32, bool)`

GetObservedOk returns a tuple with the Observed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObserved

`func (o *OperatorRuntimeMetricWorkers) SetObserved(v int32)`

SetObserved sets Observed field to given value.


### GetLive

`func (o *OperatorRuntimeMetricWorkers) GetLive() int32`

GetLive returns the Live field if non-nil, zero value otherwise.

### GetLiveOk

`func (o *OperatorRuntimeMetricWorkers) GetLiveOk() (*int32, bool)`

GetLiveOk returns a tuple with the Live field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLive

`func (o *OperatorRuntimeMetricWorkers) SetLive(v int32)`

SetLive sets Live field to given value.


### GetRunning

`func (o *OperatorRuntimeMetricWorkers) GetRunning() int32`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *OperatorRuntimeMetricWorkers) GetRunningOk() (*int32, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *OperatorRuntimeMetricWorkers) SetRunning(v int32)`

SetRunning sets Running field to given value.


### GetStarting

`func (o *OperatorRuntimeMetricWorkers) GetStarting() int32`

GetStarting returns the Starting field if non-nil, zero value otherwise.

### GetStartingOk

`func (o *OperatorRuntimeMetricWorkers) GetStartingOk() (*int32, bool)`

GetStartingOk returns a tuple with the Starting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStarting

`func (o *OperatorRuntimeMetricWorkers) SetStarting(v int32)`

SetStarting sets Starting field to given value.


### GetStale

`func (o *OperatorRuntimeMetricWorkers) GetStale() int32`

GetStale returns the Stale field if non-nil, zero value otherwise.

### GetStaleOk

`func (o *OperatorRuntimeMetricWorkers) GetStaleOk() (*int32, bool)`

GetStaleOk returns a tuple with the Stale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStale

`func (o *OperatorRuntimeMetricWorkers) SetStale(v int32)`

SetStale sets Stale field to given value.


### GetFailed

`func (o *OperatorRuntimeMetricWorkers) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *OperatorRuntimeMetricWorkers) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *OperatorRuntimeMetricWorkers) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetDraining

`func (o *OperatorRuntimeMetricWorkers) GetDraining() int32`

GetDraining returns the Draining field if non-nil, zero value otherwise.

### GetDrainingOk

`func (o *OperatorRuntimeMetricWorkers) GetDrainingOk() (*int32, bool)`

GetDrainingOk returns a tuple with the Draining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraining

`func (o *OperatorRuntimeMetricWorkers) SetDraining(v int32)`

SetDraining sets Draining field to given value.


### GetCapacitySatisfied

`func (o *OperatorRuntimeMetricWorkers) GetCapacitySatisfied() bool`

GetCapacitySatisfied returns the CapacitySatisfied field if non-nil, zero value otherwise.

### GetCapacitySatisfiedOk

`func (o *OperatorRuntimeMetricWorkers) GetCapacitySatisfiedOk() (*bool, bool)`

GetCapacitySatisfiedOk returns a tuple with the CapacitySatisfied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacitySatisfied

`func (o *OperatorRuntimeMetricWorkers) SetCapacitySatisfied(v bool)`

SetCapacitySatisfied sets CapacitySatisfied field to given value.


### GetProcessedTotal

`func (o *OperatorRuntimeMetricWorkers) GetProcessedTotal() int32`

GetProcessedTotal returns the ProcessedTotal field if non-nil, zero value otherwise.

### GetProcessedTotalOk

`func (o *OperatorRuntimeMetricWorkers) GetProcessedTotalOk() (*int32, bool)`

GetProcessedTotalOk returns a tuple with the ProcessedTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedTotal

`func (o *OperatorRuntimeMetricWorkers) SetProcessedTotal(v int32)`

SetProcessedTotal sets ProcessedTotal field to given value.


### GetFailureTotal

`func (o *OperatorRuntimeMetricWorkers) GetFailureTotal() int32`

GetFailureTotal returns the FailureTotal field if non-nil, zero value otherwise.

### GetFailureTotalOk

`func (o *OperatorRuntimeMetricWorkers) GetFailureTotalOk() (*int32, bool)`

GetFailureTotalOk returns a tuple with the FailureTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureTotal

`func (o *OperatorRuntimeMetricWorkers) SetFailureTotal(v int32)`

SetFailureTotal sets FailureTotal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


