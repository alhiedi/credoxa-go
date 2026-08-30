# OperatorRuntimeIncidentNotificationList

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

## Methods

### NewOperatorRuntimeIncidentNotificationList

`func NewOperatorRuntimeIncidentNotificationList(id string, eventId string, eventType string, schemaVersion string, idempotencyKey string, partitionKey string, tenantKey string, incidentId string, occurrenceId string, severity string, incidentStatus string, isTerminal bool, isLeased bool, leaseExpired bool, createdAt time.Time, updatedAt time.Time, ) *OperatorRuntimeIncidentNotificationList`

NewOperatorRuntimeIncidentNotificationList instantiates a new OperatorRuntimeIncidentNotificationList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentNotificationListWithDefaults

`func NewOperatorRuntimeIncidentNotificationListWithDefaults() *OperatorRuntimeIncidentNotificationList`

NewOperatorRuntimeIncidentNotificationListWithDefaults instantiates a new OperatorRuntimeIncidentNotificationList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorRuntimeIncidentNotificationList) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorRuntimeIncidentNotificationList) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorRuntimeIncidentNotificationList) SetId(v string)`

SetId sets Id field to given value.


### GetEventId

`func (o *OperatorRuntimeIncidentNotificationList) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *OperatorRuntimeIncidentNotificationList) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *OperatorRuntimeIncidentNotificationList) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetEventType

`func (o *OperatorRuntimeIncidentNotificationList) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *OperatorRuntimeIncidentNotificationList) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *OperatorRuntimeIncidentNotificationList) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetSchemaVersion

`func (o *OperatorRuntimeIncidentNotificationList) GetSchemaVersion() string`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *OperatorRuntimeIncidentNotificationList) GetSchemaVersionOk() (*string, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *OperatorRuntimeIncidentNotificationList) SetSchemaVersion(v string)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetIdempotencyKey

`func (o *OperatorRuntimeIncidentNotificationList) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *OperatorRuntimeIncidentNotificationList) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *OperatorRuntimeIncidentNotificationList) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetPartitionKey

`func (o *OperatorRuntimeIncidentNotificationList) GetPartitionKey() string`

GetPartitionKey returns the PartitionKey field if non-nil, zero value otherwise.

### GetPartitionKeyOk

`func (o *OperatorRuntimeIncidentNotificationList) GetPartitionKeyOk() (*string, bool)`

GetPartitionKeyOk returns a tuple with the PartitionKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartitionKey

`func (o *OperatorRuntimeIncidentNotificationList) SetPartitionKey(v string)`

SetPartitionKey sets PartitionKey field to given value.


### GetTenantKey

`func (o *OperatorRuntimeIncidentNotificationList) GetTenantKey() string`

GetTenantKey returns the TenantKey field if non-nil, zero value otherwise.

### GetTenantKeyOk

`func (o *OperatorRuntimeIncidentNotificationList) GetTenantKeyOk() (*string, bool)`

GetTenantKeyOk returns a tuple with the TenantKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantKey

`func (o *OperatorRuntimeIncidentNotificationList) SetTenantKey(v string)`

SetTenantKey sets TenantKey field to given value.


### GetIncidentId

`func (o *OperatorRuntimeIncidentNotificationList) GetIncidentId() string`

GetIncidentId returns the IncidentId field if non-nil, zero value otherwise.

### GetIncidentIdOk

`func (o *OperatorRuntimeIncidentNotificationList) GetIncidentIdOk() (*string, bool)`

GetIncidentIdOk returns a tuple with the IncidentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentId

`func (o *OperatorRuntimeIncidentNotificationList) SetIncidentId(v string)`

SetIncidentId sets IncidentId field to given value.


### GetOccurrenceId

`func (o *OperatorRuntimeIncidentNotificationList) GetOccurrenceId() string`

GetOccurrenceId returns the OccurrenceId field if non-nil, zero value otherwise.

### GetOccurrenceIdOk

`func (o *OperatorRuntimeIncidentNotificationList) GetOccurrenceIdOk() (*string, bool)`

