# RebuildProgressRequest

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
**TotalBucketCount** | **int32** |  | 
**ProcessedBucketCount** | **int32** |  | 
**CreatedBucketCount** | **int32** |  | 
**ChangedBucketCount** | **int32** |  | 
**IdempotentBucketCount** | **int32** |  | 

## Methods

### NewRebuildProgressRequest

`func NewRebuildProgressRequest(projectionId string, idempotencyKey string, reason string, expectedRevision int32, expectedFencingGeneration int32, expectedRebuildGeneration int32, totalBucketCount int32, processedBucketCount int32, createdBucketCount int32, changedBucketCount int32, idempotentBucketCount int32, ) *RebuildProgressRequest`

NewRebuildProgressRequest instantiates a new RebuildProgressRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRebuildProgressRequestWithDefaults

`func NewRebuildProgressRequestWithDefaults() *RebuildProgressRequest`

NewRebuildProgressRequestWithDefaults instantiates a new RebuildProgressRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *RebuildProgressRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RebuildProgressRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RebuildProgressRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *RebuildProgressRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *RebuildProgressRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *RebuildProgressRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *RebuildProgressRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetIdempotencyKey

`func (o *RebuildProgressRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *RebuildProgressRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *RebuildProgressRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetReason

`func (o *RebuildProgressRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RebuildProgressRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RebuildProgressRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetExpectedRevision

`func (o *RebuildProgressRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *RebuildProgressRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *RebuildProgressRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetExpectedFencingGeneration

`func (o *RebuildProgressRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *RebuildProgressRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *RebuildProgressRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.


### GetExpectedRebuildGeneration

`func (o *RebuildProgressRequest) GetExpectedRebuildGeneration() int32`

GetExpectedRebuildGeneration returns the ExpectedRebuildGeneration field if non-nil, zero value otherwise.

### GetExpectedRebuildGenerationOk

`func (o *RebuildProgressRequest) GetExpectedRebuildGenerationOk() (*int32, bool)`

GetExpectedRebuildGenerationOk returns a tuple with the ExpectedRebuildGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRebuildGeneration

`func (o *RebuildProgressRequest) SetExpectedRebuildGeneration(v int32)`

SetExpectedRebuildGeneration sets ExpectedRebuildGeneration field to given value.


### GetForce

`func (o *RebuildProgressRequest) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *RebuildProgressRequest) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *RebuildProgressRequest) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *RebuildProgressRequest) HasForce() bool`

HasForce returns a boolean if a field has been set.

### GetResetAttemptCount

`func (o *RebuildProgressRequest) GetResetAttemptCount() bool`

GetResetAttemptCount returns the ResetAttemptCount field if non-nil, zero value otherwise.

### GetResetAttemptCountOk

`func (o *RebuildProgressRequest) GetResetAttemptCountOk() (*bool, bool)`

GetResetAttemptCountOk returns a tuple with the ResetAttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetAttemptCount

`func (o *RebuildProgressRequest) SetResetAttemptCount(v bool)`

SetResetAttemptCount sets ResetAttemptCount field to given value.

### HasResetAttemptCount

`func (o *RebuildProgressRequest) HasResetAttemptCount() bool`

HasResetAttemptCount returns a boolean if a field has been set.

### GetPriority

`func (o *RebuildProgressRequest) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *RebuildProgressRequest) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *RebuildProgressRequest) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *RebuildProgressRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetAbandonmentTimeoutSeconds

`func (o *RebuildProgressRequest) GetAbandonmentTimeoutSeconds() int32`

GetAbandonmentTimeoutSeconds returns the AbandonmentTimeoutSeconds field if non-nil, zero value otherwise.

### GetAbandonmentTimeoutSecondsOk

`func (o *RebuildProgressRequest) GetAbandonmentTimeoutSecondsOk() (*int32, bool)`

GetAbandonmentTimeoutSecondsOk returns a tuple with the AbandonmentTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbandonmentTimeoutSeconds

`func (o *RebuildProgressRequest) SetAbandonmentTimeoutSeconds(v int32)`

SetAbandonmentTimeoutSeconds sets AbandonmentTimeoutSeconds field to given value.

### HasAbandonmentTimeoutSeconds

`func (o *RebuildProgressRequest) HasAbandonmentTimeoutSeconds() bool`

HasAbandonmentTimeoutSeconds returns a boolean if a field has been set.

### GetTotalBucketCount

`func (o *RebuildProgressRequest) GetTotalBucketCount() int32`

GetTotalBucketCount returns the TotalBucketCount field if non-nil, zero value otherwise.

### GetTotalBucketCountOk

`func (o *RebuildProgressRequest) GetTotalBucketCountOk() (*int32, bool)`

GetTotalBucketCountOk returns a tuple with the TotalBucketCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalBucketCount

`func (o *RebuildProgressRequest) SetTotalBucketCount(v int32)`

SetTotalBucketCount sets TotalBucketCount field to given value.


### GetProcessedBucketCount

`func (o *RebuildProgressRequest) GetProcessedBucketCount() int32`

GetProcessedBucketCount returns the ProcessedBucketCount field if non-nil, zero value otherwise.

### GetProcessedBucketCountOk

`func (o *RebuildProgressRequest) GetProcessedBucketCountOk() (*int32, bool)`

GetProcessedBucketCountOk returns a tuple with the ProcessedBucketCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedBucketCount

`func (o *RebuildProgressRequest) SetProcessedBucketCount(v int32)`

SetProcessedBucketCount sets ProcessedBucketCount field to given value.


### GetCreatedBucketCount

`func (o *RebuildProgressRequest) GetCreatedBucketCount() int32`

GetCreatedBucketCount returns the CreatedBucketCount field if non-nil, zero value otherwise.

### GetCreatedBucketCountOk

`func (o *RebuildProgressRequest) GetCreatedBucketCountOk() (*int32, bool)`

GetCreatedBucketCountOk returns a tuple with the CreatedBucketCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBucketCount

`func (o *RebuildProgressRequest) SetCreatedBucketCount(v int32)`

SetCreatedBucketCount sets CreatedBucketCount field to given value.


### GetChangedBucketCount

`func (o *RebuildProgressRequest) GetChangedBucketCount() int32`

GetChangedBucketCount returns the ChangedBucketCount field if non-nil, zero value otherwise.

### GetChangedBucketCountOk

`func (o *RebuildProgressRequest) GetChangedBucketCountOk() (*int32, bool)`

GetChangedBucketCountOk returns a tuple with the ChangedBucketCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangedBucketCount

`func (o *RebuildProgressRequest) SetChangedBucketCount(v int32)`

SetChangedBucketCount sets ChangedBucketCount field to given value.


### GetIdempotentBucketCount

`func (o *RebuildProgressRequest) GetIdempotentBucketCount() int32`

GetIdempotentBucketCount returns the IdempotentBucketCount field if non-nil, zero value otherwise.

### GetIdempotentBucketCountOk

`func (o *RebuildProgressRequest) GetIdempotentBucketCountOk() (*int32, bool)`

GetIdempotentBucketCountOk returns a tuple with the IdempotentBucketCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotentBucketCount

`func (o *RebuildProgressRequest) SetIdempotentBucketCount(v int32)`

SetIdempotentBucketCount sets IdempotentBucketCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


