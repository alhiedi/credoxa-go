# RuntimeRecoveryStage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**StepId** | **string** |  | 
**StepOrder** | **int64** |  | 
**StageName** | **string** |  | 
**Action** | **string** |  | 
**Status** | Pointer to [**RuntimeRecoveryStageStatusEnum**](RuntimeRecoveryStageStatusEnum.md) |  | [optional] 
**FailureStrategy** | **string** |  | 
**Attempt** | Pointer to **int64** |  | [optional] 
**IdempotencyKey** | **string** |  | 
**Compensation** | Pointer to **bool** |  | [optional] 
**Retryable** | Pointer to **bool** |  | [optional] 
**TimedOut** | Pointer to **bool** |  | [optional] 
**RequestPayload** | Pointer to **interface{}** |  | [optional] 
**ResultPayload** | Pointer to **interface{}** |  | [optional] 
**ErrorCode** | Pointer to **NullableString** |  | [optional] 
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRuntimeRecoveryStage

`func NewRuntimeRecoveryStage(id string, stepId string, stepOrder int64, stageName string, action string, failureStrategy string, idempotencyKey string, createdAt time.Time, ) *RuntimeRecoveryStage`

NewRuntimeRecoveryStage instantiates a new RuntimeRecoveryStage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeRecoveryStageWithDefaults

`func NewRuntimeRecoveryStageWithDefaults() *RuntimeRecoveryStage`

NewRuntimeRecoveryStageWithDefaults instantiates a new RuntimeRecoveryStage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RuntimeRecoveryStage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RuntimeRecoveryStage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RuntimeRecoveryStage) SetId(v string)`

SetId sets Id field to given value.


### GetStepId

`func (o *RuntimeRecoveryStage) GetStepId() string`

GetStepId returns the StepId field if non-nil, zero value otherwise.

### GetStepIdOk

`func (o *RuntimeRecoveryStage) GetStepIdOk() (*string, bool)`

GetStepIdOk returns a tuple with the StepId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepId

`func (o *RuntimeRecoveryStage) SetStepId(v string)`

SetStepId sets StepId field to given value.


### GetStepOrder

`func (o *RuntimeRecoveryStage) GetStepOrder() int64`

GetStepOrder returns the StepOrder field if non-nil, zero value otherwise.

### GetStepOrderOk

`func (o *RuntimeRecoveryStage) GetStepOrderOk() (*int64, bool)`

GetStepOrderOk returns a tuple with the StepOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepOrder

`func (o *RuntimeRecoveryStage) SetStepOrder(v int64)`

SetStepOrder sets StepOrder field to given value.


### GetStageName

`func (o *RuntimeRecoveryStage) GetStageName() string`

GetStageName returns the StageName field if non-nil, zero value otherwise.

### GetStageNameOk

`func (o *RuntimeRecoveryStage) GetStageNameOk() (*string, bool)`

GetStageNameOk returns a tuple with the StageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageName

`func (o *RuntimeRecoveryStage) SetStageName(v string)`

SetStageName sets StageName field to given value.


### GetAction

`func (o *RuntimeRecoveryStage) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *RuntimeRecoveryStage) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *RuntimeRecoveryStage) SetAction(v string)`

SetAction sets Action field to given value.


### GetStatus

`func (o *RuntimeRecoveryStage) GetStatus() RuntimeRecoveryStageStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RuntimeRecoveryStage) GetStatusOk() (*RuntimeRecoveryStageStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RuntimeRecoveryStage) SetStatus(v RuntimeRecoveryStageStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RuntimeRecoveryStage) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetFailureStrategy

`func (o *RuntimeRecoveryStage) GetFailureStrategy() string`

GetFailureStrategy returns the FailureStrategy field if non-nil, zero value otherwise.

### GetFailureStrategyOk

`func (o *RuntimeRecoveryStage) GetFailureStrategyOk() (*string, bool)`

GetFailureStrategyOk returns a tuple with the FailureStrategy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureStrategy

`func (o *RuntimeRecoveryStage) SetFailureStrategy(v string)`

SetFailureStrategy sets FailureStrategy field to given value.


### GetAttempt

`func (o *RuntimeRecoveryStage) GetAttempt() int64`

GetAttempt returns the Attempt field if non-nil, zero value otherwise.

### GetAttemptOk

`func (o *RuntimeRecoveryStage) GetAttemptOk() (*int64, bool)`

GetAttemptOk returns a tuple with the Attempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempt

`func (o *RuntimeRecoveryStage) SetAttempt(v int64)`

SetAttempt sets Attempt field to given value.

### HasAttempt

`func (o *RuntimeRecoveryStage) HasAttempt() bool`

HasAttempt returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *RuntimeRecoveryStage) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *RuntimeRecoveryStage) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *RuntimeRecoveryStage) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetCompensation

`func (o *RuntimeRecoveryStage) GetCompensation() bool`

GetCompensation returns the Compensation field if non-nil, zero value otherwise.

### GetCompensationOk

`func (o *RuntimeRecoveryStage) GetCompensationOk() (*bool, bool)`

GetCompensationOk returns a tuple with the Compensation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompensation

`func (o *RuntimeRecoveryStage) SetCompensation(v bool)`

SetCompensation sets Compensation field to given value.

### HasCompensation

`func (o *RuntimeRecoveryStage) HasCompensation() bool`

HasCompensation returns a boolean if a field has been set.

### GetRetryable

`func (o *RuntimeRecoveryStage) GetRetryable() bool`

GetRetryable returns the Retryable field if non-nil, zero value otherwise.

### GetRetryableOk

`func (o *RuntimeRecoveryStage) GetRetryableOk() (*bool, bool)`

GetRetryableOk returns a tuple with the Retryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryable

`func (o *RuntimeRecoveryStage) SetRetryable(v bool)`

SetRetryable sets Retryable field to given value.

### HasRetryable

`func (o *RuntimeRecoveryStage) HasRetryable() bool`

HasRetryable returns a boolean if a field has been set.

### GetTimedOut

`func (o *RuntimeRecoveryStage) GetTimedOut() bool`

GetTimedOut returns the TimedOut field if non-nil, zero value otherwise.

### GetTimedOutOk

`func (o *RuntimeRecoveryStage) GetTimedOutOk() (*bool, bool)`

GetTimedOutOk returns a tuple with the TimedOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimedOut

`func (o *RuntimeRecoveryStage) SetTimedOut(v bool)`

SetTimedOut sets TimedOut field to given value.

### HasTimedOut

`func (o *RuntimeRecoveryStage) HasTimedOut() bool`

HasTimedOut returns a boolean if a field has been set.

### GetRequestPayload

`func (o *RuntimeRecoveryStage) GetRequestPayload() interface{}`

GetRequestPayload returns the RequestPayload field if non-nil, zero value otherwise.

### GetRequestPayloadOk

`func (o *RuntimeRecoveryStage) GetRequestPayloadOk() (*interface{}, bool)`

GetRequestPayloadOk returns a tuple with the RequestPayload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestPayload

`func (o *RuntimeRecoveryStage) SetRequestPayload(v interface{})`

SetRequestPayload sets RequestPayload field to given value.

### HasRequestPayload

`func (o *RuntimeRecoveryStage) HasRequestPayload() bool`

HasRequestPayload returns a boolean if a field has been set.

### SetRequestPayloadNil

`func (o *RuntimeRecoveryStage) SetRequestPayloadNil(b bool)`

 SetRequestPayloadNil sets the value for RequestPayload to be an explicit nil

### UnsetRequestPayload
`func (o *RuntimeRecoveryStage) UnsetRequestPayload()`

UnsetRequestPayload ensures that no value is present for RequestPayload, not even an explicit nil
### GetResultPayload

`func (o *RuntimeRecoveryStage) GetResultPayload() interface{}`

GetResultPayload returns the ResultPayload field if non-nil, zero value otherwise.

### GetResultPayloadOk

`func (o *RuntimeRecoveryStage) GetResultPayloadOk() (*interface{}, bool)`

GetResultPayloadOk returns a tuple with the ResultPayload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultPayload

`func (o *RuntimeRecoveryStage) SetResultPayload(v interface{})`

SetResultPayload sets ResultPayload field to given value.

### HasResultPayload

`func (o *RuntimeRecoveryStage) HasResultPayload() bool`

HasResultPayload returns a boolean if a field has been set.

### SetResultPayloadNil

`func (o *RuntimeRecoveryStage) SetResultPayloadNil(b bool)`

 SetResultPayloadNil sets the value for ResultPayload to be an explicit nil

### UnsetResultPayload
`func (o *RuntimeRecoveryStage) UnsetResultPayload()`

UnsetResultPayload ensures that no value is present for ResultPayload, not even an explicit nil
### GetErrorCode

`func (o *RuntimeRecoveryStage) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *RuntimeRecoveryStage) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *RuntimeRecoveryStage) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.

### HasErrorCode

`func (o *RuntimeRecoveryStage) HasErrorCode() bool`

HasErrorCode returns a boolean if a field has been set.

### SetErrorCodeNil

`func (o *RuntimeRecoveryStage) SetErrorCodeNil(b bool)`

 SetErrorCodeNil sets the value for ErrorCode to be an explicit nil

### UnsetErrorCode
`func (o *RuntimeRecoveryStage) UnsetErrorCode()`

UnsetErrorCode ensures that no value is present for ErrorCode, not even an explicit nil
### GetErrorMessage

`func (o *RuntimeRecoveryStage) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *RuntimeRecoveryStage) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *RuntimeRecoveryStage) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *RuntimeRecoveryStage) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *RuntimeRecoveryStage) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *RuntimeRecoveryStage) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetStartedAt

`func (o *RuntimeRecoveryStage) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RuntimeRecoveryStage) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RuntimeRecoveryStage) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RuntimeRecoveryStage) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RuntimeRecoveryStage) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RuntimeRecoveryStage) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RuntimeRecoveryStage) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RuntimeRecoveryStage) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RuntimeRecoveryStage) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RuntimeRecoveryStage) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RuntimeRecoveryStage) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RuntimeRecoveryStage) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *RuntimeRecoveryStage) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RuntimeRecoveryStage) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RuntimeRecoveryStage) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


