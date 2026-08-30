# LifecycleAlert

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**AlertId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**AlertKey** | **string** |  | 
**AlertType** | [**AlertTypeEnum**](AlertTypeEnum.md) |  | 
**Severity** | [**LifecycleAlertSeverityEnum**](LifecycleAlertSeverityEnum.md) |  | 
**Status** | Pointer to [**RecoveryEscalationStatusEnum**](RecoveryEscalationStatusEnum.md) |  | [optional] [default to RECOVERYESCALATIONSTATUSENUM_OPEN]
**SourceKind** | **string** |  | 
**SourceId** | Pointer to **string** |  | [optional] 
**Title** | **string** |  | 
**Message** | **string** |  | 
**OccurrenceCount** | Pointer to **int64** |  | [optional] 
**FirstSeenAt** | Pointer to **time.Time** |  | [optional] 
**LastSeenAt** | Pointer to **time.Time** |  | [optional] 
**AcknowledgedAt** | Pointer to **NullableTime** |  | [optional] 
**AcknowledgedBy** | Pointer to **string** |  | [optional] 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**ResolvedBy** | Pointer to **string** |  | [optional] 
**RecoveryReason** | Pointer to **string** |  | [optional] 
**NotificationStatus** | Pointer to [**NotificationStatusEnum**](NotificationStatusEnum.md) |  | [optional] 
**NotificationAttempts** | Pointer to **int64** |  | [optional] 
**NotificationLastError** | Pointer to **string** |  | [optional] 
**OutboxMessageId** | Pointer to **NullableString** |  | [optional] 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**AuditEvidence** | Pointer to **interface{}** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewLifecycleAlert

`func NewLifecycleAlert(id string, alertId string, organizationId string, alertKey string, alertType AlertTypeEnum, severity LifecycleAlertSeverityEnum, sourceKind string, title string, message string, createdAt time.Time, updatedAt time.Time, ) *LifecycleAlert`

NewLifecycleAlert instantiates a new LifecycleAlert object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleAlertWithDefaults

`func NewLifecycleAlertWithDefaults() *LifecycleAlert`

NewLifecycleAlertWithDefaults instantiates a new LifecycleAlert object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LifecycleAlert) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LifecycleAlert) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LifecycleAlert) SetId(v string)`

SetId sets Id field to given value.


### GetAlertId

`func (o *LifecycleAlert) GetAlertId() string`

GetAlertId returns the AlertId field if non-nil, zero value otherwise.

### GetAlertIdOk

`func (o *LifecycleAlert) GetAlertIdOk() (*string, bool)`

GetAlertIdOk returns a tuple with the AlertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertId

`func (o *LifecycleAlert) SetAlertId(v string)`

SetAlertId sets AlertId field to given value.


### GetOrganizationId

`func (o *LifecycleAlert) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleAlert) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleAlert) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetAlertKey

`func (o *LifecycleAlert) GetAlertKey() string`

GetAlertKey returns the AlertKey field if non-nil, zero value otherwise.

### GetAlertKeyOk

`func (o *LifecycleAlert) GetAlertKeyOk() (*string, bool)`

GetAlertKeyOk returns a tuple with the AlertKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertKey

`func (o *LifecycleAlert) SetAlertKey(v string)`

SetAlertKey sets AlertKey field to given value.


### GetAlertType

`func (o *LifecycleAlert) GetAlertType() AlertTypeEnum`

GetAlertType returns the AlertType field if non-nil, zero value otherwise.

### GetAlertTypeOk

`func (o *LifecycleAlert) GetAlertTypeOk() (*AlertTypeEnum, bool)`

GetAlertTypeOk returns a tuple with the AlertType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertType

`func (o *LifecycleAlert) SetAlertType(v AlertTypeEnum)`

SetAlertType sets AlertType field to given value.


### GetSeverity

`func (o *LifecycleAlert) GetSeverity() LifecycleAlertSeverityEnum`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *LifecycleAlert) GetSeverityOk() (*LifecycleAlertSeverityEnum, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *LifecycleAlert) SetSeverity(v LifecycleAlertSeverityEnum)`

SetSeverity sets Severity field to given value.


### GetStatus

`func (o *LifecycleAlert) GetStatus() RecoveryEscalationStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LifecycleAlert) GetStatusOk() (*RecoveryEscalationStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LifecycleAlert) SetStatus(v RecoveryEscalationStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LifecycleAlert) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSourceKind

`func (o *LifecycleAlert) GetSourceKind() string`

GetSourceKind returns the SourceKind field if non-nil, zero value otherwise.

### GetSourceKindOk

`func (o *LifecycleAlert) GetSourceKindOk() (*string, bool)`

GetSourceKindOk returns a tuple with the SourceKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceKind

`func (o *LifecycleAlert) SetSourceKind(v string)`

SetSourceKind sets SourceKind field to given value.


### GetSourceId

`func (o *LifecycleAlert) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *LifecycleAlert) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *LifecycleAlert) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.

### HasSourceId

`func (o *LifecycleAlert) HasSourceId() bool`

HasSourceId returns a boolean if a field has been set.

### GetTitle

`func (o *LifecycleAlert) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *LifecycleAlert) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *LifecycleAlert) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetMessage

