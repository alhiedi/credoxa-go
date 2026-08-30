# TopologyReadinessSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**TopologyId** | **string** |  | 
**TopologyName** | **string** |  | 
**Status** | **string** |  | 
**ReadyRegionCount** | **int32** |  | 
**DegradedRegionCount** | **int32** |  | 
**UnavailableRegionCount** | **int32** |  | 
**UnknownRegionCount** | **int32** |  | 
**PrimaryReady** | **bool** |  | 
**WitnessReady** | **bool** |  | 
**PromotionCandidateCount** | **int32** |  | 
**EvaluatedAt** | **time.Time** |  | 
**Evidence** | **interface{}** |  | 

## Methods

### NewTopologyReadinessSnapshot

`func NewTopologyReadinessSnapshot(id string, organizationId string, topologyId string, topologyName string, status string, readyRegionCount int32, degradedRegionCount int32, unavailableRegionCount int32, unknownRegionCount int32, primaryReady bool, witnessReady bool, promotionCandidateCount int32, evaluatedAt time.Time, evidence interface{}, ) *TopologyReadinessSnapshot`

NewTopologyReadinessSnapshot instantiates a new TopologyReadinessSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopologyReadinessSnapshotWithDefaults

`func NewTopologyReadinessSnapshotWithDefaults() *TopologyReadinessSnapshot`

NewTopologyReadinessSnapshotWithDefaults instantiates a new TopologyReadinessSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TopologyReadinessSnapshot) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TopologyReadinessSnapshot) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TopologyReadinessSnapshot) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *TopologyReadinessSnapshot) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *TopologyReadinessSnapshot) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *TopologyReadinessSnapshot) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *TopologyReadinessSnapshot) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *TopologyReadinessSnapshot) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *TopologyReadinessSnapshot) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetTopologyName

`func (o *TopologyReadinessSnapshot) GetTopologyName() string`

GetTopologyName returns the TopologyName field if non-nil, zero value otherwise.

### GetTopologyNameOk

`func (o *TopologyReadinessSnapshot) GetTopologyNameOk() (*string, bool)`

GetTopologyNameOk returns a tuple with the TopologyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyName

`func (o *TopologyReadinessSnapshot) SetTopologyName(v string)`

SetTopologyName sets TopologyName field to given value.


### GetStatus

`func (o *TopologyReadinessSnapshot) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TopologyReadinessSnapshot) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TopologyReadinessSnapshot) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReadyRegionCount

`func (o *TopologyReadinessSnapshot) GetReadyRegionCount() int32`

GetReadyRegionCount returns the ReadyRegionCount field if non-nil, zero value otherwise.

### GetReadyRegionCountOk

`func (o *TopologyReadinessSnapshot) GetReadyRegionCountOk() (*int32, bool)`

GetReadyRegionCountOk returns a tuple with the ReadyRegionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadyRegionCount

`func (o *TopologyReadinessSnapshot) SetReadyRegionCount(v int32)`

SetReadyRegionCount sets ReadyRegionCount field to given value.


### GetDegradedRegionCount

`func (o *TopologyReadinessSnapshot) GetDegradedRegionCount() int32`

GetDegradedRegionCount returns the DegradedRegionCount field if non-nil, zero value otherwise.

### GetDegradedRegionCountOk

`func (o *TopologyReadinessSnapshot) GetDegradedRegionCountOk() (*int32, bool)`

GetDegradedRegionCountOk returns a tuple with the DegradedRegionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDegradedRegionCount

`func (o *TopologyReadinessSnapshot) SetDegradedRegionCount(v int32)`

SetDegradedRegionCount sets DegradedRegionCount field to given value.


### GetUnavailableRegionCount

`func (o *TopologyReadinessSnapshot) GetUnavailableRegionCount() int32`

GetUnavailableRegionCount returns the UnavailableRegionCount field if non-nil, zero value otherwise.

### GetUnavailableRegionCountOk

`func (o *TopologyReadinessSnapshot) GetUnavailableRegionCountOk() (*int32, bool)`

GetUnavailableRegionCountOk returns a tuple with the UnavailableRegionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnavailableRegionCount

`func (o *TopologyReadinessSnapshot) SetUnavailableRegionCount(v int32)`

SetUnavailableRegionCount sets UnavailableRegionCount field to given value.


### GetUnknownRegionCount

`func (o *TopologyReadinessSnapshot) GetUnknownRegionCount() int32`

GetUnknownRegionCount returns the UnknownRegionCount field if non-nil, zero value otherwise.

### GetUnknownRegionCountOk

`func (o *TopologyReadinessSnapshot) GetUnknownRegionCountOk() (*int32, bool)`

GetUnknownRegionCountOk returns a tuple with the UnknownRegionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnknownRegionCount

`func (o *TopologyReadinessSnapshot) SetUnknownRegionCount(v int32)`

SetUnknownRegionCount sets UnknownRegionCount field to given value.


### GetPrimaryReady

`func (o *TopologyReadinessSnapshot) GetPrimaryReady() bool`

GetPrimaryReady returns the PrimaryReady field if non-nil, zero value otherwise.

### GetPrimaryReadyOk

`func (o *TopologyReadinessSnapshot) GetPrimaryReadyOk() (*bool, bool)`

GetPrimaryReadyOk returns a tuple with the PrimaryReady field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryReady

`func (o *TopologyReadinessSnapshot) SetPrimaryReady(v bool)`

SetPrimaryReady sets PrimaryReady field to given value.


### GetWitnessReady

`func (o *TopologyReadinessSnapshot) GetWitnessReady() bool`

GetWitnessReady returns the WitnessReady field if non-nil, zero value otherwise.

### GetWitnessReadyOk

`func (o *TopologyReadinessSnapshot) GetWitnessReadyOk() (*bool, bool)`

GetWitnessReadyOk returns a tuple with the WitnessReady field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWitnessReady

`func (o *TopologyReadinessSnapshot) SetWitnessReady(v bool)`

SetWitnessReady sets WitnessReady field to given value.


### GetPromotionCandidateCount

`func (o *TopologyReadinessSnapshot) GetPromotionCandidateCount() int32`

GetPromotionCandidateCount returns the PromotionCandidateCount field if non-nil, zero value otherwise.

### GetPromotionCandidateCountOk

`func (o *TopologyReadinessSnapshot) GetPromotionCandidateCountOk() (*int32, bool)`

GetPromotionCandidateCountOk returns a tuple with the PromotionCandidateCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromotionCandidateCount

`func (o *TopologyReadinessSnapshot) SetPromotionCandidateCount(v int32)`

SetPromotionCandidateCount sets PromotionCandidateCount field to given value.


### GetEvaluatedAt

`func (o *TopologyReadinessSnapshot) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *TopologyReadinessSnapshot) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *TopologyReadinessSnapshot) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.


### GetEvidence

`func (o *TopologyReadinessSnapshot) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *TopologyReadinessSnapshot) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *TopologyReadinessSnapshot) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.


### SetEvidenceNil

`func (o *TopologyReadinessSnapshot) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *TopologyReadinessSnapshot) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


