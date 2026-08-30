# AuthorityProposalDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Votes** | [**[]AuthorityVote**](AuthorityVote.md) |  | [readonly] 
**OrganizationId** | **string** |  | 
**ProposalId** | **string** |  | 
**Fingerprint** | **string** |  | 
**TopologyRevision** | **int64** |  | 
**ExpectedEpoch** | **int64** |  | 
**ExpectedFencingToken** | **string** |  | 
**ProposedEpoch** | **int64** |  | 
**ProposedFencingToken** | **string** |  | 
**Reason** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**Topology** | **string** |  | 
**LeadershipTerm** | **string** |  | 
**ExpectedRegion** | **string** |  | 
**ProposedRegion** | **string** |  | 

## Methods

### NewAuthorityProposalDetailResponse

`func NewAuthorityProposalDetailResponse(id string, votes []AuthorityVote, organizationId string, proposalId string, fingerprint string, topologyRevision int64, expectedEpoch int64, expectedFencingToken string, proposedEpoch int64, proposedFencingToken string, reason string, createdAt time.Time, expiresAt time.Time, topology string, leadershipTerm string, expectedRegion string, proposedRegion string, ) *AuthorityProposalDetailResponse`

NewAuthorityProposalDetailResponse instantiates a new AuthorityProposalDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorityProposalDetailResponseWithDefaults

`func NewAuthorityProposalDetailResponseWithDefaults() *AuthorityProposalDetailResponse`

NewAuthorityProposalDetailResponseWithDefaults instantiates a new AuthorityProposalDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AuthorityProposalDetailResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuthorityProposalDetailResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuthorityProposalDetailResponse) SetId(v string)`

SetId sets Id field to given value.


### GetVotes

`func (o *AuthorityProposalDetailResponse) GetVotes() []AuthorityVote`

GetVotes returns the Votes field if non-nil, zero value otherwise.

### GetVotesOk

`func (o *AuthorityProposalDetailResponse) GetVotesOk() (*[]AuthorityVote, bool)`

GetVotesOk returns a tuple with the Votes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVotes

`func (o *AuthorityProposalDetailResponse) SetVotes(v []AuthorityVote)`

SetVotes sets Votes field to given value.


### GetOrganizationId

`func (o *AuthorityProposalDetailResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AuthorityProposalDetailResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AuthorityProposalDetailResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProposalId

`func (o *AuthorityProposalDetailResponse) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *AuthorityProposalDetailResponse) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *AuthorityProposalDetailResponse) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### GetFingerprint

`func (o *AuthorityProposalDetailResponse) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *AuthorityProposalDetailResponse) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *AuthorityProposalDetailResponse) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetTopologyRevision

`func (o *AuthorityProposalDetailResponse) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *AuthorityProposalDetailResponse) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *AuthorityProposalDetailResponse) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetExpectedEpoch

`func (o *AuthorityProposalDetailResponse) GetExpectedEpoch() int64`

GetExpectedEpoch returns the ExpectedEpoch field if non-nil, zero value otherwise.

### GetExpectedEpochOk

`func (o *AuthorityProposalDetailResponse) GetExpectedEpochOk() (*int64, bool)`

GetExpectedEpochOk returns a tuple with the ExpectedEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedEpoch

`func (o *AuthorityProposalDetailResponse) SetExpectedEpoch(v int64)`

SetExpectedEpoch sets ExpectedEpoch field to given value.


### GetExpectedFencingToken

`func (o *AuthorityProposalDetailResponse) GetExpectedFencingToken() string`

GetExpectedFencingToken returns the ExpectedFencingToken field if non-nil, zero value otherwise.

### GetExpectedFencingTokenOk

`func (o *AuthorityProposalDetailResponse) GetExpectedFencingTokenOk() (*string, bool)`

GetExpectedFencingTokenOk returns a tuple with the ExpectedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingToken

`func (o *AuthorityProposalDetailResponse) SetExpectedFencingToken(v string)`

SetExpectedFencingToken sets ExpectedFencingToken field to given value.


### GetProposedEpoch

`func (o *AuthorityProposalDetailResponse) GetProposedEpoch() int64`

GetProposedEpoch returns the ProposedEpoch field if non-nil, zero value otherwise.

### GetProposedEpochOk

`func (o *AuthorityProposalDetailResponse) GetProposedEpochOk() (*int64, bool)`

GetProposedEpochOk returns a tuple with the ProposedEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedEpoch

`func (o *AuthorityProposalDetailResponse) SetProposedEpoch(v int64)`

SetProposedEpoch sets ProposedEpoch field to given value.


### GetProposedFencingToken

`func (o *AuthorityProposalDetailResponse) GetProposedFencingToken() string`

GetProposedFencingToken returns the ProposedFencingToken field if non-nil, zero value otherwise.

### GetProposedFencingTokenOk

`func (o *AuthorityProposalDetailResponse) GetProposedFencingTokenOk() (*string, bool)`

GetProposedFencingTokenOk returns a tuple with the ProposedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedFencingToken

`func (o *AuthorityProposalDetailResponse) SetProposedFencingToken(v string)`

SetProposedFencingToken sets ProposedFencingToken field to given value.


### GetReason

`func (o *AuthorityProposalDetailResponse) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuthorityProposalDetailResponse) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuthorityProposalDetailResponse) SetReason(v string)`

SetReason sets Reason field to given value.


### GetStatus

`func (o *AuthorityProposalDetailResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuthorityProposalDetailResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuthorityProposalDetailResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AuthorityProposalDetailResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetMetadata

`func (o *AuthorityProposalDetailResponse) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AuthorityProposalDetailResponse) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AuthorityProposalDetailResponse) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AuthorityProposalDetailResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AuthorityProposalDetailResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AuthorityProposalDetailResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *AuthorityProposalDetailResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AuthorityProposalDetailResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AuthorityProposalDetailResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExpiresAt

`func (o *AuthorityProposalDetailResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *AuthorityProposalDetailResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *AuthorityProposalDetailResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetResolvedAt

`func (o *AuthorityProposalDetailResponse) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *AuthorityProposalDetailResponse) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *AuthorityProposalDetailResponse) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *AuthorityProposalDetailResponse) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *AuthorityProposalDetailResponse) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *AuthorityProposalDetailResponse) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetTopology

`func (o *AuthorityProposalDetailResponse) GetTopology() string`

GetTopology returns the Topology field if non-nil, zero value otherwise.

### GetTopologyOk

`func (o *AuthorityProposalDetailResponse) GetTopologyOk() (*string, bool)`

GetTopologyOk returns a tuple with the Topology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopology

`func (o *AuthorityProposalDetailResponse) SetTopology(v string)`

SetTopology sets Topology field to given value.


### GetLeadershipTerm

`func (o *AuthorityProposalDetailResponse) GetLeadershipTerm() string`

GetLeadershipTerm returns the LeadershipTerm field if non-nil, zero value otherwise.

### GetLeadershipTermOk

`func (o *AuthorityProposalDetailResponse) GetLeadershipTermOk() (*string, bool)`

GetLeadershipTermOk returns a tuple with the LeadershipTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadershipTerm

`func (o *AuthorityProposalDetailResponse) SetLeadershipTerm(v string)`

SetLeadershipTerm sets LeadershipTerm field to given value.


### GetExpectedRegion

`func (o *AuthorityProposalDetailResponse) GetExpectedRegion() string`

GetExpectedRegion returns the ExpectedRegion field if non-nil, zero value otherwise.

### GetExpectedRegionOk

`func (o *AuthorityProposalDetailResponse) GetExpectedRegionOk() (*string, bool)`

GetExpectedRegionOk returns a tuple with the ExpectedRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRegion

`func (o *AuthorityProposalDetailResponse) SetExpectedRegion(v string)`

SetExpectedRegion sets ExpectedRegion field to given value.


### GetProposedRegion

`func (o *AuthorityProposalDetailResponse) GetProposedRegion() string`

GetProposedRegion returns the ProposedRegion field if non-nil, zero value otherwise.

### GetProposedRegionOk

`func (o *AuthorityProposalDetailResponse) GetProposedRegionOk() (*string, bool)`

GetProposedRegionOk returns a tuple with the ProposedRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedRegion

`func (o *AuthorityProposalDetailResponse) SetProposedRegion(v string)`

SetProposedRegion sets ProposedRegion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


