# OperatorRuntimeAssignment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DesiredWorkers** | **int32** |  | 
**AssignedWorkers** | **int32** |  | 
**Coverage** | [**CoverageEnum**](CoverageEnum.md) |  | 
**Allocations** | **map[string]int32** |  | 
**AssignmentRevision** | **NullableInt32** |  | 
**LeaderEpoch** | **NullableInt32** |  | 

## Methods

### NewOperatorRuntimeAssignment

`func NewOperatorRuntimeAssignment(desiredWorkers int32, assignedWorkers int32, coverage CoverageEnum, allocations map[string]int32, assignmentRevision NullableInt32, leaderEpoch NullableInt32, ) *OperatorRuntimeAssignment`

NewOperatorRuntimeAssignment instantiates a new OperatorRuntimeAssignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeAssignmentWithDefaults

`func NewOperatorRuntimeAssignmentWithDefaults() *OperatorRuntimeAssignment`

NewOperatorRuntimeAssignmentWithDefaults instantiates a new OperatorRuntimeAssignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDesiredWorkers

`func (o *OperatorRuntimeAssignment) GetDesiredWorkers() int32`

GetDesiredWorkers returns the DesiredWorkers field if non-nil, zero value otherwise.

### GetDesiredWorkersOk

`func (o *OperatorRuntimeAssignment) GetDesiredWorkersOk() (*int32, bool)`

GetDesiredWorkersOk returns a tuple with the DesiredWorkers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredWorkers

`func (o *OperatorRuntimeAssignment) SetDesiredWorkers(v int32)`

SetDesiredWorkers sets DesiredWorkers field to given value.


### GetAssignedWorkers

`func (o *OperatorRuntimeAssignment) GetAssignedWorkers() int32`

GetAssignedWorkers returns the AssignedWorkers field if non-nil, zero value otherwise.

### GetAssignedWorkersOk

`func (o *OperatorRuntimeAssignment) GetAssignedWorkersOk() (*int32, bool)`

GetAssignedWorkersOk returns a tuple with the AssignedWorkers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedWorkers

`func (o *OperatorRuntimeAssignment) SetAssignedWorkers(v int32)`

SetAssignedWorkers sets AssignedWorkers field to given value.


### GetCoverage

`func (o *OperatorRuntimeAssignment) GetCoverage() CoverageEnum`

GetCoverage returns the Coverage field if non-nil, zero value otherwise.

### GetCoverageOk

`func (o *OperatorRuntimeAssignment) GetCoverageOk() (*CoverageEnum, bool)`

GetCoverageOk returns a tuple with the Coverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoverage

`func (o *OperatorRuntimeAssignment) SetCoverage(v CoverageEnum)`

SetCoverage sets Coverage field to given value.


### GetAllocations

`func (o *OperatorRuntimeAssignment) GetAllocations() map[string]int32`

GetAllocations returns the Allocations field if non-nil, zero value otherwise.

### GetAllocationsOk

`func (o *OperatorRuntimeAssignment) GetAllocationsOk() (*map[string]int32, bool)`

GetAllocationsOk returns a tuple with the Allocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocations

`func (o *OperatorRuntimeAssignment) SetAllocations(v map[string]int32)`

SetAllocations sets Allocations field to given value.


### GetAssignmentRevision

`func (o *OperatorRuntimeAssignment) GetAssignmentRevision() int32`

GetAssignmentRevision returns the AssignmentRevision field if non-nil, zero value otherwise.

### GetAssignmentRevisionOk

`func (o *OperatorRuntimeAssignment) GetAssignmentRevisionOk() (*int32, bool)`

GetAssignmentRevisionOk returns a tuple with the AssignmentRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignmentRevision

`func (o *OperatorRuntimeAssignment) SetAssignmentRevision(v int32)`

SetAssignmentRevision sets AssignmentRevision field to given value.


### SetAssignmentRevisionNil

`func (o *OperatorRuntimeAssignment) SetAssignmentRevisionNil(b bool)`

 SetAssignmentRevisionNil sets the value for AssignmentRevision to be an explicit nil

### UnsetAssignmentRevision
`func (o *OperatorRuntimeAssignment) UnsetAssignmentRevision()`

UnsetAssignmentRevision ensures that no value is present for AssignmentRevision, not even an explicit nil
### GetLeaderEpoch

`func (o *OperatorRuntimeAssignment) GetLeaderEpoch() int32`

GetLeaderEpoch returns the LeaderEpoch field if non-nil, zero value otherwise.

### GetLeaderEpochOk

`func (o *OperatorRuntimeAssignment) GetLeaderEpochOk() (*int32, bool)`

GetLeaderEpochOk returns a tuple with the LeaderEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaderEpoch

`func (o *OperatorRuntimeAssignment) SetLeaderEpoch(v int32)`

SetLeaderEpoch sets LeaderEpoch field to given value.


### SetLeaderEpochNil

`func (o *OperatorRuntimeAssignment) SetLeaderEpochNil(b bool)`

 SetLeaderEpochNil sets the value for LeaderEpoch to be an explicit nil

### UnsetLeaderEpoch
`func (o *OperatorRuntimeAssignment) UnsetLeaderEpoch()`

UnsetLeaderEpoch ensures that no value is present for LeaderEpoch, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


