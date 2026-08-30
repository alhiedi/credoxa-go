# OperatorRuntimeMetricAssignment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedWorkers** | **int32** |  | 
**AssignedWorkers** | **int32** |  | 
**Deficit** | **int32** |  | 
**Excess** | **int32** |  | 
**Satisfied** | **bool** |  | 

## Methods

### NewOperatorRuntimeMetricAssignment

`func NewOperatorRuntimeMetricAssignment(expectedWorkers int32, assignedWorkers int32, deficit int32, excess int32, satisfied bool, ) *OperatorRuntimeMetricAssignment`

NewOperatorRuntimeMetricAssignment instantiates a new OperatorRuntimeMetricAssignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricAssignmentWithDefaults

`func NewOperatorRuntimeMetricAssignmentWithDefaults() *OperatorRuntimeMetricAssignment`

NewOperatorRuntimeMetricAssignmentWithDefaults instantiates a new OperatorRuntimeMetricAssignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedWorkers

`func (o *OperatorRuntimeMetricAssignment) GetExpectedWorkers() int32`

GetExpectedWorkers returns the ExpectedWorkers field if non-nil, zero value otherwise.

### GetExpectedWorkersOk

`func (o *OperatorRuntimeMetricAssignment) GetExpectedWorkersOk() (*int32, bool)`

GetExpectedWorkersOk returns a tuple with the ExpectedWorkers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedWorkers

`func (o *OperatorRuntimeMetricAssignment) SetExpectedWorkers(v int32)`

SetExpectedWorkers sets ExpectedWorkers field to given value.


### GetAssignedWorkers

`func (o *OperatorRuntimeMetricAssignment) GetAssignedWorkers() int32`

GetAssignedWorkers returns the AssignedWorkers field if non-nil, zero value otherwise.

### GetAssignedWorkersOk

`func (o *OperatorRuntimeMetricAssignment) GetAssignedWorkersOk() (*int32, bool)`

GetAssignedWorkersOk returns a tuple with the AssignedWorkers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedWorkers

`func (o *OperatorRuntimeMetricAssignment) SetAssignedWorkers(v int32)`

SetAssignedWorkers sets AssignedWorkers field to given value.


### GetDeficit

`func (o *OperatorRuntimeMetricAssignment) GetDeficit() int32`

GetDeficit returns the Deficit field if non-nil, zero value otherwise.

### GetDeficitOk

`func (o *OperatorRuntimeMetricAssignment) GetDeficitOk() (*int32, bool)`

GetDeficitOk returns a tuple with the Deficit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeficit

`func (o *OperatorRuntimeMetricAssignment) SetDeficit(v int32)`

SetDeficit sets Deficit field to given value.


### GetExcess

`func (o *OperatorRuntimeMetricAssignment) GetExcess() int32`

GetExcess returns the Excess field if non-nil, zero value otherwise.

### GetExcessOk

`func (o *OperatorRuntimeMetricAssignment) GetExcessOk() (*int32, bool)`

GetExcessOk returns a tuple with the Excess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcess

`func (o *OperatorRuntimeMetricAssignment) SetExcess(v int32)`

SetExcess sets Excess field to given value.


### GetSatisfied

`func (o *OperatorRuntimeMetricAssignment) GetSatisfied() bool`

GetSatisfied returns the Satisfied field if non-nil, zero value otherwise.

### GetSatisfiedOk

`func (o *OperatorRuntimeMetricAssignment) GetSatisfiedOk() (*bool, bool)`

GetSatisfiedOk returns a tuple with the Satisfied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSatisfied

`func (o *OperatorRuntimeMetricAssignment) SetSatisfied(v bool)`

SetSatisfied sets Satisfied field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


