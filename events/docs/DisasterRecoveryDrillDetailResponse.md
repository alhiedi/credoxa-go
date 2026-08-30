# DisasterRecoveryDrillDetailResponse

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
**Compliance** | [**NullableDisasterRecoveryComplianceResponse**](DisasterRecoveryComplianceResponse.md) |  | 

## Methods

### NewDisasterRecoveryDrillDetailResponse

`func NewDisasterRecoveryDrillDetailResponse(drillId string, organizationId string, topologyId string, objectiveId string, workloadName string, status string, initiatedBy string, availableRecoveryRegions int32, productionTrafficAffected bool, contextFingerprint string, requestedAt time.Time, startedAt NullableTime, completedAt NullableTime, metadata interface{}, recoveryPointId NullableString, compliance NullableDisasterRecoveryComplianceResponse, ) *DisasterRecoveryDrillDetailResponse`

NewDisasterRecoveryDrillDetailResponse instantiates a new DisasterRecoveryDrillDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisasterRecoveryDrillDetailResponseWithDefaults

`func NewDisasterRecoveryDrillDetailResponseWithDefaults() *DisasterRecoveryDrillDetailResponse`

NewDisasterRecoveryDrillDetailResponseWithDefaults instantiates a new DisasterRecoveryDrillDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDrillId

`func (o *DisasterRecoveryDrillDetailResponse) GetDrillId() string`

GetDrillId returns the DrillId field if non-nil, zero value otherwise.

### GetDrillIdOk

`func (o *DisasterRecoveryDrillDetailResponse) GetDrillIdOk() (*string, bool)`

GetDrillIdOk returns a tuple with the DrillId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrillId

`func (o *DisasterRecoveryDrillDetailResponse) SetDrillId(v string)`

SetDrillId sets DrillId field to given value.


### GetOrganizationId

`func (o *DisasterRecoveryDrillDetailResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DisasterRecoveryDrillDetailResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DisasterRecoveryDrillDetailResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *DisasterRecoveryDrillDetailResponse) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *DisasterRecoveryDrillDetailResponse) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *DisasterRecoveryDrillDetailResponse) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetObjectiveId

`func (o *DisasterRecoveryDrillDetailResponse) GetObjectiveId() string`

GetObjectiveId returns the ObjectiveId field if non-nil, zero value otherwise.

### GetObjectiveIdOk

`func (o *DisasterRecoveryDrillDetailResponse) GetObjectiveIdOk() (*string, bool)`

GetObjectiveIdOk returns a tuple with the ObjectiveId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectiveId

`func (o *DisasterRecoveryDrillDetailResponse) SetObjectiveId(v string)`

SetObjectiveId sets ObjectiveId field to given value.


### GetWorkloadName

`func (o *DisasterRecoveryDrillDetailResponse) GetWorkloadName() string`

GetWorkloadName returns the WorkloadName field if non-nil, zero value otherwise.

### GetWorkloadNameOk

`func (o *DisasterRecoveryDrillDetailResponse) GetWorkloadNameOk() (*string, bool)`

GetWorkloadNameOk returns a tuple with the WorkloadName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkloadName

`func (o *DisasterRecoveryDrillDetailResponse) SetWorkloadName(v string)`

SetWorkloadName sets WorkloadName field to given value.


### GetStatus

`func (o *DisasterRecoveryDrillDetailResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DisasterRecoveryDrillDetailResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DisasterRecoveryDrillDetailResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetInitiatedBy

`func (o *DisasterRecoveryDrillDetailResponse) GetInitiatedBy() string`

GetInitiatedBy returns the InitiatedBy field if non-nil, zero value otherwise.

### GetInitiatedByOk

`func (o *DisasterRecoveryDrillDetailResponse) GetInitiatedByOk() (*string, bool)`

GetInitiatedByOk returns a tuple with the InitiatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitiatedBy

`func (o *DisasterRecoveryDrillDetailResponse) SetInitiatedBy(v string)`

SetInitiatedBy sets InitiatedBy field to given value.


### GetAvailableRecoveryRegions

`func (o *DisasterRecoveryDrillDetailResponse) GetAvailableRecoveryRegions() int32`

GetAvailableRecoveryRegions returns the AvailableRecoveryRegions field if non-nil, zero value otherwise.

### GetAvailableRecoveryRegionsOk

`func (o *DisasterRecoveryDrillDetailResponse) GetAvailableRecoveryRegionsOk() (*int32, bool)`

GetAvailableRecoveryRegionsOk returns a tuple with the AvailableRecoveryRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableRecoveryRegions

`func (o *DisasterRecoveryDrillDetailResponse) SetAvailableRecoveryRegions(v int32)`

SetAvailableRecoveryRegions sets AvailableRecoveryRegions field to given value.


### GetProductionTrafficAffected

`func (o *DisasterRecoveryDrillDetailResponse) GetProductionTrafficAffected() bool`

GetProductionTrafficAffected returns the ProductionTrafficAffected field if non-nil, zero value otherwise.

### GetProductionTrafficAffectedOk

`func (o *DisasterRecoveryDrillDetailResponse) GetProductionTrafficAffectedOk() (*bool, bool)`

GetProductionTrafficAffectedOk returns a tuple with the ProductionTrafficAffected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionTrafficAffected

`func (o *DisasterRecoveryDrillDetailResponse) SetProductionTrafficAffected(v bool)`

SetProductionTrafficAffected sets ProductionTrafficAffected field to given value.


### GetContextFingerprint

`func (o *DisasterRecoveryDrillDetailResponse) GetContextFingerprint() string`

GetContextFingerprint returns the ContextFingerprint field if non-nil, zero value otherwise.

### GetContextFingerprintOk

`func (o *DisasterRecoveryDrillDetailResponse) GetContextFingerprintOk() (*string, bool)`

GetContextFingerprintOk returns a tuple with the ContextFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextFingerprint

`func (o *DisasterRecoveryDrillDetailResponse) SetContextFingerprint(v string)`

SetContextFingerprint sets ContextFingerprint field to given value.


### GetRequestedAt

`func (o *DisasterRecoveryDrillDetailResponse) GetRequestedAt() time.Time`

GetRequestedAt returns the RequestedAt field if non-nil, zero value otherwise.

### GetRequestedAtOk

`func (o *DisasterRecoveryDrillDetailResponse) GetRequestedAtOk() (*time.Time, bool)`

GetRequestedAtOk returns a tuple with the RequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedAt

`func (o *DisasterRecoveryDrillDetailResponse) SetRequestedAt(v time.Time)`

SetRequestedAt sets RequestedAt field to given value.


### GetStartedAt

`func (o *DisasterRecoveryDrillDetailResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *DisasterRecoveryDrillDetailResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *DisasterRecoveryDrillDetailResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *DisasterRecoveryDrillDetailResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *DisasterRecoveryDrillDetailResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *DisasterRecoveryDrillDetailResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *DisasterRecoveryDrillDetailResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *DisasterRecoveryDrillDetailResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *DisasterRecoveryDrillDetailResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *DisasterRecoveryDrillDetailResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetMetadata

`func (o *DisasterRecoveryDrillDetailResponse) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DisasterRecoveryDrillDetailResponse) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DisasterRecoveryDrillDetailResponse) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *DisasterRecoveryDrillDetailResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DisasterRecoveryDrillDetailResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRecoveryPointId

