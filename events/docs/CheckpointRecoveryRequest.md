# CheckpointRecoveryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Reason** | **string** |  | 
**ExpectedFencingGeneration** | **int32** |  | 
**ExpectedRebuildGeneration** | **int32** |  | 
**Force** | Pointer to **bool** |  | [optional] [default to false]
**ExpectedCursorOccurredAt** | Pointer to **NullableTime** |  | [optional] 
**ExpectedCursorEventId** | Pointer to **NullableString** |  | [optional] 
**TargetCursorOccurredAt** | Pointer to **NullableTime** |  | [optional] 
**TargetCursorEventId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCheckpointRecoveryRequest

`func NewCheckpointRecoveryRequest(projectionId string, idempotencyKey string, reason string, expectedFencingGeneration int32, expectedRebuildGeneration int32, ) *CheckpointRecoveryRequest`

NewCheckpointRecoveryRequest instantiates a new CheckpointRecoveryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckpointRecoveryRequestWithDefaults

`func NewCheckpointRecoveryRequestWithDefaults() *CheckpointRecoveryRequest`

NewCheckpointRecoveryRequestWithDefaults instantiates a new CheckpointRecoveryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *CheckpointRecoveryRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CheckpointRecoveryRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CheckpointRecoveryRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *CheckpointRecoveryRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *CheckpointRecoveryRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *CheckpointRecoveryRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *CheckpointRecoveryRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetIdempotencyKey

