# AnalyticsLateArrivalRepairRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Reason** | **string** |  | 
**ExpectedFencingGeneration** | Pointer to **int32** |  | [optional] 
**ExpectedRebuildGeneration** | Pointer to **int32** |  | [optional] 
**StartAt** | Pointer to **time.Time** |  | [optional] 
**EndAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewAnalyticsLateArrivalRepairRequest

`func NewAnalyticsLateArrivalRepairRequest(projectionId string, idempotencyKey string, reason string, ) *AnalyticsLateArrivalRepairRequest`

NewAnalyticsLateArrivalRepairRequest instantiates a new AnalyticsLateArrivalRepairRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsLateArrivalRepairRequestWithDefaults

`func NewAnalyticsLateArrivalRepairRequestWithDefaults() *AnalyticsLateArrivalRepairRequest`

NewAnalyticsLateArrivalRepairRequestWithDefaults instantiates a new AnalyticsLateArrivalRepairRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *AnalyticsLateArrivalRepairRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AnalyticsLateArrivalRepairRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AnalyticsLateArrivalRepairRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *AnalyticsLateArrivalRepairRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *AnalyticsLateArrivalRepairRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsLateArrivalRepairRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsLateArrivalRepairRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetIdempotencyKey

`func (o *AnalyticsLateArrivalRepairRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *AnalyticsLateArrivalRepairRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *AnalyticsLateArrivalRepairRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetReason

`func (o *AnalyticsLateArrivalRepairRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AnalyticsLateArrivalRepairRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AnalyticsLateArrivalRepairRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetExpectedFencingGeneration

`func (o *AnalyticsLateArrivalRepairRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *AnalyticsLateArrivalRepairRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *AnalyticsLateArrivalRepairRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.

### HasExpectedFencingGeneration

`func (o *AnalyticsLateArrivalRepairRequest) HasExpectedFencingGeneration() bool`

HasExpectedFencingGeneration returns a boolean if a field has been set.

### GetExpectedRebuildGeneration

`func (o *AnalyticsLateArrivalRepairRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *AnalyticsLateArrivalRepairRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *AnalyticsLateArrivalRepairRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.

### HasExpectedRebuildGeneration

`func (o *AnalyticsLateArrivalRepairRequest) HasExpectedRebuildGeneration() bool`

HasExpectedRebuildGeneration returns a boolean if a field has been set.

### GetStartAt

`func (o *AnalyticsLateArrivalRepairRequest) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *AnalyticsLateArrivalRepairRequest) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *AnalyticsLateArrivalRepairRequest) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *AnalyticsLateArrivalRepairRequest) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetEndAt

`func (o *AnalyticsLateArrivalRepairRequest) GetEndAt() time.Time`

GetEndAt returns the EndAt field if non-nil, zero value otherwise.

### GetEndAtOk

`func (o *AnalyticsLateArrivalRepairRequest) GetEndAtOk() (*time.Time, bool)`

GetEndAtOk returns a tuple with the EndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndAt

`func (o *AnalyticsLateArrivalRepairRequest) SetEndAt(v time.Time)`

SetEndAt sets EndAt field to given value.

### HasEndAt

`func (o *AnalyticsLateArrivalRepairRequest) HasEndAt() bool`

HasEndAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


