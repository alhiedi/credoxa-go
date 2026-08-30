# OperatorRuntimeIncidentNotificationDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**EventId** | **string** |  | [readonly] 
**EventType** | **string** |  | 
**SchemaVersion** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**PartitionKey** | **string** |  | 
**TenantKey** | **string** |  | 
**IncidentId** | **string** |  | 
**OccurrenceId** | **string** |  | 
**OrganizationId** | Pointer to **NullableString** |  | [optional] 
**ConsumerId** | Pointer to **NullableString** |  | [optional] 
**ConsumerCode** | Pointer to **string** |  | [optional] 
**Severity** | **string** |  | 
**IncidentStatus** | **string** |  | 
**Status** | Pointer to [**RuntimeIncidentNotificationOutboxStatusEnum**](RuntimeIncidentNotificationOutboxStatusEnum.md) |  | [optional] 
**AttemptCount** | Pointer to **int64** |  | [optional] 
**MaxAttempts** | Pointer to **int64** |  | [optional] 
**NextAttemptAt** | Pointer to **time.Time** |  | [optional] 
**LeaseOwner** | Pointer to **string** |  | [optional] 
**LeaseAcquiredAt** | Pointer to **NullableTime** |  | [optional] 
**LeaseExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**IsTerminal** | **bool** |  | [readonly] 
**IsLeased** | **bool** |  | [readonly] 
**LeaseExpired** | **bool** |  | [readonly] 
**PublishedAt** | Pointer to **NullableTime** |  | [optional] 
**DeadLetteredAt** | Pointer to **NullableTime** |  | [optional] 
**LastErrorType** | Pointer to **string** |  | [optional] 
**LastErrorAt** | Pointer to **NullableTime** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**Payload** | **interface{}** |  | 
**FirstAttemptedAt** | Pointer to **NullableTime** |  | [optional] 
**LastAttemptedAt** | Pointer to **NullableTime** |  | [optional] 
**LastErrorMessage** | Pointer to **string** |  | [optional] 

## Methods

### NewOperatorRuntimeIncidentNotificationDetail

`func NewOperatorRuntimeIncidentNotificationDetail(id string, eventId string, eventType string, schemaVersion string, idempotencyKey string, partitionKey string, tenantKey string, incidentId string, occurrenceId string, severity string, incidentStatus string, isTerminal bool, isLeased bool, leaseExpired bool, createdAt time.Time, updatedAt time.Time, payload interface{}, ) *OperatorRuntimeIncidentNotificationDetail`

NewOperatorRuntimeIncidentNotificationDetail instantiates a new OperatorRuntimeIncidentNotificationDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentNotificationDetailWithDefaults

`func NewOperatorRuntimeIncidentNotificationDetailWithDefaults() *OperatorRuntimeIncidentNotificationDetail`

NewOperatorRuntimeIncidentNotificationDetailWithDefaults instantiates a new OperatorRuntimeIncidentNotificationDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorRuntimeIncidentNotificationDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorRuntimeIncidentNotificationDetail) SetId(v string)`

SetId sets Id field to given value.


### GetEventId

`func (o *OperatorRuntimeIncidentNotificationDetail) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *OperatorRuntimeIncidentNotificationDetail) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetEventType

`func (o *OperatorRuntimeIncidentNotificationDetail) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *OperatorRuntimeIncidentNotificationDetail) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetSchemaVersion

`func (o *OperatorRuntimeIncidentNotificationDetail) GetSchemaVersion() string`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetSchemaVersionOk() (*string, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *OperatorRuntimeIncidentNotificationDetail) SetSchemaVersion(v string)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetIdempotencyKey

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *OperatorRuntimeIncidentNotificationDetail) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetPartitionKey

`func (o *OperatorRuntimeIncidentNotificationDetail) GetPartitionKey() string`

GetPartitionKey returns the PartitionKey field if non-nil, zero value otherwise.

### GetPartitionKeyOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetPartitionKeyOk() (*string, bool)`

GetPartitionKeyOk returns a tuple with the PartitionKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartitionKey

`func (o *OperatorRuntimeIncidentNotificationDetail) SetPartitionKey(v string)`

SetPartitionKey sets PartitionKey field to given value.


### GetTenantKey

`func (o *OperatorRuntimeIncidentNotificationDetail) GetTenantKey() string`

