# DisasterRecoveryObjectiveResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectiveId** | **string** |  | 
**OrganizationId** | **string** |  | 
**TopologyId** | **string** |  | 
**WorkloadName** | **string** |  | 
**Criticality** | **string** |  | 
**Status** | **string** |  | 
**RpoSeconds** | **int32** |  | 
**RtoSeconds** | **int32** |  | 
**MaximumRecoveryPointAgeSeconds** | **int32** |  | 
**MinimumRecoveryRegions** | **int32** |  | 
**RequireVerifiedBackup** | **bool** |  | 
**RequireCrossRegionCopy** | **bool** |  | 
**RequireRestoreValidation** | **bool** |  | 
**PolicyRevision** | **int32** |  | 
**Fingerprint** | **string** |  | 
**Metadata** | **interface{}** |  | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewDisasterRecoveryObjectiveResponse

`func NewDisasterRecoveryObjectiveResponse(objectiveId string, organizationId string, topologyId string, workloadName string, criticality string, status string, rpoSeconds int32, rtoSeconds int32, maximumRecoveryPointAgeSeconds int32, minimumRecoveryRegions int32, requireVerifiedBackup bool, requireCrossRegionCopy bool, requireRestoreValidation bool, policyRevision int32, fingerprint string, metadata interface{}, createdAt time.Time, updatedAt time.Time, ) *DisasterRecoveryObjectiveResponse`

NewDisasterRecoveryObjectiveResponse instantiates a new DisasterRecoveryObjectiveResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisasterRecoveryObjectiveResponseWithDefaults

`func NewDisasterRecoveryObjectiveResponseWithDefaults() *DisasterRecoveryObjectiveResponse`

NewDisasterRecoveryObjectiveResponseWithDefaults instantiates a new DisasterRecoveryObjectiveResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetObjectiveId

`func (o *DisasterRecoveryObjectiveResponse) GetObjectiveId() string`

GetObjectiveId returns the ObjectiveId field if non-nil, zero value otherwise.

### GetObjectiveIdOk

`func (o *DisasterRecoveryObjectiveResponse) GetObjectiveIdOk() (*string, bool)`

GetObjectiveIdOk returns a tuple with the ObjectiveId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectiveId

`func (o *DisasterRecoveryObjectiveResponse) SetObjectiveId(v string)`

SetObjectiveId sets ObjectiveId field to given value.


### GetOrganizationId

`func (o *DisasterRecoveryObjectiveResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DisasterRecoveryObjectiveResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DisasterRecoveryObjectiveResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *DisasterRecoveryObjectiveResponse) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *DisasterRecoveryObjectiveResponse) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *DisasterRecoveryObjectiveResponse) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetWorkloadName

`func (o *DisasterRecoveryObjectiveResponse) GetWorkloadName() string`

GetWorkloadName returns the WorkloadName field if non-nil, zero value otherwise.

### GetWorkloadNameOk

`func (o *DisasterRecoveryObjectiveResponse) GetWorkloadNameOk() (*string, bool)`

GetWorkloadNameOk returns a tuple with the WorkloadName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkloadName

`func (o *DisasterRecoveryObjectiveResponse) SetWorkloadName(v string)`

SetWorkloadName sets WorkloadName field to given value.


### GetCriticality

`func (o *DisasterRecoveryObjectiveResponse) GetCriticality() string`

GetCriticality returns the Criticality field if non-nil, zero value otherwise.

### GetCriticalityOk

`func (o *DisasterRecoveryObjectiveResponse) GetCriticalityOk() (*string, bool)`

GetCriticalityOk returns a tuple with the Criticality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCriticality

`func (o *DisasterRecoveryObjectiveResponse) SetCriticality(v string)`

SetCriticality sets Criticality field to given value.


### GetStatus

`func (o *DisasterRecoveryObjectiveResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DisasterRecoveryObjectiveResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DisasterRecoveryObjectiveResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetRpoSeconds

`func (o *DisasterRecoveryObjectiveResponse) GetRpoSeconds() int32`

GetRpoSeconds returns the RpoSeconds field if non-nil, zero value otherwise.

### GetRpoSecondsOk

`func (o *DisasterRecoveryObjectiveResponse) GetRpoSecondsOk() (*int32, bool)`

GetRpoSecondsOk returns a tuple with the RpoSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRpoSeconds

`func (o *DisasterRecoveryObjectiveResponse) SetRpoSeconds(v int32)`

SetRpoSeconds sets RpoSeconds field to given value.


### GetRtoSeconds

`func (o *DisasterRecoveryObjectiveResponse) GetRtoSeconds() int32`

GetRtoSeconds returns the RtoSeconds field if non-nil, zero value otherwise.

### GetRtoSecondsOk

`func (o *DisasterRecoveryObjectiveResponse) GetRtoSecondsOk() (*int32, bool)`

GetRtoSecondsOk returns a tuple with the RtoSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRtoSeconds

`func (o *DisasterRecoveryObjectiveResponse) SetRtoSeconds(v int32)`

SetRtoSeconds sets RtoSeconds field to given value.


### GetMaximumRecoveryPointAgeSeconds

`func (o *DisasterRecoveryObjectiveResponse) GetMaximumRecoveryPointAgeSeconds() int32`

GetMaximumRecoveryPointAgeSeconds returns the MaximumRecoveryPointAgeSeconds field if non-nil, zero value otherwise.

### GetMaximumRecoveryPointAgeSecondsOk

`func (o *DisasterRecoveryObjectiveResponse) GetMaximumRecoveryPointAgeSecondsOk() (*int32, bool)`

GetMaximumRecoveryPointAgeSecondsOk returns a tuple with the MaximumRecoveryPointAgeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRecoveryPointAgeSeconds

`func (o *DisasterRecoveryObjectiveResponse) SetMaximumRecoveryPointAgeSeconds(v int32)`

SetMaximumRecoveryPointAgeSeconds sets MaximumRecoveryPointAgeSeconds field to given value.


### GetMinimumRecoveryRegions

`func (o *DisasterRecoveryObjectiveResponse) GetMinimumRecoveryRegions() int32`

GetMinimumRecoveryRegions returns the MinimumRecoveryRegions field if non-nil, zero value otherwise.

### GetMinimumRecoveryRegionsOk

`func (o *DisasterRecoveryObjectiveResponse) GetMinimumRecoveryRegionsOk() (*int32, bool)`

GetMinimumRecoveryRegionsOk returns a tuple with the MinimumRecoveryRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumRecoveryRegions

`func (o *DisasterRecoveryObjectiveResponse) SetMinimumRecoveryRegions(v int32)`

SetMinimumRecoveryRegions sets MinimumRecoveryRegions field to given value.


### GetRequireVerifiedBackup

`func (o *DisasterRecoveryObjectiveResponse) GetRequireVerifiedBackup() bool`

GetRequireVerifiedBackup returns the RequireVerifiedBackup field if non-nil, zero value otherwise.

### GetRequireVerifiedBackupOk

`func (o *DisasterRecoveryObjectiveResponse) GetRequireVerifiedBackupOk() (*bool, bool)`

GetRequireVerifiedBackupOk returns a tuple with the RequireVerifiedBackup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireVerifiedBackup

`func (o *DisasterRecoveryObjectiveResponse) SetRequireVerifiedBackup(v bool)`

SetRequireVerifiedBackup sets RequireVerifiedBackup field to given value.


### GetRequireCrossRegionCopy

`func (o *DisasterRecoveryObjectiveResponse) GetRequireCrossRegionCopy() bool`

GetRequireCrossRegionCopy returns the RequireCrossRegionCopy field if non-nil, zero value otherwise.

### GetRequireCrossRegionCopyOk

`func (o *DisasterRecoveryObjectiveResponse) GetRequireCrossRegionCopyOk() (*bool, bool)`

GetRequireCrossRegionCopyOk returns a tuple with the RequireCrossRegionCopy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireCrossRegionCopy

`func (o *DisasterRecoveryObjectiveResponse) SetRequireCrossRegionCopy(v bool)`

SetRequireCrossRegionCopy sets RequireCrossRegionCopy field to given value.


### GetRequireRestoreValidation

`func (o *DisasterRecoveryObjectiveResponse) GetRequireRestoreValidation() bool`

GetRequireRestoreValidation returns the RequireRestoreValidation field if non-nil, zero value otherwise.

### GetRequireRestoreValidationOk

`func (o *DisasterRecoveryObjectiveResponse) GetRequireRestoreValidationOk() (*bool, bool)`

GetRequireRestoreValidationOk returns a tuple with the RequireRestoreValidation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireRestoreValidation

`func (o *DisasterRecoveryObjectiveResponse) SetRequireRestoreValidation(v bool)`

SetRequireRestoreValidation sets RequireRestoreValidation field to given value.


### GetPolicyRevision

`func (o *DisasterRecoveryObjectiveResponse) GetPolicyRevision() int32`

GetPolicyRevision returns the PolicyRevision field if non-nil, zero value otherwise.

### GetPolicyRevisionOk

`func (o *DisasterRecoveryObjectiveResponse) GetPolicyRevisionOk() (*int32, bool)`

GetPolicyRevisionOk returns a tuple with the PolicyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyRevision

`func (o *DisasterRecoveryObjectiveResponse) SetPolicyRevision(v int32)`

SetPolicyRevision sets PolicyRevision field to given value.


### GetFingerprint

`func (o *DisasterRecoveryObjectiveResponse) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *DisasterRecoveryObjectiveResponse) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *DisasterRecoveryObjectiveResponse) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetMetadata

`func (o *DisasterRecoveryObjectiveResponse) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DisasterRecoveryObjectiveResponse) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DisasterRecoveryObjectiveResponse) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *DisasterRecoveryObjectiveResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DisasterRecoveryObjectiveResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *DisasterRecoveryObjectiveResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DisasterRecoveryObjectiveResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DisasterRecoveryObjectiveResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *DisasterRecoveryObjectiveResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DisasterRecoveryObjectiveResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DisasterRecoveryObjectiveResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


