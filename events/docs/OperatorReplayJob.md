# OperatorReplayJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**Status** | **string** |  | 
**TargetConsumerId** | **string** |  | 
**TargetConsumerCode** | **string** |  | 
**TargetConsumerName** | **string** |  | 
**RequestedBy** | **string** |  | 
**Reason** | **string** |  | 
**EventTypes** | **[]string** |  | 
**Sources** | **[]string** |  | 
**SubjectPrefix** | **string** |  | 
**BatchSize** | **int32** |  | 
**TotalEvents** | **NullableInt32** |  | 
**ProcessedEvents** | **int32** |  | 
**PublishedEvents** | **int32** |  | 
**FailedEvents** | **int32** |  | 
**ProgressPercentage** | **NullableFloat64** |  | 
**FailureCode** | **string** |  | 
**FailureReason** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**StartedAt** | **NullableTime** |  | 
**PausedAt** | **NullableTime** |  | 
**CancelRequestedAt** | **NullableTime** |  | 
**CancelledAt** | **NullableTime** |  | 
**CompletedAt** | **NullableTime** |  | 
**FailedAt** | **NullableTime** |  | 
**SnapshotCreatedAt** | **NullableTime** |  | 
**SnapshotReceivedAt** | **NullableTime** |  | 
**SnapshotEventId** | **NullableString** |  | 
**CursorReceivedAt** | **NullableTime** |  | 
**CursorEventId** | **NullableString** |  | 
**LockedAt** | **NullableTime** |  | 
**LockExpiresAt** | **NullableTime** |  | 
**LockedBy** | **string** |  | 

## Methods

### NewOperatorReplayJob

`func NewOperatorReplayJob(id string, organizationId string, status string, targetConsumerId string, targetConsumerCode string, targetConsumerName string, requestedBy string, reason string, eventTypes []string, sources []string, subjectPrefix string, batchSize int32, totalEvents NullableInt32, processedEvents int32, publishedEvents int32, failedEvents int32, progressPercentage NullableFloat64, failureCode string, failureReason string, createdAt time.Time, updatedAt time.Time, startedAt NullableTime, pausedAt NullableTime, cancelRequestedAt NullableTime, cancelledAt NullableTime, completedAt NullableTime, failedAt NullableTime, snapshotCreatedAt NullableTime, snapshotReceivedAt NullableTime, snapshotEventId NullableString, cursorReceivedAt NullableTime, cursorEventId NullableString, lockedAt NullableTime, lockExpiresAt NullableTime, lockedBy string, ) *OperatorReplayJob`

NewOperatorReplayJob instantiates a new OperatorReplayJob object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorReplayJobWithDefaults

`func NewOperatorReplayJobWithDefaults() *OperatorReplayJob`

NewOperatorReplayJobWithDefaults instantiates a new OperatorReplayJob object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorReplayJob) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorReplayJob) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorReplayJob) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *OperatorReplayJob) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorReplayJob) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorReplayJob) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetStatus

`func (o *OperatorReplayJob) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorReplayJob) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorReplayJob) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTargetConsumerId

`func (o *OperatorReplayJob) GetTargetConsumerId() string`

GetTargetConsumerId returns the TargetConsumerId field if non-nil, zero value otherwise.

### GetTargetConsumerIdOk

`func (o *OperatorReplayJob) GetTargetConsumerIdOk() (*string, bool)`

GetTargetConsumerIdOk returns a tuple with the TargetConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetConsumerId

`func (o *OperatorReplayJob) SetTargetConsumerId(v string)`

SetTargetConsumerId sets TargetConsumerId field to given value.


### GetTargetConsumerCode

`func (o *OperatorReplayJob) GetTargetConsumerCode() string`

GetTargetConsumerCode returns the TargetConsumerCode field if non-nil, zero value otherwise.

### GetTargetConsumerCodeOk

`func (o *OperatorReplayJob) GetTargetConsumerCodeOk() (*string, bool)`

GetTargetConsumerCodeOk returns a tuple with the TargetConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetConsumerCode

`func (o *OperatorReplayJob) SetTargetConsumerCode(v string)`

SetTargetConsumerCode sets TargetConsumerCode field to given value.


### GetTargetConsumerName

`func (o *OperatorReplayJob) GetTargetConsumerName() string`

GetTargetConsumerName returns the TargetConsumerName field if non-nil, zero value otherwise.

### GetTargetConsumerNameOk

`func (o *OperatorReplayJob) GetTargetConsumerNameOk() (*string, bool)`

GetTargetConsumerNameOk returns a tuple with the TargetConsumerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetConsumerName

`func (o *OperatorReplayJob) SetTargetConsumerName(v string)`

SetTargetConsumerName sets TargetConsumerName field to given value.


### GetRequestedBy

`func (o *OperatorReplayJob) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *OperatorReplayJob) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *OperatorReplayJob) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetReason

`func (o *OperatorReplayJob) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *OperatorReplayJob) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *OperatorReplayJob) SetReason(v string)`

SetReason sets Reason field to given value.


### GetEventTypes

`func (o *OperatorReplayJob) GetEventTypes() []string`

GetEventTypes returns the EventTypes field if non-nil, zero value otherwise.

### GetEventTypesOk

`func (o *OperatorReplayJob) GetEventTypesOk() (*[]string, bool)`

GetEventTypesOk returns a tuple with the EventTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypes

`func (o *OperatorReplayJob) SetEventTypes(v []string)`

SetEventTypes sets EventTypes field to given value.


### GetSources

`func (o *OperatorReplayJob) GetSources() []string`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *OperatorReplayJob) GetSourcesOk() (*[]string, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *OperatorReplayJob) SetSources(v []string)`

SetSources sets Sources field to given value.


### GetSubjectPrefix

`func (o *OperatorReplayJob) GetSubjectPrefix() string`

GetSubjectPrefix returns the SubjectPrefix field if non-nil, zero value otherwise.

### GetSubjectPrefixOk

`func (o *OperatorReplayJob) GetSubjectPrefixOk() (*string, bool)`

GetSubjectPrefixOk returns a tuple with the SubjectPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectPrefix

`func (o *OperatorReplayJob) SetSubjectPrefix(v string)`

SetSubjectPrefix sets SubjectPrefix field to given value.


### GetBatchSize

`func (o *OperatorReplayJob) GetBatchSize() int32`

GetBatchSize returns the BatchSize field if non-nil, zero value otherwise.

### GetBatchSizeOk

`func (o *OperatorReplayJob) GetBatchSizeOk() (*int32, bool)`

GetBatchSizeOk returns a tuple with the BatchSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchSize

`func (o *OperatorReplayJob) SetBatchSize(v int32)`

SetBatchSize sets BatchSize field to given value.


### GetTotalEvents

`func (o *OperatorReplayJob) GetTotalEvents() int32`

GetTotalEvents returns the TotalEvents field if non-nil, zero value otherwise.

### GetTotalEventsOk

`func (o *OperatorReplayJob) GetTotalEventsOk() (*int32, bool)`

GetTotalEventsOk returns a tuple with the TotalEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEvents

`func (o *OperatorReplayJob) SetTotalEvents(v int32)`

SetTotalEvents sets TotalEvents field to given value.


### SetTotalEventsNil

`func (o *OperatorReplayJob) SetTotalEventsNil(b bool)`

 SetTotalEventsNil sets the value for TotalEvents to be an explicit nil

### UnsetTotalEvents
`func (o *OperatorReplayJob) UnsetTotalEvents()`

UnsetTotalEvents ensures that no value is present for TotalEvents, not even an explicit nil
### GetProcessedEvents

`func (o *OperatorReplayJob) GetProcessedEvents() int32`

GetProcessedEvents returns the ProcessedEvents field if non-nil, zero value otherwise.

### GetProcessedEventsOk

`func (o *OperatorReplayJob) GetProcessedEventsOk() (*int32, bool)`

GetProcessedEventsOk returns a tuple with the ProcessedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedEvents

`func (o *OperatorReplayJob) SetProcessedEvents(v int32)`

SetProcessedEvents sets ProcessedEvents field to given value.


### GetPublishedEvents

`func (o *OperatorReplayJob) GetPublishedEvents() int32`

GetPublishedEvents returns the PublishedEvents field if non-nil, zero value otherwise.

### GetPublishedEventsOk

`func (o *OperatorReplayJob) GetPublishedEventsOk() (*int32, bool)`

GetPublishedEventsOk returns a tuple with the PublishedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedEvents

`func (o *OperatorReplayJob) SetPublishedEvents(v int32)`

SetPublishedEvents sets PublishedEvents field to given value.


### GetFailedEvents

`func (o *OperatorReplayJob) GetFailedEvents() int32`

GetFailedEvents returns the FailedEvents field if non-nil, zero value otherwise.

### GetFailedEventsOk

`func (o *OperatorReplayJob) GetFailedEventsOk() (*int32, bool)`

GetFailedEventsOk returns a tuple with the FailedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedEvents

`func (o *OperatorReplayJob) SetFailedEvents(v int32)`

SetFailedEvents sets FailedEvents field to given value.


### GetProgressPercentage

`func (o *OperatorReplayJob) GetProgressPercentage() float64`

GetProgressPercentage returns the ProgressPercentage field if non-nil, zero value otherwise.

### GetProgressPercentageOk

`func (o *OperatorReplayJob) GetProgressPercentageOk() (*float64, bool)`

GetProgressPercentageOk returns a tuple with the ProgressPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressPercentage

`func (o *OperatorReplayJob) SetProgressPercentage(v float64)`

SetProgressPercentage sets ProgressPercentage field to given value.


### SetProgressPercentageNil

`func (o *OperatorReplayJob) SetProgressPercentageNil(b bool)`

 SetProgressPercentageNil sets the value for ProgressPercentage to be an explicit nil

### UnsetProgressPercentage
`func (o *OperatorReplayJob) UnsetProgressPercentage()`

UnsetProgressPercentage ensures that no value is present for ProgressPercentage, not even an explicit nil
### GetFailureCode

`func (o *OperatorReplayJob) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *OperatorReplayJob) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *OperatorReplayJob) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.


