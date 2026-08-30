# OperatorRuntimeWorkerItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkerId** | **string** |  | 
**ConsumerCode** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**State** | [**OperatorRuntimeWorkerItemStateEnum**](OperatorRuntimeWorkerItemStateEnum.md) |  | 
**HeartbeatAt** | **time.Time** |  | 
**NodeId** | **NullableString** |  | 
**ProcessId** | **NullableInt32** |  | 
**ProcessedCount** | **int32** |  | 
**FailureCount** | **int32** |  | 
**ActiveDeliveries** | **int32** |  | 
**IsDraining** | **bool** |  | 
**IsStale** | **bool** |  | 
**LastError** | **string** |  | 

## Methods

### NewOperatorRuntimeWorkerItem

`func NewOperatorRuntimeWorkerItem(workerId string, consumerCode string, organizationId NullableString, state OperatorRuntimeWorkerItemStateEnum, heartbeatAt time.Time, nodeId NullableString, processId NullableInt32, processedCount int32, failureCount int32, activeDeliveries int32, isDraining bool, isStale bool, lastError string, ) *OperatorRuntimeWorkerItem`

NewOperatorRuntimeWorkerItem instantiates a new OperatorRuntimeWorkerItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeWorkerItemWithDefaults

`func NewOperatorRuntimeWorkerItemWithDefaults() *OperatorRuntimeWorkerItem`

NewOperatorRuntimeWorkerItemWithDefaults instantiates a new OperatorRuntimeWorkerItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkerId

`func (o *OperatorRuntimeWorkerItem) GetWorkerId() string`

GetWorkerId returns the WorkerId field if non-nil, zero value otherwise.

### GetWorkerIdOk

`func (o *OperatorRuntimeWorkerItem) GetWorkerIdOk() (*string, bool)`

GetWorkerIdOk returns a tuple with the WorkerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkerId

`func (o *OperatorRuntimeWorkerItem) SetWorkerId(v string)`

SetWorkerId sets WorkerId field to given value.


### GetConsumerCode

`func (o *OperatorRuntimeWorkerItem) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeWorkerItem) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeWorkerItem) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeWorkerItem) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeWorkerItem) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeWorkerItem) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorRuntimeWorkerItem) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeWorkerItem) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetState

`func (o *OperatorRuntimeWorkerItem) GetState() OperatorRuntimeWorkerItemStateEnum`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *OperatorRuntimeWorkerItem) GetStateOk() (*OperatorRuntimeWorkerItemStateEnum, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *OperatorRuntimeWorkerItem) SetState(v OperatorRuntimeWorkerItemStateEnum)`

SetState sets State field to given value.


### GetHeartbeatAt

`func (o *OperatorRuntimeWorkerItem) GetHeartbeatAt() time.Time`

GetHeartbeatAt returns the HeartbeatAt field if non-nil, zero value otherwise.

### GetHeartbeatAtOk

`func (o *OperatorRuntimeWorkerItem) GetHeartbeatAtOk() (*time.Time, bool)`

GetHeartbeatAtOk returns a tuple with the HeartbeatAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeartbeatAt

`func (o *OperatorRuntimeWorkerItem) SetHeartbeatAt(v time.Time)`

SetHeartbeatAt sets HeartbeatAt field to given value.


### GetNodeId

`func (o *OperatorRuntimeWorkerItem) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *OperatorRuntimeWorkerItem) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *OperatorRuntimeWorkerItem) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### SetNodeIdNil

`func (o *OperatorRuntimeWorkerItem) SetNodeIdNil(b bool)`

 SetNodeIdNil sets the value for NodeId to be an explicit nil

### UnsetNodeId
`func (o *OperatorRuntimeWorkerItem) UnsetNodeId()`

UnsetNodeId ensures that no value is present for NodeId, not even an explicit nil
### GetProcessId

`func (o *OperatorRuntimeWorkerItem) GetProcessId() int32`

GetProcessId returns the ProcessId field if non-nil, zero value otherwise.

### GetProcessIdOk

`func (o *OperatorRuntimeWorkerItem) GetProcessIdOk() (*int32, bool)`

GetProcessIdOk returns a tuple with the ProcessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessId

`func (o *OperatorRuntimeWorkerItem) SetProcessId(v int32)`

SetProcessId sets ProcessId field to given value.


### SetProcessIdNil

`func (o *OperatorRuntimeWorkerItem) SetProcessIdNil(b bool)`

 SetProcessIdNil sets the value for ProcessId to be an explicit nil

### UnsetProcessId
`func (o *OperatorRuntimeWorkerItem) UnsetProcessId()`

UnsetProcessId ensures that no value is present for ProcessId, not even an explicit nil
### GetProcessedCount

`func (o *OperatorRuntimeWorkerItem) GetProcessedCount() int32`

GetProcessedCount returns the ProcessedCount field if non-nil, zero value otherwise.

### GetProcessedCountOk

`func (o *OperatorRuntimeWorkerItem) GetProcessedCountOk() (*int32, bool)`

GetProcessedCountOk returns a tuple with the ProcessedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedCount

`func (o *OperatorRuntimeWorkerItem) SetProcessedCount(v int32)`

SetProcessedCount sets ProcessedCount field to given value.


### GetFailureCount

`func (o *OperatorRuntimeWorkerItem) GetFailureCount() int32`

GetFailureCount returns the FailureCount field if non-nil, zero value otherwise.

### GetFailureCountOk

`func (o *OperatorRuntimeWorkerItem) GetFailureCountOk() (*int32, bool)`

GetFailureCountOk returns a tuple with the FailureCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCount

`func (o *OperatorRuntimeWorkerItem) SetFailureCount(v int32)`

SetFailureCount sets FailureCount field to given value.


### GetActiveDeliveries

`func (o *OperatorRuntimeWorkerItem) GetActiveDeliveries() int32`

GetActiveDeliveries returns the ActiveDeliveries field if non-nil, zero value otherwise.

### GetActiveDeliveriesOk

`func (o *OperatorRuntimeWorkerItem) GetActiveDeliveriesOk() (*int32, bool)`

GetActiveDeliveriesOk returns a tuple with the ActiveDeliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDeliveries

`func (o *OperatorRuntimeWorkerItem) SetActiveDeliveries(v int32)`

SetActiveDeliveries sets ActiveDeliveries field to given value.


### GetIsDraining

`func (o *OperatorRuntimeWorkerItem) GetIsDraining() bool`

GetIsDraining returns the IsDraining field if non-nil, zero value otherwise.

### GetIsDrainingOk

`func (o *OperatorRuntimeWorkerItem) GetIsDrainingOk() (*bool, bool)`

GetIsDrainingOk returns a tuple with the IsDraining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDraining

`func (o *OperatorRuntimeWorkerItem) SetIsDraining(v bool)`

SetIsDraining sets IsDraining field to given value.


### GetIsStale

`func (o *OperatorRuntimeWorkerItem) GetIsStale() bool`

GetIsStale returns the IsStale field if non-nil, zero value otherwise.

### GetIsStaleOk

`func (o *OperatorRuntimeWorkerItem) GetIsStaleOk() (*bool, bool)`

GetIsStaleOk returns a tuple with the IsStale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsStale

`func (o *OperatorRuntimeWorkerItem) SetIsStale(v bool)`

SetIsStale sets IsStale field to given value.


### GetLastError

`func (o *OperatorRuntimeWorkerItem) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *OperatorRuntimeWorkerItem) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *OperatorRuntimeWorkerItem) SetLastError(v string)`

SetLastError sets LastError field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


