# OperatorRuntimeMetricSupervisor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DesiredProcesses** | **int32** |  | 
**ManagedProcesses** | **int32** |  | 
**RunningProcesses** | **int32** |  | 
**StartingProcesses** | **int32** |  | 
**FailedProcesses** | **int32** |  | 
**ProcessDeficit** | **int32** |  | 
**RestartCount** | **int32** |  | 
**CircuitOpen** | **bool** |  | 

## Methods

### NewOperatorRuntimeMetricSupervisor

`func NewOperatorRuntimeMetricSupervisor(desiredProcesses int32, managedProcesses int32, runningProcesses int32, startingProcesses int32, failedProcesses int32, processDeficit int32, restartCount int32, circuitOpen bool, ) *OperatorRuntimeMetricSupervisor`

NewOperatorRuntimeMetricSupervisor instantiates a new OperatorRuntimeMetricSupervisor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricSupervisorWithDefaults

`func NewOperatorRuntimeMetricSupervisorWithDefaults() *OperatorRuntimeMetricSupervisor`

NewOperatorRuntimeMetricSupervisorWithDefaults instantiates a new OperatorRuntimeMetricSupervisor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDesiredProcesses

`func (o *OperatorRuntimeMetricSupervisor) GetDesiredProcesses() int32`

GetDesiredProcesses returns the DesiredProcesses field if non-nil, zero value otherwise.

### GetDesiredProcessesOk

`func (o *OperatorRuntimeMetricSupervisor) GetDesiredProcessesOk() (*int32, bool)`

GetDesiredProcessesOk returns a tuple with the DesiredProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredProcesses

`func (o *OperatorRuntimeMetricSupervisor) SetDesiredProcesses(v int32)`

SetDesiredProcesses sets DesiredProcesses field to given value.


### GetManagedProcesses

`func (o *OperatorRuntimeMetricSupervisor) GetManagedProcesses() int32`

GetManagedProcesses returns the ManagedProcesses field if non-nil, zero value otherwise.

### GetManagedProcessesOk

`func (o *OperatorRuntimeMetricSupervisor) GetManagedProcessesOk() (*int32, bool)`

GetManagedProcessesOk returns a tuple with the ManagedProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedProcesses

`func (o *OperatorRuntimeMetricSupervisor) SetManagedProcesses(v int32)`

SetManagedProcesses sets ManagedProcesses field to given value.


### GetRunningProcesses

`func (o *OperatorRuntimeMetricSupervisor) GetRunningProcesses() int32`

GetRunningProcesses returns the RunningProcesses field if non-nil, zero value otherwise.

### GetRunningProcessesOk

`func (o *OperatorRuntimeMetricSupervisor) GetRunningProcessesOk() (*int32, bool)`

GetRunningProcessesOk returns a tuple with the RunningProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningProcesses

`func (o *OperatorRuntimeMetricSupervisor) SetRunningProcesses(v int32)`

SetRunningProcesses sets RunningProcesses field to given value.


### GetStartingProcesses

`func (o *OperatorRuntimeMetricSupervisor) GetStartingProcesses() int32`

GetStartingProcesses returns the StartingProcesses field if non-nil, zero value otherwise.

### GetStartingProcessesOk

`func (o *OperatorRuntimeMetricSupervisor) GetStartingProcessesOk() (*int32, bool)`

GetStartingProcessesOk returns a tuple with the StartingProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartingProcesses

`func (o *OperatorRuntimeMetricSupervisor) SetStartingProcesses(v int32)`

SetStartingProcesses sets StartingProcesses field to given value.


### GetFailedProcesses

`func (o *OperatorRuntimeMetricSupervisor) GetFailedProcesses() int32`

GetFailedProcesses returns the FailedProcesses field if non-nil, zero value otherwise.

### GetFailedProcessesOk

`func (o *OperatorRuntimeMetricSupervisor) GetFailedProcessesOk() (*int32, bool)`

GetFailedProcessesOk returns a tuple with the FailedProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedProcesses

`func (o *OperatorRuntimeMetricSupervisor) SetFailedProcesses(v int32)`

SetFailedProcesses sets FailedProcesses field to given value.


### GetProcessDeficit

`func (o *OperatorRuntimeMetricSupervisor) GetProcessDeficit() int32`

GetProcessDeficit returns the ProcessDeficit field if non-nil, zero value otherwise.

### GetProcessDeficitOk

`func (o *OperatorRuntimeMetricSupervisor) GetProcessDeficitOk() (*int32, bool)`

GetProcessDeficitOk returns a tuple with the ProcessDeficit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessDeficit

`func (o *OperatorRuntimeMetricSupervisor) SetProcessDeficit(v int32)`

SetProcessDeficit sets ProcessDeficit field to given value.


### GetRestartCount

`func (o *OperatorRuntimeMetricSupervisor) GetRestartCount() int32`

GetRestartCount returns the RestartCount field if non-nil, zero value otherwise.

### GetRestartCountOk

`func (o *OperatorRuntimeMetricSupervisor) GetRestartCountOk() (*int32, bool)`

GetRestartCountOk returns a tuple with the RestartCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestartCount

`func (o *OperatorRuntimeMetricSupervisor) SetRestartCount(v int32)`

SetRestartCount sets RestartCount field to given value.


### GetCircuitOpen

`func (o *OperatorRuntimeMetricSupervisor) GetCircuitOpen() bool`

GetCircuitOpen returns the CircuitOpen field if non-nil, zero value otherwise.

### GetCircuitOpenOk

`func (o *OperatorRuntimeMetricSupervisor) GetCircuitOpenOk() (*bool, bool)`

GetCircuitOpenOk returns a tuple with the CircuitOpen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitOpen

`func (o *OperatorRuntimeMetricSupervisor) SetCircuitOpen(v bool)`

SetCircuitOpen sets CircuitOpen field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


