# RebuildPreviewRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**ExpectedRevision** | Pointer to **int32** |  | [optional] 
**ExpectedFencingGeneration** | Pointer to **int32** |  | [optional] 
**ExpectedRebuildGeneration** | Pointer to **int32** |  | [optional] 
**AbandonmentTimeoutSeconds** | Pointer to **int32** |  | [optional] [default to 900]

## Methods

### NewRebuildPreviewRequest

`func NewRebuildPreviewRequest(projectionId string, ) *RebuildPreviewRequest`

NewRebuildPreviewRequest instantiates a new RebuildPreviewRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRebuildPreviewRequestWithDefaults

`func NewRebuildPreviewRequestWithDefaults() *RebuildPreviewRequest`

NewRebuildPreviewRequestWithDefaults instantiates a new RebuildPreviewRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *RebuildPreviewRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RebuildPreviewRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RebuildPreviewRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *RebuildPreviewRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *RebuildPreviewRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *RebuildPreviewRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *RebuildPreviewRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetExpectedRevision

`func (o *RebuildPreviewRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *RebuildPreviewRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *RebuildPreviewRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.

### HasExpectedRevision

`func (o *RebuildPreviewRequest) HasExpectedRevision() bool`

HasExpectedRevision returns a boolean if a field has been set.

### GetExpectedFencingGeneration

`func (o *RebuildPreviewRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *RebuildPreviewRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *RebuildPreviewRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.

### HasExpectedFencingGeneration

`func (o *RebuildPreviewRequest) HasExpectedFencingGeneration() bool`

HasExpectedFencingGeneration returns a boolean if a field has been set.

### GetExpectedRebuildGeneration

`func (o *RebuildPreviewRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *RebuildPreviewRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *RebuildPreviewRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.

### HasExpectedRebuildGeneration

`func (o *RebuildPreviewRequest) HasExpectedRebuildGeneration() bool`

HasExpectedRebuildGeneration returns a boolean if a field has been set.

### GetAbandonmentTimeoutSeconds

`func (o *RebuildPreviewRequest) GetAbandonmentTimeoutSeconds() int32`

GetAbandonmentTimeoutSeconds returns the AbandonmentTimeoutSeconds field if non-nil, zero value otherwise.

### GetAbandonmentTimeoutSecondsOk

`func (o *RebuildPreviewRequest) GetAbandonmentTimeoutSecondsOk() (*int32, bool)`

GetAbandonmentTimeoutSecondsOk returns a tuple with the AbandonmentTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbandonmentTimeoutSeconds

`func (o *RebuildPreviewRequest) SetAbandonmentTimeoutSeconds(v int32)`

SetAbandonmentTimeoutSeconds sets AbandonmentTimeoutSeconds field to given value.

### HasAbandonmentTimeoutSeconds

`func (o *RebuildPreviewRequest) HasAbandonmentTimeoutSeconds() bool`

HasAbandonmentTimeoutSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