`func (o *LifecycleAlert) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *LifecycleAlert) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *LifecycleAlert) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetOccurrenceCount

`func (o *LifecycleAlert) GetOccurrenceCount() int64`

GetOccurrenceCount returns the OccurrenceCount field if non-nil, zero value otherwise.

### GetOccurrenceCountOk

`func (o *LifecycleAlert) GetOccurrenceCountOk() (*int64, bool)`

GetOccurrenceCountOk returns a tuple with the OccurrenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceCount

`func (o *LifecycleAlert) SetOccurrenceCount(v int64)`

SetOccurrenceCount sets OccurrenceCount field to given value.

### HasOccurrenceCount

`func (o *LifecycleAlert) HasOccurrenceCount() bool`

HasOccurrenceCount returns a boolean if a field has been set.

### GetFirstSeenAt

`func (o *LifecycleAlert) GetFirstSeenAt() time.Time`

GetFirstSeenAt returns the FirstSeenAt field if non-nil, zero value otherwise.

### GetFirstSeenAtOk

`func (o *LifecycleAlert) GetFirstSeenAtOk() (*time.Time, bool)`

GetFirstSeenAtOk returns a tuple with the FirstSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstSeenAt

`func (o *LifecycleAlert) SetFirstSeenAt(v time.Time)`

SetFirstSeenAt sets FirstSeenAt field to given value.

### HasFirstSeenAt

`func (o *LifecycleAlert) HasFirstSeenAt() bool`

HasFirstSeenAt returns a boolean if a field has been set.

### GetLastSeenAt

`func (o *LifecycleAlert) GetLastSeenAt() time.Time`

GetLastSeenAt returns the LastSeenAt field if non-nil, zero value otherwise.

### GetLastSeenAtOk

`func (o *LifecycleAlert) GetLastSeenAtOk() (*time.Time, bool)`

GetLastSeenAtOk returns a tuple with the LastSeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeenAt

`func (o *LifecycleAlert) SetLastSeenAt(v time.Time)`

SetLastSeenAt sets LastSeenAt field to given value.

### HasLastSeenAt

`func (o *LifecycleAlert) HasLastSeenAt() bool`

HasLastSeenAt returns a boolean if a field has been set.

### GetAcknowledgedAt

`func (o *LifecycleAlert) GetAcknowledgedAt() time.Time`

GetAcknowledgedAt returns the AcknowledgedAt field if non-nil, zero value otherwise.

### GetAcknowledgedAtOk

`func (o *LifecycleAlert) GetAcknowledgedAtOk() (*time.Time, bool)`

GetAcknowledgedAtOk returns a tuple with the AcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedAt

`func (o *LifecycleAlert) SetAcknowledgedAt(v time.Time)`

SetAcknowledgedAt sets AcknowledgedAt field to given value.

### HasAcknowledgedAt

`func (o *LifecycleAlert) HasAcknowledgedAt() bool`

HasAcknowledgedAt returns a boolean if a field has been set.

### SetAcknowledgedAtNil

`func (o *LifecycleAlert) SetAcknowledgedAtNil(b bool)`

 SetAcknowledgedAtNil sets the value for AcknowledgedAt to be an explicit nil

### UnsetAcknowledgedAt
`func (o *LifecycleAlert) UnsetAcknowledgedAt()`

UnsetAcknowledgedAt ensures that no value is present for AcknowledgedAt, not even an explicit nil
### GetAcknowledgedBy

`func (o *LifecycleAlert) GetAcknowledgedBy() string`

GetAcknowledgedBy returns the AcknowledgedBy field if non-nil, zero value otherwise.

### GetAcknowledgedByOk

`func (o *LifecycleAlert) GetAcknowledgedByOk() (*string, bool)`

GetAcknowledgedByOk returns a tuple with the AcknowledgedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedBy

`func (o *LifecycleAlert) SetAcknowledgedBy(v string)`

SetAcknowledgedBy sets AcknowledgedBy field to given value.

### HasAcknowledgedBy

`func (o *LifecycleAlert) HasAcknowledgedBy() bool`

HasAcknowledgedBy returns a boolean if a field has been set.

### GetResolvedAt

`func (o *LifecycleAlert) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *LifecycleAlert) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *LifecycleAlert) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *LifecycleAlert) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *LifecycleAlert) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *LifecycleAlert) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *LifecycleAlert) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *LifecycleAlert) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *LifecycleAlert) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.

### HasResolvedBy

`func (o *LifecycleAlert) HasResolvedBy() bool`

HasResolvedBy returns a boolean if a field has been set.

### GetRecoveryReason

`func (o *LifecycleAlert) GetRecoveryReason() string`

GetRecoveryReason returns the RecoveryReason field if non-nil, zero value otherwise.

### GetRecoveryReasonOk

`func (o *LifecycleAlert) GetRecoveryReasonOk() (*string, bool)`

GetRecoveryReasonOk returns a tuple with the RecoveryReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryReason

`func (o *LifecycleAlert) SetRecoveryReason(v string)`

