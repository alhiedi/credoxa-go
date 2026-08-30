# ReplayDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** | Tenant that owns the replay and historical events. | [readonly] 
**TargetConsumer** | [**ReplayConsumer**](ReplayConsumer.md) |  | [readonly] 
**Status** | [**ReplayDetailStatusEnum**](ReplayDetailStatusEnum.md) |  | [readonly] 
**RequestedBy** | **string** |  | [readonly] 
**Reason** | **string** |  | [readonly] 
**EventTypes** | **interface{}** | Optional event type names. An empty list matches all event types. | [readonly] 
**Sources** | **interface{}** | Optional producer source names. An empty list matches all sources. | [readonly] 
**SubjectPrefix** | **string** |  | [readonly] 
**OccurredFrom** | **NullableTime** |  | [readonly] 
**OccurredUntil** | **NullableTime** |  | [readonly] 
**ReceivedFrom** | **NullableTime** |  | [readonly] 
**ReceivedUntil** | **NullableTime** |  | [readonly] 
**BatchSize** | **int32** |  | [readonly] 
**SnapshotCreatedAt** | **NullableTime** | Time at which the immutable replay snapshot was captured. | [readonly] 
**SnapshotReceivedAt** | **NullableTime** |  | [readonly] 
**SnapshotEventId** | **NullableString** |  | [readonly] 
**TotalEvents** | **NullableInt32** |  | [readonly] 
**ProcessedEvents** | **int32** |  | [readonly] 
**PublishedEvents** | **int32** |  | [readonly] 
**FailedEvents** | **int32** |  | [readonly] 
**CursorReceivedAt** | **NullableTime** |  | [readonly] 
**CursorEventId** | **NullableString** |  | [readonly] 
**FailureCode** | **string** |  | [readonly] 
**FailureReason** | **string** |  | [readonly] 
**StartedAt** | **NullableTime** |  | [readonly] 
**PausedAt** | **NullableTime** |  | [readonly] 
**CancelRequestedAt** | **NullableTime** |  | [readonly] 
**CancelledAt** | **NullableTime** |  | [readonly] 
**CompletedAt** | **NullableTime** |  | [readonly] 
**FailedAt** | **NullableTime** |  | [readonly] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**ProgressPercentage** | **float64** |  | [readonly] 
**IsTerminal** | **bool** |  | [readonly] 
**IsCancellable** | **bool** |  | [readonly] 
**IsPauseable** | **bool** |  | [readonly] 
**IsResumable** | **bool** |  | [readonly] 
**IsRetryable** | **bool** |  | [readonly] 

## Methods

### NewReplayDetail

`func NewReplayDetail(id string, organizationId string, targetConsumer ReplayConsumer, status ReplayDetailStatusEnum, requestedBy string, reason string, eventTypes interface{}, sources interface{}, subjectPrefix string, occurredFrom NullableTime, occurredUntil NullableTime, receivedFrom NullableTime, receivedUntil NullableTime, batchSize int32, snapshotCreatedAt NullableTime, snapshotReceivedAt NullableTime, snapshotEventId NullableString, totalEvents NullableInt32, processedEvents int32, publishedEvents int32, failedEvents int32, cursorReceivedAt NullableTime, cursorEventId NullableString, failureCode string, failureReason string, startedAt NullableTime, pausedAt NullableTime, cancelRequestedAt NullableTime, cancelledAt NullableTime, completedAt NullableTime, failedAt NullableTime, createdAt time.Time, updatedAt time.Time, progressPercentage float64, isTerminal bool, isCancellable bool, isPauseable bool, isResumable bool, isRetryable bool, ) *ReplayDetail`

NewReplayDetail instantiates a new ReplayDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReplayDetailWithDefaults

`func NewReplayDetailWithDefaults() *ReplayDetail`

NewReplayDetailWithDefaults instantiates a new ReplayDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReplayDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReplayDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReplayDetail) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *ReplayDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ReplayDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ReplayDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTargetConsumer

`func (o *ReplayDetail) GetTargetConsumer() ReplayConsumer`

GetTargetConsumer returns the TargetConsumer field if non-nil, zero value otherwise.

### GetTargetConsumerOk