GetTenantKey returns the TenantKey field if non-nil, zero value otherwise.

### GetTenantKeyOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetTenantKeyOk() (*string, bool)`

GetTenantKeyOk returns a tuple with the TenantKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantKey

`func (o *OperatorRuntimeIncidentNotificationDetail) SetTenantKey(v string)`

SetTenantKey sets TenantKey field to given value.


### GetIncidentId

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIncidentId() string`

GetIncidentId returns the IncidentId field if non-nil, zero value otherwise.

### GetIncidentIdOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIncidentIdOk() (*string, bool)`

GetIncidentIdOk returns a tuple with the IncidentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentId

`func (o *OperatorRuntimeIncidentNotificationDetail) SetIncidentId(v string)`

SetIncidentId sets IncidentId field to given value.


### GetOccurrenceId

`func (o *OperatorRuntimeIncidentNotificationDetail) GetOccurrenceId() string`

GetOccurrenceId returns the OccurrenceId field if non-nil, zero value otherwise.

### GetOccurrenceIdOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetOccurrenceIdOk() (*string, bool)`

GetOccurrenceIdOk returns a tuple with the OccurrenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceId

`func (o *OperatorRuntimeIncidentNotificationDetail) SetOccurrenceId(v string)`

SetOccurrenceId sets OccurrenceId field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeIncidentNotificationDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeIncidentNotificationDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *OperatorRuntimeIncidentNotificationDetail) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerId

`func (o *OperatorRuntimeIncidentNotificationDetail) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorRuntimeIncidentNotificationDetail) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *OperatorRuntimeIncidentNotificationDetail) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorRuntimeIncidentNotificationDetail) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeIncidentNotificationDetail) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.

### HasConsumerCode

`func (o *OperatorRuntimeIncidentNotificationDetail) HasConsumerCode() bool`

HasConsumerCode returns a boolean if a field has been set.

### GetSeverity

`func (o *OperatorRuntimeIncidentNotificationDetail) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeIncidentNotificationDetail) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetIncidentStatus

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIncidentStatus() string`

GetIncidentStatus returns the IncidentStatus field if non-nil, zero value otherwise.

### GetIncidentStatusOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIncidentStatusOk() (*string, bool)`

GetIncidentStatusOk returns a tuple with the IncidentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentStatus

`func (o *OperatorRuntimeIncidentNotificationDetail) SetIncidentStatus(v string)`

SetIncidentStatus sets IncidentStatus field to given value.


### GetStatus

`func (o *OperatorRuntimeIncidentNotificationDetail) GetStatus() RuntimeIncidentNotificationOutboxStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetStatusOk() (*RuntimeIncidentNotificationOutboxStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeIncidentNotificationDetail) SetStatus(v RuntimeIncidentNotificationOutboxStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperatorRuntimeIncidentNotificationDetail) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAttemptCount

`func (o *OperatorRuntimeIncidentNotificationDetail) GetAttemptCount() int64`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetAttemptCountOk() (*int64, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *OperatorRuntimeIncidentNotificationDetail) SetAttemptCount(v int64)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *OperatorRuntimeIncidentNotificationDetail) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationDetail) GetMaxAttempts() int64`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetMaxAttemptsOk() (*int64, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationDetail) SetMaxAttempts(v int64)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationDetail) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.

### GetNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetNextAttemptAt() time.Time`

GetNextAttemptAt returns the NextAttemptAt field if non-nil, zero value otherwise.

### GetNextAttemptAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetNextAttemptAtOk() (*time.Time, bool)`

GetNextAttemptAtOk returns a tuple with the NextAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetNextAttemptAt(v time.Time)`

SetNextAttemptAt sets NextAttemptAt field to given value.

### HasNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasNextAttemptAt() bool`

HasNextAttemptAt returns a boolean if a field has been set.

### GetLeaseOwner

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseOwner() string`

GetLeaseOwner returns the LeaseOwner field if non-nil, zero value otherwise.

### GetLeaseOwnerOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseOwnerOk() (*string, bool)`

GetLeaseOwnerOk returns a tuple with the LeaseOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseOwner

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLeaseOwner(v string)`

SetLeaseOwner sets LeaseOwner field to given value.

### HasLeaseOwner

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLeaseOwner() bool`

HasLeaseOwner returns a boolean if a field has been set.

### GetLeaseAcquiredAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseAcquiredAt() time.Time`

GetLeaseAcquiredAt returns the LeaseAcquiredAt field if non-nil, zero value otherwise.

### GetLeaseAcquiredAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseAcquiredAtOk() (*time.Time, bool)`

GetLeaseAcquiredAtOk returns a tuple with the LeaseAcquiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseAcquiredAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLeaseAcquiredAt(v time.Time)`

SetLeaseAcquiredAt sets LeaseAcquiredAt field to given value.

### HasLeaseAcquiredAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLeaseAcquiredAt() bool`

HasLeaseAcquiredAt returns a boolean if a field has been set.

### SetLeaseAcquiredAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLeaseAcquiredAtNil(b bool)`

 SetLeaseAcquiredAtNil sets the value for LeaseAcquiredAt to be an explicit nil

### UnsetLeaseAcquiredAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetLeaseAcquiredAt()`

UnsetLeaseAcquiredAt ensures that no value is present for LeaseAcquiredAt, not even an explicit nil
### GetLeaseExpiresAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseExpiresAt() time.Time`

GetLeaseExpiresAt returns the LeaseExpiresAt field if non-nil, zero value otherwise.

### GetLeaseExpiresAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseExpiresAtOk() (*time.Time, bool)`

GetLeaseExpiresAtOk returns a tuple with the LeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpiresAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLeaseExpiresAt(v time.Time)`

SetLeaseExpiresAt sets LeaseExpiresAt field to given value.

### HasLeaseExpiresAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLeaseExpiresAt() bool`

HasLeaseExpiresAt returns a boolean if a field has been set.

### SetLeaseExpiresAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLeaseExpiresAtNil(b bool)`

 SetLeaseExpiresAtNil sets the value for LeaseExpiresAt to be an explicit nil

### UnsetLeaseExpiresAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetLeaseExpiresAt()`

UnsetLeaseExpiresAt ensures that no value is present for LeaseExpiresAt, not even an explicit nil
### GetIsTerminal

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIsTerminal() bool`

GetIsTerminal returns the IsTerminal field if non-nil, zero value otherwise.

### GetIsTerminalOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIsTerminalOk() (*bool, bool)`

GetIsTerminalOk returns a tuple with the IsTerminal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTerminal

`func (o *OperatorRuntimeIncidentNotificationDetail) SetIsTerminal(v bool)`

SetIsTerminal sets IsTerminal field to given value.


### GetIsLeased

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIsLeased() bool`

GetIsLeased returns the IsLeased field if non-nil, zero value otherwise.

### GetIsLeasedOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetIsLeasedOk() (*bool, bool)`

GetIsLeasedOk returns a tuple with the IsLeased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLeased

`func (o *OperatorRuntimeIncidentNotificationDetail) SetIsLeased(v bool)`

SetIsLeased sets IsLeased field to given value.


### GetLeaseExpired

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseExpired() bool`

GetLeaseExpired returns the LeaseExpired field if non-nil, zero value otherwise.

### GetLeaseExpiredOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLeaseExpiredOk() (*bool, bool)`

GetLeaseExpiredOk returns a tuple with the LeaseExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpired

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLeaseExpired(v bool)`

SetLeaseExpired sets LeaseExpired field to given value.


### GetPublishedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### SetPublishedAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetDeadLetteredAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetDeadLetteredAt() time.Time`

GetDeadLetteredAt returns the DeadLetteredAt field if non-nil, zero value otherwise.

### GetDeadLetteredAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetDeadLetteredAtOk() (*time.Time, bool)`

GetDeadLetteredAtOk returns a tuple with the DeadLetteredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetteredAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetDeadLetteredAt(v time.Time)`

SetDeadLetteredAt sets DeadLetteredAt field to given value.

### HasDeadLetteredAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasDeadLetteredAt() bool`

HasDeadLetteredAt returns a boolean if a field has been set.

### SetDeadLetteredAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetDeadLetteredAtNil(b bool)`

 SetDeadLetteredAtNil sets the value for DeadLetteredAt to be an explicit nil

### UnsetDeadLetteredAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetDeadLetteredAt()`

UnsetDeadLetteredAt ensures that no value is present for DeadLetteredAt, not even an explicit nil
### GetLastErrorType

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastErrorType() string`

GetLastErrorType returns the LastErrorType field if non-nil, zero value otherwise.

### GetLastErrorTypeOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastErrorTypeOk() (*string, bool)`

