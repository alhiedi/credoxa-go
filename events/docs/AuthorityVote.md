# AuthorityVote

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**ControllerId** | **string** |  | 
**Decision** | **string** |  | 
**VotingWeight** | **int64** |  | 
**LeadershipTerm** | **int64** |  | 
**TopologyRevision** | **int64** |  | 
**ObservedEpoch** | **int64** |  | 
**ObservedFencingToken** | **string** |  | 
**Reason** | Pointer to **string** |  | [optional] 
**VotedAt** | **time.Time** |  | 
**CreatedAt** | **time.Time** |  | [readonly] 
**Proposal** | **string** |  | 
**Member** | **string** |  | 
**ObservedRegion** | **string** |  | 

## Methods

### NewAuthorityVote

`func NewAuthorityVote(id string, controllerId string, decision string, votingWeight int64, leadershipTerm int64, topologyRevision int64, observedEpoch int64, observedFencingToken string, votedAt time.Time, createdAt time.Time, proposal string, member string, observedRegion string, ) *AuthorityVote`

NewAuthorityVote instantiates a new AuthorityVote object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorityVoteWithDefaults

`func NewAuthorityVoteWithDefaults() *AuthorityVote`

NewAuthorityVoteWithDefaults instantiates a new AuthorityVote object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AuthorityVote) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuthorityVote) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuthorityVote) SetId(v string)`

SetId sets Id field to given value.


### GetControllerId

`func (o *AuthorityVote) GetControllerId() string`

GetControllerId returns the ControllerId field if non-nil, zero value otherwise.

### GetControllerIdOk

`func (o *AuthorityVote) GetControllerIdOk() (*string, bool)`

GetControllerIdOk returns a tuple with the ControllerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerId

`func (o *AuthorityVote) SetControllerId(v string)`

SetControllerId sets ControllerId field to given value.


### GetDecision

`func (o *AuthorityVote) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *AuthorityVote) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *AuthorityVote) SetDecision(v string)`

SetDecision sets Decision field to given value.


### GetVotingWeight

`func (o *AuthorityVote) GetVotingWeight() int64`

GetVotingWeight returns the VotingWeight field if non-nil, zero value otherwise.

### GetVotingWeightOk

`func (o *AuthorityVote) GetVotingWeightOk() (*int64, bool)`

GetVotingWeightOk returns a tuple with the VotingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotingWeight

`func (o *AuthorityVote) SetVotingWeight(v int64)`

SetVotingWeight sets VotingWeight field to given value.


### GetLeadershipTerm

`func (o *AuthorityVote) GetLeadershipTerm() int64`

GetLeadershipTerm returns the LeadershipTerm field if non-nil, zero value otherwise.

### GetLeadershipTermOk

`func (o *AuthorityVote) GetLeadershipTermOk() (*int64, bool)`

GetLeadershipTermOk returns a tuple with the LeadershipTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadershipTerm

`func (o *AuthorityVote) SetLeadershipTerm(v int64)`

SetLeadershipTerm sets LeadershipTerm field to given value.


### GetTopologyRevision

`func (o *AuthorityVote) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *AuthorityVote) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *AuthorityVote) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetObservedEpoch

`func (o *AuthorityVote) GetObservedEpoch() int64`

GetObservedEpoch returns the ObservedEpoch field if non-nil, zero value otherwise.

### GetObservedEpochOk

`func (o *AuthorityVote) GetObservedEpochOk() (*int64, bool)`

GetObservedEpochOk returns a tuple with the ObservedEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedEpoch

`func (o *AuthorityVote) SetObservedEpoch(v int64)`

SetObservedEpoch sets ObservedEpoch field to given value.


### GetObservedFencingToken

`func (o *AuthorityVote) GetObservedFencingToken() string`

GetObservedFencingToken returns the ObservedFencingToken field if non-nil, zero value otherwise.

### GetObservedFencingTokenOk

`func (o *AuthorityVote) GetObservedFencingTokenOk() (*string, bool)`

GetObservedFencingTokenOk returns a tuple with the ObservedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedFencingToken

`func (o *AuthorityVote) SetObservedFencingToken(v string)`

SetObservedFencingToken sets ObservedFencingToken field to given value.


### GetReason

`func (o *AuthorityVote) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuthorityVote) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuthorityVote) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AuthorityVote) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetVotedAt

`func (o *AuthorityVote) GetVotedAt() time.Time`

GetVotedAt returns the VotedAt field if non-nil, zero value otherwise.

### GetVotedAtOk

`func (o *AuthorityVote) GetVotedAtOk() (*time.Time, bool)`

GetVotedAtOk returns a tuple with the VotedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotedAt

`func (o *AuthorityVote) SetVotedAt(v time.Time)`

SetVotedAt sets VotedAt field to given value.


### GetCreatedAt

`func (o *AuthorityVote) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AuthorityVote) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AuthorityVote) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetProposal

`func (o *AuthorityVote) GetProposal() string`

GetProposal returns the Proposal field if non-nil, zero value otherwise.

### GetProposalOk

`func (o *AuthorityVote) GetProposalOk() (*string, bool)`

GetProposalOk returns a tuple with the Proposal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposal

`func (o *AuthorityVote) SetProposal(v string)`

SetProposal sets Proposal field to given value.


### GetMember

`func (o *AuthorityVote) GetMember() string`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *AuthorityVote) GetMemberOk() (*string, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *AuthorityVote) SetMember(v string)`

SetMember sets Member field to given value.


### GetObservedRegion

`func (o *AuthorityVote) GetObservedRegion() string`

GetObservedRegion returns the ObservedRegion field if non-nil, zero value otherwise.

### GetObservedRegionOk

`func (o *AuthorityVote) GetObservedRegionOk() (*string, bool)`

GetObservedRegionOk returns a tuple with the ObservedRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedRegion

`func (o *AuthorityVote) SetObservedRegion(v string)`

SetObservedRegion sets ObservedRegion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