### GetFailureReason

`func (o *OperatorReplayJob) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *OperatorReplayJob) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *OperatorReplayJob) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.


### GetCreatedAt

`func (o *OperatorReplayJob) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorReplayJob) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorReplayJob) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorReplayJob) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorReplayJob) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorReplayJob) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetStartedAt

`func (o *OperatorReplayJob) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *OperatorReplayJob) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *OperatorReplayJob) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *OperatorReplayJob) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *OperatorReplayJob) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetPausedAt

`func (o *OperatorReplayJob) GetPausedAt() time.Time`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *OperatorReplayJob) GetPausedAtOk() (*time.Time, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *OperatorReplayJob) SetPausedAt(v time.Time)`

SetPausedAt sets PausedAt field to given value.


### SetPausedAtNil

`func (o *OperatorReplayJob) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *OperatorReplayJob) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetCancelRequestedAt

`func (o *OperatorReplayJob) GetCancelRequestedAt() time.Time`

GetCancelRequestedAt returns the CancelRequestedAt field if non-nil, zero value otherwise.

### GetCancelRequestedAtOk

`func (o *OperatorReplayJob) GetCancelRequestedAtOk() (*time.Time, bool)`

GetCancelRequestedAtOk returns a tuple with the CancelRequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelRequestedAt

`func (o *OperatorReplayJob) SetCancelRequestedAt(v time.Time)`

SetCancelRequestedAt sets CancelRequestedAt field to given value.


### SetCancelRequestedAtNil

`func (o *OperatorReplayJob) SetCancelRequestedAtNil(b bool)`

 SetCancelRequestedAtNil sets the value for CancelRequestedAt to be an explicit nil

### UnsetCancelRequestedAt
`func (o *OperatorReplayJob) UnsetCancelRequestedAt()`

UnsetCancelRequestedAt ensures that no value is present for CancelRequestedAt, not even an explicit nil
### GetCancelledAt

`func (o *OperatorReplayJob) GetCancelledAt() time.Time`

GetCancelledAt returns the CancelledAt field if non-nil, zero value otherwise.

### GetCancelledAtOk

`func (o *OperatorReplayJob) GetCancelledAtOk() (*time.Time, bool)`

GetCancelledAtOk returns a tuple with the CancelledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelledAt

`func (o *OperatorReplayJob) SetCancelledAt(v time.Time)`

SetCancelledAt sets CancelledAt field to given value.


### SetCancelledAtNil

`func (o *OperatorReplayJob) SetCancelledAtNil(b bool)`

 SetCancelledAtNil sets the value for CancelledAt to be an explicit nil

### UnsetCancelledAt
`func (o *OperatorReplayJob) UnsetCancelledAt()`

UnsetCancelledAt ensures that no value is present for CancelledAt, not even an explicit nil
### GetCompletedAt

`func (o *OperatorReplayJob) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *OperatorReplayJob) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *OperatorReplayJob) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *OperatorReplayJob) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *OperatorReplayJob) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetFailedAt

`func (o *OperatorReplayJob) GetFailedAt() time.Time`

GetFailedAt returns the FailedAt field if non-nil, zero value otherwise.

### GetFailedAtOk

`func (o *OperatorReplayJob) GetFailedAtOk() (*time.Time, bool)`

GetFailedAtOk returns a tuple with the FailedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedAt

`func (o *OperatorReplayJob) SetFailedAt(v time.Time)`

SetFailedAt sets FailedAt field to given value.


### SetFailedAtNil

`func (o *OperatorReplayJob) SetFailedAtNil(b bool)`

 SetFailedAtNil sets the value for FailedAt to be an explicit nil

### UnsetFailedAt
`func (o *OperatorReplayJob) UnsetFailedAt()`

UnsetFailedAt ensures that no value is present for FailedAt, not even an explicit nil
### GetSnapshotCreatedAt

`func (o *OperatorReplayJob) GetSnapshotCreatedAt() time.Time`

GetSnapshotCreatedAt returns the SnapshotCreatedAt field if non-nil, zero value otherwise.

### GetSnapshotCreatedAtOk

`func (o *OperatorReplayJob) GetSnapshotCreatedAtOk() (*time.Time, bool)`

GetSnapshotCreatedAtOk returns a tuple with the SnapshotCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotCreatedAt

`func (o *OperatorReplayJob) SetSnapshotCreatedAt(v time.Time)`

SetSnapshotCreatedAt sets SnapshotCreatedAt field to given value.


### SetSnapshotCreatedAtNil

`func (o *OperatorReplayJob) SetSnapshotCreatedAtNil(b bool)`

 SetSnapshotCreatedAtNil sets the value for SnapshotCreatedAt to be an explicit nil

### UnsetSnapshotCreatedAt
`func (o *OperatorReplayJob) UnsetSnapshotCreatedAt()`

UnsetSnapshotCreatedAt ensures that no value is present for SnapshotCreatedAt, not even an explicit nil
### GetSnapshotReceivedAt

`func (o *OperatorReplayJob) GetSnapshotReceivedAt() time.Time`

GetSnapshotReceivedAt returns the SnapshotReceivedAt field if non-nil, zero value otherwise.

### GetSnapshotReceivedAtOk

`func (o *OperatorReplayJob) GetSnapshotReceivedAtOk() (*time.Time, bool)`

GetSnapshotReceivedAtOk returns a tuple with the SnapshotReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotReceivedAt

`func (o *OperatorReplayJob) SetSnapshotReceivedAt(v time.Time)`

SetSnapshotReceivedAt sets SnapshotReceivedAt field to given value.


### SetSnapshotReceivedAtNil

`func (o *OperatorReplayJob) SetSnapshotReceivedAtNil(b bool)`

 SetSnapshotReceivedAtNil sets the value for SnapshotReceivedAt to be an explicit nil

### UnsetSnapshotReceivedAt
`func (o *OperatorReplayJob) UnsetSnapshotReceivedAt()`

UnsetSnapshotReceivedAt ensures that no value is present for SnapshotReceivedAt, not even an explicit nil
### GetSnapshotEventId

`func (o *OperatorReplayJob) GetSnapshotEventId() string`

GetSnapshotEventId returns the SnapshotEventId field if non-nil, zero value otherwise.

### GetSnapshotEventIdOk

`func (o *OperatorReplayJob) GetSnapshotEventIdOk() (*string, bool)`

GetSnapshotEventIdOk returns a tuple with the SnapshotEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotEventId

`func (o *OperatorReplayJob) SetSnapshotEventId(v string)`

SetSnapshotEventId sets SnapshotEventId field to given value.


### SetSnapshotEventIdNil

`func (o *OperatorReplayJob) SetSnapshotEventIdNil(b bool)`

 SetSnapshotEventIdNil sets the value for SnapshotEventId to be an explicit nil

### UnsetSnapshotEventId
`func (o *OperatorReplayJob) UnsetSnapshotEventId()`

