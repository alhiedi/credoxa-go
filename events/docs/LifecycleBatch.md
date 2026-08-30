# LifecycleBatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**BatchId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Kind** | [**LifecycleBatchKindEnum**](LifecycleBatchKindEnum.md) |  | 
**Status** | Pointer to [**LifecycleBatchStatusEnum**](LifecycleBatchStatusEnum.md) |  | [optional] 
**Sequence** | **int64** |  | 
**IdempotencyKey** | **string** |  | 
**CandidateCount** | Pointer to **int64** |  | [optional] 
**ProcessedCount** | Pointer to **int64** |  | [optional] 
**SucceededCount** | Pointer to **int64** |  | [optional] 
**FailedCount** | Pointer to **int64** |  | [optional] 
**HeldCount** | Pointer to **int64** |  | [optional] 
**ManifestId** | Pointer to **NullableString** |  | [optional] 
**ManifestChecksum** | Pointer to **string** |  | [optional] 
**StorageReference** | Pointer to **string** |  | [optional] 
**ArchiveVerifiedAt** | Pointer to **NullableTime** |  | [optional] 
**LeaseOwner** | Pointer to **string** |  | [optional] 
**LeaseAcquiredAt** | Pointer to **NullableTime** |  | [optional] 
**LeaseExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CursorStart** | Pointer to **interface{}** |  | [optional] 
**CursorEnd** | Pointer to **interface{}** |  | [optional] 
**FailureCode** | Pointer to **string** |  | [optional] 
**FailureDetail** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**Execution** | **string** |  | 

## Methods

### NewLifecycleBatch

`func NewLifecycleBatch(id string, batchId string, organizationId string, kind LifecycleBatchKindEnum, sequence int64, idempotencyKey string, createdAt time.Time, updatedAt time.Time, execution string, ) *LifecycleBatch`

NewLifecycleBatch instantiates a new LifecycleBatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleBatchWithDefaults

`func NewLifecycleBatchWithDefaults() *LifecycleBatch`

NewLifecycleBatchWithDefaults instantiates a new LifecycleBatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LifecycleBatch) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LifecycleBatch) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LifecycleBatch) SetId(v string)`

SetId sets Id field to given value.


### GetBatchId

`func (o *LifecycleBatch) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *LifecycleBatch) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *LifecycleBatch) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.


### GetOrganizationId

`func (o *LifecycleBatch) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleBatch) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleBatch) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetKind

`func (o *LifecycleBatch) GetKind() LifecycleBatchKindEnum`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *LifecycleBatch) GetKindOk() (*LifecycleBatchKindEnum, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *LifecycleBatch) SetKind(v LifecycleBatchKindEnum)`

SetKind sets Kind field to given value.


### GetStatus

`func (o *LifecycleBatch) GetStatus() LifecycleBatchStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LifecycleBatch) GetStatusOk() (*LifecycleBatchStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LifecycleBatch) SetStatus(v LifecycleBatchStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LifecycleBatch) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSequence

`func (o *LifecycleBatch) GetSequence() int64`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *LifecycleBatch) GetSequenceOk() (*int64, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *LifecycleBatch) SetSequence(v int64)`

SetSequence sets Sequence field to given value.


### GetIdempotencyKey

