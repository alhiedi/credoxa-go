# RepairPreviewRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**ExpectedRevision** | Pointer to **int32** |  | [optional] 
**ExpectedFencingGeneration** | Pointer to **int32** |  | [optional] 
**ExpectedRebuildGeneration** | Pointer to **int32** |  | [optional] 

## Methods

### NewRepairPreviewRequest

`func NewRepairPreviewRequest(projectionId string, ) *RepairPreviewRequest`

NewRepairPreviewRequest instantiates a new RepairPreviewRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairPreviewRequestWithDefaults

`func NewRepairPreviewRequestWithDefaults() *RepairPreviewRequest`

NewRepairPreviewRequestWithDefaults instantiates a new RepairPreviewRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *RepairPreviewRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RepairPreviewRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RepairPreviewRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *RepairPreviewRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *RepairPreviewRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *RepairPreviewRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *RepairPreviewRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetExpectedRevision

`func (o *RepairPreviewRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *RepairPreviewRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *RepairPreviewRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.

### HasExpectedRevision

`func (o *RepairPreviewRequest) HasExpectedRevision() bool`

HasExpectedRevision returns a boolean if a field has been set.

### GetExpectedFencingGeneration

`func (o *RepairPreviewRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *RepairPreviewRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *RepairPreviewRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.

### HasExpectedFencingGeneration

`func (o *RepairPreviewRequest) HasExpectedFencingGeneration() bool`

HasExpectedFencingGeneration returns a boolean if a field has been set.

### GetExpectedRebuildGeneration

`func (o *RepairPreviewRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *RepairPreviewRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *RepairPreviewRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.

### HasExpectedRebuildGeneration

`func (o *RepairPreviewRequest) HasExpectedRebuildGeneration() bool`

HasExpectedRebuildGeneration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


