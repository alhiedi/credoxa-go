# OperatorRuntimeSupervisor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DesiredProcesses** | **int32** |  | 
**ManagedProcesses** | **int32** |  | 
**RunningProcesses** | **int32** |  | 
**StartingProcesses** | **int32** |  | 
**StoppedProcesses** | **int32** |  | 
**FailedProcesses** | **int32** |  | 
**ProcessDeficit** | **int32** |  | 
**RestartCount** | **int32** |  | 
**CircuitState** | [**CircuitStateEnum**](CircuitStateEnum.md) |  | 
**CircuitOpenSlots** | **[]int32** |  | 
**LastReconciledAt** | **NullableTime** |  | 

## Methods

### NewOperatorRuntimeSupervisor

`func NewOperatorRuntimeSupervisor(desiredProcesses int32, managedProcesses int32, runningProcesses int32, startingProcesses int32, stoppedProcesses int32, failedProcesses int32, processDeficit int32, restartCount int32, circuitState CircuitStateEnum, circuitOpenSlots []int32, lastReconciledAt NullableTime, ) *OperatorRuntimeSupervisor`

NewOperatorRuntimeSupervisor instantiates a new OperatorRuntimeSupervisor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeSupervisorWithDefaults

`func NewOperatorRuntimeSupervisorWithDefaults() *OperatorRuntimeSupervisor`

NewOperatorRuntimeSupervisorWithDefaults instantiates a new OperatorRuntimeSupervisor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDesiredProcesses

`func (o *OperatorRuntimeSupervisor) GetDesiredProcesses() int32`

GetDesiredProcesses returns the DesiredProcesses field if non-nil, zero value otherwise.

### GetDesiredProcessesOk

`func (o *OperatorRuntimeSupervisor) GetDesiredProcessesOk() (*int32, bool)`

GetDesiredProcessesOk returns a tuple with the DesiredProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredProcesses

`func (o *OperatorRuntimeSupervisor) SetDesiredProcesses(v int32)`

SetDesiredProcesses sets DesiredProcesses field to given value.


### GetManagedProcesses

`func (o *OperatorRuntimeSupervisor) GetManagedProcesses() int32`

GetManagedProcesses returns the ManagedProcesses field if non-nil, zero value otherwise.

### GetManagedProcessesOk

`func (o *OperatorRuntimeSupervisor) GetManagedProcessesOk() (*int32, bool)`

GetManagedProcessesOk returns a tuple with the ManagedProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedProcesses

`func (o *OperatorRuntimeSupervisor) SetManagedProcesses(v int32)`

SetManagedProcesses sets ManagedProcesses field to given value.


### GetRunningProcesses

`func (o *OperatorRuntimeSupervisor) GetRunningProcesses() int32`

GetRunningProcesses returns the RunningProcesses field if non-nil, zero value otherwise.

### GetRunningProcessesOk

`func (o *OperatorRuntimeSupervisor) GetRunningProcessesOk() (*int32, bool)`

GetRunningProcessesOk returns a tuple with the RunningProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningProcesses

`func (o *OperatorRuntimeSupervisor) SetRunningProcesses(v int32)`

SetRunningProcesses sets RunningProcesses field to given value.


### GetStartingProcesses

`func (o *OperatorRuntimeSupervisor) GetStartingProcesses() int32`

GetStartingProcesses returns the StartingProcesses field if non-nil, zero value otherwise.

### GetStartingProcessesOk

`func (o *OperatorRuntimeSupervisor) GetStartingProcessesOk() (*int32, bool)`

GetStartingProcessesOk returns a tuple with the StartingProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartingProcesses

`func (o *OperatorRuntimeSupervisor) SetStartingProcesses(v int32)`

SetStartingProcesses sets StartingProcesses field to given value.


### GetStoppedProcesses

`func (o *OperatorRuntimeSupervisor) GetStoppedProcesses() int32`

GetStoppedProcesses returns the StoppedProcesses field if non-nil, zero value otherwise.

### GetStoppedProcessesOk

`func (o *OperatorRuntimeSupervisor) GetStoppedProcessesOk() (*int32, bool)`

