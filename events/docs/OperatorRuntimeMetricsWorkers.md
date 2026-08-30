# OperatorRuntimeMetricsWorkers

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
**CapacityRatio** | **float64** |  | 
**ProcessedTotal** | **int32** |  | 
**FailureTotal** | **int32** |  | 

## Methods

### NewOperatorRuntimeMetricsWorkers

`func NewOperatorRuntimeMetricsWorkers(observed int32, live int32, running int32, starting int32, stale int32, failed int32, draining int32, capacityRatio float64, processedTotal int32, failureTotal int32, ) *OperatorRuntimeMetricsWorkers`

NewOperatorRuntimeMetricsWorkers instantiates a new OperatorRuntimeMetricsWorkers object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsWorkersWithDefaults

`func NewOperatorRuntimeMetricsWorkersWithDefaults() *OperatorRuntimeMetricsWorkers`

NewOperatorRuntimeMetricsWorkersWithDefaults instantiates a new OperatorRuntimeMetricsWorkers object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetObserved

`func (o *OperatorRuntimeMetricsWorkers) GetObserved() int32`

GetObserved returns the Observed field if non-nil, zero value otherwise.

### GetObservedOk

`func (o *OperatorRuntimeMetricsWorkers) GetObservedOk() (*int32, bool)`

GetObservedOk returns a tuple with the Observed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObserved

`func (o *OperatorRuntimeMetricsWorkers) SetObserved(v int32)`

SetObserved sets Observed field to given value.


### GetLive

`func (o *OperatorRuntimeMetricsWorkers) GetLive() int32`

GetLive returns the Live field if non-nil, zero value otherwise.

### GetLiveOk

`func (o *OperatorRuntimeMetricsWorkers) GetLiveOk() (*int32, bool)`

GetLiveOk returns a tuple with the Live field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLive

`func (o *OperatorRuntimeMetricsWorkers) SetLive(v int32)`

SetLive sets Live field to given value.


### GetRunning

`func (o *OperatorRuntimeMetricsWorkers) GetRunning() int32`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *OperatorRuntimeMetricsWorkers) GetRunningOk() (*int32, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *OperatorRuntimeMetricsWorkers) SetRunning(v int32)`

SetRunning sets Running field to given value.


### GetStarting

`func (o *OperatorRuntimeMetricsWorkers) GetStarting() int32`

GetStarting returns the Starting field if non-nil, zero value otherwise.

### GetStartingOk

`func (o *OperatorRuntimeMetricsWorkers) GetStartingOk() (*int32, bool)`

GetStartingOk returns a tuple with the Starting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStarting

`func (o *OperatorRuntimeMetricsWorkers) SetStarting(v int32)`

SetStarting sets Starting field to given value.


### GetStale

`func (o *OperatorRuntimeMetricsWorkers) GetStale() int32`

GetStale returns the Stale field if non-nil, zero value otherwise.

### GetStaleOk

`func (o *OperatorRuntimeMetricsWorkers) GetStaleOk() (*int32, bool)`

GetStaleOk returns a tuple with the Stale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStale

`func (o *OperatorRuntimeMetricsWorkers) SetStale(v int32)`

SetStale sets Stale field to given value.


### GetFailed

`func (o *OperatorRuntimeMetricsWorkers) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *OperatorRuntimeMetricsWorkers) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *OperatorRuntimeMetricsWorkers) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetDraining

`func (o *OperatorRuntimeMetricsWorkers) GetDraining() int32`

GetDraining returns the Draining field if non-nil, zero value otherwise.

### GetDrainingOk

`func (o *OperatorRuntimeMetricsWorkers) GetDrainingOk() (*int32, bool)`

GetDrainingOk returns a tuple with the Draining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraining

`func (o *OperatorRuntimeMetricsWorkers) SetDraining(v int32)`

SetDraining sets Draining field to given value.


### GetCapacityRatio

`func (o *OperatorRuntimeMetricsWorkers) GetCapacityRatio() float64`

GetCapacityRatio returns the CapacityRatio field if non-nil, zero value otherwise.

### GetCapacityRatioOk

`func (o *OperatorRuntimeMetricsWorkers) GetCapacityRatioOk() (*float64, bool)`

GetCapacityRatioOk returns a tuple with the CapacityRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacityRatio

`func (o *OperatorRuntimeMetricsWorkers) SetCapacityRatio(v float64)`

SetCapacityRatio sets CapacityRatio field to given value.


### GetProcessedTotal

`func (o *OperatorRuntimeMetricsWorkers) GetProcessedTotal() int32`

GetProcessedTotal returns the ProcessedTotal field if non-nil, zero value otherwise.

### GetProcessedTotalOk

`func (o *OperatorRuntimeMetricsWorkers) GetProcessedTotalOk() (*int32, bool)`

GetProcessedTotalOk returns a tuple with the ProcessedTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedTotal

`func (o *OperatorRuntimeMetricsWorkers) SetProcessedTotal(v int32)`

SetProcessedTotal sets ProcessedTotal field to given value.


### GetFailureTotal

`func (o *OperatorRuntimeMetricsWorkers) GetFailureTotal() int32`

GetFailureTotal returns the FailureTotal field if non-nil, zero value otherwise.

### GetFailureTotalOk

`func (o *OperatorRuntimeMetricsWorkers) GetFailureTotalOk() (*int32, bool)`

GetFailureTotalOk returns a tuple with the FailureTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureTotal

`func (o *OperatorRuntimeMetricsWorkers) SetFailureTotal(v int32)`

SetFailureTotal sets FailureTotal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