`func (o *ReplayDetail) GetTargetConsumerOk() (*ReplayConsumer, bool)`

GetTargetConsumerOk returns a tuple with the TargetConsumer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetConsumer

`func (o *ReplayDetail) SetTargetConsumer(v ReplayConsumer)`

SetTargetConsumer sets TargetConsumer field to given value.


### GetStatus

`func (o *ReplayDetail) GetStatus() ReplayDetailStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReplayDetail) GetStatusOk() (*ReplayDetailStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReplayDetail) SetStatus(v ReplayDetailStatusEnum)`

SetStatus sets Status field to given value.


### GetRequestedBy

`func (o *ReplayDetail) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *ReplayDetail) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *ReplayDetail) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetReason

`func (o *ReplayDetail) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ReplayDetail) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ReplayDetail) SetReason(v string)`

SetReason sets Reason field to given value.


### GetEventTypes

`func (o *ReplayDetail) GetEventTypes() interface{}`

GetEventTypes returns the EventTypes field if non-nil, zero value otherwise.

### GetEventTypesOk

`func (o *ReplayDetail) GetEventTypesOk() (*interface{}, bool)`

GetEventTypesOk returns a tuple with the EventTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypes

`func (o *ReplayDetail) SetEventTypes(v interface{})`

SetEventTypes sets EventTypes field to given value.


### SetEventTypesNil

`func (o *ReplayDetail) SetEventTypesNil(b bool)`

 SetEventTypesNil sets the value for EventTypes to be an explicit nil

### UnsetEventTypes
`func (o *ReplayDetail) UnsetEventTypes()`

UnsetEventTypes ensures that no value is present for EventTypes, not even an explicit nil
### GetSources

`func (o *ReplayDetail) GetSources() interface{}`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ReplayDetail) GetSourcesOk() (*interface{}, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ReplayDetail) SetSources(v interface{})`

SetSources sets Sources field to given value.


### SetSourcesNil

`func (o *ReplayDetail) SetSourcesNil(b bool)`

 SetSourcesNil sets the value for Sources to be an explicit nil

### UnsetSources
`func (o *ReplayDetail) UnsetSources()`

UnsetSources ensures that no value is present for Sources, not even an explicit nil
### GetSubjectPrefix

`func (o *ReplayDetail) GetSubjectPrefix() string`

GetSubjectPrefix returns the SubjectPrefix field if non-nil, zero value otherwise.

### GetSubjectPrefixOk

`func (o *ReplayDetail) GetSubjectPrefixOk() (*string, bool)`

GetSubjectPrefixOk returns a tuple with the SubjectPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectPrefix

`func (o *ReplayDetail) SetSubjectPrefix(v string)`

SetSubjectPrefix sets SubjectPrefix field to given value.


### GetOccurredFrom

`func (o *ReplayDetail) GetOccurredFrom() time.Time`

GetOccurredFrom returns the OccurredFrom field if non-nil, zero value otherwise.

### GetOccurredFromOk

`func (o *ReplayDetail) GetOccurredFromOk() (*time.Time, bool)`

GetOccurredFromOk returns a tuple with the OccurredFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredFrom

`func (o *ReplayDetail) SetOccurredFrom(v time.Time)`

SetOccurredFrom sets OccurredFrom field to given value.


### SetOccurredFromNil

`func (o *ReplayDetail) SetOccurredFromNil(b bool)`

 SetOccurredFromNil sets the value for OccurredFrom to be an explicit nil

### UnsetOccurredFrom
`func (o *ReplayDetail) UnsetOccurredFrom()`

UnsetOccurredFrom ensures that no value is present for OccurredFrom, not even an explicit nil
### GetOccurredUntil

`func (o *ReplayDetail) GetOccurredUntil() time.Time`

GetOccurredUntil returns the OccurredUntil field if non-nil, zero value otherwise.

### GetOccurredUntilOk

`func (o *ReplayDetail) GetOccurredUntilOk() (*time.Time, bool)`

GetOccurredUntilOk returns a tuple with the OccurredUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredUntil

`func (o *ReplayDetail) SetOccurredUntil(v time.Time)`

SetOccurredUntil sets OccurredUntil field to given value.


