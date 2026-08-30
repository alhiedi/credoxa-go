# RuntimeRecoveryVerification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**StageExecutionId** | **NullableString** |  | [readonly] 
**Status** | [**RuntimeRecoveryVerificationStatusEnum**](RuntimeRecoveryVerificationStatusEnum.md) |  | 
**Recovered** | Pointer to **bool** |  | [optional] 
**PolicyFingerprint** | **string** |  | 
**SnapshotCollectedAt** | Pointer to **NullableTime** |  | [optional] 
**EvaluatedAt** | **time.Time** |  | 
**SnapshotAgeSeconds** | Pointer to **NullableFloat64** |  | [optional] 
**Snapshot** | Pointer to **interface{}** |  | [optional] 
**RuleResults** | Pointer to **interface{}** |  | [optional] 
**Failures** | Pointer to **interface{}** |  | [optional] 
**Reason** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRuntimeRecoveryVerification

`func NewRuntimeRecoveryVerification(id string, stageExecutionId NullableString, status RuntimeRecoveryVerificationStatusEnum, policyFingerprint string, evaluatedAt time.Time, createdAt time.Time, ) *RuntimeRecoveryVerification`

NewRuntimeRecoveryVerification instantiates a new RuntimeRecoveryVerification object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeRecoveryVerificationWithDefaults

`func NewRuntimeRecoveryVerificationWithDefaults() *RuntimeRecoveryVerification`

NewRuntimeRecoveryVerificationWithDefaults instantiates a new RuntimeRecoveryVerification object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RuntimeRecoveryVerification) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RuntimeRecoveryVerification) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RuntimeRecoveryVerification) SetId(v string)`

SetId sets Id field to given value.


### GetStageExecutionId

`func (o *RuntimeRecoveryVerification) GetStageExecutionId() string`

GetStageExecutionId returns the StageExecutionId field if non-nil, zero value otherwise.

### GetStageExecutionIdOk

`func (o *RuntimeRecoveryVerification) GetStageExecutionIdOk() (*string, bool)`

GetStageExecutionIdOk returns a tuple with the StageExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageExecutionId

`func (o *RuntimeRecoveryVerification) SetStageExecutionId(v string)`

SetStageExecutionId sets StageExecutionId field to given value.


### SetStageExecutionIdNil

`func (o *RuntimeRecoveryVerification) SetStageExecutionIdNil(b bool)`

 SetStageExecutionIdNil sets the value for StageExecutionId to be an explicit nil

### UnsetStageExecutionId
`func (o *RuntimeRecoveryVerification) UnsetStageExecutionId()`

UnsetStageExecutionId ensures that no value is present for StageExecutionId, not even an explicit nil
### GetStatus

`func (o *RuntimeRecoveryVerification) GetStatus() RuntimeRecoveryVerificationStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RuntimeRecoveryVerification) GetStatusOk() (*RuntimeRecoveryVerificationStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RuntimeRecoveryVerification) SetStatus(v RuntimeRecoveryVerificationStatusEnum)`

SetStatus sets Status field to given value.


### GetRecovered

`func (o *RuntimeRecoveryVerification) GetRecovered() bool`

GetRecovered returns the Recovered field if non-nil, zero value otherwise.

### GetRecoveredOk

`func (o *RuntimeRecoveryVerification) GetRecoveredOk() (*bool, bool)`

GetRecoveredOk returns a tuple with the Recovered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecovered

`func (o *RuntimeRecoveryVerification) SetRecovered(v bool)`

SetRecovered sets Recovered field to given value.

### HasRecovered

`func (o *RuntimeRecoveryVerification) HasRecovered() bool`

HasRecovered returns a boolean if a field has been set.

### GetPolicyFingerprint

`func (o *RuntimeRecoveryVerification) GetPolicyFingerprint() string`

GetPolicyFingerprint returns the PolicyFingerprint field if non-nil, zero value otherwise.

### GetPolicyFingerprintOk

`func (o *RuntimeRecoveryVerification) GetPolicyFingerprintOk() (*string, bool)`

GetPolicyFingerprintOk returns a tuple with the PolicyFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyFingerprint

`func (o *RuntimeRecoveryVerification) SetPolicyFingerprint(v string)`

SetPolicyFingerprint sets PolicyFingerprint field to given value.


### GetSnapshotCollectedAt

`func (o *RuntimeRecoveryVerification) GetSnapshotCollectedAt() time.Time`

GetSnapshotCollectedAt returns the SnapshotCollectedAt field if non-nil, zero value otherwise.

### GetSnapshotCollectedAtOk

`func (o *RuntimeRecoveryVerification) GetSnapshotCollectedAtOk() (*time.Time, bool)`

GetSnapshotCollectedAtOk returns a tuple with the SnapshotCollectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotCollectedAt

`func (o *RuntimeRecoveryVerification) SetSnapshotCollectedAt(v time.Time)`

SetSnapshotCollectedAt sets SnapshotCollectedAt field to given value.

### HasSnapshotCollectedAt

`func (o *RuntimeRecoveryVerification) HasSnapshotCollectedAt() bool`

HasSnapshotCollectedAt returns a boolean if a field has been set.

### SetSnapshotCollectedAtNil

`func (o *RuntimeRecoveryVerification) SetSnapshotCollectedAtNil(b bool)`

 SetSnapshotCollectedAtNil sets the value for SnapshotCollectedAt to be an explicit nil

### UnsetSnapshotCollectedAt
`func (o *RuntimeRecoveryVerification) UnsetSnapshotCollectedAt()`

UnsetSnapshotCollectedAt ensures that no value is present for SnapshotCollectedAt, not even an explicit nil
### GetEvaluatedAt

`func (o *RuntimeRecoveryVerification) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *RuntimeRecoveryVerification) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *RuntimeRecoveryVerification) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.


