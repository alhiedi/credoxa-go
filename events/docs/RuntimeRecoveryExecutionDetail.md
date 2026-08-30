# RuntimeRecoveryExecutionDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**ConsumerId** | Pointer to **NullableString** |  | [optional] 
**IncidentId** | Pointer to **NullableString** |  | [optional] 
**PolicyId** | Pointer to **NullableString** |  | [optional] 
**RecoveryPlanId** | **string** |  | 
**RecoveryPlanRevision** | **int64** |  | 
**Status** | Pointer to [**RuntimeRecoveryExecutionStatusEnum**](RuntimeRecoveryExecutionStatusEnum.md) |  | [optional] [default to RUNTIMERECOVERYEXECUTIONSTATUSENUM_PENDING]
**CurrentStage** | Pointer to **int64** |  | [optional] 
**AttemptCount** | Pointer to **int64** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CorrelationId** | **string** |  | 
**FailureCode** | Pointer to **NullableString** |  | [optional] 
**FailureReason** | Pointer to **NullableString** |  | [optional] 
**EscalationRequired** | Pointer to **bool** |  | [optional] 
**LeaseOwner** | Pointer to **NullableString** |  | [optional] 
**LeaseEpoch** | Pointer to **NullableInt64** |  | [optional] 
**LeaseExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**VerificationDueAt** | Pointer to **NullableTime** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**IsActive** | **bool** |  | [readonly] 
**IsTerminal** | **bool** |  | [readonly] 
**SafetyDecision** | Pointer to **interface{}** |  | [optional] 
**RecoverySnapshotBefore** | Pointer to **interface{}** |  | [optional] 
**RecoverySnapshotAfter** | Pointer to **interface{}** |  | [optional] 
**OrchestrationReport** | Pointer to **interface{}** |  | [optional] 
**StageExecutions** | [**[]RuntimeRecoveryStage**](RuntimeRecoveryStage.md) |  | [readonly] 
**Verifications** | [**[]RuntimeRecoveryVerification**](RuntimeRecoveryVerification.md) |  | [readonly] 
**Occurrences** | [**[]RuntimeRecoveryOccurrence**](RuntimeRecoveryOccurrence.md) |  | [readonly] 
**Dispatch** | [**RuntimeRecoveryDispatch**](RuntimeRecoveryDispatch.md) |  | [readonly] 

## Methods

### NewRuntimeRecoveryExecutionDetail

`func NewRuntimeRecoveryExecutionDetail(id string, organizationId string, recoveryPlanId string, recoveryPlanRevision int64, correlationId string, createdAt time.Time, updatedAt time.Time, isActive bool, isTerminal bool, stageExecutions []RuntimeRecoveryStage, verifications []RuntimeRecoveryVerification, occurrences []RuntimeRecoveryOccurrence, dispatch RuntimeRecoveryDispatch, ) *RuntimeRecoveryExecutionDetail`

NewRuntimeRecoveryExecutionDetail instantiates a new RuntimeRecoveryExecutionDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeRecoveryExecutionDetailWithDefaults

`func NewRuntimeRecoveryExecutionDetailWithDefaults() *RuntimeRecoveryExecutionDetail`

NewRuntimeRecoveryExecutionDetailWithDefaults instantiates a new RuntimeRecoveryExecutionDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RuntimeRecoveryExecutionDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RuntimeRecoveryExecutionDetail) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RuntimeRecoveryExecutionDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RuntimeRecoveryExecutionDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetConsumerId

`func (o *RuntimeRecoveryExecutionDetail) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *RuntimeRecoveryExecutionDetail) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *RuntimeRecoveryExecutionDetail) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *RuntimeRecoveryExecutionDetail) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *RuntimeRecoveryExecutionDetail) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetIncidentId

`func (o *RuntimeRecoveryExecutionDetail) GetIncidentId() string`

GetIncidentId returns the IncidentId field if non-nil, zero value otherwise.

### GetIncidentIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetIncidentIdOk() (*string, bool)`

GetIncidentIdOk returns a tuple with the IncidentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentId

`func (o *RuntimeRecoveryExecutionDetail) SetIncidentId(v string)`

SetIncidentId sets IncidentId field to given value.

### HasIncidentId

`func (o *RuntimeRecoveryExecutionDetail) HasIncidentId() bool`