### SetOccurredUntilNil

`func (o *ReplayDetail) SetOccurredUntilNil(b bool)`

 SetOccurredUntilNil sets the value for OccurredUntil to be an explicit nil

### UnsetOccurredUntil
`func (o *ReplayDetail) UnsetOccurredUntil()`

UnsetOccurredUntil ensures that no value is present for OccurredUntil, not even an explicit nil
### GetReceivedFrom

`func (o *ReplayDetail) GetReceivedFrom() time.Time`

GetReceivedFrom returns the ReceivedFrom field if non-nil, zero value otherwise.

### GetReceivedFromOk

`func (o *ReplayDetail) GetReceivedFromOk() (*time.Time, bool)`

GetReceivedFromOk returns a tuple with the ReceivedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedFrom

`func (o *ReplayDetail) SetReceivedFrom(v time.Time)`

SetReceivedFrom sets ReceivedFrom field to given value.


### SetReceivedFromNil

`func (o *ReplayDetail) SetReceivedFromNil(b bool)`

 SetReceivedFromNil sets the value for ReceivedFrom to be an explicit nil

### UnsetReceivedFrom
`func (o *ReplayDetail) UnsetReceivedFrom()`

UnsetReceivedFrom ensures that no value is present for ReceivedFrom, not even an explicit nil
### GetReceivedUntil

`func (o *ReplayDetail) GetReceivedUntil() time.Time`

GetReceivedUntil returns the ReceivedUntil field if non-nil, zero value otherwise.

### GetReceivedUntilOk

`func (o *ReplayDetail) GetReceivedUntilOk() (*time.Time, bool)`

GetReceivedUntilOk returns a tuple with the ReceivedUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedUntil

`func (o *ReplayDetail) SetReceivedUntil(v time.Time)`

SetReceivedUntil sets ReceivedUntil field to given value.


### SetReceivedUntilNil

`func (o *ReplayDetail) SetReceivedUntilNil(b bool)`

 SetReceivedUntilNil sets the value for ReceivedUntil to be an explicit nil

### UnsetReceivedUntil
`func (o *ReplayDetail) UnsetReceivedUntil()`

UnsetReceivedUntil ensures that no value is present for ReceivedUntil, not even an explicit nil
### GetBatchSize

`func (o *ReplayDetail) GetBatchSize() int32`

GetBatchSize returns the BatchSize field if non-nil, zero value otherwise.

### GetBatchSizeOk

`func (o *ReplayDetail) GetBatchSizeOk() (*int32, bool)`

GetBatchSizeOk returns a tuple with the BatchSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchSize

`func (o *ReplayDetail) SetBatchSize(v int32)`

SetBatchSize sets BatchSize field to given value.


### GetSnapshotCreatedAt

`func (o *ReplayDetail) GetSnapshotCreatedAt() time.Time`

GetSnapshotCreatedAt returns the SnapshotCreatedAt field if non-nil, zero value otherwise.

### GetSnapshotCreatedAtOk

`func (o *ReplayDetail) GetSnapshotCreatedAtOk() (*time.Time, bool)`

GetSnapshotCreatedAtOk returns a tuple with the SnapshotCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotCreatedAt

`func (o *ReplayDetail) SetSnapshotCreatedAt(v time.Time)`

SetSnapshotCreatedAt sets SnapshotCreatedAt field to given value.


### SetSnapshotCreatedAtNil

`func (o *ReplayDetail) SetSnapshotCreatedAtNil(b bool)`

 SetSnapshotCreatedAtNil sets the value for SnapshotCreatedAt to be an explicit nil

### UnsetSnapshotCreatedAt
`func (o *ReplayDetail) UnsetSnapshotCreatedAt()`

UnsetSnapshotCreatedAt ensures that no value is present for SnapshotCreatedAt, not even an explicit nil
### GetSnapshotReceivedAt

`func (o *ReplayDetail) GetSnapshotReceivedAt() time.Time`

GetSnapshotReceivedAt returns the SnapshotReceivedAt field if non-nil, zero value otherwise.

### GetSnapshotReceivedAtOk

`func (o *ReplayDetail) GetSnapshotReceivedAtOk() (*time.Time, bool)`

