# DrillCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectiveId** | **string** |  | 
**AvailableRecoveryRegions** | **int32** |  | 
**InitiatedBy** | Pointer to **string** |  | [optional] 
**ProductionTrafficAffected** | Pointer to **bool** |  | [optional] [default to false]
**Metadata** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewDrillCreateRequest

`func NewDrillCreateRequest(objectiveId string, availableRecoveryRegions int32, ) *DrillCreateRequest`

NewDrillCreateRequest instantiates a new DrillCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDrillCreateRequestWithDefaults

`func NewDrillCreateRequestWithDefaults() *DrillCreateRequest`

NewDrillCreateRequestWithDefaults instantiates a new DrillCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetObjectiveId

`func (o *DrillCreateRequest) GetObjectiveId() string`

GetObjectiveId returns the ObjectiveId field if non-nil, zero value otherwise.

### GetObjectiveIdOk

`func (o *DrillCreateRequest) GetObjectiveIdOk() (*string, bool)`

GetObjectiveIdOk returns a tuple with the ObjectiveId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectiveId

`func (o *DrillCreateRequest) SetObjectiveId(v string)`

SetObjectiveId sets ObjectiveId field to given value.


### GetAvailableRecoveryRegions

`func (o *DrillCreateRequest) GetAvailableRecoveryRegions() int32`

GetAvailableRecoveryRegions returns the AvailableRecoveryRegions field if non-nil, zero value otherwise.

### GetAvailableRecoveryRegionsOk

`func (o *DrillCreateRequest) GetAvailableRecoveryRegionsOk() (*int32, bool)`

GetAvailableRecoveryRegionsOk returns a tuple with the AvailableRecoveryRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableRecoveryRegions

`func (o *DrillCreateRequest) SetAvailableRecoveryRegions(v int32)`

SetAvailableRecoveryRegions sets AvailableRecoveryRegions field to given value.


### GetInitiatedBy

`func (o *DrillCreateRequest) GetInitiatedBy() string`

GetInitiatedBy returns the InitiatedBy field if non-nil, zero value otherwise.

### GetInitiatedByOk

`func (o *DrillCreateRequest) GetInitiatedByOk() (*string, bool)`

GetInitiatedByOk returns a tuple with the InitiatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitiatedBy

`func (o *DrillCreateRequest) SetInitiatedBy(v string)`

SetInitiatedBy sets InitiatedBy field to given value.

### HasInitiatedBy

`func (o *DrillCreateRequest) HasInitiatedBy() bool`

HasInitiatedBy returns a boolean if a field has been set.

### GetProductionTrafficAffected

`func (o *DrillCreateRequest) GetProductionTrafficAffected() bool`

GetProductionTrafficAffected returns the ProductionTrafficAffected field if non-nil, zero value otherwise.

### GetProductionTrafficAffectedOk

`func (o *DrillCreateRequest) GetProductionTrafficAffectedOk() (*bool, bool)`

GetProductionTrafficAffectedOk returns a tuple with the ProductionTrafficAffected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionTrafficAffected

`func (o *DrillCreateRequest) SetProductionTrafficAffected(v bool)`

SetProductionTrafficAffected sets ProductionTrafficAffected field to given value.

### HasProductionTrafficAffected

`func (o *DrillCreateRequest) HasProductionTrafficAffected() bool`

HasProductionTrafficAffected returns a boolean if a field has been set.

### GetMetadata

`func (o *DrillCreateRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DrillCreateRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DrillCreateRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DrillCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *DrillCreateRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DrillCreateRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