`func (o *LifecycleBatch) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *LifecycleBatch) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *LifecycleBatch) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetCandidateCount

`func (o *LifecycleBatch) GetCandidateCount() int64`

GetCandidateCount returns the CandidateCount field if non-nil, zero value otherwise.

### GetCandidateCountOk

`func (o *LifecycleBatch) GetCandidateCountOk() (*int64, bool)`

GetCandidateCountOk returns a tuple with the CandidateCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCandidateCount

`func (o *LifecycleBatch) SetCandidateCount(v int64)`

SetCandidateCount sets CandidateCount field to given value.

### HasCandidateCount

`func (o *LifecycleBatch) HasCandidateCount() bool`

HasCandidateCount returns a boolean if a field has been set.

### GetProcessedCount

`func (o *LifecycleBatch) GetProcessedCount() int64`

GetProcessedCount returns the ProcessedCount field if non-nil, zero value otherwise.

### GetProcessedCountOk

`func (o *LifecycleBatch) GetProcessedCountOk() (*int64, bool)`

GetProcessedCountOk returns a tuple with the ProcessedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedCount

`func (o *LifecycleBatch) SetProcessedCount(v int64)`

SetProcessedCount sets ProcessedCount field to given value.

### HasProcessedCount

`func (o *LifecycleBatch) HasProcessedCount() bool`

HasProcessedCount returns a boolean if a field has been set.

### GetSucceededCount

`func (o *LifecycleBatch) GetSucceededCount() int64`

GetSucceededCount returns the SucceededCount field if non-nil, zero value otherwise.

### GetSucceededCountOk

`func (o *LifecycleBatch) GetSucceededCountOk() (*int64, bool)`

GetSucceededCountOk returns a tuple with the SucceededCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSucceededCount

`func (o *LifecycleBatch) SetSucceededCount(v int64)`

SetSucceededCount sets SucceededCount field to given value.

### HasSucceededCount

`func (o *LifecycleBatch) HasSucceededCount() bool`

HasSucceededCount returns a boolean if a field has been set.

### GetFailedCount

`func (o *LifecycleBatch) GetFailedCount() int64`

GetFailedCount returns the FailedCount field if non-nil, zero value otherwise.

### GetFailedCountOk

`func (o *LifecycleBatch) GetFailedCountOk() (*int64, bool)`

GetFailedCountOk returns a tuple with the FailedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedCount

`func (o *LifecycleBatch) SetFailedCount(v int64)`

SetFailedCount sets FailedCount field to given value.

### HasFailedCount

`func (o *LifecycleBatch) HasFailedCount() bool`

HasFailedCount returns a boolean if a field has been set.

### GetHeldCount

`func (o *LifecycleBatch) GetHeldCount() int64`

GetHeldCount returns the HeldCount field if non-nil, zero value otherwise.

### GetHeldCountOk

`func (o *LifecycleBatch) GetHeldCountOk() (*int64, bool)`

GetHeldCountOk returns a tuple with the HeldCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeldCount

`func (o *LifecycleBatch) SetHeldCount(v int64)`

SetHeldCount sets HeldCount field to given value.

### HasHeldCount

`func (o *LifecycleBatch) HasHeldCount() bool`

HasHeldCount returns a boolean if a field has been set.

### GetManifestId

`func (o *LifecycleBatch) GetManifestId() string`

GetManifestId returns the ManifestId field if non-nil, zero value otherwise.

### GetManifestIdOk

`func (o *LifecycleBatch) GetManifestIdOk() (*string, bool)`

GetManifestIdOk returns a tuple with the ManifestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifestId

`func (o *LifecycleBatch) SetManifestId(v string)`

SetManifestId sets ManifestId field to given value.

### HasManifestId

`func (o *LifecycleBatch) HasManifestId() bool`

HasManifestId returns a boolean if a field has been set.

### SetManifestIdNil

`func (o *LifecycleBatch) SetManifestIdNil(b bool)`

 SetManifestIdNil sets the value for ManifestId to be an explicit nil

### UnsetManifestId
`func (o *LifecycleBatch) UnsetManifestId()`

UnsetManifestId ensures that no value is present for ManifestId, not even an explicit nil
### GetManifestChecksum

`func (o *LifecycleBatch) GetManifestChecksum() string`

GetManifestChecksum returns the ManifestChecksum field if non-nil, zero value otherwise.

### GetManifestChecksumOk

`func (o *LifecycleBatch) GetManifestChecksumOk() (*string, bool)`

GetManifestChecksumOk returns a tuple with the ManifestChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifestChecksum

`func (o *LifecycleBatch) SetManifestChecksum(v string)`

SetManifestChecksum sets ManifestChecksum field to given value.

### HasManifestChecksum

`func (o *LifecycleBatch) HasManifestChecksum() bool`

HasManifestChecksum returns a boolean if a field has been set.

### GetStorageReference

`func (o *LifecycleBatch) GetStorageReference() string`

GetStorageReference returns the StorageReference field if non-nil, zero value otherwise.

### GetStorageReferenceOk

`func (o *LifecycleBatch) GetStorageReferenceOk() (*string, bool)`

GetStorageReferenceOk returns a tuple with the StorageReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageReference

`func (o *LifecycleBatch) SetStorageReference(v string)`

SetStorageReference sets StorageReference field to given value.

### HasStorageReference

`func (o *LifecycleBatch) HasStorageReference() bool`

HasStorageReference returns a boolean if a field has been set.

### GetArchiveVerifiedAt

`func (o *LifecycleBatch) GetArchiveVerifiedAt() time.Time`

GetArchiveVerifiedAt returns the ArchiveVerifiedAt field if non-nil, zero value otherwise.

### GetArchiveVerifiedAtOk

`func (o *LifecycleBatch) GetArchiveVerifiedAtOk() (*time.Time, bool)`

GetArchiveVerifiedAtOk returns a tuple with the ArchiveVerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveVerifiedAt

`func (o *LifecycleBatch) SetArchiveVerifiedAt(v time.Time)`

SetArchiveVerifiedAt sets ArchiveVerifiedAt field to given value.

### HasArchiveVerifiedAt

`func (o *LifecycleBatch) HasArchiveVerifiedAt() bool`

HasArchiveVerifiedAt returns a boolean if a field has been set.

### SetArchiveVerifiedAtNil

`func (o *LifecycleBatch) SetArchiveVerifiedAtNil(b bool)`

 SetArchiveVerifiedAtNil sets the value for ArchiveVerifiedAt to be an explicit nil

### UnsetArchiveVerifiedAt
`func (o *LifecycleBatch) UnsetArchiveVerifiedAt()`

UnsetArchiveVerifiedAt ensures that no value is present for ArchiveVerifiedAt, not even an explicit nil
### GetLeaseOwner

`func (o *LifecycleBatch) GetLeaseOwner() string`

GetLeaseOwner returns the LeaseOwner field if non-nil, zero value otherwise.

### GetLeaseOwnerOk

`func (o *LifecycleBatch) GetLeaseOwnerOk() (*string, bool)`

GetLeaseOwnerOk returns a tuple with the LeaseOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseOwner

`func (o *LifecycleBatch) SetLeaseOwner(v string)`

SetLeaseOwner sets LeaseOwner field to given value.

### HasLeaseOwner

`func (o *LifecycleBatch) HasLeaseOwner() bool`

HasLeaseOwner returns a boolean if a field has been set.

### GetLeaseAcquiredAt

`func (o *LifecycleBatch) GetLeaseAcquiredAt() time.Time`

GetLeaseAcquiredAt returns the LeaseAcquiredAt field if non-nil, zero value otherwise.

### GetLeaseAcquiredAtOk

`func (o *LifecycleBatch) GetLeaseAcquiredAtOk() (*time.Time, bool)`

GetLeaseAcquiredAtOk returns a tuple with the LeaseAcquiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseAcquiredAt

`func (o *LifecycleBatch) SetLeaseAcquiredAt(v time.Time)`

SetLeaseAcquiredAt sets LeaseAcquiredAt field to given value.

### HasLeaseAcquiredAt

`func (o *LifecycleBatch) HasLeaseAcquiredAt() bool`

HasLeaseAcquiredAt returns a boolean if a field has been set.

### SetLeaseAcquiredAtNil

`func (o *LifecycleBatch) SetLeaseAcquiredAtNil(b bool)`

 SetLeaseAcquiredAtNil sets the value for LeaseAcquiredAt to be an explicit nil

### UnsetLeaseAcquiredAt
`func (o *LifecycleBatch) UnsetLeaseAcquiredAt()`

UnsetLeaseAcquiredAt ensures that no value is present for LeaseAcquiredAt, not even an explicit nil
### GetLeaseExpiresAt

`func (o *LifecycleBatch) GetLeaseExpiresAt() time.Time`

GetLeaseExpiresAt returns the LeaseExpiresAt field if non-nil, zero value otherwise.

### GetLeaseExpiresAtOk

`func (o *LifecycleBatch) GetLeaseExpiresAtOk() (*time.Time, bool)`

GetLeaseExpiresAtOk returns a tuple with the LeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpiresAt

`func (o *LifecycleBatch) SetLeaseExpiresAt(v time.Time)`

SetLeaseExpiresAt sets LeaseExpiresAt field to given value.

### HasLeaseExpiresAt

`func (o *LifecycleBatch) HasLeaseExpiresAt() bool`

HasLeaseExpiresAt returns a boolean if a field has been set.

### SetLeaseExpiresAtNil

`func (o *LifecycleBatch) SetLeaseExpiresAtNil(b bool)`

 SetLeaseExpiresAtNil sets the value for LeaseExpiresAt to be an explicit nil

### UnsetLeaseExpiresAt
`func (o *LifecycleBatch) UnsetLeaseExpiresAt()`

UnsetLeaseExpiresAt ensures that no value is present for LeaseExpiresAt, not even an explicit nil
### GetStartedAt

`func (o *LifecycleBatch) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *LifecycleBatch) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *LifecycleBatch) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *LifecycleBatch) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *LifecycleBatch) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *LifecycleBatch) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *LifecycleBatch) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *LifecycleBatch) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *LifecycleBatch) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *LifecycleBatch) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *LifecycleBatch) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *LifecycleBatch) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCursorStart

`func (o *LifecycleBatch) GetCursorStart() interface{}`

GetCursorStart returns the CursorStart field if non-nil, zero value otherwise.

### GetCursorStartOk

`func (o *LifecycleBatch) GetCursorStartOk() (*interface{}, bool)`

GetCursorStartOk returns a tuple with the CursorStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorStart

`func (o *LifecycleBatch) SetCursorStart(v interface{})`

SetCursorStart sets CursorStart field to given value.

### HasCursorStart

`func (o *LifecycleBatch) HasCursorStart() bool`

HasCursorStart returns a boolean if a field has been set.

### SetCursorStartNil

`func (o *LifecycleBatch) SetCursorStartNil(b bool)`

 SetCursorStartNil sets the value for CursorStart to be an explicit nil

### UnsetCursorStart
`func (o *LifecycleBatch) UnsetCursorStart()`

UnsetCursorStart ensures that no value is present for CursorStart, not even an explicit nil
### GetCursorEnd

`func (o *LifecycleBatch) GetCursorEnd() interface{}`

GetCursorEnd returns the CursorEnd field if non-nil, zero value otherwise.

### GetCursorEndOk

`func (o *LifecycleBatch) GetCursorEndOk() (*interface{}, bool)`

GetCursorEndOk returns a tuple with the CursorEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorEnd

`func (o *LifecycleBatch) SetCursorEnd(v interface{})`

SetCursorEnd sets CursorEnd field to given value.

### HasCursorEnd

`func (o *LifecycleBatch) HasCursorEnd() bool`

HasCursorEnd returns a boolean if a field has been set.

### SetCursorEndNil

`func (o *LifecycleBatch) SetCursorEndNil(b bool)`

 SetCursorEndNil sets the value for CursorEnd to be an explicit nil

### UnsetCursorEnd
`func (o *LifecycleBatch) UnsetCursorEnd()`

UnsetCursorEnd ensures that no value is present for CursorEnd, not even an explicit nil
### GetFailureCode

`func (o *LifecycleBatch) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *LifecycleBatch) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *LifecycleBatch) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *LifecycleBatch) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### GetFailureDetail

`func (o *LifecycleBatch) GetFailureDetail() string`

GetFailureDetail returns the FailureDetail field if non-nil, zero value otherwise.

### GetFailureDetailOk

`func (o *LifecycleBatch) GetFailureDetailOk() (*string, bool)`

GetFailureDetailOk returns a tuple with the FailureDetail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureDetail

`func (o *LifecycleBatch) SetFailureDetail(v string)`

SetFailureDetail sets FailureDetail field to given value.

### HasFailureDetail

`func (o *LifecycleBatch) HasFailureDetail() bool`

HasFailureDetail returns a boolean if a field has been set.

### GetMetadata

`func (o *LifecycleBatch) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LifecycleBatch) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LifecycleBatch) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LifecycleBatch) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *LifecycleBatch) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *LifecycleBatch) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRevision

`func (o *LifecycleBatch) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *LifecycleBatch) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *LifecycleBatch) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *LifecycleBatch) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *LifecycleBatch) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LifecycleBatch) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LifecycleBatch) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *LifecycleBatch) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LifecycleBatch) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LifecycleBatch) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetExecution

`func (o *LifecycleBatch) GetExecution() string`

GetExecution returns the Execution field if non-nil, zero value otherwise.

### GetExecutionOk

`func (o *LifecycleBatch) GetExecutionOk() (*string, bool)`

GetExecutionOk returns a tuple with the Execution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecution

`func (o *LifecycleBatch) SetExecution(v string)`

SetExecution sets Execution field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