UnsetSnapshotEventId ensures that no value is present for SnapshotEventId, not even an explicit nil
### GetCursorReceivedAt

`func (o *OperatorReplayJob) GetCursorReceivedAt() time.Time`

GetCursorReceivedAt returns the CursorReceivedAt field if non-nil, zero value otherwise.

### GetCursorReceivedAtOk

`func (o *OperatorReplayJob) GetCursorReceivedAtOk() (*time.Time, bool)`

GetCursorReceivedAtOk returns a tuple with the CursorReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorReceivedAt

`func (o *OperatorReplayJob) SetCursorReceivedAt(v time.Time)`

SetCursorReceivedAt sets CursorReceivedAt field to given value.


### SetCursorReceivedAtNil

`func (o *OperatorReplayJob) SetCursorReceivedAtNil(b bool)`

 SetCursorReceivedAtNil sets the value for CursorReceivedAt to be an explicit nil

### UnsetCursorReceivedAt
`func (o *OperatorReplayJob) UnsetCursorReceivedAt()`

UnsetCursorReceivedAt ensures that no value is present for CursorReceivedAt, not even an explicit nil
### GetCursorEventId

`func (o *OperatorReplayJob) GetCursorEventId() string`

GetCursorEventId returns the CursorEventId field if non-nil, zero value otherwise.

### GetCursorEventIdOk

`func (o *OperatorReplayJob) GetCursorEventIdOk() (*string, bool)`

GetCursorEventIdOk returns a tuple with the CursorEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorEventId

`func (o *OperatorReplayJob) SetCursorEventId(v string)`

SetCursorEventId sets CursorEventId field to given value.


### SetCursorEventIdNil

`func (o *OperatorReplayJob) SetCursorEventIdNil(b bool)`

 SetCursorEventIdNil sets the value for CursorEventId to be an explicit nil

### UnsetCursorEventId
`func (o *OperatorReplayJob) UnsetCursorEventId()`

UnsetCursorEventId ensures that no value is present for CursorEventId, not even an explicit nil
### GetLockedAt

`func (o *OperatorReplayJob) GetLockedAt() time.Time`

GetLockedAt returns the LockedAt field if non-nil, zero value otherwise.

### GetLockedAtOk

`func (o *OperatorReplayJob) GetLockedAtOk() (*time.Time, bool)`

GetLockedAtOk returns a tuple with the LockedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockedAt

`func (o *OperatorReplayJob) SetLockedAt(v time.Time)`

SetLockedAt sets LockedAt field to given value.


### SetLockedAtNil

`func (o *OperatorReplayJob) SetLockedAtNil(b bool)`

 SetLockedAtNil sets the value for LockedAt to be an explicit nil

### UnsetLockedAt
`func (o *OperatorReplayJob) UnsetLockedAt()`

UnsetLockedAt ensures that no value is present for LockedAt, not even an explicit nil
### GetLockExpiresAt

`func (o *OperatorReplayJob) GetLockExpiresAt() time.Time`

GetLockExpiresAt returns the LockExpiresAt field if non-nil, zero value otherwise.

### GetLockExpiresAtOk

`func (o *OperatorReplayJob) GetLockExpiresAtOk() (*time.Time, bool)`

GetLockExpiresAtOk returns a tuple with the LockExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockExpiresAt

`func (o *OperatorReplayJob) SetLockExpiresAt(v time.Time)`

SetLockExpiresAt sets LockExpiresAt field to given value.


### SetLockExpiresAtNil

`func (o *OperatorReplayJob) SetLockExpiresAtNil(b bool)`

 SetLockExpiresAtNil sets the value for LockExpiresAt to be an explicit nil

### UnsetLockExpiresAt
`func (o *OperatorReplayJob) UnsetLockExpiresAt()`

UnsetLockExpiresAt ensures that no value is present for LockExpiresAt, not even an explicit nil
### GetLockedBy

`func (o *OperatorReplayJob) GetLockedBy() string`

GetLockedBy returns the LockedBy field if non-nil, zero value otherwise.

### GetLockedByOk

`func (o *OperatorReplayJob) GetLockedByOk() (*string, bool)`

GetLockedByOk returns a tuple with the LockedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockedBy

`func (o *OperatorReplayJob) SetLockedBy(v string)`

SetLockedBy sets LockedBy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


