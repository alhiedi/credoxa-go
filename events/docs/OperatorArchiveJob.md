# OperatorArchiveJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**Status** | **string** |  | 
**Source** | Pointer to **string** |  | [optional] 
**IdempotencyKey** | Pointer to **string** |  | [optional] 
**WindowStart** | Pointer to **NullableTime** |  | [optional] 
**WindowEnd** | Pointer to **NullableTime** |  | [optional] 
**AttemptCount** | Pointer to **int32** |  | [optional] 
**MaxAttempts** | Pointer to **int32** |  | [optional] 
**Retryable** | **bool** |  | 
**EventCount** | Pointer to **NullableInt32** |  | [optional] 
**UncompressedBytes** | Pointer to **NullableInt32** |  | [optional] 
**StoredBytes** | Pointer to **NullableInt32** |  | [optional] 
**Checksum** | Pointer to **NullableString** |  | [optional] 
**StorageUri** | Pointer to **NullableString** |  | [optional] 
**FailureCode** | Pointer to **NullableString** |  | [optional] 
**FailureReason** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewOperatorArchiveJob

`func NewOperatorArchiveJob(id string, organizationId string, status string, retryable bool, ) *OperatorArchiveJob`

NewOperatorArchiveJob instantiates a new OperatorArchiveJob object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorArchiveJobWithDefaults

`func NewOperatorArchiveJobWithDefaults() *OperatorArchiveJob`

NewOperatorArchiveJobWithDefaults instantiates a new OperatorArchiveJob object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorArchiveJob) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorArchiveJob) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorArchiveJob) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *OperatorArchiveJob) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorArchiveJob) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorArchiveJob) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetStatus

`func (o *OperatorArchiveJob) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorArchiveJob) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorArchiveJob) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSource

`func (o *OperatorArchiveJob) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *OperatorArchiveJob) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *OperatorArchiveJob) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *OperatorArchiveJob) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *OperatorArchiveJob) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *OperatorArchiveJob) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *OperatorArchiveJob) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.

### HasIdempotencyKey

`func (o *OperatorArchiveJob) HasIdempotencyKey() bool`

HasIdempotencyKey returns a boolean if a field has been set.

### GetWindowStart

`func (o *OperatorArchiveJob) GetWindowStart() time.Time`

GetWindowStart returns the WindowStart field if non-nil, zero value otherwise.

### GetWindowStartOk

`func (o *OperatorArchiveJob) GetWindowStartOk() (*time.Time, bool)`

GetWindowStartOk returns a tuple with the WindowStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowStart

`func (o *OperatorArchiveJob) SetWindowStart(v time.Time)`

SetWindowStart sets WindowStart field to given value.

### HasWindowStart

`func (o *OperatorArchiveJob) HasWindowStart() bool`

HasWindowStart returns a boolean if a field has been set.

### SetWindowStartNil

`func (o *OperatorArchiveJob) SetWindowStartNil(b bool)`

 SetWindowStartNil sets the value for WindowStart to be an explicit nil

### UnsetWindowStart
`func (o *OperatorArchiveJob) UnsetWindowStart()`

UnsetWindowStart ensures that no value is present for WindowStart, not even an explicit nil
### GetWindowEnd

`func (o *OperatorArchiveJob) GetWindowEnd() time.Time`

GetWindowEnd returns the WindowEnd field if non-nil, zero value otherwise.

### GetWindowEndOk

`func (o *OperatorArchiveJob) GetWindowEndOk() (*time.Time, bool)`

GetWindowEndOk returns a tuple with the WindowEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowEnd

`func (o *OperatorArchiveJob) SetWindowEnd(v time.Time)`

SetWindowEnd sets WindowEnd field to given value.

### HasWindowEnd

`func (o *OperatorArchiveJob) HasWindowEnd() bool`

HasWindowEnd returns a boolean if a field has been set.

### SetWindowEndNil

`func (o *OperatorArchiveJob) SetWindowEndNil(b bool)`

 SetWindowEndNil sets the value for WindowEnd to be an explicit nil

### UnsetWindowEnd
`func (o *OperatorArchiveJob) UnsetWindowEnd()`

UnsetWindowEnd ensures that no value is present for WindowEnd, not even an explicit nil
### GetAttemptCount

`func (o *OperatorArchiveJob) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *OperatorArchiveJob) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *OperatorArchiveJob) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *OperatorArchiveJob) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetMaxAttempts

`func (o *OperatorArchiveJob) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorArchiveJob) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorArchiveJob) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *OperatorArchiveJob) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.

### GetRetryable

`func (o *OperatorArchiveJob) GetRetryable() bool`

GetRetryable returns the Retryable field if non-nil, zero value otherwise.

### GetRetryableOk

`func (o *OperatorArchiveJob) GetRetryableOk() (*bool, bool)`

GetRetryableOk returns a tuple with the Retryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryable

`func (o *OperatorArchiveJob) SetRetryable(v bool)`

SetRetryable sets Retryable field to given value.


### GetEventCount

`func (o *OperatorArchiveJob) GetEventCount() int32`

GetEventCount returns the EventCount field if non-nil, zero value otherwise.

### GetEventCountOk

`func (o *OperatorArchiveJob) GetEventCountOk() (*int32, bool)`

GetEventCountOk returns a tuple with the EventCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventCount

`func (o *OperatorArchiveJob) SetEventCount(v int32)`

SetEventCount sets EventCount field to given value.

### HasEventCount

`func (o *OperatorArchiveJob) HasEventCount() bool`

HasEventCount returns a boolean if a field has been set.

### SetEventCountNil

`func (o *OperatorArchiveJob) SetEventCountNil(b bool)`

 SetEventCountNil sets the value for EventCount to be an explicit nil

