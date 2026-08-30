# RecoveryEscalation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**ConsumerId** | Pointer to **NullableString** |  | [optional] 
**ExecutionId** | **NullableString** |  | [readonly] 
**QuarantineId** | **NullableString** |  | [readonly] 
**PolicyId** | **string** |  | [readonly] 
**TriggerCode** | **string** |  | 
**Severity** | [**RecoveryEscalationSeverityEnum**](RecoveryEscalationSeverityEnum.md) |  | 
**Status** | Pointer to [**RecoveryEscalationStatusEnum**](RecoveryEscalationStatusEnum.md) |  | [optional] 
**OccurrenceCount** | Pointer to **int64** |  | [optional] 
**Title** | **string** |  | 
**Summary** | **string** |  | 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**RecipientRoutes** | Pointer to **interface{}** |  | [optional] 
**FirstTriggeredAt** | **time.Time** |  | 
**LastTriggeredAt** | **time.Time** |  | 
**SuppressedUntil** | Pointer to **NullableTime** |  | [optional] 
**AcknowledgedAt** | Pointer to **NullableTime** |  | [optional] 
**AcknowledgedBy** | Pointer to **NullableString** |  | [optional] 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**ResolvedBy** | Pointer to **NullableString** |  | [optional] 
**Resolution** | Pointer to **NullableString** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**Events** | [**[]RecoveryEscalationEvent**](RecoveryEscalationEvent.md) |  | [readonly] 
**Notifications** | [**[]RecoveryEscalationNotification**](RecoveryEscalationNotification.md) |  | [readonly] 

## Methods

### NewRecoveryEscalation

`func NewRecoveryEscalation(id string, organizationId string, executionId NullableString, quarantineId NullableString, policyId string, triggerCode string, severity RecoveryEscalationSeverityEnum, title string, summary string, firstTriggeredAt time.Time, lastTriggeredAt time.Time, createdAt time.Time, updatedAt time.Time, events []RecoveryEscalationEvent, notifications []RecoveryEscalationNotification, ) *RecoveryEscalation`

NewRecoveryEscalation instantiates a new RecoveryEscalation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecoveryEscalationWithDefaults

`func NewRecoveryEscalationWithDefaults() *RecoveryEscalation`

NewRecoveryEscalationWithDefaults instantiates a new RecoveryEscalation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecoveryEscalation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecoveryEscalation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecoveryEscalation) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RecoveryEscalation) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RecoveryEscalation) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RecoveryEscalation) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetConsumerId

