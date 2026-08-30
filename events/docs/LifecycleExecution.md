# LifecycleExecution

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**ExecutionId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Kind** | [**LifecycleExecutionKindEnum**](LifecycleExecutionKindEnum.md) |  | 
**Status** | Pointer to [**LifecycleExecutionStatusEnum**](LifecycleExecutionStatusEnum.md) |  | [optional] 
**DryRun** | Pointer to **bool** |  | [optional] 
**RequestedBy** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Cursor** | Pointer to **interface{}** |  | [optional] 
**PlannedCount** | Pointer to **int64** |  | [optional] 
**ProcessedCount** | Pointer to **int64** |  | [optional] 
**SucceededCount** | Pointer to **int64** |  | [optional] 
**FailedCount** | Pointer to **int64** |  | [optional] 
**HeldCount** | Pointer to **int64** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**FailureCode** | Pointer to **string** |  | [optional] 
**FailureDetail** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**PolicyVersion** | **string** |  | 

## Methods

### NewLifecycleExecution

`func NewLifecycleExecution(id string, executionId string, organizationId string, kind LifecycleExecutionKindEnum, requestedBy string, idempotencyKey string, createdAt time.Time, updatedAt time.Time, policyVersion string, ) *LifecycleExecution`

NewLifecycleExecution instantiates a new LifecycleExecution object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleExecutionWithDefaults

`func NewLifecycleExecutionWithDefaults() *LifecycleExecution`

NewLifecycleExecutionWithDefaults instantiates a new LifecycleExecution object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LifecycleExecution) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LifecycleExecution) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LifecycleExecution) SetId(v string)`

SetId sets Id field to given value.


### GetExecutionId

`func (o *LifecycleExecution) GetExecutionId() string`

GetExecutionId returns the ExecutionId field if non-nil, zero value otherwise.

### GetExecutionIdOk

`func (o *LifecycleExecution) GetExecutionIdOk() (*string, bool)`

GetExecutionIdOk returns a tuple with the ExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionId

`func (o *LifecycleExecution) SetExecutionId(v string)`

SetExecutionId sets ExecutionId field to given value.


### GetOrganizationId

`func (o *LifecycleExecution) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleExecution) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleExecution) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetKind

`func (o *LifecycleExecution) GetKind() LifecycleExecutionKindEnum`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *LifecycleExecution) GetKindOk() (*LifecycleExecutionKindEnum, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *LifecycleExecution) SetKind(v LifecycleExecutionKindEnum)`

SetKind sets Kind field to given value.


### GetStatus

`func (o *LifecycleExecution) GetStatus() LifecycleExecutionStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LifecycleExecution) GetStatusOk() (*LifecycleExecutionStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LifecycleExecution) SetStatus(v LifecycleExecutionStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LifecycleExecution) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDryRun

`func (o *LifecycleExecution) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *LifecycleExecution) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *LifecycleExecution) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.

### HasDryRun

`func (o *LifecycleExecution) HasDryRun() bool`

HasDryRun returns a boolean if a field has been set.

### GetRequestedBy

`func (o *LifecycleExecution) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *LifecycleExecution) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *LifecycleExecution) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetIdempotencyKey

