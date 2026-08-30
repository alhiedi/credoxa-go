# SaaSOperatorOutboxRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MessageId** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**DestinationService** | **string** |  | 
**MessageType** | **string** |  | 
**SchemaVersion** | **int32** |  | 
**AggregateType** | **string** |  | 
**AggregateId** | **string** |  | 
**Status** | **string** |  | 
**AttemptCount** | **int32** |  | 
**MaximumAttempts** | **int32** |  | 
**AvailableAt** | **time.Time** |  | 
**AcknowledgedAt** | **NullableTime** |  | 
**DeadLetteredAt** | **NullableTime** |  | 
**LastErrorCode** | **NullableString** |  | 
**ResponseStatus** | **NullableInt32** |  | 
**ResponseReference** | **NullableString** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewSaaSOperatorOutboxRecord

`func NewSaaSOperatorOutboxRecord(messageId string, organizationId NullableString, destinationService string, messageType string, schemaVersion int32, aggregateType string, aggregateId string, status string, attemptCount int32, maximumAttempts int32, availableAt time.Time, acknowledgedAt NullableTime, deadLetteredAt NullableTime, lastErrorCode NullableString, responseStatus NullableInt32, responseReference NullableString, createdAt time.Time, ) *SaaSOperatorOutboxRecord`

NewSaaSOperatorOutboxRecord instantiates a new SaaSOperatorOutboxRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaaSOperatorOutboxRecordWithDefaults

`func NewSaaSOperatorOutboxRecordWithDefaults() *SaaSOperatorOutboxRecord`

NewSaaSOperatorOutboxRecordWithDefaults instantiates a new SaaSOperatorOutboxRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessageId

`func (o *SaaSOperatorOutboxRecord) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *SaaSOperatorOutboxRecord) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *SaaSOperatorOutboxRecord) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.


### GetOrganizationId

`func (o *SaaSOperatorOutboxRecord) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *SaaSOperatorOutboxRecord) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *SaaSOperatorOutboxRecord) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *SaaSOperatorOutboxRecord) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *SaaSOperatorOutboxRecord) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetDestinationService

`func (o *SaaSOperatorOutboxRecord) GetDestinationService() string`

GetDestinationService returns the DestinationService field if non-nil, zero value otherwise.

### GetDestinationServiceOk

`func (o *SaaSOperatorOutboxRecord) GetDestinationServiceOk() (*string, bool)`

GetDestinationServiceOk returns a tuple with the DestinationService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationService

`func (o *SaaSOperatorOutboxRecord) SetDestinationService(v string)`

SetDestinationService sets DestinationService field to given value.


### GetMessageType

`func (o *SaaSOperatorOutboxRecord) GetMessageType() string`

GetMessageType returns the MessageType field if non-nil, zero value otherwise.

### GetMessageTypeOk

`func (o *SaaSOperatorOutboxRecord) GetMessageTypeOk() (*string, bool)`

GetMessageTypeOk returns a tuple with the MessageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageType

`func (o *SaaSOperatorOutboxRecord) SetMessageType(v string)`

SetMessageType sets MessageType field to given value.


### GetSchemaVersion

`func (o *SaaSOperatorOutboxRecord) GetSchemaVersion() int32`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *SaaSOperatorOutboxRecord) GetSchemaVersionOk() (*int32, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *SaaSOperatorOutboxRecord) SetSchemaVersion(v int32)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetAggregateType

`func (o *SaaSOperatorOutboxRecord) GetAggregateType() string`

GetAggregateType returns the AggregateType field if non-nil, zero value otherwise.

### GetAggregateTypeOk

`func (o *SaaSOperatorOutboxRecord) GetAggregateTypeOk() (*string, bool)`

GetAggregateTypeOk returns a tuple with the AggregateType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregateType

`func (o *SaaSOperatorOutboxRecord) SetAggregateType(v string)`

SetAggregateType sets AggregateType field to given value.


### GetAggregateId

`func (o *SaaSOperatorOutboxRecord) GetAggregateId() string`

GetAggregateId returns the AggregateId field if non-nil, zero value otherwise.

### GetAggregateIdOk

`func (o *SaaSOperatorOutboxRecord) GetAggregateIdOk() (*string, bool)`

GetAggregateIdOk returns a tuple with the AggregateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregateId

`func (o *SaaSOperatorOutboxRecord) SetAggregateId(v string)`

SetAggregateId sets AggregateId field to given value.


### GetStatus

`func (o *SaaSOperatorOutboxRecord) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SaaSOperatorOutboxRecord) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SaaSOperatorOutboxRecord) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAttemptCount

`func (o *SaaSOperatorOutboxRecord) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *SaaSOperatorOutboxRecord) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *SaaSOperatorOutboxRecord) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.


### GetMaximumAttempts

`func (o *SaaSOperatorOutboxRecord) GetMaximumAttempts() int32`

GetMaximumAttempts returns the MaximumAttempts field if non-nil, zero value otherwise.

### GetMaximumAttemptsOk

`func (o *SaaSOperatorOutboxRecord) GetMaximumAttemptsOk() (*int32, bool)`

GetMaximumAttemptsOk returns a tuple with the MaximumAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumAttempts

`func (o *SaaSOperatorOutboxRecord) SetMaximumAttempts(v int32)`

SetMaximumAttempts sets MaximumAttempts field to given value.


### GetAvailableAt

`func (o *SaaSOperatorOutboxRecord) GetAvailableAt() time.Time`

GetAvailableAt returns the AvailableAt field if non-nil, zero value otherwise.

### GetAvailableAtOk