### GetSnapshotAgeSeconds

`func (o *RuntimeRecoveryVerification) GetSnapshotAgeSeconds() float64`

GetSnapshotAgeSeconds returns the SnapshotAgeSeconds field if non-nil, zero value otherwise.

### GetSnapshotAgeSecondsOk

`func (o *RuntimeRecoveryVerification) GetSnapshotAgeSecondsOk() (*float64, bool)`

GetSnapshotAgeSecondsOk returns a tuple with the SnapshotAgeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotAgeSeconds

`func (o *RuntimeRecoveryVerification) SetSnapshotAgeSeconds(v float64)`

SetSnapshotAgeSeconds sets SnapshotAgeSeconds field to given value.

### HasSnapshotAgeSeconds

`func (o *RuntimeRecoveryVerification) HasSnapshotAgeSeconds() bool`

HasSnapshotAgeSeconds returns a boolean if a field has been set.

### SetSnapshotAgeSecondsNil

`func (o *RuntimeRecoveryVerification) SetSnapshotAgeSecondsNil(b bool)`

 SetSnapshotAgeSecondsNil sets the value for SnapshotAgeSeconds to be an explicit nil

### UnsetSnapshotAgeSeconds
`func (o *RuntimeRecoveryVerification) UnsetSnapshotAgeSeconds()`

UnsetSnapshotAgeSeconds ensures that no value is present for SnapshotAgeSeconds, not even an explicit nil
### GetSnapshot

`func (o *RuntimeRecoveryVerification) GetSnapshot() interface{}`

GetSnapshot returns the Snapshot field if non-nil, zero value otherwise.

### GetSnapshotOk

`func (o *RuntimeRecoveryVerification) GetSnapshotOk() (*interface{}, bool)`

GetSnapshotOk returns a tuple with the Snapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshot

`func (o *RuntimeRecoveryVerification) SetSnapshot(v interface{})`

SetSnapshot sets Snapshot field to given value.

### HasSnapshot

`func (o *RuntimeRecoveryVerification) HasSnapshot() bool`

HasSnapshot returns a boolean if a field has been set.

### SetSnapshotNil

`func (o *RuntimeRecoveryVerification) SetSnapshotNil(b bool)`

 SetSnapshotNil sets the value for Snapshot to be an explicit nil

### UnsetSnapshot
`func (o *RuntimeRecoveryVerification) UnsetSnapshot()`

UnsetSnapshot ensures that no value is present for Snapshot, not even an explicit nil
### GetRuleResults

`func (o *RuntimeRecoveryVerification) GetRuleResults() interface{}`

GetRuleResults returns the RuleResults field if non-nil, zero value otherwise.

### GetRuleResultsOk

`func (o *RuntimeRecoveryVerification) GetRuleResultsOk() (*interface{}, bool)`

GetRuleResultsOk returns a tuple with the RuleResults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleResults

`func (o *RuntimeRecoveryVerification) SetRuleResults(v interface{})`

SetRuleResults sets RuleResults field to given value.

### HasRuleResults

`func (o *RuntimeRecoveryVerification) HasRuleResults() bool`

HasRuleResults returns a boolean if a field has been set.

### SetRuleResultsNil

`func (o *RuntimeRecoveryVerification) SetRuleResultsNil(b bool)`

 SetRuleResultsNil sets the value for RuleResults to be an explicit nil

### UnsetRuleResults
`func (o *RuntimeRecoveryVerification) UnsetRuleResults()`

UnsetRuleResults ensures that no value is present for RuleResults, not even an explicit nil
### GetFailures

`func (o *RuntimeRecoveryVerification) GetFailures() interface{}`

GetFailures returns the Failures field if non-nil, zero value otherwise.

### GetFailuresOk

`func (o *RuntimeRecoveryVerification) GetFailuresOk() (*interface{}, bool)`

GetFailuresOk returns a tuple with the Failures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailures

`func (o *RuntimeRecoveryVerification) SetFailures(v interface{})`

SetFailures sets Failures field to given value.

### HasFailures

`func (o *RuntimeRecoveryVerification) HasFailures() bool`

HasFailures returns a boolean if a field has been set.

### SetFailuresNil

`func (o *RuntimeRecoveryVerification) SetFailuresNil(b bool)`

 SetFailuresNil sets the value for Failures to be an explicit nil

### UnsetFailures
`func (o *RuntimeRecoveryVerification) UnsetFailures()`

UnsetFailures ensures that no value is present for Failures, not even an explicit nil
### GetReason

`func (o *RuntimeRecoveryVerification) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RuntimeRecoveryVerification) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RuntimeRecoveryVerification) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *RuntimeRecoveryVerification) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *RuntimeRecoveryVerification) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *RuntimeRecoveryVerification) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetCreatedAt

`func (o *RuntimeRecoveryVerification) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RuntimeRecoveryVerification) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RuntimeRecoveryVerification) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


