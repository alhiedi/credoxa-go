# OperatorRuntimeIncidentNotificationActionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OutboxId** | **string** |  | 
**EventId** | **string** |  | 
**Action** | **string** |  | 
**PreviousStatus** | **string** |  | 
**Status** | **string** |  | 
**AttemptCount** | **int32** |  | 
**MaxAttempts** | **int32** |  | 
**NextAttemptAt** | **time.Time** |  | 
**Revision** | **int32** |  | 
**Actor** | **string** |  | 
**OccurredAt** | **time.Time** |  | 

## Methods

### NewOperatorRuntimeIncidentNotificationActionResponse

`func NewOperatorRuntimeIncidentNotificationActionResponse(outboxId string, eventId string, action string, previousStatus string, status string, attemptCount int32, maxAttempts int32, nextAttemptAt time.Time, revision int32, actor string, occurredAt time.Time, ) *OperatorRuntimeIncidentNotificationActionResponse`

NewOperatorRuntimeIncidentNotificationActionResponse instantiates a new OperatorRuntimeIncidentNotificationActionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentNotificationActionResponseWithDefaults

`func NewOperatorRuntimeIncidentNotificationActionResponseWithDefaults() *OperatorRuntimeIncidentNotificationActionResponse`

NewOperatorRuntimeIncidentNotificationActionResponseWithDefaults instantiates a new OperatorRuntimeIncidentNotificationActionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutboxId

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetOutboxId() string`

GetOutboxId returns the OutboxId field if non-nil, zero value otherwise.

### GetOutboxIdOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetOutboxIdOk() (*string, bool)`

GetOutboxIdOk returns a tuple with the OutboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboxId

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetOutboxId(v string)`

SetOutboxId sets OutboxId field to given value.


### GetEventId

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetAction

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetAction(v string)`

SetAction sets Action field to given value.


### GetPreviousStatus

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetPreviousStatus() string`

GetPreviousStatus returns the PreviousStatus field if non-nil, zero value otherwise.

### GetPreviousStatusOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetPreviousStatusOk() (*string, bool)`

GetPreviousStatusOk returns a tuple with the PreviousStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousStatus

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetPreviousStatus(v string)`

SetPreviousStatus sets PreviousStatus field to given value.


### GetStatus

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAttemptCount

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.


### GetMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.


### GetNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetNextAttemptAt() time.Time`

GetNextAttemptAt returns the NextAttemptAt field if non-nil, zero value otherwise.

### GetNextAttemptAtOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetNextAttemptAtOk() (*time.Time, bool)`

GetNextAttemptAtOk returns a tuple with the NextAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextAttemptAt

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetNextAttemptAt(v time.Time)`

SetNextAttemptAt sets NextAttemptAt field to given value.


### GetRevision

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetActor

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetActor() string`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetActorOk() (*string, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetActor(v string)`

SetActor sets Actor field to given value.


### GetOccurredAt

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *OperatorRuntimeIncidentNotificationActionResponse) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *OperatorRuntimeIncidentNotificationActionResponse) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