`func (o *RecoveryEscalation) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *RecoveryEscalation) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *RecoveryEscalation) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *RecoveryEscalation) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *RecoveryEscalation) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *RecoveryEscalation) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetExecutionId

`func (o *RecoveryEscalation) GetExecutionId() string`

GetExecutionId returns the ExecutionId field if non-nil, zero value otherwise.

### GetExecutionIdOk

`func (o *RecoveryEscalation) GetExecutionIdOk() (*string, bool)`

GetExecutionIdOk returns a tuple with the ExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionId

`func (o *RecoveryEscalation) SetExecutionId(v string)`

SetExecutionId sets ExecutionId field to given value.


### SetExecutionIdNil

`func (o *RecoveryEscalation) SetExecutionIdNil(b bool)`

 SetExecutionIdNil sets the value for ExecutionId to be an explicit nil

### UnsetExecutionId
`func (o *RecoveryEscalation) UnsetExecutionId()`

UnsetExecutionId ensures that no value is present for ExecutionId, not even an explicit nil
### GetQuarantineId

`func (o *RecoveryEscalation) GetQuarantineId() string`

GetQuarantineId returns the QuarantineId field if non-nil, zero value otherwise.

### GetQuarantineIdOk

`func (o *RecoveryEscalation) GetQuarantineIdOk() (*string, bool)`

GetQuarantineIdOk returns a tuple with the QuarantineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuarantineId

`func (o *RecoveryEscalation) SetQuarantineId(v string)`

SetQuarantineId sets QuarantineId field to given value.


### SetQuarantineIdNil

`func (o *RecoveryEscalation) SetQuarantineIdNil(b bool)`

 SetQuarantineIdNil sets the value for QuarantineId to be an explicit nil

### UnsetQuarantineId
`func (o *RecoveryEscalation) UnsetQuarantineId()`

UnsetQuarantineId ensures that no value is present for QuarantineId, not even an explicit nil
### GetPolicyId

`func (o *RecoveryEscalation) GetPolicyId() string`

GetPolicyId returns the PolicyId field if non-nil, zero value otherwise.

### GetPolicyIdOk

`func (o *RecoveryEscalation) GetPolicyIdOk() (*string, bool)`

GetPolicyIdOk returns a tuple with the PolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyId

`func (o *RecoveryEscalation) SetPolicyId(v string)`

SetPolicyId sets PolicyId field to given value.


### GetTriggerCode

`func (o *RecoveryEscalation) GetTriggerCode() string`

GetTriggerCode returns the TriggerCode field if non-nil, zero value otherwise.

### GetTriggerCodeOk

`func (o *RecoveryEscalation) GetTriggerCodeOk() (*string, bool)`

GetTriggerCodeOk returns a tuple with the TriggerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerCode

`func (o *RecoveryEscalation) SetTriggerCode(v string)`

SetTriggerCode sets TriggerCode field to given value.


### GetSeverity

`func (o *RecoveryEscalation) GetSeverity() RecoveryEscalationSeverityEnum`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *RecoveryEscalation) GetSeverityOk() (*RecoveryEscalationSeverityEnum, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *RecoveryEscalation) SetSeverity(v RecoveryEscalationSeverityEnum)`

SetSeverity sets Severity field to given value.


### GetStatus

`func (o *RecoveryEscalation) GetStatus() RecoveryEscalationStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecoveryEscalation) GetStatusOk() (*RecoveryEscalationStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecoveryEscalation) SetStatus(v RecoveryEscalationStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RecoveryEscalation) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetOccurrenceCount

`func (o *RecoveryEscalation) GetOccurrenceCount() int64`

GetOccurrenceCount returns the OccurrenceCount field if non-nil, zero value otherwise.

### GetOccurrenceCountOk

`func (o *RecoveryEscalation) GetOccurrenceCountOk() (*int64, bool)`

GetOccurrenceCountOk returns a tuple with the OccurrenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceCount

`func (o *RecoveryEscalation) SetOccurrenceCount(v int64)`

SetOccurrenceCount sets OccurrenceCount field to given value.

### HasOccurrenceCount

`func (o *RecoveryEscalation) HasOccurrenceCount() bool`

HasOccurrenceCount returns a boolean if a field has been set.

### GetTitle

`func (o *RecoveryEscalation) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *RecoveryEscalation) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *RecoveryEscalation) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSummary

`func (o *RecoveryEscalation) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *RecoveryEscalation) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *RecoveryEscalation) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetEvidence

`func (o *RecoveryEscalation) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *RecoveryEscalation) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *RecoveryEscalation) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *RecoveryEscalation) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *RecoveryEscalation) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *RecoveryEscalation) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetRecipientRoutes

`func (o *RecoveryEscalation) GetRecipientRoutes() interface{}`

GetRecipientRoutes returns the RecipientRoutes field if non-nil, zero value otherwise.

### GetRecipientRoutesOk

`func (o *RecoveryEscalation) GetRecipientRoutesOk() (*interface{}, bool)`

GetRecipientRoutesOk returns a tuple with the RecipientRoutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientRoutes

`func (o *RecoveryEscalation) SetRecipientRoutes(v interface{})`

SetRecipientRoutes sets RecipientRoutes field to given value.

### HasRecipientRoutes

