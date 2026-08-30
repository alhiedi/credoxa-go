# OperatorRuntimeDeliveries

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pending** | **int32** |  | 
**Processing** | **int32** |  | 
**RetryScheduled** | **int32** |  | 
**Backlog** | **int32** |  | 
**Failed** | **int32** |  | 
**DeadLettered** | **int32** |  | 
**Exhausted** | **int32** |  | 
**TerminalFailures** | **int32** |  | 
**Locked** | **int32** |  | 
**StaleProcessing** | **int32** |  | 
**OldestPendingAt** | **NullableTime** |  | 
**ObservedAt** | **NullableTime** |  | 

## Methods

### NewOperatorRuntimeDeliveries

`func NewOperatorRuntimeDeliveries(pending int32, processing int32, retryScheduled int32, backlog int32, failed int32, deadLettered int32, exhausted int32, terminalFailures int32, locked int32, staleProcessing int32, oldestPendingAt NullableTime, observedAt NullableTime, ) *OperatorRuntimeDeliveries`

NewOperatorRuntimeDeliveries instantiates a new OperatorRuntimeDeliveries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeDeliveriesWithDefaults

`func NewOperatorRuntimeDeliveriesWithDefaults() *OperatorRuntimeDeliveries`

NewOperatorRuntimeDeliveriesWithDefaults instantiates a new OperatorRuntimeDeliveries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPending

`func (o *OperatorRuntimeDeliveries) GetPending() int32`

GetPending returns the Pending field if non-nil, zero value otherwise.

### GetPendingOk

`func (o *OperatorRuntimeDeliveries) GetPendingOk() (*int32, bool)`

GetPendingOk returns a tuple with the Pending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPending

`func (o *OperatorRuntimeDeliveries) SetPending(v int32)`

SetPending sets Pending field to given value.


### GetProcessing

`func (o *OperatorRuntimeDeliveries) GetProcessing() int32`

GetProcessing returns the Processing field if non-nil, zero value otherwise.

### GetProcessingOk

`func (o *OperatorRuntimeDeliveries) GetProcessingOk() (*int32, bool)`

GetProcessingOk returns a tuple with the Processing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessing

`func (o *OperatorRuntimeDeliveries) SetProcessing(v int32)`

SetProcessing sets Processing field to given value.


### GetRetryScheduled

`func (o *OperatorRuntimeDeliveries) GetRetryScheduled() int32`

GetRetryScheduled returns the RetryScheduled field if non-nil, zero value otherwise.

### GetRetryScheduledOk

`func (o *OperatorRuntimeDeliveries) GetRetryScheduledOk() (*int32, bool)`

GetRetryScheduledOk returns a tuple with the RetryScheduled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryScheduled

`func (o *OperatorRuntimeDeliveries) SetRetryScheduled(v int32)`

SetRetryScheduled sets RetryScheduled field to given value.


### GetBacklog

`func (o *OperatorRuntimeDeliveries) GetBacklog() int32`

GetBacklog returns the Backlog field if non-nil, zero value otherwise.

### GetBacklogOk

`func (o *OperatorRuntimeDeliveries) GetBacklogOk() (*int32, bool)`

GetBacklogOk returns a tuple with the Backlog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBacklog

`func (o *OperatorRuntimeDeliveries) SetBacklog(v int32)`

SetBacklog sets Backlog field to given value.


### GetFailed

`func (o *OperatorRuntimeDeliveries) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *OperatorRuntimeDeliveries) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *OperatorRuntimeDeliveries) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetDeadLettered

`func (o *OperatorRuntimeDeliveries) GetDeadLettered() int32`

GetDeadLettered returns the DeadLettered field if non-nil, zero value otherwise.

### GetDeadLetteredOk

`func (o *OperatorRuntimeDeliveries) GetDeadLetteredOk() (*int32, bool)`

GetDeadLetteredOk returns a tuple with the DeadLettered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLettered

`func (o *OperatorRuntimeDeliveries) SetDeadLettered(v int32)`

SetDeadLettered sets DeadLettered field to given value.


### GetExhausted

`func (o *OperatorRuntimeDeliveries) GetExhausted() int32`

GetExhausted returns the Exhausted field if non-nil, zero value otherwise.

### GetExhaustedOk

`func (o *OperatorRuntimeDeliveries) GetExhaustedOk() (*int32, bool)`

GetExhaustedOk returns a tuple with the Exhausted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExhausted

`func (o *OperatorRuntimeDeliveries) SetExhausted(v int32)`

SetExhausted sets Exhausted field to given value.


### GetTerminalFailures

`func (o *OperatorRuntimeDeliveries) GetTerminalFailures() int32`

GetTerminalFailures returns the TerminalFailures field if non-nil, zero value otherwise.

### GetTerminalFailuresOk

`func (o *OperatorRuntimeDeliveries) GetTerminalFailuresOk() (*int32, bool)`

GetTerminalFailuresOk returns a tuple with the TerminalFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerminalFailures

`func (o *OperatorRuntimeDeliveries) SetTerminalFailures(v int32)`

SetTerminalFailures sets TerminalFailures field to given value.


### GetLocked

`func (o *OperatorRuntimeDeliveries) GetLocked() int32`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *OperatorRuntimeDeliveries) GetLockedOk() (*int32, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *OperatorRuntimeDeliveries) SetLocked(v int32)`

SetLocked sets Locked field to given value.


### GetStaleProcessing

`func (o *OperatorRuntimeDeliveries) GetStaleProcessing() int32`

GetStaleProcessing returns the StaleProcessing field if non-nil, zero value otherwise.

### GetStaleProcessingOk

`func (o *OperatorRuntimeDeliveries) GetStaleProcessingOk() (*int32, bool)`

GetStaleProcessingOk returns a tuple with the StaleProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaleProcessing

`func (o *OperatorRuntimeDeliveries) SetStaleProcessing(v int32)`

SetStaleProcessing sets StaleProcessing field to given value.


### GetOldestPendingAt

`func (o *OperatorRuntimeDeliveries) GetOldestPendingAt() time.Time`

GetOldestPendingAt returns the OldestPendingAt field if non-nil, zero value otherwise.

### GetOldestPendingAtOk

`func (o *OperatorRuntimeDeliveries) GetOldestPendingAtOk() (*time.Time, bool)`

GetOldestPendingAtOk returns a tuple with the OldestPendingAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldestPendingAt

`func (o *OperatorRuntimeDeliveries) SetOldestPendingAt(v time.Time)`

SetOldestPendingAt sets OldestPendingAt field to given value.


### SetOldestPendingAtNil

`func (o *OperatorRuntimeDeliveries) SetOldestPendingAtNil(b bool)`

 SetOldestPendingAtNil sets the value for OldestPendingAt to be an explicit nil

### UnsetOldestPendingAt
`func (o *OperatorRuntimeDeliveries) UnsetOldestPendingAt()`

UnsetOldestPendingAt ensures that no value is present for OldestPendingAt, not even an explicit nil
### GetObservedAt

`func (o *OperatorRuntimeDeliveries) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *OperatorRuntimeDeliveries) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *OperatorRuntimeDeliveries) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### SetObservedAtNil

`func (o *OperatorRuntimeDeliveries) SetObservedAtNil(b bool)`

 SetObservedAtNil sets the value for ObservedAt to be an explicit nil

### UnsetObservedAt
`func (o *OperatorRuntimeDeliveries) UnsetObservedAt()`

UnsetObservedAt ensures that no value is present for ObservedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