GetLastErrorTypeOk returns a tuple with the LastErrorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorType

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLastErrorType(v string)`

SetLastErrorType sets LastErrorType field to given value.

### HasLastErrorType

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLastErrorType() bool`

HasLastErrorType returns a boolean if a field has been set.

### GetLastErrorAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastErrorAt() time.Time`

GetLastErrorAt returns the LastErrorAt field if non-nil, zero value otherwise.

### GetLastErrorAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastErrorAtOk() (*time.Time, bool)`

GetLastErrorAtOk returns a tuple with the LastErrorAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLastErrorAt(v time.Time)`

SetLastErrorAt sets LastErrorAt field to given value.

### HasLastErrorAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLastErrorAt() bool`

HasLastErrorAt returns a boolean if a field has been set.

### SetLastErrorAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLastErrorAtNil(b bool)`

 SetLastErrorAtNil sets the value for LastErrorAt to be an explicit nil

### UnsetLastErrorAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetLastErrorAt()`

UnsetLastErrorAt ensures that no value is present for LastErrorAt, not even an explicit nil
### GetRevision

`func (o *OperatorRuntimeIncidentNotificationDetail) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *OperatorRuntimeIncidentNotificationDetail) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *OperatorRuntimeIncidentNotificationDetail) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetPayload

`func (o *OperatorRuntimeIncidentNotificationDetail) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *OperatorRuntimeIncidentNotificationDetail) SetPayload(v interface{})`

SetPayload sets Payload field to given value.


### SetPayloadNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetFirstAttemptedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetFirstAttemptedAt() time.Time`

GetFirstAttemptedAt returns the FirstAttemptedAt field if non-nil, zero value otherwise.

### GetFirstAttemptedAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetFirstAttemptedAtOk() (*time.Time, bool)`

GetFirstAttemptedAtOk returns a tuple with the FirstAttemptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstAttemptedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetFirstAttemptedAt(v time.Time)`

SetFirstAttemptedAt sets FirstAttemptedAt field to given value.

### HasFirstAttemptedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasFirstAttemptedAt() bool`

HasFirstAttemptedAt returns a boolean if a field has been set.

### SetFirstAttemptedAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetFirstAttemptedAtNil(b bool)`

 SetFirstAttemptedAtNil sets the value for FirstAttemptedAt to be an explicit nil

### UnsetFirstAttemptedAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetFirstAttemptedAt()`

UnsetFirstAttemptedAt ensures that no value is present for FirstAttemptedAt, not even an explicit nil
### GetLastAttemptedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastAttemptedAt() time.Time`

GetLastAttemptedAt returns the LastAttemptedAt field if non-nil, zero value otherwise.

### GetLastAttemptedAtOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastAttemptedAtOk() (*time.Time, bool)`

GetLastAttemptedAtOk returns a tuple with the LastAttemptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAttemptedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLastAttemptedAt(v time.Time)`

SetLastAttemptedAt sets LastAttemptedAt field to given value.

### HasLastAttemptedAt

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLastAttemptedAt() bool`

HasLastAttemptedAt returns a boolean if a field has been set.

### SetLastAttemptedAtNil

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLastAttemptedAtNil(b bool)`

 SetLastAttemptedAtNil sets the value for LastAttemptedAt to be an explicit nil

### UnsetLastAttemptedAt
`func (o *OperatorRuntimeIncidentNotificationDetail) UnsetLastAttemptedAt()`

UnsetLastAttemptedAt ensures that no value is present for LastAttemptedAt, not even an explicit nil
### GetLastErrorMessage

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastErrorMessage() string`

GetLastErrorMessage returns the LastErrorMessage field if non-nil, zero value otherwise.

### GetLastErrorMessageOk

`func (o *OperatorRuntimeIncidentNotificationDetail) GetLastErrorMessageOk() (*string, bool)`

GetLastErrorMessageOk returns a tuple with the LastErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorMessage

`func (o *OperatorRuntimeIncidentNotificationDetail) SetLastErrorMessage(v string)`

SetLastErrorMessage sets LastErrorMessage field to given value.

### HasLastErrorMessage

`func (o *OperatorRuntimeIncidentNotificationDetail) HasLastErrorMessage() bool`

HasLastErrorMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