GetOccurrenceIdOk returns a tuple with the OccurrenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceId

`func (o *OperatorRuntimeIncidentNotificationList) SetOccurrenceId(v string)`

SetOccurrenceId sets OccurrenceId field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeIncidentNotificationList) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeIncidentNotificationList) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeIncidentNotificationList) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *OperatorRuntimeIncidentNotificationList) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *OperatorRuntimeIncidentNotificationList) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeIncidentNotificationList) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerId

`func (o *OperatorRuntimeIncidentNotificationList) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorRuntimeIncidentNotificationList) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorRuntimeIncidentNotificationList) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *OperatorRuntimeIncidentNotificationList) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *OperatorRuntimeIncidentNotificationList) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *OperatorRuntimeIncidentNotificationList) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorRuntimeIncidentNotificationList) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeIncidentNotificationList) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeIncidentNotificationList) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.

### HasConsumerCode

`func (o *OperatorRuntimeIncidentNotificationList) HasConsumerCode() bool`

HasConsumerCode returns a boolean if a field has been set.

### GetSeverity

`func (o *OperatorRuntimeIncidentNotificationList) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeIncidentNotificationList) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeIncidentNotificationList) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetIncidentStatus

`func (o *OperatorRuntimeIncidentNotificationList) GetIncidentStatus() string`

GetIncidentStatus returns the IncidentStatus field if non-nil, zero value otherwise.

### GetIncidentStatusOk

`func (o *OperatorRuntimeIncidentNotificationList) GetIncidentStatusOk() (*string, bool)`

GetIncidentStatusOk returns a tuple with the IncidentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentStatus

`func (o *OperatorRuntimeIncidentNotificationList) SetIncidentStatus(v string)`

SetIncidentStatus sets IncidentStatus field to given value.


### GetStatus

`func (o *OperatorRuntimeIncidentNotificationList) GetStatus() RuntimeIncidentNotificationOutboxStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeIncidentNotificationList) GetStatusOk() (*RuntimeIncidentNotificationOutboxStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeIncidentNotificationList) SetStatus(v RuntimeIncidentNotificationOutboxStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperatorRuntimeIncidentNotificationList) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAttemptCount

`func (o *OperatorRuntimeIncidentNotificationList) GetAttemptCount() int64`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *OperatorRuntimeIncidentNotificationList) GetAttemptCountOk() (*int64, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *OperatorRuntimeIncidentNotificationList) SetAttemptCount(v int64)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *OperatorRuntimeIncidentNotificationList) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationList) GetMaxAttempts() int64`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorRuntimeIncidentNotificationList) GetMaxAttemptsOk() (*int64, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationList) SetMaxAttempts(v int64)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationList) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.

### GetNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationList) GetNextAttemptAt() time.Time`

GetNextAttemptAt returns the NextAttemptAt field if non-nil, zero value otherwise.

### GetNextAttemptAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetNextAttemptAtOk() (*time.Time, bool)`

GetNextAttemptAtOk returns a tuple with the NextAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationList) SetNextAttemptAt(v time.Time)`

SetNextAttemptAt sets NextAttemptAt field to given value.

### HasNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationList) HasNextAttemptAt() bool`

HasNextAttemptAt returns a boolean if a field has been set.

### GetLeaseOwner

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseOwner() string`

GetLeaseOwner returns the LeaseOwner field if non-nil, zero value otherwise.

### GetLeaseOwnerOk

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseOwnerOk() (*string, bool)`

GetLeaseOwnerOk returns a tuple with the LeaseOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseOwner

`func (o *OperatorRuntimeIncidentNotificationList) SetLeaseOwner(v string)`

SetLeaseOwner sets LeaseOwner field to given value.

### HasLeaseOwner

`func (o *OperatorRuntimeIncidentNotificationList) HasLeaseOwner() bool`

HasLeaseOwner returns a boolean if a field has been set.