GetSnapshotReceivedAtOk returns a tuple with the SnapshotReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotReceivedAt

`func (o *ReplayDetail) SetSnapshotReceivedAt(v time.Time)`

SetSnapshotReceivedAt sets SnapshotReceivedAt field to given value.


### SetSnapshotReceivedAtNil

`func (o *ReplayDetail) SetSnapshotReceivedAtNil(b bool)`

 SetSnapshotReceivedAtNil sets the value for SnapshotReceivedAt to be an explicit nil

### UnsetSnapshotReceivedAt
`func (o *ReplayDetail) UnsetSnapshotReceivedAt()`

UnsetSnapshotReceivedAt ensures that no value is present for SnapshotReceivedAt, not even an explicit nil
### GetSnapshotEventId

`func (o *ReplayDetail) GetSnapshotEventId() string`

GetSnapshotEventId returns the SnapshotEventId field if non-nil, zero value otherwise.

### GetSnapshotEventIdOk

`func (o *ReplayDetail) GetSnapshotEventIdOk() (*string, bool)`

GetSnapshotEventIdOk returns a tuple with the SnapshotEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotEventId

`func (o *ReplayDetail) SetSnapshotEventId(v string)`

SetSnapshotEventId sets SnapshotEventId field to given value.


### SetSnapshotEventIdNil

`func (o *ReplayDetail) SetSnapshotEventIdNil(b bool)`

 SetSnapshotEventIdNil sets the value for SnapshotEventId to be an explicit nil

### UnsetSnapshotEventId
`func (o *ReplayDetail) UnsetSnapshotEventId()`

UnsetSnapshotEventId ensures that no value is present for SnapshotEventId, not even an explicit nil
### GetTotalEvents

`func (o *ReplayDetail) GetTotalEvents() int32`

GetTotalEvents returns the TotalEvents field if non-nil, zero value otherwise.

### GetTotalEventsOk

`func (o *ReplayDetail) GetTotalEventsOk() (*int32, bool)`

GetTotalEventsOk returns a tuple with the TotalEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalEvents

`func (o *ReplayDetail) SetTotalEvents(v int32)`

SetTotalEvents sets TotalEvents field to given value.


### SetTotalEventsNil

`func (o *ReplayDetail) SetTotalEventsNil(b bool)`

 SetTotalEventsNil sets the value for TotalEvents to be an explicit nil

### UnsetTotalEvents
`func (o *ReplayDetail) UnsetTotalEvents()`

UnsetTotalEvents ensures that no value is present for TotalEvents, not even an explicit nil
### GetProcessedEvents

`func (o *ReplayDetail) GetProcessedEvents() int32`

GetProcessedEvents returns the ProcessedEvents field if non-nil, zero value otherwise.

### GetProcessedEventsOk

`func (o *ReplayDetail) GetProcessedEventsOk() (*int32, bool)`

GetProcessedEventsOk returns a tuple with the ProcessedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedEvents

`func (o *ReplayDetail) SetProcessedEvents(v int32)`

SetProcessedEvents sets ProcessedEvents field to given value.


### GetPublishedEvents

`func (o *ReplayDetail) GetPublishedEvents() int32`

GetPublishedEvents returns the PublishedEvents field if non-nil, zero value otherwise.

### GetPublishedEventsOk

`func (o *ReplayDetail) GetPublishedEventsOk() (*int32, bool)`

GetPublishedEventsOk returns a tuple with the PublishedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedEvents

`func (o *ReplayDetail) SetPublishedEvents(v int32)`

SetPublishedEvents sets PublishedEvents field to given value.


### GetFailedEvents

`func (o *ReplayDetail) GetFailedEvents() int32`

GetFailedEvents returns the FailedEvents field if non-nil, zero value otherwise.

### GetFailedEventsOk

`func (o *ReplayDetail) GetFailedEventsOk() (*int32, bool)`

GetFailedEventsOk returns a tuple with the FailedEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedEvents

`func (o *ReplayDetail) SetFailedEvents(v int32)`

SetFailedEvents sets FailedEvents field to given value.


### GetCursorReceivedAt

`func (o *ReplayDetail) GetCursorReceivedAt() time.Time`