GetStoppedProcessesOk returns a tuple with the StoppedProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoppedProcesses

`func (o *OperatorRuntimeSupervisor) SetStoppedProcesses(v int32)`

SetStoppedProcesses sets StoppedProcesses field to given value.


### GetFailedProcesses

`func (o *OperatorRuntimeSupervisor) GetFailedProcesses() int32`

GetFailedProcesses returns the FailedProcesses field if non-nil, zero value otherwise.

### GetFailedProcessesOk

`func (o *OperatorRuntimeSupervisor) GetFailedProcessesOk() (*int32, bool)`

GetFailedProcessesOk returns a tuple with the FailedProcesses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedProcesses

`func (o *OperatorRuntimeSupervisor) SetFailedProcesses(v int32)`

SetFailedProcesses sets FailedProcesses field to given value.


### GetProcessDeficit

`func (o *OperatorRuntimeSupervisor) GetProcessDeficit() int32`

GetProcessDeficit returns the ProcessDeficit field if non-nil, zero value otherwise.

### GetProcessDeficitOk

`func (o *OperatorRuntimeSupervisor) GetProcessDeficitOk() (*int32, bool)`

GetProcessDeficitOk returns a tuple with the ProcessDeficit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessDeficit

`func (o *OperatorRuntimeSupervisor) SetProcessDeficit(v int32)`

SetProcessDeficit sets ProcessDeficit field to given value.


### GetRestartCount

`func (o *OperatorRuntimeSupervisor) GetRestartCount() int32`

GetRestartCount returns the RestartCount field if non-nil, zero value otherwise.

### GetRestartCountOk

`func (o *OperatorRuntimeSupervisor) GetRestartCountOk() (*int32, bool)`

GetRestartCountOk returns a tuple with the RestartCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestartCount

`func (o *OperatorRuntimeSupervisor) SetRestartCount(v int32)`

SetRestartCount sets RestartCount field to given value.


### GetCircuitState

`func (o *OperatorRuntimeSupervisor) GetCircuitState() CircuitStateEnum`

GetCircuitState returns the CircuitState field if non-nil, zero value otherwise.

### GetCircuitStateOk

`func (o *OperatorRuntimeSupervisor) GetCircuitStateOk() (*CircuitStateEnum, bool)`

GetCircuitStateOk returns a tuple with the CircuitState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitState

`func (o *OperatorRuntimeSupervisor) SetCircuitState(v CircuitStateEnum)`

SetCircuitState sets CircuitState field to given value.


### GetCircuitOpenSlots

`func (o *OperatorRuntimeSupervisor) GetCircuitOpenSlots() []int32`

GetCircuitOpenSlots returns the CircuitOpenSlots field if non-nil, zero value otherwise.

### GetCircuitOpenSlotsOk

`func (o *OperatorRuntimeSupervisor) GetCircuitOpenSlotsOk() (*[]int32, bool)`

GetCircuitOpenSlotsOk returns a tuple with the CircuitOpenSlots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitOpenSlots

`func (o *OperatorRuntimeSupervisor) SetCircuitOpenSlots(v []int32)`

SetCircuitOpenSlots sets CircuitOpenSlots field to given value.


### GetLastReconciledAt

`func (o *OperatorRuntimeSupervisor) GetLastReconciledAt() time.Time`

GetLastReconciledAt returns the LastReconciledAt field if non-nil, zero value otherwise.

### GetLastReconciledAtOk

`func (o *OperatorRuntimeSupervisor) GetLastReconciledAtOk() (*time.Time, bool)`

GetLastReconciledAtOk returns a tuple with the LastReconciledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReconciledAt

`func (o *OperatorRuntimeSupervisor) SetLastReconciledAt(v time.Time)`

SetLastReconciledAt sets LastReconciledAt field to given value.


### SetLastReconciledAtNil

`func (o *OperatorRuntimeSupervisor) SetLastReconciledAtNil(b bool)`

 SetLastReconciledAtNil sets the value for LastReconciledAt to be an explicit nil

### UnsetLastReconciledAt
`func (o *OperatorRuntimeSupervisor) UnsetLastReconciledAt()`

UnsetLastReconciledAt ensures that no value is present for LastReconciledAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


