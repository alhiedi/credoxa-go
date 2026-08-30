# LeadershipTerm

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Term** | **int64** |  | 
**TopologyRevision** | **int64** |  | 
**FencingToken** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] 
**ElectedVotingWeight** | **int64** |  | 
**QuorumWeight** | **int64** |  | 
**StartedAt** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**EndedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**Topology** | **string** |  | 
**MembershipRevision** | **string** |  | 
**Leader** | **string** |  | 
**LeaderRegion** | **string** |  | 

## Methods

### NewLeadershipTerm

`func NewLeadershipTerm(id string, organizationId string, term int64, topologyRevision int64, fencingToken string, electedVotingWeight int64, quorumWeight int64, startedAt time.Time, expiresAt time.Time, createdAt time.Time, topology string, membershipRevision string, leader string, leaderRegion string, ) *LeadershipTerm`

NewLeadershipTerm instantiates a new LeadershipTerm object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeadershipTermWithDefaults

`func NewLeadershipTermWithDefaults() *LeadershipTerm`

NewLeadershipTermWithDefaults instantiates a new LeadershipTerm object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LeadershipTerm) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LeadershipTerm) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LeadershipTerm) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *LeadershipTerm) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LeadershipTerm) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LeadershipTerm) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTerm

`func (o *LeadershipTerm) GetTerm() int64`

GetTerm returns the Term field if non-nil, zero value otherwise.

### GetTermOk

`func (o *LeadershipTerm) GetTermOk() (*int64, bool)`

GetTermOk returns a tuple with the Term field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerm

`func (o *LeadershipTerm) SetTerm(v int64)`

SetTerm sets Term field to given value.


### GetTopologyRevision

`func (o *LeadershipTerm) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *LeadershipTerm) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *LeadershipTerm) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetFencingToken

`func (o *LeadershipTerm) GetFencingToken() string`

GetFencingToken returns the FencingToken field if non-nil, zero value otherwise.

### GetFencingTokenOk

`func (o *LeadershipTerm) GetFencingTokenOk() (*string, bool)`

GetFencingTokenOk returns a tuple with the FencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFencingToken

`func (o *LeadershipTerm) SetFencingToken(v string)`

SetFencingToken sets FencingToken field to given value.


### GetStatus

`func (o *LeadershipTerm) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LeadershipTerm) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LeadershipTerm) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LeadershipTerm) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetElectedVotingWeight

`func (o *LeadershipTerm) GetElectedVotingWeight() int64`

GetElectedVotingWeight returns the ElectedVotingWeight field if non-nil, zero value otherwise.

### GetElectedVotingWeightOk

`func (o *LeadershipTerm) GetElectedVotingWeightOk() (*int64, bool)`

GetElectedVotingWeightOk returns a tuple with the ElectedVotingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElectedVotingWeight

`func (o *LeadershipTerm) SetElectedVotingWeight(v int64)`

SetElectedVotingWeight sets ElectedVotingWeight field to given value.


### GetQuorumWeight

`func (o *LeadershipTerm) GetQuorumWeight() int64`

GetQuorumWeight returns the QuorumWeight field if non-nil, zero value otherwise.

### GetQuorumWeightOk

`func (o *LeadershipTerm) GetQuorumWeightOk() (*int64, bool)`

GetQuorumWeightOk returns a tuple with the QuorumWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuorumWeight

`func (o *LeadershipTerm) SetQuorumWeight(v int64)`

SetQuorumWeight sets QuorumWeight field to given value.


### GetStartedAt

`func (o *LeadershipTerm) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *LeadershipTerm) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *LeadershipTerm) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetExpiresAt

`func (o *LeadershipTerm) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *LeadershipTerm) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *LeadershipTerm) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetEndedAt

`func (o *LeadershipTerm) GetEndedAt() time.Time`

GetEndedAt returns the EndedAt field if non-nil, zero value otherwise.

### GetEndedAtOk

`func (o *LeadershipTerm) GetEndedAtOk() (*time.Time, bool)`

GetEndedAtOk returns a tuple with the EndedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndedAt

`func (o *LeadershipTerm) SetEndedAt(v time.Time)`

SetEndedAt sets EndedAt field to given value.

### HasEndedAt

`func (o *LeadershipTerm) HasEndedAt() bool`

HasEndedAt returns a boolean if a field has been set.

### SetEndedAtNil

`func (o *LeadershipTerm) SetEndedAtNil(b bool)`

 SetEndedAtNil sets the value for EndedAt to be an explicit nil

### UnsetEndedAt
`func (o *LeadershipTerm) UnsetEndedAt()`

UnsetEndedAt ensures that no value is present for EndedAt, not even an explicit nil
### GetCreatedAt

`func (o *LeadershipTerm) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LeadershipTerm) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LeadershipTerm) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetTopology

`func (o *LeadershipTerm) GetTopology() string`

GetTopology returns the Topology field if non-nil, zero value otherwise.

### GetTopologyOk

`func (o *LeadershipTerm) GetTopologyOk() (*string, bool)`

GetTopologyOk returns a tuple with the Topology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopology

`func (o *LeadershipTerm) SetTopology(v string)`

SetTopology sets Topology field to given value.


### GetMembershipRevision

`func (o *LeadershipTerm) GetMembershipRevision() string`

GetMembershipRevision returns the MembershipRevision field if non-nil, zero value otherwise.

### GetMembershipRevisionOk

`func (o *LeadershipTerm) GetMembershipRevisionOk() (*string, bool)`

GetMembershipRevisionOk returns a tuple with the MembershipRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipRevision

`func (o *LeadershipTerm) SetMembershipRevision(v string)`

SetMembershipRevision sets MembershipRevision field to given value.


### GetLeader

`func (o *LeadershipTerm) GetLeader() string`

GetLeader returns the Leader field if non-nil, zero value otherwise.

### GetLeaderOk

`func (o *LeadershipTerm) GetLeaderOk() (*string, bool)`

GetLeaderOk returns a tuple with the Leader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeader

`func (o *LeadershipTerm) SetLeader(v string)`

SetLeader sets Leader field to given value.


### GetLeaderRegion

`func (o *LeadershipTerm) GetLeaderRegion() string`

GetLeaderRegion returns the LeaderRegion field if non-nil, zero value otherwise.

### GetLeaderRegionOk

`func (o *LeadershipTerm) GetLeaderRegionOk() (*string, bool)`

GetLeaderRegionOk returns a tuple with the LeaderRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaderRegion

`func (o *LeadershipTerm) SetLeaderRegion(v string)`

SetLeaderRegion sets LeaderRegion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