`func (o *RecoveryEscalation) HasRecipientRoutes() bool`

HasRecipientRoutes returns a boolean if a field has been set.

### SetRecipientRoutesNil

`func (o *RecoveryEscalation) SetRecipientRoutesNil(b bool)`

 SetRecipientRoutesNil sets the value for RecipientRoutes to be an explicit nil

### UnsetRecipientRoutes
`func (o *RecoveryEscalation) UnsetRecipientRoutes()`

UnsetRecipientRoutes ensures that no value is present for RecipientRoutes, not even an explicit nil
### GetFirstTriggeredAt

`func (o *RecoveryEscalation) GetFirstTriggeredAt() time.Time`

GetFirstTriggeredAt returns the FirstTriggeredAt field if non-nil, zero value otherwise.

### GetFirstTriggeredAtOk

`func (o *RecoveryEscalation) GetFirstTriggeredAtOk() (*time.Time, bool)`

GetFirstTriggeredAtOk returns a tuple with the FirstTriggeredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstTriggeredAt

`func (o *RecoveryEscalation) SetFirstTriggeredAt(v time.Time)`

SetFirstTriggeredAt sets FirstTriggeredAt field to given value.


### GetLastTriggeredAt

`func (o *RecoveryEscalation) GetLastTriggeredAt() time.Time`

GetLastTriggeredAt returns the LastTriggeredAt field if non-nil, zero value otherwise.

### GetLastTriggeredAtOk

`func (o *RecoveryEscalation) GetLastTriggeredAtOk() (*time.Time, bool)`

GetLastTriggeredAtOk returns a tuple with the LastTriggeredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastTriggeredAt

`func (o *RecoveryEscalation) SetLastTriggeredAt(v time.Time)`

SetLastTriggeredAt sets LastTriggeredAt field to given value.


### GetSuppressedUntil

`func (o *RecoveryEscalation) GetSuppressedUntil() time.Time`

GetSuppressedUntil returns the SuppressedUntil field if non-nil, zero value otherwise.

### GetSuppressedUntilOk

`func (o *RecoveryEscalation) GetSuppressedUntilOk() (*time.Time, bool)`

GetSuppressedUntilOk returns a tuple with the SuppressedUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuppressedUntil

`func (o *RecoveryEscalation) SetSuppressedUntil(v time.Time)`

SetSuppressedUntil sets SuppressedUntil field to given value.

### HasSuppressedUntil

`func (o *RecoveryEscalation) HasSuppressedUntil() bool`

HasSuppressedUntil returns a boolean if a field has been set.

### SetSuppressedUntilNil

`func (o *RecoveryEscalation) SetSuppressedUntilNil(b bool)`

 SetSuppressedUntilNil sets the value for SuppressedUntil to be an explicit nil

### UnsetSuppressedUntil
`func (o *RecoveryEscalation) UnsetSuppressedUntil()`

UnsetSuppressedUntil ensures that no value is present for SuppressedUntil, not even an explicit nil
### GetAcknowledgedAt

`func (o *RecoveryEscalation) GetAcknowledgedAt() time.Time`

GetAcknowledgedAt returns the AcknowledgedAt field if non-nil, zero value otherwise.

### GetAcknowledgedAtOk

`func (o *RecoveryEscalation) GetAcknowledgedAtOk() (*time.Time, bool)`

GetAcknowledgedAtOk returns a tuple with the AcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedAt

`func (o *RecoveryEscalation) SetAcknowledgedAt(v time.Time)`

SetAcknowledgedAt sets AcknowledgedAt field to given value.

### HasAcknowledgedAt

`func (o *RecoveryEscalation) HasAcknowledgedAt() bool`

HasAcknowledgedAt returns a boolean if a field has been set.

### SetAcknowledgedAtNil

`func (o *RecoveryEscalation) SetAcknowledgedAtNil(b bool)`

 SetAcknowledgedAtNil sets the value for AcknowledgedAt to be an explicit nil