`func (o *SaaSOperatorOutboxRecord) GetAvailableAtOk() (*time.Time, bool)`

GetAvailableAtOk returns a tuple with the AvailableAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableAt

`func (o *SaaSOperatorOutboxRecord) SetAvailableAt(v time.Time)`

SetAvailableAt sets AvailableAt field to given value.


### GetAcknowledgedAt

`func (o *SaaSOperatorOutboxRecord) GetAcknowledgedAt() time.Time`

GetAcknowledgedAt returns the AcknowledgedAt field if non-nil, zero value otherwise.

### GetAcknowledgedAtOk

`func (o *SaaSOperatorOutboxRecord) GetAcknowledgedAtOk() (*time.Time, bool)`

GetAcknowledgedAtOk returns a tuple with the AcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedAt

`func (o *SaaSOperatorOutboxRecord) SetAcknowledgedAt(v time.Time)`

SetAcknowledgedAt sets AcknowledgedAt field to given value.


### SetAcknowledgedAtNil

`func (o *SaaSOperatorOutboxRecord) SetAcknowledgedAtNil(b bool)`

 SetAcknowledgedAtNil sets the value for AcknowledgedAt to be an explicit nil

### UnsetAcknowledgedAt
`func (o *SaaSOperatorOutboxRecord) UnsetAcknowledgedAt()`

UnsetAcknowledgedAt ensures that no value is present for AcknowledgedAt, not even an explicit nil
### GetDeadLetteredAt

`func (o *SaaSOperatorOutboxRecord) GetDeadLetteredAt() time.Time`

GetDeadLetteredAt returns the DeadLetteredAt field if non-nil, zero value otherwise.

### GetDeadLetteredAtOk

`func (o *SaaSOperatorOutboxRecord) GetDeadLetteredAtOk() (*time.Time, bool)`

GetDeadLetteredAtOk returns a tuple with the DeadLetteredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetteredAt

`func (o *SaaSOperatorOutboxRecord) SetDeadLetteredAt(v time.Time)`

SetDeadLetteredAt sets DeadLetteredAt field to given value.


### SetDeadLetteredAtNil

`func (o *SaaSOperatorOutboxRecord) SetDeadLetteredAtNil(b bool)`

 SetDeadLetteredAtNil sets the value for DeadLetteredAt to be an explicit nil

### UnsetDeadLetteredAt
`func (o *SaaSOperatorOutboxRecord) UnsetDeadLetteredAt()`

UnsetDeadLetteredAt ensures that no value is present for DeadLetteredAt, not even an explicit nil
### GetLastErrorCode

`func (o *SaaSOperatorOutboxRecord) GetLastErrorCode() string`

GetLastErrorCode returns the LastErrorCode field if non-nil, zero value otherwise.

### GetLastErrorCodeOk

`func (o *SaaSOperatorOutboxRecord) GetLastErrorCodeOk() (*string, bool)`

GetLastErrorCodeOk returns a tuple with the LastErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorCode

`func (o *SaaSOperatorOutboxRecord) SetLastErrorCode(v string)`

SetLastErrorCode sets LastErrorCode field to given value.


### SetLastErrorCodeNil

`func (o *SaaSOperatorOutboxRecord) SetLastErrorCodeNil(b bool)`

 SetLastErrorCodeNil sets the value for LastErrorCode to be an explicit nil

### UnsetLastErrorCode
`func (o *SaaSOperatorOutboxRecord) UnsetLastErrorCode()`

UnsetLastErrorCode ensures that no value is present for LastErrorCode, not even an explicit nil
### GetResponseStatus

`func (o *SaaSOperatorOutboxRecord) GetResponseStatus() int32`

GetResponseStatus returns the ResponseStatus field if non-nil, zero value otherwise.

### GetResponseStatusOk

`func (o *SaaSOperatorOutboxRecord) GetResponseStatusOk() (*int32, bool)`

GetResponseStatusOk returns a tuple with the ResponseStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseStatus

`func (o *SaaSOperatorOutboxRecord) SetResponseStatus(v int32)`

SetResponseStatus sets ResponseStatus field to given value.


### SetResponseStatusNil

`func (o *SaaSOperatorOutboxRecord) SetResponseStatusNil(b bool)`

 SetResponseStatusNil sets the value for ResponseStatus to be an explicit nil

### UnsetResponseStatus
`func (o *SaaSOperatorOutboxRecord) UnsetResponseStatus()`

UnsetResponseStatus ensures that no value is present for ResponseStatus, not even an explicit nil
### GetResponseReference

`func (o *SaaSOperatorOutboxRecord) GetResponseReference() string`

GetResponseReference returns the ResponseReference field if non-nil, zero value otherwise.

### GetResponseReferenceOk

`func (o *SaaSOperatorOutboxRecord) GetResponseReferenceOk() (*string, bool)`

GetResponseReferenceOk returns a tuple with the ResponseReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseReference

`func (o *SaaSOperatorOutboxRecord) SetResponseReference(v string)`

SetResponseReference sets ResponseReference field to given value.


### SetResponseReferenceNil

`func (o *SaaSOperatorOutboxRecord) SetResponseReferenceNil(b bool)`

 SetResponseReferenceNil sets the value for ResponseReference to be an explicit nil

### UnsetResponseReference
`func (o *SaaSOperatorOutboxRecord) UnsetResponseReference()`

UnsetResponseReference ensures that no value is present for ResponseReference, not even an explicit nil
### GetCreatedAt

`func (o *SaaSOperatorOutboxRecord) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SaaSOperatorOutboxRecord) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SaaSOperatorOutboxRecord) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


