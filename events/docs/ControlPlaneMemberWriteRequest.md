# ControlPlaneMemberWriteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopologyId** | **string** |  | 
**RegionId** | **string** |  | 
**ControllerId** | **string** |  | 
**Role** | [**RoleEnum**](RoleEnum.md) |  | 
**State** | Pointer to [**RegionalControlPlaneStateEnum**](RegionalControlPlaneStateEnum.md) |  | [optional] [default to REGIONALCONTROLPLANESTATEENUM_ACTIVE]
**Priority** | Pointer to **int32** |  | [optional] [default to 100]
**VotingWeight** | Pointer to **int32** |  | [optional] [default to 1]
**FailureDomain** | **string** |  | 
**Metadata** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewControlPlaneMemberWriteRequest

`func NewControlPlaneMemberWriteRequest(topologyId string, regionId string, controllerId string, role RoleEnum, failureDomain string, ) *ControlPlaneMemberWriteRequest`

NewControlPlaneMemberWriteRequest instantiates a new ControlPlaneMemberWriteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlaneMemberWriteRequestWithDefaults

`func NewControlPlaneMemberWriteRequestWithDefaults() *ControlPlaneMemberWriteRequest`

NewControlPlaneMemberWriteRequestWithDefaults instantiates a new ControlPlaneMemberWriteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopologyId

`func (o *ControlPlaneMemberWriteRequest) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *ControlPlaneMemberWriteRequest) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *ControlPlaneMemberWriteRequest) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetRegionId

`func (o *ControlPlaneMemberWriteRequest) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *ControlPlaneMemberWriteRequest) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *ControlPlaneMemberWriteRequest) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.


### GetControllerId

`func (o *ControlPlaneMemberWriteRequest) GetControllerId() string`

GetControllerId returns the ControllerId field if non-nil, zero value otherwise.

### GetControllerIdOk

`func (o *ControlPlaneMemberWriteRequest) GetControllerIdOk() (*string, bool)`

GetControllerIdOk returns a tuple with the ControllerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerId

`func (o *ControlPlaneMemberWriteRequest) SetControllerId(v string)`

SetControllerId sets ControllerId field to given value.


### GetRole

`func (o *ControlPlaneMemberWriteRequest) GetRole() RoleEnum`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ControlPlaneMemberWriteRequest) GetRoleOk() (*RoleEnum, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ControlPlaneMemberWriteRequest) SetRole(v RoleEnum)`

SetRole sets Role field to given value.


### GetState

`func (o *ControlPlaneMemberWriteRequest) GetState() RegionalControlPlaneStateEnum`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ControlPlaneMemberWriteRequest) GetStateOk() (*RegionalControlPlaneStateEnum, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ControlPlaneMemberWriteRequest) SetState(v RegionalControlPlaneStateEnum)`

SetState sets State field to given value.

### HasState

`func (o *ControlPlaneMemberWriteRequest) HasState() bool`

HasState returns a boolean if a field has been set.

### GetPriority

`func (o *ControlPlaneMemberWriteRequest) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ControlPlaneMemberWriteRequest) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ControlPlaneMemberWriteRequest) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ControlPlaneMemberWriteRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetVotingWeight

`func (o *ControlPlaneMemberWriteRequest) GetVotingWeight() int32`

GetVotingWeight returns the VotingWeight field if non-nil, zero value otherwise.

### GetVotingWeightOk

`func (o *ControlPlaneMemberWriteRequest) GetVotingWeightOk() (*int32, bool)`

GetVotingWeightOk returns a tuple with the VotingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotingWeight

`func (o *ControlPlaneMemberWriteRequest) SetVotingWeight(v int32)`

SetVotingWeight sets VotingWeight field to given value.

### HasVotingWeight

`func (o *ControlPlaneMemberWriteRequest) HasVotingWeight() bool`

HasVotingWeight returns a boolean if a field has been set.

### GetFailureDomain

`func (o *ControlPlaneMemberWriteRequest) GetFailureDomain() string`

GetFailureDomain returns the FailureDomain field if non-nil, zero value otherwise.

### GetFailureDomainOk

`func (o *ControlPlaneMemberWriteRequest) GetFailureDomainOk() (*string, bool)`

GetFailureDomainOk returns a tuple with the FailureDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureDomain

`func (o *ControlPlaneMemberWriteRequest) SetFailureDomain(v string)`

SetFailureDomain sets FailureDomain field to given value.


### GetMetadata

`func (o *ControlPlaneMemberWriteRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ControlPlaneMemberWriteRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ControlPlaneMemberWriteRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ControlPlaneMemberWriteRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ControlPlaneMemberWriteRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ControlPlaneMemberWriteRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


