# ConvergenceSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Divergences** | [**[]Divergence**](Divergence.md) |  | [readonly] 
**OrganizationId** | **string** |  | 
**Fingerprint** | **string** |  | 
**TopologyRevision** | **int64** |  | 
**ExpectedEpoch** | **int64** |  | 
**ExpectedFencingToken** | **string** |  | 
**Status** | **string** |  | 
**ReachableVotingWeight** | **int64** |  | 
**QuorumWeight** | **int64** |  | 
**ObservationCount** | **int64** |  | 
**DivergenceCount** | **int64** |  | 
**EvaluatedAt** | **time.Time** |  | 
**CreatedAt** | **time.Time** |  | [readonly] 
**Topology** | **string** |  | 
**LeadershipTerm** | **string** |  | 
**ExpectedRegion** | **string** |  | 

## Methods

### NewConvergenceSnapshot

`func NewConvergenceSnapshot(id string, divergences []Divergence, organizationId string, fingerprint string, topologyRevision int64, expectedEpoch int64, expectedFencingToken string, status string, reachableVotingWeight int64, quorumWeight int64, observationCount int64, divergenceCount int64, evaluatedAt time.Time, createdAt time.Time, topology string, leadershipTerm string, expectedRegion string, ) *ConvergenceSnapshot`

NewConvergenceSnapshot instantiates a new ConvergenceSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConvergenceSnapshotWithDefaults

`func NewConvergenceSnapshotWithDefaults() *ConvergenceSnapshot`

NewConvergenceSnapshotWithDefaults instantiates a new ConvergenceSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ConvergenceSnapshot) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConvergenceSnapshot) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConvergenceSnapshot) SetId(v string)`

SetId sets Id field to given value.


### GetDivergences

`func (o *ConvergenceSnapshot) GetDivergences() []Divergence`

GetDivergences returns the Divergences field if non-nil, zero value otherwise.

### GetDivergencesOk

`func (o *ConvergenceSnapshot) GetDivergencesOk() (*[]Divergence, bool)`

GetDivergencesOk returns a tuple with the Divergences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivergences

`func (o *ConvergenceSnapshot) SetDivergences(v []Divergence)`

SetDivergences sets Divergences field to given value.


### GetOrganizationId

`func (o *ConvergenceSnapshot) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ConvergenceSnapshot) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ConvergenceSnapshot) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetFingerprint

`func (o *ConvergenceSnapshot) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *ConvergenceSnapshot) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *ConvergenceSnapshot) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetTopologyRevision

`func (o *ConvergenceSnapshot) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *ConvergenceSnapshot) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *ConvergenceSnapshot) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetExpectedEpoch

`func (o *ConvergenceSnapshot) GetExpectedEpoch() int64`

GetExpectedEpoch returns the ExpectedEpoch field if non-nil, zero value otherwise.

### GetExpectedEpochOk

`func (o *ConvergenceSnapshot) GetExpectedEpochOk() (*int64, bool)`

GetExpectedEpochOk returns a tuple with the ExpectedEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedEpoch

`func (o *ConvergenceSnapshot) SetExpectedEpoch(v int64)`

SetExpectedEpoch sets ExpectedEpoch field to given value.


### GetExpectedFencingToken

`func (o *ConvergenceSnapshot) GetExpectedFencingToken() string`

GetExpectedFencingToken returns the ExpectedFencingToken field if non-nil, zero value otherwise.

### GetExpectedFencingTokenOk

`func (o *ConvergenceSnapshot) GetExpectedFencingTokenOk() (*string, bool)`

GetExpectedFencingTokenOk returns a tuple with the ExpectedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingToken

`func (o *ConvergenceSnapshot) SetExpectedFencingToken(v string)`

SetExpectedFencingToken sets ExpectedFencingToken field to given value.


### GetStatus

