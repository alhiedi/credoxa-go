# DisasterRecoveryDrillResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DrillId** | **string** |  | 
**OrganizationId** | **string** |  | 
**TopologyId** | **string** |  | 
**ObjectiveId** | **string** |  | 
**WorkloadName** | **string** |  | 
**Status** | **string** |  | 
**InitiatedBy** | **string** |  | 
**AvailableRecoveryRegions** | **int32** |  | 
**ProductionTrafficAffected** | **bool** |  | 
**ContextFingerprint** | **string** |  | 
**RequestedAt** | **time.Time** |  | 
**StartedAt** | **NullableTime** |  | 
**CompletedAt** | **NullableTime** |  | 
**Metadata** | **interface{}** |  | 
**RecoveryPointId** | **NullableString** |  | 

## Methods

### NewDisasterRecoveryDrillResponse

`func NewDisasterRecoveryDrillResponse(drillId string, organizationId string, topologyId string, objectiveId string, workloadName string, status string, initiatedBy string, availableRecoveryRegions int32, productionTrafficAffected bool, contextFingerprint string, requestedAt time.Time, startedAt NullableTime, completedAt NullableTime, metadata interface{}, recoveryPointId NullableString, ) *DisasterRecoveryDrillResponse`

NewDisasterRecoveryDrillResponse instantiates a new DisasterRecoveryDrillResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisasterRecoveryDrillResponseWithDefaults

`func NewDisasterRecoveryDrillResponseWithDefaults() *DisasterRecoveryDrillResponse`

NewDisasterRecoveryDrillResponseWithDefaults instantiates a new DisasterRecoveryDrillResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDrillId

`func (o *DisasterRecoveryDrillResponse) GetDrillId() string`

GetDrillId returns the DrillId field if non-nil, zero value otherwise.

### GetDrillIdOk

`func (o *DisasterRecoveryDrillResponse) GetDrillIdOk() (*string, bool)`

GetDrillIdOk returns a tuple with the DrillId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrillId

`func (o *DisasterRecoveryDrillResponse) SetDrillId(v string)`

SetDrillId sets DrillId field to given value.


### GetOrganizationId

`func (o *DisasterRecoveryDrillResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DisasterRecoveryDrillResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DisasterRecoveryDrillResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *DisasterRecoveryDrillResponse) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *DisasterRecoveryDrillResponse) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *DisasterRecoveryDrillResponse) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetObjectiveId

`func (o *DisasterRecoveryDrillResponse) GetObjectiveId() string`

GetObjectiveId returns the ObjectiveId field if non-nil, zero value otherwise.

### GetObjectiveIdOk

`func (o *DisasterRecoveryDrillResponse) GetObjectiveIdOk() (*string, bool)`

GetObjectiveIdOk returns a tuple with the ObjectiveId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectiveId

`func (o *DisasterRecoveryDrillResponse) SetObjectiveId(v string)`

SetObjectiveId sets ObjectiveId field to given value.


### GetWorkloadName

`func (o *DisasterRecoveryDrillResponse) GetWorkloadName() string`

GetWorkloadName returns the WorkloadName field if non-nil, zero value otherwise.

### GetWorkloadNameOk

`func (o *DisasterRecoveryDrillResponse) GetWorkloadNameOk() (*string, bool)`

GetWorkloadNameOk returns a tuple with the WorkloadName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkloadName

`func (o *DisasterRecoveryDrillResponse) SetWorkloadName(v string)`

SetWorkloadName sets WorkloadName field to given value.


### GetStatus

`func (o *DisasterRecoveryDrillResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DisasterRecoveryDrillResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DisasterRecoveryDrillResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetInitiatedBy

`func (o *DisasterRecoveryDrillResponse) GetInitiatedBy() string`

GetInitiatedBy returns the InitiatedBy field if non-nil, zero value otherwise.

### GetInitiatedByOk

`func (o *DisasterRecoveryDrillResponse) GetInitiatedByOk() (*string, bool)`

GetInitiatedByOk returns a tuple with the InitiatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitiatedBy

`func (o *DisasterRecoveryDrillResponse) SetInitiatedBy(v string)`

SetInitiatedBy sets InitiatedBy field to given value.


### GetAvailableRecoveryRegions

`func (o *DisasterRecoveryDrillResponse) GetAvailableRecoveryRegions() int32`

GetAvailableRecoveryRegions returns the AvailableRecoveryRegions field if non-nil, zero value otherwise.

### GetAvailableRecoveryRegionsOk

`func (o *DisasterRecoveryDrillResponse) GetAvailableRecoveryRegionsOk() (*int32, bool)`

GetAvailableRecoveryRegionsOk returns a tuple with the AvailableRecoveryRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableRecoveryRegions

`func (o *DisasterRecoveryDrillResponse) SetAvailableRecoveryRegions(v int32)`

SetAvailableRecoveryRegions sets AvailableRecoveryRegions field to given value.


### GetProductionTrafficAffected

`func (o *DisasterRecoveryDrillResponse) GetProductionTrafficAffected() bool`

GetProductionTrafficAffected returns the ProductionTrafficAffected field if non-nil, zero value otherwise.

### GetProductionTrafficAffectedOk

`func (o *DisasterRecoveryDrillResponse) GetProductionTrafficAffectedOk() (*bool, bool)`

GetProductionTrafficAffectedOk returns a tuple with the ProductionTrafficAffected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionTrafficAffected

`func (o *DisasterRecoveryDrillResponse) SetProductionTrafficAffected(v bool)`

SetProductionTrafficAffected sets ProductionTrafficAffected field to given value.


### GetContextFingerprint

`func (o *DisasterRecoveryDrillResponse) GetContextFingerprint() string`

GetContextFingerprint returns the ContextFingerprint field if non-nil, zero value otherwise.

### GetContextFingerprintOk

`func (o *DisasterRecoveryDrillResponse) GetContextFingerprintOk() (*string, bool)`

GetContextFingerprintOk returns a tuple with the ContextFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextFingerprint

`func (o *DisasterRecoveryDrillResponse) SetContextFingerprint(v string)`

SetContextFingerprint sets ContextFingerprint field to given value.


### GetRequestedAt

`func (o *DisasterRecoveryDrillResponse) GetRequestedAt() time.Time`

GetRequestedAt returns the RequestedAt field if non-nil, zero value otherwise.

### GetRequestedAtOk

`func (o *DisasterRecoveryDrillResponse) GetRequestedAtOk() (*time.Time, bool)`

GetRequestedAtOk returns a tuple with the RequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedAt

`func (o *DisasterRecoveryDrillResponse) SetRequestedAt(v time.Time)`

SetRequestedAt sets RequestedAt field to given value.


### GetStartedAt

`func (o *DisasterRecoveryDrillResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *DisasterRecoveryDrillResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *DisasterRecoveryDrillResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *DisasterRecoveryDrillResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *DisasterRecoveryDrillResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *DisasterRecoveryDrillResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *DisasterRecoveryDrillResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *DisasterRecoveryDrillResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *DisasterRecoveryDrillResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *DisasterRecoveryDrillResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetMetadata

`func (o *DisasterRecoveryDrillResponse) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DisasterRecoveryDrillResponse) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DisasterRecoveryDrillResponse) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *DisasterRecoveryDrillResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DisasterRecoveryDrillResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRecoveryPointId

`func (o *DisasterRecoveryDrillResponse) GetRecoveryPointId() string`

GetRecoveryPointId returns the RecoveryPointId field if non-nil, zero value otherwise.

### GetRecoveryPointIdOk

`func (o *DisasterRecoveryDrillResponse) GetRecoveryPointIdOk() (*string, bool)`

GetRecoveryPointIdOk returns a tuple with the RecoveryPointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPointId

`func (o *DisasterRecoveryDrillResponse) SetRecoveryPointId(v string)`

SetRecoveryPointId sets RecoveryPointId field to given value.


### SetRecoveryPointIdNil

`func (o *DisasterRecoveryDrillResponse) SetRecoveryPointIdNil(b bool)`

 SetRecoveryPointIdNil sets the value for RecoveryPointId to be an explicit nil

### UnsetRecoveryPointId
`func (o *DisasterRecoveryDrillResponse) UnsetRecoveryPointId()`

UnsetRecoveryPointId ensures that no value is present for RecoveryPointId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