HasIncidentId returns a boolean if a field has been set.

### SetIncidentIdNil

`func (o *RuntimeRecoveryExecutionDetail) SetIncidentIdNil(b bool)`

 SetIncidentIdNil sets the value for IncidentId to be an explicit nil

### UnsetIncidentId
`func (o *RuntimeRecoveryExecutionDetail) UnsetIncidentId()`

UnsetIncidentId ensures that no value is present for IncidentId, not even an explicit nil
### GetPolicyId

`func (o *RuntimeRecoveryExecutionDetail) GetPolicyId() string`

GetPolicyId returns the PolicyId field if non-nil, zero value otherwise.

### GetPolicyIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetPolicyIdOk() (*string, bool)`

GetPolicyIdOk returns a tuple with the PolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyId

`func (o *RuntimeRecoveryExecutionDetail) SetPolicyId(v string)`

SetPolicyId sets PolicyId field to given value.

### HasPolicyId

`func (o *RuntimeRecoveryExecutionDetail) HasPolicyId() bool`

HasPolicyId returns a boolean if a field has been set.

### SetPolicyIdNil

`func (o *RuntimeRecoveryExecutionDetail) SetPolicyIdNil(b bool)`

 SetPolicyIdNil sets the value for PolicyId to be an explicit nil

### UnsetPolicyId
`func (o *RuntimeRecoveryExecutionDetail) UnsetPolicyId()`

UnsetPolicyId ensures that no value is present for PolicyId, not even an explicit nil
### GetRecoveryPlanId

`func (o *RuntimeRecoveryExecutionDetail) GetRecoveryPlanId() string`

GetRecoveryPlanId returns the RecoveryPlanId field if non-nil, zero value otherwise.

### GetRecoveryPlanIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetRecoveryPlanIdOk() (*string, bool)`

GetRecoveryPlanIdOk returns a tuple with the RecoveryPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPlanId

`func (o *RuntimeRecoveryExecutionDetail) SetRecoveryPlanId(v string)`

SetRecoveryPlanId sets RecoveryPlanId field to given value.


### GetRecoveryPlanRevision

`func (o *RuntimeRecoveryExecutionDetail) GetRecoveryPlanRevision() int64`

GetRecoveryPlanRevision returns the RecoveryPlanRevision field if non-nil, zero value otherwise.

### GetRecoveryPlanRevisionOk

`func (o *RuntimeRecoveryExecutionDetail) GetRecoveryPlanRevisionOk() (*int64, bool)`

GetRecoveryPlanRevisionOk returns a tuple with the RecoveryPlanRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPlanRevision

`func (o *RuntimeRecoveryExecutionDetail) SetRecoveryPlanRevision(v int64)`

SetRecoveryPlanRevision sets RecoveryPlanRevision field to given value.


### GetStatus

`func (o *RuntimeRecoveryExecutionDetail) GetStatus() RuntimeRecoveryExecutionStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RuntimeRecoveryExecutionDetail) GetStatusOk() (*RuntimeRecoveryExecutionStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RuntimeRecoveryExecutionDetail) SetStatus(v RuntimeRecoveryExecutionStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RuntimeRecoveryExecutionDetail) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCurrentStage

`func (o *RuntimeRecoveryExecutionDetail) GetCurrentStage() int64`

GetCurrentStage returns the CurrentStage field if non-nil, zero value otherwise.

### GetCurrentStageOk

`func (o *RuntimeRecoveryExecutionDetail) GetCurrentStageOk() (*int64, bool)`

GetCurrentStageOk returns a tuple with the CurrentStage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStage

`func (o *RuntimeRecoveryExecutionDetail) SetCurrentStage(v int64)`

SetCurrentStage sets CurrentStage field to given value.

### HasCurrentStage

`func (o *RuntimeRecoveryExecutionDetail) HasCurrentStage() bool`

HasCurrentStage returns a boolean if a field has been set.

### GetAttemptCount

`func (o *RuntimeRecoveryExecutionDetail) GetAttemptCount() int64`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *RuntimeRecoveryExecutionDetail) GetAttemptCountOk() (*int64, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *RuntimeRecoveryExecutionDetail) SetAttemptCount(v int64)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *RuntimeRecoveryExecutionDetail) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetRevision

`func (o *RuntimeRecoveryExecutionDetail) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *RuntimeRecoveryExecutionDetail) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *RuntimeRecoveryExecutionDetail) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *RuntimeRecoveryExecutionDetail) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCorrelationId

`func (o *RuntimeRecoveryExecutionDetail) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *RuntimeRecoveryExecutionDetail) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *RuntimeRecoveryExecutionDetail) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetFailureCode

`func (o *RuntimeRecoveryExecutionDetail) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *RuntimeRecoveryExecutionDetail) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *RuntimeRecoveryExecutionDetail) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *RuntimeRecoveryExecutionDetail) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### SetFailureCodeNil

`func (o *RuntimeRecoveryExecutionDetail) SetFailureCodeNil(b bool)`

 SetFailureCodeNil sets the value for FailureCode to be an explicit nil

### UnsetFailureCode
`func (o *RuntimeRecoveryExecutionDetail) UnsetFailureCode()`

UnsetFailureCode ensures that no value is present for FailureCode, not even an explicit nil
### GetFailureReason

`func (o *RuntimeRecoveryExecutionDetail) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *RuntimeRecoveryExecutionDetail) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *RuntimeRecoveryExecutionDetail) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *RuntimeRecoveryExecutionDetail) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### SetFailureReasonNil

`func (o *RuntimeRecoveryExecutionDetail) SetFailureReasonNil(b bool)`

 SetFailureReasonNil sets the value for FailureReason to be an explicit nil

### UnsetFailureReason
`func (o *RuntimeRecoveryExecutionDetail) UnsetFailureReason()`

UnsetFailureReason ensures that no value is present for FailureReason, not even an explicit nil
### GetEscalationRequired

`func (o *RuntimeRecoveryExecutionDetail) GetEscalationRequired() bool`

GetEscalationRequired returns the EscalationRequired field if non-nil, zero value otherwise.

### GetEscalationRequiredOk

`func (o *RuntimeRecoveryExecutionDetail) GetEscalationRequiredOk() (*bool, bool)`

GetEscalationRequiredOk returns a tuple with the EscalationRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEscalationRequired

`func (o *RuntimeRecoveryExecutionDetail) SetEscalationRequired(v bool)`

SetEscalationRequired sets EscalationRequired field to given value.

### HasEscalationRequired

`func (o *RuntimeRecoveryExecutionDetail) HasEscalationRequired() bool`

HasEscalationRequired returns a boolean if a field has been set.

### GetLeaseOwner

`func (o *RuntimeRecoveryExecutionDetail) GetLeaseOwner() string`

GetLeaseOwner returns the LeaseOwner field if non-nil, zero value otherwise.

### GetLeaseOwnerOk

`func (o *RuntimeRecoveryExecutionDetail) GetLeaseOwnerOk() (*string, bool)`

GetLeaseOwnerOk returns a tuple with the LeaseOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseOwner

`func (o *RuntimeRecoveryExecutionDetail) SetLeaseOwner(v string)`

SetLeaseOwner sets LeaseOwner field to given value.

### HasLeaseOwner

`func (o *RuntimeRecoveryExecutionDetail) HasLeaseOwner() bool`

HasLeaseOwner returns a boolean if a field has been set.

### SetLeaseOwnerNil

`func (o *RuntimeRecoveryExecutionDetail) SetLeaseOwnerNil(b bool)`

 SetLeaseOwnerNil sets the value for LeaseOwner to be an explicit nil

### UnsetLeaseOwner
`func (o *RuntimeRecoveryExecutionDetail) UnsetLeaseOwner()`

UnsetLeaseOwner ensures that no value is present for LeaseOwner, not even an explicit nil
### GetLeaseEpoch

`func (o *RuntimeRecoveryExecutionDetail) GetLeaseEpoch() int64`

GetLeaseEpoch returns the LeaseEpoch field if non-nil, zero value otherwise.

### GetLeaseEpochOk

`func (o *RuntimeRecoveryExecutionDetail) GetLeaseEpochOk() (*int64, bool)`

GetLeaseEpochOk returns a tuple with the LeaseEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseEpoch

`func (o *RuntimeRecoveryExecutionDetail) SetLeaseEpoch(v int64)`

SetLeaseEpoch sets LeaseEpoch field to given value.

### HasLeaseEpoch

`func (o *RuntimeRecoveryExecutionDetail) HasLeaseEpoch() bool`

HasLeaseEpoch returns a boolean if a field has been set.

### SetLeaseEpochNil

`func (o *RuntimeRecoveryExecutionDetail) SetLeaseEpochNil(b bool)`

 SetLeaseEpochNil sets the value for LeaseEpoch to be an explicit nil

### UnsetLeaseEpoch
`func (o *RuntimeRecoveryExecutionDetail) UnsetLeaseEpoch()`

UnsetLeaseEpoch ensures that no value is present for LeaseEpoch, not even an explicit nil
### GetLeaseExpiresAt

`func (o *RuntimeRecoveryExecutionDetail) GetLeaseExpiresAt() time.Time`

GetLeaseExpiresAt returns the LeaseExpiresAt field if non-nil, zero value otherwise.

### GetLeaseExpiresAtOk

`func (o *RuntimeRecoveryExecutionDetail) GetLeaseExpiresAtOk() (*time.Time, bool)`

GetLeaseExpiresAtOk returns a tuple with the LeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpiresAt

`func (o *RuntimeRecoveryExecutionDetail) SetLeaseExpiresAt(v time.Time)`

SetLeaseExpiresAt sets LeaseExpiresAt field to given value.

### HasLeaseExpiresAt

`func (o *RuntimeRecoveryExecutionDetail) HasLeaseExpiresAt() bool`

HasLeaseExpiresAt returns a boolean if a field has been set.

### SetLeaseExpiresAtNil

`func (o *RuntimeRecoveryExecutionDetail) SetLeaseExpiresAtNil(b bool)`

 SetLeaseExpiresAtNil sets the value for LeaseExpiresAt to be an explicit nil

### UnsetLeaseExpiresAt
`func (o *RuntimeRecoveryExecutionDetail) UnsetLeaseExpiresAt()`

UnsetLeaseExpiresAt ensures that no value is present for LeaseExpiresAt, not even an explicit nil
### GetVerificationDueAt

`func (o *RuntimeRecoveryExecutionDetail) GetVerificationDueAt() time.Time`

GetVerificationDueAt returns the VerificationDueAt field if non-nil, zero value otherwise.

### GetVerificationDueAtOk

`func (o *RuntimeRecoveryExecutionDetail) GetVerificationDueAtOk() (*time.Time, bool)`

GetVerificationDueAtOk returns a tuple with the VerificationDueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationDueAt

`func (o *RuntimeRecoveryExecutionDetail) SetVerificationDueAt(v time.Time)`

SetVerificationDueAt sets VerificationDueAt field to given value.

### HasVerificationDueAt

`func (o *RuntimeRecoveryExecutionDetail) HasVerificationDueAt() bool`

HasVerificationDueAt returns a boolean if a field has been set.

### SetVerificationDueAtNil

`func (o *RuntimeRecoveryExecutionDetail) SetVerificationDueAtNil(b bool)`

 SetVerificationDueAtNil sets the value for VerificationDueAt to be an explicit nil

### UnsetVerificationDueAt
`func (o *RuntimeRecoveryExecutionDetail) UnsetVerificationDueAt()`

UnsetVerificationDueAt ensures that no value is present for VerificationDueAt, not even an explicit nil
### GetStartedAt

`func (o *RuntimeRecoveryExecutionDetail) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RuntimeRecoveryExecutionDetail) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RuntimeRecoveryExecutionDetail) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RuntimeRecoveryExecutionDetail) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RuntimeRecoveryExecutionDetail) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RuntimeRecoveryExecutionDetail) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RuntimeRecoveryExecutionDetail) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RuntimeRecoveryExecutionDetail) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RuntimeRecoveryExecutionDetail) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RuntimeRecoveryExecutionDetail) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RuntimeRecoveryExecutionDetail) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RuntimeRecoveryExecutionDetail) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *RuntimeRecoveryExecutionDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RuntimeRecoveryExecutionDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RuntimeRecoveryExecutionDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RuntimeRecoveryExecutionDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RuntimeRecoveryExecutionDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RuntimeRecoveryExecutionDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetIsActive

`func (o *RuntimeRecoveryExecutionDetail) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *RuntimeRecoveryExecutionDetail) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *RuntimeRecoveryExecutionDetail) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetIsTerminal

`func (o *RuntimeRecoveryExecutionDetail) GetIsTerminal() bool`

GetIsTerminal returns the IsTerminal field if non-nil, zero value otherwise.

### GetIsTerminalOk

`func (o *RuntimeRecoveryExecutionDetail) GetIsTerminalOk() (*bool, bool)`

GetIsTerminalOk returns a tuple with the IsTerminal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTerminal

`func (o *RuntimeRecoveryExecutionDetail) SetIsTerminal(v bool)`

SetIsTerminal sets IsTerminal field to given value.


### GetSafetyDecision

`func (o *RuntimeRecoveryExecutionDetail) GetSafetyDecision() interface{}`

GetSafetyDecision returns the SafetyDecision field if non-nil, zero value otherwise.

### GetSafetyDecisionOk

`func (o *RuntimeRecoveryExecutionDetail) GetSafetyDecisionOk() (*interface{}, bool)`

GetSafetyDecisionOk returns a tuple with the SafetyDecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyDecision

`func (o *RuntimeRecoveryExecutionDetail) SetSafetyDecision(v interface{})`

SetSafetyDecision sets SafetyDecision field to given value.

### HasSafetyDecision

`func (o *RuntimeRecoveryExecutionDetail) HasSafetyDecision() bool`

HasSafetyDecision returns a boolean if a field has been set.

### SetSafetyDecisionNil

`func (o *RuntimeRecoveryExecutionDetail) SetSafetyDecisionNil(b bool)`

 SetSafetyDecisionNil sets the value for SafetyDecision to be an explicit nil

### UnsetSafetyDecision
`func (o *RuntimeRecoveryExecutionDetail) UnsetSafetyDecision()`

UnsetSafetyDecision ensures that no value is present for SafetyDecision, not even an explicit nil
### GetRecoverySnapshotBefore

`func (o *RuntimeRecoveryExecutionDetail) GetRecoverySnapshotBefore() interface{}`

GetRecoverySnapshotBefore returns the RecoverySnapshotBefore field if non-nil, zero value otherwise.

### GetRecoverySnapshotBeforeOk

`func (o *RuntimeRecoveryExecutionDetail) GetRecoverySnapshotBeforeOk() (*interface{}, bool)`

GetRecoverySnapshotBeforeOk returns a tuple with the RecoverySnapshotBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoverySnapshotBefore

`func (o *RuntimeRecoveryExecutionDetail) SetRecoverySnapshotBefore(v interface{})`

SetRecoverySnapshotBefore sets RecoverySnapshotBefore field to given value.

### HasRecoverySnapshotBefore

`func (o *RuntimeRecoveryExecutionDetail) HasRecoverySnapshotBefore() bool`

HasRecoverySnapshotBefore returns a boolean if a field has been set.

### SetRecoverySnapshotBeforeNil

`func (o *RuntimeRecoveryExecutionDetail) SetRecoverySnapshotBeforeNil(b bool)`

 SetRecoverySnapshotBeforeNil sets the value for RecoverySnapshotBefore to be an explicit nil

### UnsetRecoverySnapshotBefore
`func (o *RuntimeRecoveryExecutionDetail) UnsetRecoverySnapshotBefore()`

UnsetRecoverySnapshotBefore ensures that no value is present for RecoverySnapshotBefore, not even an explicit nil
### GetRecoverySnapshotAfter

`func (o *RuntimeRecoveryExecutionDetail) GetRecoverySnapshotAfter() interface{}`

GetRecoverySnapshotAfter returns the RecoverySnapshotAfter field if non-nil, zero value otherwise.

### GetRecoverySnapshotAfterOk

`func (o *RuntimeRecoveryExecutionDetail) GetRecoverySnapshotAfterOk() (*interface{}, bool)`

GetRecoverySnapshotAfterOk returns a tuple with the RecoverySnapshotAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoverySnapshotAfter

`func (o *RuntimeRecoveryExecutionDetail) SetRecoverySnapshotAfter(v interface{})`

SetRecoverySnapshotAfter sets RecoverySnapshotAfter field to given value.

### HasRecoverySnapshotAfter

`func (o *RuntimeRecoveryExecutionDetail) HasRecoverySnapshotAfter() bool`

HasRecoverySnapshotAfter returns a boolean if a field has been set.

### SetRecoverySnapshotAfterNil

`func (o *RuntimeRecoveryExecutionDetail) SetRecoverySnapshotAfterNil(b bool)`

 SetRecoverySnapshotAfterNil sets the value for RecoverySnapshotAfter to be an explicit nil

### UnsetRecoverySnapshotAfter
`func (o *RuntimeRecoveryExecutionDetail) UnsetRecoverySnapshotAfter()`

UnsetRecoverySnapshotAfter ensures that no value is present for RecoverySnapshotAfter, not even an explicit nil
### GetOrchestrationReport

`func (o *RuntimeRecoveryExecutionDetail) GetOrchestrationReport() interface{}`

GetOrchestrationReport returns the OrchestrationReport field if non-nil, zero value otherwise.

### GetOrchestrationReportOk

`func (o *RuntimeRecoveryExecutionDetail) GetOrchestrationReportOk() (*interface{}, bool)`

GetOrchestrationReportOk returns a tuple with the OrchestrationReport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrchestrationReport

`func (o *RuntimeRecoveryExecutionDetail) SetOrchestrationReport(v interface{})`

SetOrchestrationReport sets OrchestrationReport field to given value.

### HasOrchestrationReport

`func (o *RuntimeRecoveryExecutionDetail) HasOrchestrationReport() bool`

HasOrchestrationReport returns a boolean if a field has been set.

### SetOrchestrationReportNil

`func (o *RuntimeRecoveryExecutionDetail) SetOrchestrationReportNil(b bool)`

 SetOrchestrationReportNil sets the value for OrchestrationReport to be an explicit nil

### UnsetOrchestrationReport
`func (o *RuntimeRecoveryExecutionDetail) UnsetOrchestrationReport()`

UnsetOrchestrationReport ensures that no value is present for OrchestrationReport, not even an explicit nil
### GetStageExecutions

`func (o *RuntimeRecoveryExecutionDetail) GetStageExecutions() []RuntimeRecoveryStage`

GetStageExecutions returns the StageExecutions field if non-nil, zero value otherwise.

### GetStageExecutionsOk

`func (o *RuntimeRecoveryExecutionDetail) GetStageExecutionsOk() (*[]RuntimeRecoveryStage, bool)`

GetStageExecutionsOk returns a tuple with the StageExecutions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageExecutions

`func (o *RuntimeRecoveryExecutionDetail) SetStageExecutions(v []RuntimeRecoveryStage)`

SetStageExecutions sets StageExecutions field to given value.


### GetVerifications

`func (o *RuntimeRecoveryExecutionDetail) GetVerifications() []RuntimeRecoveryVerification`

GetVerifications returns the Verifications field if non-nil, zero value otherwise.

### GetVerificationsOk

`func (o *RuntimeRecoveryExecutionDetail) GetVerificationsOk() (*[]RuntimeRecoveryVerification, bool)`

GetVerificationsOk returns a tuple with the Verifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifications

`func (o *RuntimeRecoveryExecutionDetail) SetVerifications(v []RuntimeRecoveryVerification)`

SetVerifications sets Verifications field to given value.


### GetOccurrences

`func (o *RuntimeRecoveryExecutionDetail) GetOccurrences() []RuntimeRecoveryOccurrence`

GetOccurrences returns the Occurrences field if non-nil, zero value otherwise.

### GetOccurrencesOk

`func (o *RuntimeRecoveryExecutionDetail) GetOccurrencesOk() (*[]RuntimeRecoveryOccurrence, bool)`

GetOccurrencesOk returns a tuple with the Occurrences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrences

`func (o *RuntimeRecoveryExecutionDetail) SetOccurrences(v []RuntimeRecoveryOccurrence)`

SetOccurrences sets Occurrences field to given value.


### GetDispatch

`func (o *RuntimeRecoveryExecutionDetail) GetDispatch() RuntimeRecoveryDispatch`

GetDispatch returns the Dispatch field if non-nil, zero value otherwise.

### GetDispatchOk

`func (o *RuntimeRecoveryExecutionDetail) GetDispatchOk() (*RuntimeRecoveryDispatch, bool)`

GetDispatchOk returns a tuple with the Dispatch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDispatch

`func (o *RuntimeRecoveryExecutionDetail) SetDispatch(v RuntimeRecoveryDispatch)`

SetDispatch sets Dispatch field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