### UnsetAcknowledgedAt
`func (o *RecoveryEscalation) UnsetAcknowledgedAt()`

UnsetAcknowledgedAt ensures that no value is present for AcknowledgedAt, not even an explicit nil
### GetAcknowledgedBy

`func (o *RecoveryEscalation) GetAcknowledgedBy() string`

GetAcknowledgedBy returns the AcknowledgedBy field if non-nil, zero value otherwise.

### GetAcknowledgedByOk

`func (o *RecoveryEscalation) GetAcknowledgedByOk() (*string, bool)`

GetAcknowledgedByOk returns a tuple with the AcknowledgedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedBy

`func (o *RecoveryEscalation) SetAcknowledgedBy(v string)`

SetAcknowledgedBy sets AcknowledgedBy field to given value.

### HasAcknowledgedBy

`func (o *RecoveryEscalation) HasAcknowledgedBy() bool`

HasAcknowledgedBy returns a boolean if a field has been set.

### SetAcknowledgedByNil

`func (o *RecoveryEscalation) SetAcknowledgedByNil(b bool)`

 SetAcknowledgedByNil sets the value for AcknowledgedBy to be an explicit nil

### UnsetAcknowledgedBy
`func (o *RecoveryEscalation) UnsetAcknowledgedBy()`

UnsetAcknowledgedBy ensures that no value is present for AcknowledgedBy, not even an explicit nil
### GetResolvedAt

`func (o *RecoveryEscalation) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *RecoveryEscalation) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *RecoveryEscalation) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *RecoveryEscalation) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *RecoveryEscalation) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *RecoveryEscalation) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *RecoveryEscalation) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *RecoveryEscalation) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *RecoveryEscalation) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.

### HasResolvedBy

`func (o *RecoveryEscalation) HasResolvedBy() bool`

HasResolvedBy returns a boolean if a field has been set.

### SetResolvedByNil

`func (o *RecoveryEscalation) SetResolvedByNil(b bool)`

 SetResolvedByNil sets the value for ResolvedBy to be an explicit nil

### UnsetResolvedBy
`func (o *RecoveryEscalation) UnsetResolvedBy()`

UnsetResolvedBy ensures that no value is present for ResolvedBy, not even an explicit nil
### GetResolution

`func (o *RecoveryEscalation) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *RecoveryEscalation) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *RecoveryEscalation) SetResolution(v string)`

SetResolution sets Resolution field to given value.

### HasResolution

`func (o *RecoveryEscalation) HasResolution() bool`

HasResolution returns a boolean if a field has been set.

### SetResolutionNil

`func (o *RecoveryEscalation) SetResolutionNil(b bool)`

 SetResolutionNil sets the value for Resolution to be an explicit nil

### UnsetResolution
`func (o *RecoveryEscalation) UnsetResolution()`

UnsetResolution ensures that no value is present for Resolution, not even an explicit nil
### GetRevision

`func (o *RecoveryEscalation) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *RecoveryEscalation) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *RecoveryEscalation) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *RecoveryEscalation) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *RecoveryEscalation) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecoveryEscalation) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecoveryEscalation) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RecoveryEscalation) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RecoveryEscalation) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RecoveryEscalation) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetEvents

`func (o *RecoveryEscalation) GetEvents() []RecoveryEscalationEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *RecoveryEscalation) GetEventsOk() (*[]RecoveryEscalationEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *RecoveryEscalation) SetEvents(v []RecoveryEscalationEvent)`

SetEvents sets Events field to given value.


### GetNotifications

`func (o *RecoveryEscalation) GetNotifications() []RecoveryEscalationNotification`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *RecoveryEscalation) GetNotificationsOk() (*[]RecoveryEscalationNotification, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *RecoveryEscalation) SetNotifications(v []RecoveryEscalationNotification)`

SetNotifications sets Notifications field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


