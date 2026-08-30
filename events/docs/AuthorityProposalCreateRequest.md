# AuthorityProposalCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopologyId** | **string** |  | 
**LeadershipTermId** | **string** |  | 
**ProposedRegionId** | **string** |  | 
**Reason** | **string** |  | 
**TtlSeconds** | Pointer to **int32** |  | [optional] [default to 60]
**Metadata** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewAuthorityProposalCreateRequest

`func NewAuthorityProposalCreateRequest(topologyId string, leadershipTermId string, proposedRegionId string, reason string, ) *AuthorityProposalCreateRequest`

NewAuthorityProposalCreateRequest instantiates a new AuthorityProposalCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorityProposalCreateRequestWithDefaults

`func NewAuthorityProposalCreateRequestWithDefaults() *AuthorityProposalCreateRequest`

NewAuthorityProposalCreateRequestWithDefaults instantiates a new AuthorityProposalCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopologyId

`func (o *AuthorityProposalCreateRequest) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *AuthorityProposalCreateRequest) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *AuthorityProposalCreateRequest) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetLeadershipTermId

`func (o *AuthorityProposalCreateRequest) GetLeadershipTermId() string`

GetLeadershipTermId returns the LeadershipTermId field if non-nil, zero value otherwise.

### GetLeadershipTermIdOk

`func (o *AuthorityProposalCreateRequest) GetLeadershipTermIdOk() (*string, bool)`

GetLeadershipTermIdOk returns a tuple with the LeadershipTermId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadershipTermId

`func (o *AuthorityProposalCreateRequest) SetLeadershipTermId(v string)`

SetLeadershipTermId sets LeadershipTermId field to given value.


### GetProposedRegionId

`func (o *AuthorityProposalCreateRequest) GetProposedRegionId() string`

GetProposedRegionId returns the ProposedRegionId field if non-nil, zero value otherwise.

### GetProposedRegionIdOk

`func (o *AuthorityProposalCreateRequest) GetProposedRegionIdOk() (*string, bool)`

GetProposedRegionIdOk returns a tuple with the ProposedRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposedRegionId

`func (o *AuthorityProposalCreateRequest) SetProposedRegionId(v string)`

SetProposedRegionId sets ProposedRegionId field to given value.


### GetReason

`func (o *AuthorityProposalCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuthorityProposalCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuthorityProposalCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetTtlSeconds

`func (o *AuthorityProposalCreateRequest) GetTtlSeconds() int32`

GetTtlSeconds returns the TtlSeconds field if non-nil, zero value otherwise.

### GetTtlSecondsOk

`func (o *AuthorityProposalCreateRequest) GetTtlSecondsOk() (*int32, bool)`

GetTtlSecondsOk returns a tuple with the TtlSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtlSeconds

`func (o *AuthorityProposalCreateRequest) SetTtlSeconds(v int32)`

SetTtlSeconds sets TtlSeconds field to given value.

### HasTtlSeconds

`func (o *AuthorityProposalCreateRequest) HasTtlSeconds() bool`

HasTtlSeconds returns a boolean if a field has been set.

### GetMetadata

`func (o *AuthorityProposalCreateRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AuthorityProposalCreateRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AuthorityProposalCreateRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AuthorityProposalCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AuthorityProposalCreateRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AuthorityProposalCreateRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