GetCursorReceivedAt returns the CursorReceivedAt field if non-nil, zero value otherwise.

### GetCursorReceivedAtOk

`func (o *ReplayDetail) GetCursorReceivedAtOk() (*time.Time, bool)`

GetCursorReceivedAtOk returns a tuple with the CursorReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorReceivedAt

`func (o *ReplayDetail) SetCursorReceivedAt(v time.Time)`

SetCursorReceivedAt sets CursorReceivedAt field to given value.


### SetCursorReceivedAtNil

`func (o *ReplayDetail) SetCursorReceivedAtNil(b bool)`

 SetCursorReceivedAtNil sets the value for CursorReceivedAt to be an explicit nil

### UnsetCursorReceivedAt
`func (o *ReplayDetail) UnsetCursorReceivedAt()`

UnsetCursorReceivedAt ensures that no value is present for CursorReceivedAt, not even an explicit nil
### GetCursorEventId

`func (o *ReplayDetail) GetCursorEventId() string`

GetCursorEventId returns the CursorEventId field if non-nil, zero value otherwise.

### GetCursorEventIdOk

`func (o *ReplayDetail) GetCursorEventIdOk() (*string, bool)`

GetCursorEventIdOk returns a tuple with the CursorEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorEventId

`func (o *ReplayDetail) SetCursorEventId(v string)`

SetCursorEventId sets CursorEventId field to given value.


### SetCursorEventIdNil

`func (o *ReplayDetail) SetCursorEventIdNil(b bool)`

 SetCursorEventIdNil sets the value for CursorEventId to be an explicit nil

### UnsetCursorEventId
`func (o *ReplayDetail) UnsetCursorEventId()`

UnsetCursorEventId ensures that no value is present for CursorEventId, not even an explicit nil
### GetFailureCode

`func (o *ReplayDetail) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *ReplayDetail) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *ReplayDetail) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.


### GetFailureReason

`func (o *ReplayDetail) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *ReplayDetail) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *ReplayDetail) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.


### GetStartedAt

`func (o *ReplayDetail) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *ReplayDetail) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *ReplayDetail) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *ReplayDetail) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *ReplayDetail) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetPausedAt

`func (o *ReplayDetail) GetPausedAt() time.Time`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *ReplayDetail) GetPausedAtOk() (*time.Time, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *ReplayDetail) SetPausedAt(v time.Time)`

SetPausedAt sets PausedAt field to given value.


### SetPausedAtNil

`func (o *ReplayDetail) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *ReplayDetail) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetCancelRequestedAt

`func (o *ReplayDetail) GetCancelRequestedAt() time.Time`

GetCancelRequestedAt returns the CancelRequestedAt field if non-nil, zero value otherwise.

### GetCancelRequestedAtOk

`func (o *ReplayDetail) GetCancelRequestedAtOk() (*time.Time, bool)`

GetCancelRequestedAtOk returns a tuple with the CancelRequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelRequestedAt

`func (o *ReplayDetail) SetCancelRequestedAt(v time.Time)`

SetCancelRequestedAt sets CancelRequestedAt field to given value.


### SetCancelRequestedAtNil

`func (o *ReplayDetail) SetCancelRequestedAtNil(b bool)`

 SetCancelRequestedAtNil sets the value for CancelRequestedAt to be an explicit nil

### UnsetCancelRequestedAt
`func (o *ReplayDetail) UnsetCancelRequestedAt()`

UnsetCancelRequestedAt ensures that no value is present for CancelRequestedAt, not even an explicit nil
### GetCancelledAt

`func (o *ReplayDetail) GetCancelledAt() time.Time`

GetCancelledAt returns the CancelledAt field if non-nil, zero value otherwise.

### GetCancelledAtOk

`func (o *ReplayDetail) GetCancelledAtOk() (*time.Time, bool)`

GetCancelledAtOk returns a tuple with the CancelledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelledAt

`func (o *ReplayDetail) SetCancelledAt(v time.Time)`

SetCancelledAt sets CancelledAt field to given value.


### SetCancelledAtNil

`func (o *ReplayDetail) SetCancelledAtNil(b bool)`

 SetCancelledAtNil sets the value for CancelledAt to be an explicit nil

### UnsetCancelledAt
`func (o *ReplayDetail) UnsetCancelledAt()`

UnsetCancelledAt ensures that no value is present for CancelledAt, not even an explicit nil
### GetCompletedAt

`func (o *ReplayDetail) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ReplayDetail) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ReplayDetail) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *ReplayDetail) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ReplayDetail) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetFailedAt

`func (o *ReplayDetail) GetFailedAt() time.Time`

GetFailedAt returns the FailedAt field if non-nil, zero value otherwise.

### GetFailedAtOk

`func (o *ReplayDetail) GetFailedAtOk() (*time.Time, bool)`

GetFailedAtOk returns a tuple with the FailedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedAt

`func (o *ReplayDetail) SetFailedAt(v time.Time)`

SetFailedAt sets FailedAt field to given value.


### SetFailedAtNil

`func (o *ReplayDetail) SetFailedAtNil(b bool)`

 SetFailedAtNil sets the value for FailedAt to be an explicit nil

### UnsetFailedAt
`func (o *ReplayDetail) UnsetFailedAt()`

UnsetFailedAt ensures that no value is present for FailedAt, not even an explicit nil
### GetCreatedAt

`func (o *ReplayDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReplayDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReplayDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ReplayDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ReplayDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ReplayDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetProgressPercentage

`func (o *ReplayDetail) GetProgressPercentage() float64`

GetProgressPercentage returns the ProgressPercentage field if non-nil, zero value otherwise.

### GetProgressPercentageOk

`func (o *ReplayDetail) GetProgressPercentageOk() (*float64, bool)`

GetProgressPercentageOk returns a tuple with the ProgressPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressPercentage

`func (o *ReplayDetail) SetProgressPercentage(v float64)`

SetProgressPercentage sets ProgressPercentage field to given value.


### GetIsTerminal

`func (o *ReplayDetail) GetIsTerminal() bool`

GetIsTerminal returns the IsTerminal field if non-nil, zero value otherwise.

### GetIsTerminalOk

`func (o *ReplayDetail) GetIsTerminalOk() (*bool, bool)`

GetIsTerminalOk returns a tuple with the IsTerminal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTerminal

`func (o *ReplayDetail) SetIsTerminal(v bool)`

SetIsTerminal sets IsTerminal field to given value.


### GetIsCancellable

`func (o *ReplayDetail) GetIsCancellable() bool`

GetIsCancellable returns the IsCancellable field if non-nil, zero value otherwise.

### GetIsCancellableOk

`func (o *ReplayDetail) GetIsCancellableOk() (*bool, bool)`

GetIsCancellableOk returns a tuple with the IsCancellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCancellable

`func (o *ReplayDetail) SetIsCancellable(v bool)`

SetIsCancellable sets IsCancellable field to given value.


### GetIsPauseable

`func (o *ReplayDetail) GetIsPauseable() bool`

GetIsPauseable returns the IsPauseable field if non-nil, zero value otherwise.

### GetIsPauseableOk

`func (o *ReplayDetail) GetIsPauseableOk() (*bool, bool)`

GetIsPauseableOk returns a tuple with the IsPauseable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPauseable

`func (o *ReplayDetail) SetIsPauseable(v bool)`

SetIsPauseable sets IsPauseable field to given value.


### GetIsResumable

`func (o *ReplayDetail) GetIsResumable() bool`

GetIsResumable returns the IsResumable field if non-nil, zero value otherwise.

### GetIsResumableOk

`func (o *ReplayDetail) GetIsResumableOk() (*bool, bool)`

GetIsResumableOk returns a tuple with the IsResumable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsResumable

`func (o *ReplayDetail) SetIsResumable(v bool)`

SetIsResumable sets IsResumable field to given value.


### GetIsRetryable

`func (o *ReplayDetail) GetIsRetryable() bool`

GetIsRetryable returns the IsRetryable field if non-nil, zero value otherwise.

### GetIsRetryableOk

`func (o *ReplayDetail) GetIsRetryableOk() (*bool, bool)`

GetIsRetryableOk returns a tuple with the IsRetryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRetryable

`func (o *ReplayDetail) SetIsRetryable(v bool)`

SetIsRetryable sets IsRetryable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