### GetLeaseAcquiredAt

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseAcquiredAt() time.Time`

GetLeaseAcquiredAt returns the LeaseAcquiredAt field if non-nil, zero value otherwise.

### GetLeaseAcquiredAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseAcquiredAtOk() (*time.Time, bool)`

GetLeaseAcquiredAtOk returns a tuple with the LeaseAcquiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseAcquiredAt

`func (o *OperatorRuntimeIncidentNotificationList) SetLeaseAcquiredAt(v time.Time)`

SetLeaseAcquiredAt sets LeaseAcquiredAt field to given value.

### HasLeaseAcquiredAt

`func (o *OperatorRuntimeIncidentNotificationList) HasLeaseAcquiredAt() bool`

HasLeaseAcquiredAt returns a boolean if a field has been set.

### SetLeaseAcquiredAtNil

`func (o *OperatorRuntimeIncidentNotificationList) SetLeaseAcquiredAtNil(b bool)`

 SetLeaseAcquiredAtNil sets the value for LeaseAcquiredAt to be an explicit nil

### UnsetLeaseAcquiredAt
`func (o *OperatorRuntimeIncidentNotificationList) UnsetLeaseAcquiredAt()`

UnsetLeaseAcquiredAt ensures that no value is present for LeaseAcquiredAt, not even an explicit nil
### GetLeaseExpiresAt

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseExpiresAt() time.Time`

GetLeaseExpiresAt returns the LeaseExpiresAt field if non-nil, zero value otherwise.

### GetLeaseExpiresAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseExpiresAtOk() (*time.Time, bool)`

GetLeaseExpiresAtOk returns a tuple with the LeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpiresAt

`func (o *OperatorRuntimeIncidentNotificationList) SetLeaseExpiresAt(v time.Time)`

SetLeaseExpiresAt sets LeaseExpiresAt field to given value.

### HasLeaseExpiresAt

`func (o *OperatorRuntimeIncidentNotificationList) HasLeaseExpiresAt() bool`

HasLeaseExpiresAt returns a boolean if a field has been set.

### SetLeaseExpiresAtNil

`func (o *OperatorRuntimeIncidentNotificationList) SetLeaseExpiresAtNil(b bool)`

 SetLeaseExpiresAtNil sets the value for LeaseExpiresAt to be an explicit nil

### UnsetLeaseExpiresAt
`func (o *OperatorRuntimeIncidentNotificationList) UnsetLeaseExpiresAt()`

UnsetLeaseExpiresAt ensures that no value is present for LeaseExpiresAt, not even an explicit nil
### GetIsTerminal

`func (o *OperatorRuntimeIncidentNotificationList) GetIsTerminal() bool`

GetIsTerminal returns the IsTerminal field if non-nil, zero value otherwise.

### GetIsTerminalOk

`func (o *OperatorRuntimeIncidentNotificationList) GetIsTerminalOk() (*bool, bool)`

GetIsTerminalOk returns a tuple with the IsTerminal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTerminal

`func (o *OperatorRuntimeIncidentNotificationList) SetIsTerminal(v bool)`

SetIsTerminal sets IsTerminal field to given value.


### GetIsLeased

`func (o *OperatorRuntimeIncidentNotificationList) GetIsLeased() bool`

GetIsLeased returns the IsLeased field if non-nil, zero value otherwise.

### GetIsLeasedOk

`func (o *OperatorRuntimeIncidentNotificationList) GetIsLeasedOk() (*bool, bool)`

GetIsLeasedOk returns a tuple with the IsLeased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLeased

`func (o *OperatorRuntimeIncidentNotificationList) SetIsLeased(v bool)`

SetIsLeased sets IsLeased field to given value.


### GetLeaseExpired

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseExpired() bool`

GetLeaseExpired returns the LeaseExpired field if non-nil, zero value otherwise.

### GetLeaseExpiredOk

`func (o *OperatorRuntimeIncidentNotificationList) GetLeaseExpiredOk() (*bool, bool)`

GetLeaseExpiredOk returns a tuple with the LeaseExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpired

`func (o *OperatorRuntimeIncidentNotificationList) SetLeaseExpired(v bool)`

SetLeaseExpired sets LeaseExpired field to given value.


### GetPublishedAt

`func (o *OperatorRuntimeIncidentNotificationList) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *OperatorRuntimeIncidentNotificationList) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *OperatorRuntimeIncidentNotificationList) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### SetPublishedAtNil

