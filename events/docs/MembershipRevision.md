# MembershipRevision

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Revision** | **int64** |  | 
**TopologyRevision** | **int64** |  | 
**Fingerprint** | **string** |  | 
**MemberCount** | **int64** |  | 
**TotalVotingWeight** | **int64** |  | 
**QuorumWeight** | **int64** |  | 
**MinimumFailureDomains** | **int64** |  | 
**WitnessRequired** | Pointer to **bool** |  | [optional] 
**Configuration** | Pointer to **interface{}** |  | [optional] 
**CreatedBy** | Pointer to **string** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**Topology** | **string** |  | 

## Methods

### NewMembershipRevision

`func NewMembershipRevision(id string, organizationId string, revision int64, topologyRevision int64, fingerprint string, memberCount int64, totalVotingWeight int64, quorumWeight int64, minimumFailureDomains int64, createdAt time.Time, topology string, ) *MembershipRevision`

NewMembershipRevision instantiates a new MembershipRevision object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMembershipRevisionWithDefaults

`func NewMembershipRevisionWithDefaults() *MembershipRevision`

NewMembershipRevisionWithDefaults instantiates a new MembershipRevision object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MembershipRevision) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MembershipRevision) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MembershipRevision) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *MembershipRevision) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *MembershipRevision) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *MembershipRevision) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRevision

`func (o *MembershipRevision) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *MembershipRevision) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *MembershipRevision) SetRevision(v int64)`

SetRevision sets Revision field to given value.


### GetTopologyRevision

`func (o *MembershipRevision) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *MembershipRevision) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *MembershipRevision) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetFingerprint

`func (o *MembershipRevision) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *MembershipRevision) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *MembershipRevision) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetMemberCount

`func (o *MembershipRevision) GetMemberCount() int64`

GetMemberCount returns the MemberCount field if non-nil, zero value otherwise.

### GetMemberCountOk

`func (o *MembershipRevision) GetMemberCountOk() (*int64, bool)`

GetMemberCountOk returns a tuple with the MemberCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberCount

`func (o *MembershipRevision) SetMemberCount(v int64)`

SetMemberCount sets MemberCount field to given value.


### GetTotalVotingWeight

`func (o *MembershipRevision) GetTotalVotingWeight() int64`

GetTotalVotingWeight returns the TotalVotingWeight field if non-nil, zero value otherwise.

### GetTotalVotingWeightOk

`func (o *MembershipRevision) GetTotalVotingWeightOk() (*int64, bool)`

GetTotalVotingWeightOk returns a tuple with the TotalVotingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalVotingWeight

`func (o *MembershipRevision) SetTotalVotingWeight(v int64)`

SetTotalVotingWeight sets TotalVotingWeight field to given value.


### GetQuorumWeight

`func (o *MembershipRevision) GetQuorumWeight() int64`

GetQuorumWeight returns the QuorumWeight field if non-nil, zero value otherwise.

### GetQuorumWeightOk

`func (o *MembershipRevision) GetQuorumWeightOk() (*int64, bool)`

GetQuorumWeightOk returns a tuple with the QuorumWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuorumWeight

`func (o *MembershipRevision) SetQuorumWeight(v int64)`

SetQuorumWeight sets QuorumWeight field to given value.


### GetMinimumFailureDomains

`func (o *MembershipRevision) GetMinimumFailureDomains() int64`

GetMinimumFailureDomains returns the MinimumFailureDomains field if non-nil, zero value otherwise.

### GetMinimumFailureDomainsOk

`func (o *MembershipRevision) GetMinimumFailureDomainsOk() (*int64, bool)`

GetMinimumFailureDomainsOk returns a tuple with the MinimumFailureDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumFailureDomains

`func (o *MembershipRevision) SetMinimumFailureDomains(v int64)`

SetMinimumFailureDomains sets MinimumFailureDomains field to given value.


### GetWitnessRequired

`func (o *MembershipRevision) GetWitnessRequired() bool`

GetWitnessRequired returns the WitnessRequired field if non-nil, zero value otherwise.

### GetWitnessRequiredOk

`func (o *MembershipRevision) GetWitnessRequiredOk() (*bool, bool)`

GetWitnessRequiredOk returns a tuple with the WitnessRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWitnessRequired

`func (o *MembershipRevision) SetWitnessRequired(v bool)`

SetWitnessRequired sets WitnessRequired field to given value.

### HasWitnessRequired

`func (o *MembershipRevision) HasWitnessRequired() bool`

HasWitnessRequired returns a boolean if a field has been set.

### GetConfiguration

`func (o *MembershipRevision) GetConfiguration() interface{}`

GetConfiguration returns the Configuration field if non-nil, zero value otherwise.

### GetConfigurationOk

`func (o *MembershipRevision) GetConfigurationOk() (*interface{}, bool)`

GetConfigurationOk returns a tuple with the Configuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguration

`func (o *MembershipRevision) SetConfiguration(v interface{})`

SetConfiguration sets Configuration field to given value.

### HasConfiguration

`func (o *MembershipRevision) HasConfiguration() bool`

HasConfiguration returns a boolean if a field has been set.

### SetConfigurationNil

`func (o *MembershipRevision) SetConfigurationNil(b bool)`

 SetConfigurationNil sets the value for Configuration to be an explicit nil

### UnsetConfiguration
`func (o *MembershipRevision) UnsetConfiguration()`

UnsetConfiguration ensures that no value is present for Configuration, not even an explicit nil
### GetCreatedBy

`func (o *MembershipRevision) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *MembershipRevision) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *MembershipRevision) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *MembershipRevision) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *MembershipRevision) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MembershipRevision) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MembershipRevision) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetTopology

`func (o *MembershipRevision) GetTopology() string`

GetTopology returns the Topology field if non-nil, zero value otherwise.

### GetTopologyOk

`func (o *MembershipRevision) GetTopologyOk() (*string, bool)`

GetTopologyOk returns a tuple with the Topology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopology

`func (o *MembershipRevision) SetTopology(v string)`

SetTopology sets Topology field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


