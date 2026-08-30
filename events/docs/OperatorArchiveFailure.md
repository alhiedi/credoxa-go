# OperatorArchiveFailure

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobId** | **string** |  | 
**Status** | **string** |  | 
**AttemptCount** | **int32** |  | 
**MaxAttempts** | **int32** |  | 
**Retryable** | **bool** |  | 
**FailureCode** | **string** |  | 
**FailureReason** | **string** |  | 
**CreatedAt** | **NullableTime** |  | 
**FailedAt** | **NullableTime** |  | 

## Methods

### NewOperatorArchiveFailure

`func NewOperatorArchiveFailure(jobId string, status string, attemptCount int32, maxAttempts int32, retryable bool, failureCode string, failureReason string, createdAt NullableTime, failedAt NullableTime, ) *OperatorArchiveFailure`

NewOperatorArchiveFailure instantiates a new OperatorArchiveFailure object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorArchiveFailureWithDefaults

`func NewOperatorArchiveFailureWithDefaults() *OperatorArchiveFailure`

NewOperatorArchiveFailureWithDefaults instantiates a new OperatorArchiveFailure object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobId

`func (o *OperatorArchiveFailure) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *OperatorArchiveFailure) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *OperatorArchiveFailure) SetJobId(v string)`

SetJobId sets JobId field to given value.


### GetStatus

`func (o *OperatorArchiveFailure) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorArchiveFailure) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorArchiveFailure) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAttemptCount

`func (o *OperatorArchiveFailure) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *OperatorArchiveFailure) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *OperatorArchiveFailure) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.


### GetMaxAttempts

`func (o *OperatorArchiveFailure) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorArchiveFailure) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorArchiveFailure) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetRetryable

`func (o *OperatorArchiveFailure) GetRetryable() bool`

GetRetryable returns the Retryable field if non-nil, zero value otherwise.

### GetRetryableOk

`func (o *OperatorArchiveFailure) GetRetryableOk() (*bool, bool)`

GetRetryableOk returns a tuple with the Retryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryable

`func (o *OperatorArchiveFailure) SetRetryable(v bool)`

SetRetryable sets Retryable field to given value.


### GetFailureCode

`func (o *OperatorArchiveFailure) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *OperatorArchiveFailure) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *OperatorArchiveFailure) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.


### GetFailureReason

`func (o *OperatorArchiveFailure) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *OperatorArchiveFailure) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *OperatorArchiveFailure) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.


### GetCreatedAt

`func (o *OperatorArchiveFailure) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorArchiveFailure) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorArchiveFailure) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *OperatorArchiveFailure) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *OperatorArchiveFailure) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetFailedAt

`func (o *OperatorArchiveFailure) GetFailedAt() time.Time`

GetFailedAt returns the FailedAt field if non-nil, zero value otherwise.

### GetFailedAtOk

`func (o *OperatorArchiveFailure) GetFailedAtOk() (*time.Time, bool)`

GetFailedAtOk returns a tuple with the FailedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedAt

`func (o *OperatorArchiveFailure) SetFailedAt(v time.Time)`

SetFailedAt sets FailedAt field to given value.


### SetFailedAtNil

`func (o *OperatorArchiveFailure) SetFailedAtNil(b bool)`

 SetFailedAtNil sets the value for FailedAt to be an explicit nil

### UnsetFailedAt
`func (o *OperatorArchiveFailure) UnsetFailedAt()`

UnsetFailedAt ensures that no value is present for FailedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