`func (o *OperatorRuntimeIncidentNotificationList) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *OperatorRuntimeIncidentNotificationList) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetDeadLetteredAt

`func (o *OperatorRuntimeIncidentNotificationList) GetDeadLetteredAt() time.Time`

GetDeadLetteredAt returns the DeadLetteredAt field if non-nil, zero value otherwise.

### GetDeadLetteredAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetDeadLetteredAtOk() (*time.Time, bool)`

GetDeadLetteredAtOk returns a tuple with the DeadLetteredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetteredAt

`func (o *OperatorRuntimeIncidentNotificationList) SetDeadLetteredAt(v time.Time)`

SetDeadLetteredAt sets DeadLetteredAt field to given value.

### HasDeadLetteredAt

`func (o *OperatorRuntimeIncidentNotificationList) HasDeadLetteredAt() bool`

HasDeadLetteredAt returns a boolean if a field has been set.

### SetDeadLetteredAtNil

`func (o *OperatorRuntimeIncidentNotificationList) SetDeadLetteredAtNil(b bool)`

 SetDeadLetteredAtNil sets the value for DeadLetteredAt to be an explicit nil

### UnsetDeadLetteredAt
`func (o *OperatorRuntimeIncidentNotificationList) UnsetDeadLetteredAt()`

UnsetDeadLetteredAt ensures that no value is present for DeadLetteredAt, not even an explicit nil
### GetLastErrorType

`func (o *OperatorRuntimeIncidentNotificationList) GetLastErrorType() string`

GetLastErrorType returns the LastErrorType field if non-nil, zero value otherwise.

### GetLastErrorTypeOk

`func (o *OperatorRuntimeIncidentNotificationList) GetLastErrorTypeOk() (*string, bool)`

GetLastErrorTypeOk returns a tuple with the LastErrorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorType

`func (o *OperatorRuntimeIncidentNotificationList) SetLastErrorType(v string)`

SetLastErrorType sets LastErrorType field to given value.

### HasLastErrorType

`func (o *OperatorRuntimeIncidentNotificationList) HasLastErrorType() bool`

HasLastErrorType returns a boolean if a field has been set.

### GetLastErrorAt

`func (o *OperatorRuntimeIncidentNotificationList) GetLastErrorAt() time.Time`

GetLastErrorAt returns the LastErrorAt field if non-nil, zero value otherwise.

### GetLastErrorAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetLastErrorAtOk() (*time.Time, bool)`

GetLastErrorAtOk returns a tuple with the LastErrorAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorAt

`func (o *OperatorRuntimeIncidentNotificationList) SetLastErrorAt(v time.Time)`

SetLastErrorAt sets LastErrorAt field to given value.

### HasLastErrorAt

`func (o *OperatorRuntimeIncidentNotificationList) HasLastErrorAt() bool`

HasLastErrorAt returns a boolean if a field has been set.

### SetLastErrorAtNil

`func (o *OperatorRuntimeIncidentNotificationList) SetLastErrorAtNil(b bool)`

 SetLastErrorAtNil sets the value for LastErrorAt to be an explicit nil

### UnsetLastErrorAt
`func (o *OperatorRuntimeIncidentNotificationList) UnsetLastErrorAt()`

UnsetLastErrorAt ensures that no value is present for LastErrorAt, not even an explicit nil
### GetRevision

`func (o *OperatorRuntimeIncidentNotificationList) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *OperatorRuntimeIncidentNotificationList) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *OperatorRuntimeIncidentNotificationList) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *OperatorRuntimeIncidentNotificationList) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OperatorRuntimeIncidentNotificationList) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorRuntimeIncidentNotificationList) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorRuntimeIncidentNotificationList) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorRuntimeIncidentNotificationList) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorRuntimeIncidentNotificationList) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


