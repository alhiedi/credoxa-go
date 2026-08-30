# RuntimeRecoveryExecutionList

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

## Methods

### NewRuntimeRecoveryExecutionList

`func NewRuntimeRecoveryExecutionList(id string, organizationId string, recoveryPlanId string, recoveryPlanRevision int64, correlationId string, createdAt time.Time, updatedAt time.Time, isActive bool, isTerminal bool, ) *RuntimeRecoveryExecutionList`

NewRuntimeRecoveryExecutionList instantiates a new RuntimeRecoveryExecutionList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeRecoveryExecutionListWithDefaults

`func NewRuntimeRecoveryExecutionListWithDefaults() *RuntimeRecoveryExecutionList`

NewRuntimeRecoveryExecutionListWithDefaults instantiates a new RuntimeRecoveryExecutionList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RuntimeRecoveryExecutionList) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RuntimeRecoveryExecutionList) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RuntimeRecoveryExecutionList) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RuntimeRecoveryExecutionList) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RuntimeRecoveryExecutionList) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RuntimeRecoveryExecutionList) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetConsumerId

`func (o *RuntimeRecoveryExecutionList) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *RuntimeRecoveryExecutionList) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *RuntimeRecoveryExecutionList) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *RuntimeRecoveryExecutionList) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *RuntimeRecoveryExecutionList) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *RuntimeRecoveryExecutionList) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetIncidentId

`func (o *RuntimeRecoveryExecutionList) GetIncidentId() string`

GetIncidentId returns the IncidentId field if non-nil, zero value otherwise.

### GetIncidentIdOk

`func (o *RuntimeRecoveryExecutionList) GetIncidentIdOk() (*string, bool)`

GetIncidentIdOk returns a tuple with the IncidentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentId

`func (o *RuntimeRecoveryExecutionList) SetIncidentId(v string)`

SetIncidentId sets IncidentId field to given value.

### HasIncidentId

`func (o *RuntimeRecoveryExecutionList) HasIncidentId() bool`

HasIncidentId returns a boolean if a field has been set.

### SetIncidentIdNil

`func (o *RuntimeRecoveryExecutionList) SetIncidentIdNil(b bool)`

 SetIncidentIdNil sets the value for IncidentId to be an explicit nil

### UnsetIncidentId
`func (o *RuntimeRecoveryExecutionList) UnsetIncidentId()`

UnsetIncidentId ensures that no value is present for IncidentId, not even an explicit nil
### GetPolicyId

`func (o *RuntimeRecoveryExecutionList) GetPolicyId() string`

GetPolicyId returns the PolicyId field if non-nil, zero value otherwise.

### GetPolicyIdOk

`func (o *RuntimeRecoveryExecutionList) GetPolicyIdOk() (*string, bool)`

GetPolicyIdOk returns a tuple with the PolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyId

`func (o *RuntimeRecoveryExecutionList) SetPolicyId(v string)`

SetPolicyId sets PolicyId field to given value.

### HasPolicyId

`func (o *RuntimeRecoveryExecutionList) HasPolicyId() bool`

HasPolicyId returns a boolean if a field has been set.

### SetPolicyIdNil

`func (o *RuntimeRecoveryExecutionList) SetPolicyIdNil(b bool)`

 SetPolicyIdNil sets the value for PolicyId to be an explicit nil

### UnsetPolicyId
`func (o *RuntimeRecoveryExecutionList) UnsetPolicyId()`

UnsetPolicyId ensures that no value is present for PolicyId, not even an explicit nil
### GetRecoveryPlanId

`func (o *RuntimeRecoveryExecutionList) GetRecoveryPlanId() string`

GetRecoveryPlanId returns the RecoveryPlanId field if non-nil, zero value otherwise.

### GetRecoveryPlanIdOk

`func (o *RuntimeRecoveryExecutionList) GetRecoveryPlanIdOk() (*string, bool)`

GetRecoveryPlanIdOk returns a tuple with the RecoveryPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPlanId

`func (o *RuntimeRecoveryExecutionList) SetRecoveryPlanId(v string)`

SetRecoveryPlanId sets RecoveryPlanId field to given value.


### GetRecoveryPlanRevision

`func (o *RuntimeRecoveryExecutionList) GetRecoveryPlanRevision() int64`

GetRecoveryPlanRevision returns the RecoveryPlanRevision field if non-nil, zero value otherwise.

### GetRecoveryPlanRevisionOk

`func (o *RuntimeRecoveryExecutionList) GetRecoveryPlanRevisionOk() (*int64, bool)`

GetRecoveryPlanRevisionOk returns a tuple with the RecoveryPlanRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPlanRevision

`func (o *RuntimeRecoveryExecutionList) SetRecoveryPlanRevision(v int64)`

SetRecoveryPlanRevision sets RecoveryPlanRevision field to given value.


### GetStatus

`func (o *RuntimeRecoveryExecutionList) GetStatus() RuntimeRecoveryExecutionStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RuntimeRecoveryExecutionList) GetStatusOk() (*RuntimeRecoveryExecutionStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RuntimeRecoveryExecutionList) SetStatus(v RuntimeRecoveryExecutionStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RuntimeRecoveryExecutionList) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCurrentStage

`func (o *RuntimeRecoveryExecutionList) GetCurrentStage() int64`

GetCurrentStage returns the CurrentStage field if non-nil, zero value otherwise.

### GetCurrentStageOk

`func (o *RuntimeRecoveryExecutionList) GetCurrentStageOk() (*int64, bool)`

GetCurrentStageOk returns a tuple with the CurrentStage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStage

`func (o *RuntimeRecoveryExecutionList) SetCurrentStage(v int64)`

SetCurrentStage sets CurrentStage field to given value.

### HasCurrentStage

`func (o *RuntimeRecoveryExecutionList) HasCurrentStage() bool`

HasCurrentStage returns a boolean if a field has been set.

### GetAttemptCount

`func (o *RuntimeRecoveryExecutionList) GetAttemptCount() int64`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *RuntimeRecoveryExecutionList) GetAttemptCountOk() (*int64, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *RuntimeRecoveryExecutionList) SetAttemptCount(v int64)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *RuntimeRecoveryExecutionList) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetRevision

`func (o *RuntimeRecoveryExecutionList) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *RuntimeRecoveryExecutionList) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *RuntimeRecoveryExecutionList) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *RuntimeRecoveryExecutionList) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCorrelationId

`func (o *RuntimeRecoveryExecutionList) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *RuntimeRecoveryExecutionList) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *RuntimeRecoveryExecutionList) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetFailureCode

`func (o *RuntimeRecoveryExecutionList) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *RuntimeRecoveryExecutionList) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *RuntimeRecoveryExecutionList) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *RuntimeRecoveryExecutionList) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### SetFailureCodeNil

`func (o *RuntimeRecoveryExecutionList) SetFailureCodeNil(b bool)`

 SetFailureCodeNil sets the value for FailureCode to be an explicit nil

### UnsetFailureCode
`func (o *RuntimeRecoveryExecutionList) UnsetFailureCode()`

UnsetFailureCode ensures that no value is present for FailureCode, not even an explicit nil
### GetFailureReason

`func (o *RuntimeRecoveryExecutionList) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *RuntimeRecoveryExecutionList) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *RuntimeRecoveryExecutionList) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *RuntimeRecoveryExecutionList) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### SetFailureReasonNil

`func (o *RuntimeRecoveryExecutionList) SetFailureReasonNil(b bool)`

 SetFailureReasonNil sets the value for FailureReason to be an explicit nil

### UnsetFailureReason
`func (o *RuntimeRecoveryExecutionList) UnsetFailureReason()`

UnsetFailureReason ensures that no value is present for FailureReason, not even an explicit nil
### GetEscalationRequired

`func (o *RuntimeRecoveryExecutionList) GetEscalationRequired() bool`

GetEscalationRequired returns the EscalationRequired field if non-nil, zero value otherwise.

### GetEscalationRequiredOk

`func (o *RuntimeRecoveryExecutionList) GetEscalationRequiredOk() (*bool, bool)`

GetEscalationRequiredOk returns a tuple with the EscalationRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEscalationRequired

`func (o *RuntimeRecoveryExecutionList) SetEscalationRequired(v bool)`

SetEscalationRequired sets EscalationRequired field to given value.

### HasEscalationRequired

`func (o *RuntimeRecoveryExecutionList) HasEscalationRequired() bool`

HasEscalationRequired returns a boolean if a field has been set.

### GetLeaseOwner

`func (o *RuntimeRecoveryExecutionList) GetLeaseOwner() string`

GetLeaseOwner returns the LeaseOwner field if non-nil, zero value otherwise.

### GetLeaseOwnerOk

`func (o *RuntimeRecoveryExecutionList) GetLeaseOwnerOk() (*string, bool)`

GetLeaseOwnerOk returns a tuple with the LeaseOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseOwner

`func (o *RuntimeRecoveryExecutionList) SetLeaseOwner(v string)`

SetLeaseOwner sets LeaseOwner field to given value.

### HasLeaseOwner

`func (o *RuntimeRecoveryExecutionList) HasLeaseOwner() bool`

HasLeaseOwner returns a boolean if a field has been set.

### SetLeaseOwnerNil

`func (o *RuntimeRecoveryExecutionList) SetLeaseOwnerNil(b bool)`

 SetLeaseOwnerNil sets the value for LeaseOwner to be an explicit nil

### UnsetLeaseOwner
`func (o *RuntimeRecoveryExecutionList) UnsetLeaseOwner()`

UnsetLeaseOwner ensures that no value is present for LeaseOwner, not even an explicit nil
### GetLeaseEpoch

`func (o *RuntimeRecoveryExecutionList) GetLeaseEpoch() int64`

GetLeaseEpoch returns the LeaseEpoch field if non-nil, zero value otherwise.

### GetLeaseEpochOk