### UnsetEventCount
`func (o *OperatorArchiveJob) UnsetEventCount()`

UnsetEventCount ensures that no value is present for EventCount, not even an explicit nil
### GetUncompressedBytes

`func (o *OperatorArchiveJob) GetUncompressedBytes() int32`

GetUncompressedBytes returns the UncompressedBytes field if non-nil, zero value otherwise.

### GetUncompressedBytesOk

`func (o *OperatorArchiveJob) GetUncompressedBytesOk() (*int32, bool)`

GetUncompressedBytesOk returns a tuple with the UncompressedBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUncompressedBytes

`func (o *OperatorArchiveJob) SetUncompressedBytes(v int32)`

SetUncompressedBytes sets UncompressedBytes field to given value.

### HasUncompressedBytes

`func (o *OperatorArchiveJob) HasUncompressedBytes() bool`

HasUncompressedBytes returns a boolean if a field has been set.

### SetUncompressedBytesNil

`func (o *OperatorArchiveJob) SetUncompressedBytesNil(b bool)`

 SetUncompressedBytesNil sets the value for UncompressedBytes to be an explicit nil

### UnsetUncompressedBytes
`func (o *OperatorArchiveJob) UnsetUncompressedBytes()`

UnsetUncompressedBytes ensures that no value is present for UncompressedBytes, not even an explicit nil
### GetStoredBytes

`func (o *OperatorArchiveJob) GetStoredBytes() int32`

GetStoredBytes returns the StoredBytes field if non-nil, zero value otherwise.

### GetStoredBytesOk

`func (o *OperatorArchiveJob) GetStoredBytesOk() (*int32, bool)`

GetStoredBytesOk returns a tuple with the StoredBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoredBytes

`func (o *OperatorArchiveJob) SetStoredBytes(v int32)`

SetStoredBytes sets StoredBytes field to given value.

### HasStoredBytes

`func (o *OperatorArchiveJob) HasStoredBytes() bool`

HasStoredBytes returns a boolean if a field has been set.

### SetStoredBytesNil

`func (o *OperatorArchiveJob) SetStoredBytesNil(b bool)`

 SetStoredBytesNil sets the value for StoredBytes to be an explicit nil

### UnsetStoredBytes
`func (o *OperatorArchiveJob) UnsetStoredBytes()`

UnsetStoredBytes ensures that no value is present for StoredBytes, not even an explicit nil
### GetChecksum

`func (o *OperatorArchiveJob) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *OperatorArchiveJob) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *OperatorArchiveJob) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *OperatorArchiveJob) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### SetChecksumNil

`func (o *OperatorArchiveJob) SetChecksumNil(b bool)`

 SetChecksumNil sets the value for Checksum to be an explicit nil

### UnsetChecksum
`func (o *OperatorArchiveJob) UnsetChecksum()`

UnsetChecksum ensures that no value is present for Checksum, not even an explicit nil
### GetStorageUri

`func (o *OperatorArchiveJob) GetStorageUri() string`

GetStorageUri returns the StorageUri field if non-nil, zero value otherwise.

### GetStorageUriOk

`func (o *OperatorArchiveJob) GetStorageUriOk() (*string, bool)`

GetStorageUriOk returns a tuple with the StorageUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageUri

`func (o *OperatorArchiveJob) SetStorageUri(v string)`

SetStorageUri sets StorageUri field to given value.

### HasStorageUri

`func (o *OperatorArchiveJob) HasStorageUri() bool`

HasStorageUri returns a boolean if a field has been set.

### SetStorageUriNil

`func (o *OperatorArchiveJob) SetStorageUriNil(b bool)`

 SetStorageUriNil sets the value for StorageUri to be an explicit nil

### UnsetStorageUri
`func (o *OperatorArchiveJob) UnsetStorageUri()`

UnsetStorageUri ensures that no value is present for StorageUri, not even an explicit nil
### GetFailureCode

`func (o *OperatorArchiveJob) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *OperatorArchiveJob) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *OperatorArchiveJob) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *OperatorArchiveJob) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### SetFailureCodeNil

`func (o *OperatorArchiveJob) SetFailureCodeNil(b bool)`

 SetFailureCodeNil sets the value for FailureCode to be an explicit nil

### UnsetFailureCode
`func (o *OperatorArchiveJob) UnsetFailureCode()`

UnsetFailureCode ensures that no value is present for FailureCode, not even an explicit nil
### GetFailureReason

`func (o *OperatorArchiveJob) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *OperatorArchiveJob) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *OperatorArchiveJob) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *OperatorArchiveJob) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### SetFailureReasonNil

`func (o *OperatorArchiveJob) SetFailureReasonNil(b bool)`

 SetFailureReasonNil sets the value for FailureReason to be an explicit nil

### UnsetFailureReason
`func (o *OperatorArchiveJob) UnsetFailureReason()`

UnsetFailureReason ensures that no value is present for FailureReason, not even an explicit nil
### GetCreatedAt

`func (o *OperatorArchiveJob) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorArchiveJob) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorArchiveJob) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *OperatorArchiveJob) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *OperatorArchiveJob) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *OperatorArchiveJob) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *OperatorArchiveJob) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorArchiveJob) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorArchiveJob) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *OperatorArchiveJob) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *OperatorArchiveJob) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *OperatorArchiveJob) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetStartedAt

`func (o *OperatorArchiveJob) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *OperatorArchiveJob) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *OperatorArchiveJob) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *OperatorArchiveJob) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *OperatorArchiveJob) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *OperatorArchiveJob) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *OperatorArchiveJob) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *OperatorArchiveJob) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *OperatorArchiveJob) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *OperatorArchiveJob) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *OperatorArchiveJob) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *OperatorArchiveJob) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


