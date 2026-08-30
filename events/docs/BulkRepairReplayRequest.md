# BulkRepairReplayRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**RepairIds** | **[]string** |  | 
**IdempotencyKey** | **string** |  | 
**Reason** | **string** |  | 
**ExpectedFencingGeneration** | **int32** |  | 
**ExpectedRebuildGeneration** | **int32** |  | 
**MaximumItems** | Pointer to **int32** |  | [optional] [default to 100]
**DryRun** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewBulkRepairReplayRequest

`func NewBulkRepairReplayRequest(projectionId string, repairIds []string, idempotencyKey string, reason string, expectedFencingGeneration int32, expectedRebuildGeneration int32, ) *BulkRepairReplayRequest`

NewBulkRepairReplayRequest instantiates a new BulkRepairReplayRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkRepairReplayRequestWithDefaults

`func NewBulkRepairReplayRequestWithDefaults() *BulkRepairReplayRequest`

NewBulkRepairReplayRequestWithDefaults instantiates a new BulkRepairReplayRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *BulkRepairReplayRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *BulkRepairReplayRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *BulkRepairReplayRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *BulkRepairReplayRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *BulkRepairReplayRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *BulkRepairReplayRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *BulkRepairReplayRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetRepairIds

`func (o *BulkRepairReplayRequest) GetRepairIds() []string`

GetRepairIds returns the RepairIds field if non-nil, zero value otherwise.

### GetRepairIdsOk

`func (o *BulkRepairReplayRequest) GetRepairIdsOk() (*[]string, bool)`

GetRepairIdsOk returns a tuple with the RepairIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepairIds

`func (o *BulkRepairReplayRequest) SetRepairIds(v []string)`

SetRepairIds sets RepairIds field to given value.


### GetIdempotencyKey

`func (o *BulkRepairReplayRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *BulkRepairReplayRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *BulkRepairReplayRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetReason

`func (o *BulkRepairReplayRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *BulkRepairReplayRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *BulkRepairReplayRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetExpectedFencingGeneration

`func (o *BulkRepairReplayRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *BulkRepairReplayRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *BulkRepairReplayRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.


### GetExpectedRebuildGeneration

`func (o *BulkRepairReplayRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *BulkRepairReplayRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *BulkRepairReplayRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.


### GetMaximumItems

`func (o *BulkRepairReplayRequest) GetMaximumItems() int32`

GetMaximumItems returns the MaximumItems field if non-nil, zero value otherwise.

### GetMaximumItemsOk

`func (o *BulkRepairReplayRequest) GetMaximumItemsOk() (*int32, bool)`

GetMaximumItemsOk returns a tuple with the MaximumItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumItems

`func (o *BulkRepairReplayRequest) SetMaximumItems(v int32)`

SetMaximumItems sets MaximumItems field to given value.

### HasMaximumItems

`func (o *BulkRepairReplayRequest) HasMaximumItems() bool`

HasMaximumItems returns a boolean if a field has been set.

### GetDryRun

`func (o *BulkRepairReplayRequest) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *BulkRepairReplayRequest) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *BulkRepairReplayRequest) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.

### HasDryRun

`func (o *BulkRepairReplayRequest) HasDryRun() bool`

HasDryRun returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