`func (o *ConvergenceSnapshot) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ConvergenceSnapshot) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ConvergenceSnapshot) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReachableVotingWeight

`func (o *ConvergenceSnapshot) GetReachableVotingWeight() int64`

GetReachableVotingWeight returns the ReachableVotingWeight field if non-nil, zero value otherwise.

### GetReachableVotingWeightOk

`func (o *ConvergenceSnapshot) GetReachableVotingWeightOk() (*int64, bool)`

GetReachableVotingWeightOk returns a tuple with the ReachableVotingWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReachableVotingWeight

`func (o *ConvergenceSnapshot) SetReachableVotingWeight(v int64)`

SetReachableVotingWeight sets ReachableVotingWeight field to given value.


### GetQuorumWeight

`func (o *ConvergenceSnapshot) GetQuorumWeight() int64`

GetQuorumWeight returns the QuorumWeight field if non-nil, zero value otherwise.

### GetQuorumWeightOk

`func (o *ConvergenceSnapshot) GetQuorumWeightOk() (*int64, bool)`

GetQuorumWeightOk returns a tuple with the QuorumWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuorumWeight

`func (o *ConvergenceSnapshot) SetQuorumWeight(v int64)`

SetQuorumWeight sets QuorumWeight field to given value.


### GetObservationCount

`func (o *ConvergenceSnapshot) GetObservationCount() int64`

GetObservationCount returns the ObservationCount field if non-nil, zero value otherwise.

### GetObservationCountOk

`func (o *ConvergenceSnapshot) GetObservationCountOk() (*int64, bool)`

GetObservationCountOk returns a tuple with the ObservationCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservationCount

`func (o *ConvergenceSnapshot) SetObservationCount(v int64)`

SetObservationCount sets ObservationCount field to given value.


### GetDivergenceCount

`func (o *ConvergenceSnapshot) GetDivergenceCount() int64`

GetDivergenceCount returns the DivergenceCount field if non-nil, zero value otherwise.

### GetDivergenceCountOk

`func (o *ConvergenceSnapshot) GetDivergenceCountOk() (*int64, bool)`

GetDivergenceCountOk returns a tuple with the DivergenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivergenceCount

`func (o *ConvergenceSnapshot) SetDivergenceCount(v int64)`

SetDivergenceCount sets DivergenceCount field to given value.


### GetEvaluatedAt

`func (o *ConvergenceSnapshot) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *ConvergenceSnapshot) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *ConvergenceSnapshot) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.


### GetCreatedAt

`func (o *ConvergenceSnapshot) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ConvergenceSnapshot) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ConvergenceSnapshot) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetTopology

`func (o *ConvergenceSnapshot) GetTopology() string`

GetTopology returns the Topology field if non-nil, zero value otherwise.

### GetTopologyOk

`func (o *ConvergenceSnapshot) GetTopologyOk() (*string, bool)`

GetTopologyOk returns a tuple with the Topology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopology

`func (o *ConvergenceSnapshot) SetTopology(v string)`

SetTopology sets Topology field to given value.


### GetLeadershipTerm

`func (o *ConvergenceSnapshot) GetLeadershipTerm() string`

GetLeadershipTerm returns the LeadershipTerm field if non-nil, zero value otherwise.

### GetLeadershipTermOk

`func (o *ConvergenceSnapshot) GetLeadershipTermOk() (*string, bool)`

GetLeadershipTermOk returns a tuple with the LeadershipTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadershipTerm

`func (o *ConvergenceSnapshot) SetLeadershipTerm(v string)`

SetLeadershipTerm sets LeadershipTerm field to given value.


### GetExpectedRegion

`func (o *ConvergenceSnapshot) GetExpectedRegion() string`

GetExpectedRegion returns the ExpectedRegion field if non-nil, zero value otherwise.

### GetExpectedRegionOk

`func (o *ConvergenceSnapshot) GetExpectedRegionOk() (*string, bool)`

GetExpectedRegionOk returns a tuple with the ExpectedRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRegion

`func (o *ConvergenceSnapshot) SetExpectedRegion(v string)`

SetExpectedRegion sets ExpectedRegion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


