# RebuildActionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Reason** | **string** |  | 
**ExpectedRevision** | **int32** |  | 
**ExpectedFencingGeneration** | **int32** |  | 
**ExpectedRebuildGeneration** | **int32** |  | 
**Force** | Pointer to **bool** |  | [optional] [default to false]
**ResetAttemptCount** | Pointer to **bool** |  | [optional] [default to false]
**Priority** | Pointer to **int32** |  | [optional] 
**AbandonmentTimeoutSeconds** | Pointer to **int32** |  | [optional] [default to 900]

## Methods

### NewRebuildActionRequest

`func NewRebuildActionRequest(projectionId string, idempotencyKey string, reason string, expectedRevision int32, expectedFencingGeneration int32, expectedRebuildGeneration int32, ) *RebuildActionRequest`

NewRebuildActionRequest instantiates a new RebuildActionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRebuildActionRequestWithDefaults

`func NewRebuildActionRequestWithDefaults() *RebuildActionRequest`

NewRebuildActionRequestWithDefaults instantiates a new RebuildActionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *RebuildActionRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RebuildActionRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RebuildActionRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *RebuildActionRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *RebuildActionRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *RebuildActionRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *RebuildActionRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetIdempotencyKey

`func (o *RebuildActionRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *RebuildActionRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *RebuildActionRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetReason

`func (o *RebuildActionRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RebuildActionRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RebuildActionRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetExpectedRevision

`func (o *RebuildActionRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *RebuildActionRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *RebuildActionRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetExpectedFencingGeneration

`func (o *RebuildActionRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *RebuildActionRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *RebuildActionRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.


### GetExpectedRebuildGeneration

`func (o *RebuildActionRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *RebuildActionRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *RebuildActionRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.


### GetForce

`func (o *RebuildActionRequest) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *RebuildActionRequest) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *RebuildActionRequest) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *RebuildActionRequest) HasForce() bool`

HasForce returns a boolean if a field has been set.

### GetResetAttemptCount

`func (o *RebuildActionRequest) GetResetAttemptCount() bool`

GetResetAttemptCount returns the ResetAttemptCount field if non-nil, zero value otherwise.

### GetResetAttemptCountOk

`func (o *RebuildActionRequest) GetResetAttemptCountOk() (*bool, bool)`

GetResetAttemptCountOk returns a tuple with the ResetAttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetAttemptCount

`func (o *RebuildActionRequest) SetResetAttemptCount(v bool)`

SetResetAttemptCount sets ResetAttemptCount field to given value.

### HasResetAttemptCount

`func (o *RebuildActionRequest) HasResetAttemptCount() bool`

HasResetAttemptCount returns a boolean if a field has been set.

### GetPriority

`func (o *RebuildActionRequest) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *RebuildActionRequest) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *RebuildActionRequest) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *RebuildActionRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetAbandonmentTimeoutSeconds

`func (o *RebuildActionRequest) GetAbandonmentTimeoutSeconds() int32`

GetAbandonmentTimeoutSeconds returns the AbandonmentTimeoutSeconds field if non-nil, zero value otherwise.

### GetAbandonmentTimeoutSecondsOk

`func (o *RebuildActionRequest) GetAbandonmentTimeoutSecondsOk() (*int32, bool)`

GetAbandonmentTimeoutSecondsOk returns a tuple with the AbandonmentTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbandonmentTimeoutSeconds

`func (o *RebuildActionRequest) SetAbandonmentTimeoutSeconds(v int32)`

SetAbandonmentTimeoutSeconds sets AbandonmentTimeoutSeconds field to given value.

### HasAbandonmentTimeoutSeconds

`func (o *RebuildActionRequest) HasAbandonmentTimeoutSeconds() bool`

HasAbandonmentTimeoutSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


