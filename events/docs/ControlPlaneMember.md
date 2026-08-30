# ControlPlaneMember

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | [readonly] 
**TopologyId** | **string** |  | [readonly] 
**RegionId** | **string** |  | [readonly] 
**ControllerId** | **string** |  | 
**Role** | **string** |  | 
**State** | Pointer to **string** |  | [optional] 
**Priority** | Pointer to **int64** |  | [optional] 
**VotingWeight** | Pointer to **int64** |  | [optional] 
**FailureDomain** | **string** |  | 
**RegistrationRevision** | **int32** |  | [readonly] 
**LastSeenAt** | **time.Time** |  | 
**FencedAt** | **NullableTime** |  | [readonly] 
**RetiredAt** | **NullableTime** |  | [readonly] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewControlPlaneMember

`func NewControlPlaneMember(id string, organizationId string, topologyId string, regionId string, controllerId string, role string, failureDomain string, registrationRevision int32, lastSeenAt time.Time, fencedAt NullableTime, retiredAt NullableTime, createdAt time.Time, updatedAt time.Time, ) *ControlPlaneMember`

NewControlPlaneMember instantiates a new ControlPlaneMember object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlaneMemberWithDefaults

`func NewControlPlaneMemberWithDefaults() *ControlPlaneMember`

NewControlPlaneMemberWithDefaults instantiates a new ControlPlaneMember object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ControlPlaneMember) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ControlPlaneMember) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ControlPlaneMember) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *ControlPlaneMember) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ControlPlaneMember) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ControlPlaneMember) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *ControlPlaneMember) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *ControlPlaneMember) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *ControlPlaneMember) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetRegionId

`func (o *ControlPlaneMember) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *ControlPlaneMember) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *ControlPlaneMember) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.


### GetControllerId

`func (o *ControlPlaneMember) GetControllerId() string`

GetControllerId returns the ControllerId field if non-nil, zero value otherwise.

### GetControllerIdOk

`func (o *ControlPlaneMember) GetControllerIdOk() (*string, bool)`

GetControllerIdOk returns a tuple with the ControllerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerId

`func (o *ControlPlaneMember) SetControllerId(v string)`

SetControllerId sets ControllerId field to given value.


### GetRole

`func (o *ControlPlaneMember) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ControlPlaneMember) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ControlPlaneMember) SetRole(v string)`

SetRole sets Role field to given value.


### GetState

`func (o *ControlPlaneMember) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ControlPlaneMember) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ControlPlaneMember) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ControlPlaneMember) HasState() bool`

HasState returns a boolean if a field has been set.

### GetPriority

`func (o *ControlPlaneMember) GetPriority() int64`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ControlPlaneMember) GetPriorityOk() (*int64, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ControlPlaneMember) SetPriority(v int64)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ControlPlaneMember) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetVotingWeight

`func (o *ControlPlaneMember) GetVotingWeight() int64`

GetVotingWeight returns the VotingWeight field if non-nil, zero value otherwise.

### GetVotingWeightOk

`func (o *ControlPlaneMember) GetVotingWeightOk() (*int64, bool)`

GetVotingWeightOk returns a tuple with the VotingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotingWeight

`func (o *ControlPlaneMember) SetVotingWeight(v int64)`

SetVotingWeight sets VotingWeight field to given value.

### HasVotingWeight

`func (o *ControlPlaneMember) HasVotingWeight() bool`

HasVotingWeight returns a boolean if a field has been set.

### GetFailureDomain

`func (o *ControlPlaneMember) GetFailureDomain() string`

GetFailureDomain returns the FailureDomain field if non-nil, zero value otherwise.

### GetFailureDomainOk

`func (o *ControlPlaneMember) GetFailureDomainOk() (*string, bool)`

GetFailureDomainOk returns a tuple with the FailureDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureDomain

`func (o *ControlPlaneMember) SetFailureDomain(v string)`

SetFailureDomain sets FailureDomain field to given value.


### GetRegistrationRevision

`func (o *ControlPlaneMember) GetRegistrationRevision() int32`

GetRegistrationRevision returns the RegistrationRevision field if non-nil, zero value otherwise.

### GetRegistrationRevisionOk

`func (o *ControlPlaneMember) GetRegistrationRevisionOk() (*int32, bool)`

GetRegistrationRevisionOk returns a tuple with the RegistrationRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistrationRevision

`func (o *ControlPlaneMember) SetRegistrationRevision(v int32)`

SetRegistrationRevision sets RegistrationRevision field to given value.


### GetLastSeenAt

`func (o *ControlPlaneMember) GetLastSeenAt() time.Time`

GetLastSeenAt returns the LastSeenAt field if non-nil, zero value otherwise.

### GetLastSeenAtOk

`func (o *ControlPlaneMember) GetLastSeenAtOk() (*time.Time, bool)`

GetLastSeenAtOk returns a tuple with the LastSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenAt

`func (o *ControlPlaneMember) SetLastSeenAt(v time.Time)`

SetLastSeenAt sets LastSeenAt field to given value.


### GetFencedAt

`func (o *ControlPlaneMember) GetFencedAt() time.Time`

GetFencedAt returns the FencedAt field if non-nil, zero value otherwise.

### GetFencedAtOk

`func (o *ControlPlaneMember) GetFencedAtOk() (*time.Time, bool)`

GetFencedAtOk returns a tuple with the FencedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFencedAt

`func (o *ControlPlaneMember) SetFencedAt(v time.Time)`

SetFencedAt sets FencedAt field to given value.


### SetFencedAtNil

`func (o *ControlPlaneMember) SetFencedAtNil(b bool)`

 SetFencedAtNil sets the value for FencedAt to be an explicit nil

### UnsetFencedAt
`func (o *ControlPlaneMember) UnsetFencedAt()`

UnsetFencedAt ensures that no value is present for FencedAt, not even an explicit nil
### GetRetiredAt

`func (o *ControlPlaneMember) GetRetiredAt() time.Time`

GetRetiredAt returns the RetiredAt field if non-nil, zero value otherwise.

### GetRetiredAtOk

`func (o *ControlPlaneMember) GetRetiredAtOk() (*time.Time, bool)`

GetRetiredAtOk returns a tuple with the RetiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetiredAt

`func (o *ControlPlaneMember) SetRetiredAt(v time.Time)`

SetRetiredAt sets RetiredAt field to given value.


### SetRetiredAtNil

`func (o *ControlPlaneMember) SetRetiredAtNil(b bool)`

 SetRetiredAtNil sets the value for RetiredAt to be an explicit nil

### UnsetRetiredAt
`func (o *ControlPlaneMember) UnsetRetiredAt()`

UnsetRetiredAt ensures that no value is present for RetiredAt, not even an explicit nil
### GetMetadata

`func (o *ControlPlaneMember) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ControlPlaneMember) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ControlPlaneMember) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ControlPlaneMember) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ControlPlaneMember) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ControlPlaneMember) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *ControlPlaneMember) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ControlPlaneMember) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ControlPlaneMember) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ControlPlaneMember) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ControlPlaneMember) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ControlPlaneMember) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