`func (o *RuntimeRecoveryExecutionList) GetLeaseEpochOk() (*int64, bool)`

GetLeaseEpochOk returns a tuple with the LeaseEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseEpoch

`func (o *RuntimeRecoveryExecutionList) SetLeaseEpoch(v int64)`

SetLeaseEpoch sets LeaseEpoch field to given value.

### HasLeaseEpoch

`func (o *RuntimeRecoveryExecutionList) HasLeaseEpoch() bool`

HasLeaseEpoch returns a boolean if a field has been set.

### SetLeaseEpochNil

`func (o *RuntimeRecoveryExecutionList) SetLeaseEpochNil(b bool)`

 SetLeaseEpochNil sets the value for LeaseEpoch to be an explicit nil

### UnsetLeaseEpoch
`func (o *RuntimeRecoveryExecutionList) UnsetLeaseEpoch()`

UnsetLeaseEpoch ensures that no value is present for LeaseEpoch, not even an explicit nil
### GetLeaseExpiresAt

`func (o *RuntimeRecoveryExecutionList) GetLeaseExpiresAt() time.Time`

GetLeaseExpiresAt returns the LeaseExpiresAt field if non-nil, zero value otherwise.

### GetLeaseExpiresAtOk

`func (o *RuntimeRecoveryExecutionList) GetLeaseExpiresAtOk() (*time.Time, bool)`

GetLeaseExpiresAtOk returns a tuple with the LeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpiresAt

`func (o *RuntimeRecoveryExecutionList) SetLeaseExpiresAt(v time.Time)`

SetLeaseExpiresAt sets LeaseExpiresAt field to given value.

### HasLeaseExpiresAt

`func (o *RuntimeRecoveryExecutionList) HasLeaseExpiresAt() bool`

HasLeaseExpiresAt returns a boolean if a field has been set.

### SetLeaseExpiresAtNil

`func (o *RuntimeRecoveryExecutionList) SetLeaseExpiresAtNil(b bool)`

 SetLeaseExpiresAtNil sets the value for LeaseExpiresAt to be an explicit nil

### UnsetLeaseExpiresAt
`func (o *RuntimeRecoveryExecutionList) UnsetLeaseExpiresAt()`

UnsetLeaseExpiresAt ensures that no value is present for LeaseExpiresAt, not even an explicit nil
### GetVerificationDueAt

`func (o *RuntimeRecoveryExecutionList) GetVerificationDueAt() time.Time`

GetVerificationDueAt returns the VerificationDueAt field if non-nil, zero value otherwise.

### GetVerificationDueAtOk

`func (o *RuntimeRecoveryExecutionList) GetVerificationDueAtOk() (*time.Time, bool)`

GetVerificationDueAtOk returns a tuple with the VerificationDueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationDueAt

`func (o *RuntimeRecoveryExecutionList) SetVerificationDueAt(v time.Time)`

SetVerificationDueAt sets VerificationDueAt field to given value.

### HasVerificationDueAt

`func (o *RuntimeRecoveryExecutionList) HasVerificationDueAt() bool`

HasVerificationDueAt returns a boolean if a field has been set.

### SetVerificationDueAtNil

`func (o *RuntimeRecoveryExecutionList) SetVerificationDueAtNil(b bool)`

 SetVerificationDueAtNil sets the value for VerificationDueAt to be an explicit nil

### UnsetVerificationDueAt
`func (o *RuntimeRecoveryExecutionList) UnsetVerificationDueAt()`

UnsetVerificationDueAt ensures that no value is present for VerificationDueAt, not even an explicit nil
### GetStartedAt

`func (o *RuntimeRecoveryExecutionList) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RuntimeRecoveryExecutionList) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RuntimeRecoveryExecutionList) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RuntimeRecoveryExecutionList) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RuntimeRecoveryExecutionList) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RuntimeRecoveryExecutionList) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RuntimeRecoveryExecutionList) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RuntimeRecoveryExecutionList) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RuntimeRecoveryExecutionList) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RuntimeRecoveryExecutionList) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RuntimeRecoveryExecutionList) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RuntimeRecoveryExecutionList) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *RuntimeRecoveryExecutionList) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RuntimeRecoveryExecutionList) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RuntimeRecoveryExecutionList) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RuntimeRecoveryExecutionList) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RuntimeRecoveryExecutionList) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RuntimeRecoveryExecutionList) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetIsActive

`func (o *RuntimeRecoveryExecutionList) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *RuntimeRecoveryExecutionList) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *RuntimeRecoveryExecutionList) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetIsTerminal

`func (o *RuntimeRecoveryExecutionList) GetIsTerminal() bool`

GetIsTerminal returns the IsTerminal field if non-nil, zero value otherwise.

### GetIsTerminalOk

`func (o *RuntimeRecoveryExecutionList) GetIsTerminalOk() (*bool, bool)`

GetIsTerminalOk returns a tuple with the IsTerminal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTerminal

`func (o *RuntimeRecoveryExecutionList) SetIsTerminal(v bool)`

SetIsTerminal sets IsTerminal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


