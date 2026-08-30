# ObjectiveCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopologyId** | **string** |  | 
**WorkloadName** | **string** |  | 
**Criticality** | [**CriticalityEnum**](CriticalityEnum.md) |  | 
**RpoSeconds** | **int32** |  | 
**RtoSeconds** | **int32** |  | 
**MinimumRecoveryRegions** | **int32** |  | 
**RequireVerifiedBackup** | Pointer to **bool** |  | [optional] [default to true]
**RequireCrossRegionCopy** | Pointer to **bool** |  | [optional] [default to true]
**RequireRestoreValidation** | Pointer to **bool** |  | [optional] [default to true]
**Metadata** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewObjectiveCreateRequest

`func NewObjectiveCreateRequest(topologyId string, workloadName string, criticality CriticalityEnum, rpoSeconds int32, rtoSeconds int32, minimumRecoveryRegions int32, ) *ObjectiveCreateRequest`

NewObjectiveCreateRequest instantiates a new ObjectiveCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewObjectiveCreateRequestWithDefaults

`func NewObjectiveCreateRequestWithDefaults() *ObjectiveCreateRequest`

NewObjectiveCreateRequestWithDefaults instantiates a new ObjectiveCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopologyId

`func (o *ObjectiveCreateRequest) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *ObjectiveCreateRequest) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *ObjectiveCreateRequest) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetWorkloadName

`func (o *ObjectiveCreateRequest) GetWorkloadName() string`

GetWorkloadName returns the WorkloadName field if non-nil, zero value otherwise.

### GetWorkloadNameOk

`func (o *ObjectiveCreateRequest) GetWorkloadNameOk() (*string, bool)`

GetWorkloadNameOk returns a tuple with the WorkloadName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkloadName

`func (o *ObjectiveCreateRequest) SetWorkloadName(v string)`

SetWorkloadName sets WorkloadName field to given value.


### GetCriticality

`func (o *ObjectiveCreateRequest) GetCriticality() CriticalityEnum`

GetCriticality returns the Criticality field if non-nil, zero value otherwise.

### GetCriticalityOk

`func (o *ObjectiveCreateRequest) GetCriticalityOk() (*CriticalityEnum, bool)`

GetCriticalityOk returns a tuple with the Criticality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCriticality

`func (o *ObjectiveCreateRequest) SetCriticality(v CriticalityEnum)`

SetCriticality sets Criticality field to given value.


### GetRpoSeconds

`func (o *ObjectiveCreateRequest) GetRpoSeconds() int32`

GetRpoSeconds returns the RpoSeconds field if non-nil, zero value otherwise.

### GetRpoSecondsOk

`func (o *ObjectiveCreateRequest) GetRpoSecondsOk() (*int32, bool)`

GetRpoSecondsOk returns a tuple with the RpoSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRpoSeconds

`func (o *ObjectiveCreateRequest) SetRpoSeconds(v int32)`

SetRpoSeconds sets RpoSeconds field to given value.


### GetRtoSeconds

`func (o *ObjectiveCreateRequest) GetRtoSeconds() int32`

GetRtoSeconds returns the RtoSeconds field if non-nil, zero value otherwise.

### GetRtoSecondsOk

`func (o *ObjectiveCreateRequest) GetRtoSecondsOk() (*int32, bool)`

GetRtoSecondsOk returns a tuple with the RtoSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRtoSeconds

`func (o *ObjectiveCreateRequest) SetRtoSeconds(v int32)`

SetRtoSeconds sets RtoSeconds field to given value.


### GetMinimumRecoveryRegions

`func (o *ObjectiveCreateRequest) GetMinimumRecoveryRegions() int32`

GetMinimumRecoveryRegions returns the MinimumRecoveryRegions field if non-nil, zero value otherwise.

### GetMinimumRecoveryRegionsOk

`func (o *ObjectiveCreateRequest) GetMinimumRecoveryRegionsOk() (*int32, bool)`

GetMinimumRecoveryRegionsOk returns a tuple with the MinimumRecoveryRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumRecoveryRegions

`func (o *ObjectiveCreateRequest) SetMinimumRecoveryRegions(v int32)`

SetMinimumRecoveryRegions sets MinimumRecoveryRegions field to given value.


### GetRequireVerifiedBackup

`func (o *ObjectiveCreateRequest) GetRequireVerifiedBackup() bool`

GetRequireVerifiedBackup returns the RequireVerifiedBackup field if non-nil, zero value otherwise.

### GetRequireVerifiedBackupOk

`func (o *ObjectiveCreateRequest) GetRequireVerifiedBackupOk() (*bool, bool)`

GetRequireVerifiedBackupOk returns a tuple with the RequireVerifiedBackup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireVerifiedBackup

`func (o *ObjectiveCreateRequest) SetRequireVerifiedBackup(v bool)`

SetRequireVerifiedBackup sets RequireVerifiedBackup field to given value.

### HasRequireVerifiedBackup

`func (o *ObjectiveCreateRequest) HasRequireVerifiedBackup() bool`

HasRequireVerifiedBackup returns a boolean if a field has been set.

### GetRequireCrossRegionCopy

`func (o *ObjectiveCreateRequest) GetRequireCrossRegionCopy() bool`

GetRequireCrossRegionCopy returns the RequireCrossRegionCopy field if non-nil, zero value otherwise.

### GetRequireCrossRegionCopyOk

`func (o *ObjectiveCreateRequest) GetRequireCrossRegionCopyOk() (*bool, bool)`

GetRequireCrossRegionCopyOk returns a tuple with the RequireCrossRegionCopy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireCrossRegionCopy

`func (o *ObjectiveCreateRequest) SetRequireCrossRegionCopy(v bool)`

SetRequireCrossRegionCopy sets RequireCrossRegionCopy field to given value.

### HasRequireCrossRegionCopy

`func (o *ObjectiveCreateRequest) HasRequireCrossRegionCopy() bool`

HasRequireCrossRegionCopy returns a boolean if a field has been set.

### GetRequireRestoreValidation

`func (o *ObjectiveCreateRequest) GetRequireRestoreValidation() bool`

GetRequireRestoreValidation returns the RequireRestoreValidation field if non-nil, zero value otherwise.

### GetRequireRestoreValidationOk

`func (o *ObjectiveCreateRequest) GetRequireRestoreValidationOk() (*bool, bool)`

GetRequireRestoreValidationOk returns a tuple with the RequireRestoreValidation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireRestoreValidation

`func (o *ObjectiveCreateRequest) SetRequireRestoreValidation(v bool)`

SetRequireRestoreValidation sets RequireRestoreValidation field to given value.

### HasRequireRestoreValidation

`func (o *ObjectiveCreateRequest) HasRequireRestoreValidation() bool`

HasRequireRestoreValidation returns a boolean if a field has been set.

### GetMetadata

`func (o *ObjectiveCreateRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ObjectiveCreateRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ObjectiveCreateRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ObjectiveCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ObjectiveCreateRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ObjectiveCreateRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