`func (o *DisasterRecoveryDrillDetailResponse) GetRecoveryPointId() string`

GetRecoveryPointId returns the RecoveryPointId field if non-nil, zero value otherwise.

### GetRecoveryPointIdOk

`func (o *DisasterRecoveryDrillDetailResponse) GetRecoveryPointIdOk() (*string, bool)`

GetRecoveryPointIdOk returns a tuple with the RecoveryPointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPointId

`func (o *DisasterRecoveryDrillDetailResponse) SetRecoveryPointId(v string)`

SetRecoveryPointId sets RecoveryPointId field to given value.


### SetRecoveryPointIdNil

`func (o *DisasterRecoveryDrillDetailResponse) SetRecoveryPointIdNil(b bool)`

 SetRecoveryPointIdNil sets the value for RecoveryPointId to be an explicit nil

### UnsetRecoveryPointId
`func (o *DisasterRecoveryDrillDetailResponse) UnsetRecoveryPointId()`

UnsetRecoveryPointId ensures that no value is present for RecoveryPointId, not even an explicit nil
### GetCompliance

`func (o *DisasterRecoveryDrillDetailResponse) GetCompliance() DisasterRecoveryComplianceResponse`

GetCompliance returns the Compliance field if non-nil, zero value otherwise.

### GetComplianceOk

`func (o *DisasterRecoveryDrillDetailResponse) GetComplianceOk() (*DisasterRecoveryComplianceResponse, bool)`

GetComplianceOk returns a tuple with the Compliance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompliance

`func (o *DisasterRecoveryDrillDetailResponse) SetCompliance(v DisasterRecoveryComplianceResponse)`

SetCompliance sets Compliance field to given value.


### SetComplianceNil

`func (o *DisasterRecoveryDrillDetailResponse) SetComplianceNil(b bool)`

 SetComplianceNil sets the value for Compliance to be an explicit nil

### UnsetCompliance
`func (o *DisasterRecoveryDrillDetailResponse) UnsetCompliance()`

UnsetCompliance ensures that no value is present for Compliance, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


