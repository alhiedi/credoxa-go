# OperatorRuntimeMetricsDeliveries

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
**StaleProcessing** | **int32** |  | 

## Methods

### NewOperatorRuntimeMetricsDeliveries

`func NewOperatorRuntimeMetricsDeliveries(pending int32, processing int32, retryScheduled int32, backlog int32, failed int32, deadLettered int32, exhausted int32, terminalFailures int32, staleProcessing int32, ) *OperatorRuntimeMetricsDeliveries`

NewOperatorRuntimeMetricsDeliveries instantiates a new OperatorRuntimeMetricsDeliveries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsDeliveriesWithDefaults

`func NewOperatorRuntimeMetricsDeliveriesWithDefaults() *OperatorRuntimeMetricsDeliveries`

NewOperatorRuntimeMetricsDeliveriesWithDefaults instantiates a new OperatorRuntimeMetricsDeliveries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPending

`func (o *OperatorRuntimeMetricsDeliveries) GetPending() int32`

GetPending returns the Pending field if non-nil, zero value otherwise.

### GetPendingOk

`func (o *OperatorRuntimeMetricsDeliveries) GetPendingOk() (*int32, bool)`

GetPendingOk returns a tuple with the Pending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPending

`func (o *OperatorRuntimeMetricsDeliveries) SetPending(v int32)`

SetPending sets Pending field to given value.


### GetProcessing

`func (o *OperatorRuntimeMetricsDeliveries) GetProcessing() int32`

GetProcessing returns the Processing field if non-nil, zero value otherwise.

### GetProcessingOk

`func (o *OperatorRuntimeMetricsDeliveries) GetProcessingOk() (*int32, bool)`

GetProcessingOk returns a tuple with the Processing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessing

`func (o *OperatorRuntimeMetricsDeliveries) SetProcessing(v int32)`

SetProcessing sets Processing field to given value.


### GetRetryScheduled

`func (o *OperatorRuntimeMetricsDeliveries) GetRetryScheduled() int32`

GetRetryScheduled returns the RetryScheduled field if non-nil, zero value otherwise.

### GetRetryScheduledOk

`func (o *OperatorRuntimeMetricsDeliveries) GetRetryScheduledOk() (*int32, bool)`

GetRetryScheduledOk returns a tuple with the RetryScheduled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryScheduled

`func (o *OperatorRuntimeMetricsDeliveries) SetRetryScheduled(v int32)`

SetRetryScheduled sets RetryScheduled field to given value.


### GetBacklog

`func (o *OperatorRuntimeMetricsDeliveries) GetBacklog() int32`

GetBacklog returns the Backlog field if non-nil, zero value otherwise.

### GetBacklogOk

`func (o *OperatorRuntimeMetricsDeliveries) GetBacklogOk() (*int32, bool)`

GetBacklogOk returns a tuple with the Backlog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBacklog

`func (o *OperatorRuntimeMetricsDeliveries) SetBacklog(v int32)`

SetBacklog sets Backlog field to given value.


### GetFailed

`func (o *OperatorRuntimeMetricsDeliveries) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *OperatorRuntimeMetricsDeliveries) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *OperatorRuntimeMetricsDeliveries) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetDeadLettered

`func (o *OperatorRuntimeMetricsDeliveries) GetDeadLettered() int32`

GetDeadLettered returns the DeadLettered field if non-nil, zero value otherwise.

### GetDeadLetteredOk

`func (o *OperatorRuntimeMetricsDeliveries) GetDeadLetteredOk() (*int32, bool)`

GetDeadLetteredOk returns a tuple with the DeadLettered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLettered

`func (o *OperatorRuntimeMetricsDeliveries) SetDeadLettered(v int32)`

SetDeadLettered sets DeadLettered field to given value.


### GetExhausted

`func (o *OperatorRuntimeMetricsDeliveries) GetExhausted() int32`

GetExhausted returns the Exhausted field if non-nil, zero value otherwise.

### GetExhaustedOk

`func (o *OperatorRuntimeMetricsDeliveries) GetExhaustedOk() (*int32, bool)`

GetExhaustedOk returns a tuple with the Exhausted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExhausted

`func (o *OperatorRuntimeMetricsDeliveries) SetExhausted(v int32)`

SetExhausted sets Exhausted field to given value.


### GetTerminalFailures

`func (o *OperatorRuntimeMetricsDeliveries) GetTerminalFailures() int32`

GetTerminalFailures returns the TerminalFailures field if non-nil, zero value otherwise.

### GetTerminalFailuresOk

`func (o *OperatorRuntimeMetricsDeliveries) GetTerminalFailuresOk() (*int32, bool)`

GetTerminalFailuresOk returns a tuple with the TerminalFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerminalFailures

`func (o *OperatorRuntimeMetricsDeliveries) SetTerminalFailures(v int32)`

SetTerminalFailures sets TerminalFailures field to given value.


### GetStaleProcessing

`func (o *OperatorRuntimeMetricsDeliveries) GetStaleProcessing() int32`

GetStaleProcessing returns the StaleProcessing field if non-nil, zero value otherwise.

### GetStaleProcessingOk

`func (o *OperatorRuntimeMetricsDeliveries) GetStaleProcessingOk() (*int32, bool)`

GetStaleProcessingOk returns a tuple with the StaleProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaleProcessing

`func (o *OperatorRuntimeMetricsDeliveries) SetStaleProcessing(v int32)`

SetStaleProcessing sets StaleProcessing field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