SetRecoveryReason sets RecoveryReason field to given value.

### HasRecoveryReason

`func (o *LifecycleAlert) HasRecoveryReason() bool`

HasRecoveryReason returns a boolean if a field has been set.

### GetNotificationStatus

`func (o *LifecycleAlert) GetNotificationStatus() NotificationStatusEnum`

GetNotificationStatus returns the NotificationStatus field if non-nil, zero value otherwise.

### GetNotificationStatusOk

`func (o *LifecycleAlert) GetNotificationStatusOk() (*NotificationStatusEnum, bool)`

GetNotificationStatusOk returns a tuple with the NotificationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationStatus

`func (o *LifecycleAlert) SetNotificationStatus(v NotificationStatusEnum)`

SetNotificationStatus sets NotificationStatus field to given value.

### HasNotificationStatus

`func (o *LifecycleAlert) HasNotificationStatus() bool`

HasNotificationStatus returns a boolean if a field has been set.

### GetNotificationAttempts

`func (o *LifecycleAlert) GetNotificationAttempts() int64`

GetNotificationAttempts returns the NotificationAttempts field if non-nil, zero value otherwise.

### GetNotificationAttemptsOk

`func (o *LifecycleAlert) GetNotificationAttemptsOk() (*int64, bool)`

GetNotificationAttemptsOk returns a tuple with the NotificationAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationAttempts

`func (o *LifecycleAlert) SetNotificationAttempts(v int64)`

SetNotificationAttempts sets NotificationAttempts field to given value.

### HasNotificationAttempts

`func (o *LifecycleAlert) HasNotificationAttempts() bool`

HasNotificationAttempts returns a boolean if a field has been set.

### GetNotificationLastError

`func (o *LifecycleAlert) GetNotificationLastError() string`

GetNotificationLastError returns the NotificationLastError field if non-nil, zero value otherwise.

### GetNotificationLastErrorOk

`func (o *LifecycleAlert) GetNotificationLastErrorOk() (*string, bool)`

GetNotificationLastErrorOk returns a tuple with the NotificationLastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationLastError

`func (o *LifecycleAlert) SetNotificationLastError(v string)`

SetNotificationLastError sets NotificationLastError field to given value.

### HasNotificationLastError

`func (o *LifecycleAlert) HasNotificationLastError() bool`

HasNotificationLastError returns a boolean if a field has been set.

### GetOutboxMessageId

`func (o *LifecycleAlert) GetOutboxMessageId() string`

GetOutboxMessageId returns the OutboxMessageId field if non-nil, zero value otherwise.

### GetOutboxMessageIdOk

`func (o *LifecycleAlert) GetOutboxMessageIdOk() (*string, bool)`

GetOutboxMessageIdOk returns a tuple with the OutboxMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboxMessageId

`func (o *LifecycleAlert) SetOutboxMessageId(v string)`

SetOutboxMessageId sets OutboxMessageId field to given value.

### HasOutboxMessageId

`func (o *LifecycleAlert) HasOutboxMessageId() bool`

HasOutboxMessageId returns a boolean if a field has been set.

### SetOutboxMessageIdNil

`func (o *LifecycleAlert) SetOutboxMessageIdNil(b bool)`

 SetOutboxMessageIdNil sets the value for OutboxMessageId to be an explicit nil

### UnsetOutboxMessageId
`func (o *LifecycleAlert) UnsetOutboxMessageId()`

UnsetOutboxMessageId ensures that no value is present for OutboxMessageId, not even an explicit nil
### GetEvidence

`func (o *LifecycleAlert) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *LifecycleAlert) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *LifecycleAlert) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *LifecycleAlert) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *LifecycleAlert) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *LifecycleAlert) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetAuditEvidence

`func (o *LifecycleAlert) GetAuditEvidence() interface{}`

GetAuditEvidence returns the AuditEvidence field if non-nil, zero value otherwise.

### GetAuditEvidenceOk

`func (o *LifecycleAlert) GetAuditEvidenceOk() (*interface{}, bool)`

GetAuditEvidenceOk returns a tuple with the AuditEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditEvidence

`func (o *LifecycleAlert) SetAuditEvidence(v interface{})`

SetAuditEvidence sets AuditEvidence field to given value.

### HasAuditEvidence

`func (o *LifecycleAlert) HasAuditEvidence() bool`

HasAuditEvidence returns a boolean if a field has been set.

### SetAuditEvidenceNil

`func (o *LifecycleAlert) SetAuditEvidenceNil(b bool)`

 SetAuditEvidenceNil sets the value for AuditEvidence to be an explicit nil

### UnsetAuditEvidence
`func (o *LifecycleAlert) UnsetAuditEvidence()`

UnsetAuditEvidence ensures that no value is present for AuditEvidence, not even an explicit nil
### GetRevision

`func (o *LifecycleAlert) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *LifecycleAlert) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *LifecycleAlert) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *LifecycleAlert) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *LifecycleAlert) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LifecycleAlert) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LifecycleAlert) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *LifecycleAlert) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LifecycleAlert) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LifecycleAlert) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


