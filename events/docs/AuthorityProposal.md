# AuthorityProposal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
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

### NewAuthorityProposal

`func NewAuthorityProposal(id string, organizationId string, proposalId string, fingerprint string, topologyRevision int64, expectedEpoch int64, expectedFencingToken string, proposedEpoch int64, proposedFencingToken string, reason string, createdAt time.Time, expiresAt time.Time, topology string, leadershipTerm string, expectedRegion string, proposedRegion string, ) *AuthorityProposal`

NewAuthorityProposal instantiates a new AuthorityProposal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorityProposalWithDefaults

`func NewAuthorityProposalWithDefaults() *AuthorityProposal`

NewAuthorityProposalWithDefaults instantiates a new AuthorityProposal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AuthorityProposal) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuthorityProposal) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuthorityProposal) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *AuthorityProposal) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AuthorityProposal) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AuthorityProposal) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProposalId

`func (o *AuthorityProposal) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *AuthorityProposal) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *AuthorityProposal) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### GetFingerprint

`func (o *AuthorityProposal) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *AuthorityProposal) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *AuthorityProposal) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetTopologyRevision

`func (o *AuthorityProposal) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *AuthorityProposal) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *AuthorityProposal) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetExpectedEpoch

`func (o *AuthorityProposal) GetExpectedEpoch() int64`

GetExpectedEpoch returns the ExpectedEpoch field if non-nil, zero value otherwise.

### GetExpectedEpochOk

`func (o *AuthorityProposal) GetExpectedEpochOk() (*int64, bool)`

GetExpectedEpochOk returns a tuple with the ExpectedEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedEpoch

`func (o *AuthorityProposal) SetExpectedEpoch(v int64)`

SetExpectedEpoch sets ExpectedEpoch field to given value.


### GetExpectedFencingToken

`func (o *AuthorityProposal) GetExpectedFencingToken() string`

GetExpectedFencingToken returns the ExpectedFencingToken field if non-nil, zero value otherwise.

### GetExpectedFencingTokenOk

`func (o *AuthorityProposal) GetExpectedFencingTokenOk() (*string, bool)`

GetExpectedFencingTokenOk returns a tuple with the ExpectedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingToken

`func (o *AuthorityProposal) SetExpectedFencingToken(v string)`

SetExpectedFencingToken sets ExpectedFencingToken field to given value.


### GetProposedEpoch

`func (o *AuthorityProposal) GetProposedEpoch() int64`

GetProposedEpoch returns the ProposedEpoch field if non-nil, zero value otherwise.

### GetProposedEpochOk

`func (o *AuthorityProposal) GetProposedEpochOk() (*int64, bool)`

GetProposedEpochOk returns a tuple with the ProposedEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedEpoch

`func (o *AuthorityProposal) SetProposedEpoch(v int64)`

SetProposedEpoch sets ProposedEpoch field to given value.


### GetProposedFencingToken

`func (o *AuthorityProposal) GetProposedFencingToken() string`

GetProposedFencingToken returns the ProposedFencingToken field if non-nil, zero value otherwise.

### GetProposedFencingTokenOk

`func (o *AuthorityProposal) GetProposedFencingTokenOk() (*string, bool)`

GetProposedFencingTokenOk returns a tuple with the ProposedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedFencingToken

`func (o *AuthorityProposal) SetProposedFencingToken(v string)`

SetProposedFencingToken sets ProposedFencingToken field to given value.


### GetReason

`func (o *AuthorityProposal) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuthorityProposal) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuthorityProposal) SetReason(v string)`

SetReason sets Reason field to given value.


### GetStatus

`func (o *AuthorityProposal) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuthorityProposal) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuthorityProposal) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AuthorityProposal) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetMetadata

`func (o *AuthorityProposal) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AuthorityProposal) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AuthorityProposal) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AuthorityProposal) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AuthorityProposal) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AuthorityProposal) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *AuthorityProposal) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AuthorityProposal) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AuthorityProposal) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExpiresAt

`func (o *AuthorityProposal) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *AuthorityProposal) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *AuthorityProposal) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetResolvedAt

`func (o *AuthorityProposal) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *AuthorityProposal) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *AuthorityProposal) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *AuthorityProposal) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *AuthorityProposal) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *AuthorityProposal) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetTopology

`func (o *AuthorityProposal) GetTopology() string`

GetTopology returns the Topology field if non-nil, zero value otherwise.

### GetTopologyOk

`func (o *AuthorityProposal) GetTopologyOk() (*string, bool)`

GetTopologyOk returns a tuple with the Topology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopology

`func (o *AuthorityProposal) SetTopology(v string)`

SetTopology sets Topology field to given value.


### GetLeadershipTerm

`func (o *AuthorityProposal) GetLeadershipTerm() string`

GetLeadershipTerm returns the LeadershipTerm field if non-nil, zero value otherwise.

### GetLeadershipTermOk

`func (o *AuthorityProposal) GetLeadershipTermOk() (*string, bool)`

GetLeadershipTermOk returns a tuple with the LeadershipTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadershipTerm

`func (o *AuthorityProposal) SetLeadershipTerm(v string)`

SetLeadershipTerm sets LeadershipTerm field to given value.


### GetExpectedRegion

`func (o *AuthorityProposal) GetExpectedRegion() string`

GetExpectedRegion returns the ExpectedRegion field if non-nil, zero value otherwise.

### GetExpectedRegionOk

`func (o *AuthorityProposal) GetExpectedRegionOk() (*string, bool)`

GetExpectedRegionOk returns a tuple with the ExpectedRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRegion

`func (o *AuthorityProposal) SetExpectedRegion(v string)`

SetExpectedRegion sets ExpectedRegion field to given value.


### GetProposedRegion

`func (o *AuthorityProposal) GetProposedRegion() string`

GetProposedRegion returns the ProposedRegion field if non-nil, zero value otherwise.

### GetProposedRegionOk

`func (o *AuthorityProposal) GetProposedRegionOk() (*string, bool)`

GetProposedRegionOk returns a tuple with the ProposedRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedRegion

`func (o *AuthorityProposal) SetProposedRegion(v string)`

SetProposedRegion sets ProposedRegion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