`func (o *LifecycleExecution) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *LifecycleExecution) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *LifecycleExecution) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetCursor

`func (o *LifecycleExecution) GetCursor() interface{}`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *LifecycleExecution) GetCursorOk() (*interface{}, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *LifecycleExecution) SetCursor(v interface{})`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *LifecycleExecution) HasCursor() bool`

HasCursor returns a boolean if a field has been set.

### SetCursorNil

`func (o *LifecycleExecution) SetCursorNil(b bool)`

 SetCursorNil sets the value for Cursor to be an explicit nil

### UnsetCursor
`func (o *LifecycleExecution) UnsetCursor()`

UnsetCursor ensures that no value is present for Cursor, not even an explicit nil
### GetPlannedCount

`func (o *LifecycleExecution) GetPlannedCount() int64`

GetPlannedCount returns the PlannedCount field if non-nil, zero value otherwise.

### GetPlannedCountOk

`func (o *LifecycleExecution) GetPlannedCountOk() (*int64, bool)`

GetPlannedCountOk returns a tuple with the PlannedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlannedCount

`func (o *LifecycleExecution) SetPlannedCount(v int64)`

SetPlannedCount sets PlannedCount field to given value.

### HasPlannedCount

`func (o *LifecycleExecution) HasPlannedCount() bool`

HasPlannedCount returns a boolean if a field has been set.

### GetProcessedCount

`func (o *LifecycleExecution) GetProcessedCount() int64`

GetProcessedCount returns the ProcessedCount field if non-nil, zero value otherwise.

### GetProcessedCountOk

`func (o *LifecycleExecution) GetProcessedCountOk() (*int64, bool)`

GetProcessedCountOk returns a tuple with the ProcessedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedCount

`func (o *LifecycleExecution) SetProcessedCount(v int64)`

SetProcessedCount sets ProcessedCount field to given value.

### HasProcessedCount

`func (o *LifecycleExecution) HasProcessedCount() bool`

HasProcessedCount returns a boolean if a field has been set.

### GetSucceededCount

`func (o *LifecycleExecution) GetSucceededCount() int64`

GetSucceededCount returns the SucceededCount field if non-nil, zero value otherwise.

### GetSucceededCountOk

`func (o *LifecycleExecution) GetSucceededCountOk() (*int64, bool)`

GetSucceededCountOk returns a tuple with the SucceededCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSucceededCount

`func (o *LifecycleExecution) SetSucceededCount(v int64)`

SetSucceededCount sets SucceededCount field to given value.

### HasSucceededCount

`func (o *LifecycleExecution) HasSucceededCount() bool`

HasSucceededCount returns a boolean if a field has been set.

### GetFailedCount

`func (o *LifecycleExecution) GetFailedCount() int64`

GetFailedCount returns the FailedCount field if non-nil, zero value otherwise.

### GetFailedCountOk

`func (o *LifecycleExecution) GetFailedCountOk() (*int64, bool)`

GetFailedCountOk returns a tuple with the FailedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedCount

`func (o *LifecycleExecution) SetFailedCount(v int64)`

SetFailedCount sets FailedCount field to given value.

### HasFailedCount

`func (o *LifecycleExecution) HasFailedCount() bool`

HasFailedCount returns a boolean if a field has been set.

### GetHeldCount

`func (o *LifecycleExecution) GetHeldCount() int64`

GetHeldCount returns the HeldCount field if non-nil, zero value otherwise.

### GetHeldCountOk

`func (o *LifecycleExecution) GetHeldCountOk() (*int64, bool)`

GetHeldCountOk returns a tuple with the HeldCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeldCount

`func (o *LifecycleExecution) SetHeldCount(v int64)`

SetHeldCount sets HeldCount field to given value.

### HasHeldCount

`func (o *LifecycleExecution) HasHeldCount() bool`

HasHeldCount returns a boolean if a field has been set.

### GetStartedAt

`func (o *LifecycleExecution) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *LifecycleExecution) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *LifecycleExecution) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *LifecycleExecution) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *LifecycleExecution) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *LifecycleExecution) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *LifecycleExecution) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *LifecycleExecution) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *LifecycleExecution) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *LifecycleExecution) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *LifecycleExecution) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *LifecycleExecution) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetFailureCode

`func (o *LifecycleExecution) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *LifecycleExecution) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *LifecycleExecution) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *LifecycleExecution) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### GetFailureDetail

`func (o *LifecycleExecution) GetFailureDetail() string`

GetFailureDetail returns the FailureDetail field if non-nil, zero value otherwise.

### GetFailureDetailOk

`func (o *LifecycleExecution) GetFailureDetailOk() (*string, bool)`

GetFailureDetailOk returns a tuple with the FailureDetail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureDetail

`func (o *LifecycleExecution) SetFailureDetail(v string)`

SetFailureDetail sets FailureDetail field to given value.

### HasFailureDetail

`func (o *LifecycleExecution) HasFailureDetail() bool`

HasFailureDetail returns a boolean if a field has been set.

### GetMetadata

`func (o *LifecycleExecution) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LifecycleExecution) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LifecycleExecution) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LifecycleExecution) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *LifecycleExecution) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *LifecycleExecution) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRevision

`func (o *LifecycleExecution) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *LifecycleExecution) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *LifecycleExecution) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *LifecycleExecution) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *LifecycleExecution) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LifecycleExecution) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LifecycleExecution) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *LifecycleExecution) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LifecycleExecution) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LifecycleExecution) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetPolicyVersion

`func (o *LifecycleExecution) GetPolicyVersion() string`

GetPolicyVersion returns the PolicyVersion field if non-nil, zero value otherwise.

### GetPolicyVersionOk

`func (o *LifecycleExecution) GetPolicyVersionOk() (*string, bool)`

GetPolicyVersionOk returns a tuple with the PolicyVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyVersion

`func (o *LifecycleExecution) SetPolicyVersion(v string)`

SetPolicyVersion sets PolicyVersion field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