`func (o *CheckpointRecoveryRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *CheckpointRecoveryRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *CheckpointRecoveryRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetReason

`func (o *CheckpointRecoveryRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CheckpointRecoveryRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CheckpointRecoveryRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetExpectedFencingGeneration

`func (o *CheckpointRecoveryRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *CheckpointRecoveryRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *CheckpointRecoveryRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.


### GetExpectedRebuildGeneration

`func (o *CheckpointRecoveryRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *CheckpointRecoveryRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *CheckpointRecoveryRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.


### GetForce

`func (o *CheckpointRecoveryRequest) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *CheckpointRecoveryRequest) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *CheckpointRecoveryRequest) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *CheckpointRecoveryRequest) HasForce() bool`

HasForce returns a boolean if a field has been set.

### GetExpectedCursorOccurredAt

`func (o *CheckpointRecoveryRequest) GetExpectedCursorOccurredAt() time.Time`

GetExpectedCursorOccurredAt returns the ExpectedCursorOccurredAt field if non-nil, zero value otherwise.

### GetExpectedCursorOccurredAtOk

`func (o *CheckpointRecoveryRequest) GetExpectedCursorOccurredAtOk() (*time.Time, bool)`

GetExpectedCursorOccurredAtOk returns a tuple with the ExpectedCursorOccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedCursorOccurredAt

`func (o *CheckpointRecoveryRequest) SetExpectedCursorOccurredAt(v time.Time)`

SetExpectedCursorOccurredAt sets ExpectedCursorOccurredAt field to given value.

### HasExpectedCursorOccurredAt

`func (o *CheckpointRecoveryRequest) HasExpectedCursorOccurredAt() bool`

HasExpectedCursorOccurredAt returns a boolean if a field has been set.

### SetExpectedCursorOccurredAtNil

`func (o *CheckpointRecoveryRequest) SetExpectedCursorOccurredAtNil(b bool)`

 SetExpectedCursorOccurredAtNil sets the value for ExpectedCursorOccurredAt to be an explicit nil

### UnsetExpectedCursorOccurredAt
`func (o *CheckpointRecoveryRequest) UnsetExpectedCursorOccurredAt()`

UnsetExpectedCursorOccurredAt ensures that no value is present for ExpectedCursorOccurredAt, not even an explicit nil
### GetExpectedCursorEventId

`func (o *CheckpointRecoveryRequest) GetExpectedCursorEventId() string`

GetExpectedCursorEventId returns the ExpectedCursorEventId field if non-nil, zero value otherwise.

### GetExpectedCursorEventIdOk

`func (o *CheckpointRecoveryRequest) GetExpectedCursorEventIdOk() (*string, bool)`

GetExpectedCursorEventIdOk returns a tuple with the ExpectedCursorEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedCursorEventId

`func (o *CheckpointRecoveryRequest) SetExpectedCursorEventId(v string)`

SetExpectedCursorEventId sets ExpectedCursorEventId field to given value.

### HasExpectedCursorEventId

`func (o *CheckpointRecoveryRequest) HasExpectedCursorEventId() bool`

HasExpectedCursorEventId returns a boolean if a field has been set.

### SetExpectedCursorEventIdNil

`func (o *CheckpointRecoveryRequest) SetExpectedCursorEventIdNil(b bool)`

 SetExpectedCursorEventIdNil sets the value for ExpectedCursorEventId to be an explicit nil

### UnsetExpectedCursorEventId
`func (o *CheckpointRecoveryRequest) UnsetExpectedCursorEventId()`

UnsetExpectedCursorEventId ensures that no value is present for ExpectedCursorEventId, not even an explicit nil
### GetTargetCursorOccurredAt

`func (o *CheckpointRecoveryRequest) GetTargetCursorOccurredAt() time.Time`

GetTargetCursorOccurredAt returns the TargetCursorOccurredAt field if non-nil, zero value otherwise.

### GetTargetCursorOccurredAtOk

`func (o *CheckpointRecoveryRequest) GetTargetCursorOccurredAtOk() (*time.Time, bool)`

GetTargetCursorOccurredAtOk returns a tuple with the TargetCursorOccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetCursorOccurredAt

`func (o *CheckpointRecoveryRequest) SetTargetCursorOccurredAt(v time.Time)`

SetTargetCursorOccurredAt sets TargetCursorOccurredAt field to given value.

### HasTargetCursorOccurredAt

`func (o *CheckpointRecoveryRequest) HasTargetCursorOccurredAt() bool`

HasTargetCursorOccurredAt returns a boolean if a field has been set.

### SetTargetCursorOccurredAtNil

`func (o *CheckpointRecoveryRequest) SetTargetCursorOccurredAtNil(b bool)`

 SetTargetCursorOccurredAtNil sets the value for TargetCursorOccurredAt to be an explicit nil

### UnsetTargetCursorOccurredAt
`func (o *CheckpointRecoveryRequest) UnsetTargetCursorOccurredAt()`

UnsetTargetCursorOccurredAt ensures that no value is present for TargetCursorOccurredAt, not even an explicit nil
### GetTargetCursorEventId

`func (o *CheckpointRecoveryRequest) GetTargetCursorEventId() string`

GetTargetCursorEventId returns the TargetCursorEventId field if non-nil, zero value otherwise.

### GetTargetCursorEventIdOk

`func (o *CheckpointRecoveryRequest) GetTargetCursorEventIdOk() (*string, bool)`

GetTargetCursorEventIdOk returns a tuple with the TargetCursorEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetCursorEventId

`func (o *CheckpointRecoveryRequest) SetTargetCursorEventId(v string)`

SetTargetCursorEventId sets TargetCursorEventId field to given value.

### HasTargetCursorEventId

`func (o *CheckpointRecoveryRequest) HasTargetCursorEventId() bool`

HasTargetCursorEventId returns a boolean if a field has been set.

### SetTargetCursorEventIdNil

`func (o *CheckpointRecoveryRequest) SetTargetCursorEventIdNil(b bool)`

 SetTargetCursorEventIdNil sets the value for TargetCursorEventId to be an explicit nil

### UnsetTargetCursorEventId
`func (o *CheckpointRecoveryRequest) UnsetTargetCursorEventId()`

UnsetTargetCursorEventId ensures that no value is present for TargetCursorEventId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


