# OperatorConsumerDeliverySummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**Counts** | **map[string]int32** |  | 
**Backlog** | **int32** |  | 
**RetryBacklog** | **int32** |  | 
**ExhaustedFailures** | **int32** |  | 
**Locked** | **int32** |  | 

## Methods

### NewOperatorConsumerDeliverySummary

`func NewOperatorConsumerDeliverySummary(total int32, counts map[string]int32, backlog int32, retryBacklog int32, exhaustedFailures int32, locked int32, ) *OperatorConsumerDeliverySummary`

NewOperatorConsumerDeliverySummary instantiates a new OperatorConsumerDeliverySummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerDeliverySummaryWithDefaults

`func NewOperatorConsumerDeliverySummaryWithDefaults() *OperatorConsumerDeliverySummary`

NewOperatorConsumerDeliverySummaryWithDefaults instantiates a new OperatorConsumerDeliverySummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OperatorConsumerDeliverySummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OperatorConsumerDeliverySummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OperatorConsumerDeliverySummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetCounts

`func (o *OperatorConsumerDeliverySummary) GetCounts() map[string]int32`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *OperatorConsumerDeliverySummary) GetCountsOk() (*map[string]int32, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *OperatorConsumerDeliverySummary) SetCounts(v map[string]int32)`

SetCounts sets Counts field to given value.


### GetBacklog

`func (o *OperatorConsumerDeliverySummary) GetBacklog() int32`

GetBacklog returns the Backlog field if non-nil, zero value otherwise.

### GetBacklogOk

`func (o *OperatorConsumerDeliverySummary) GetBacklogOk() (*int32, bool)`

GetBacklogOk returns a tuple with the Backlog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBacklog

`func (o *OperatorConsumerDeliverySummary) SetBacklog(v int32)`

SetBacklog sets Backlog field to given value.


### GetRetryBacklog

`func (o *OperatorConsumerDeliverySummary) GetRetryBacklog() int32`

GetRetryBacklog returns the RetryBacklog field if non-nil, zero value otherwise.

### GetRetryBacklogOk

`func (o *OperatorConsumerDeliverySummary) GetRetryBacklogOk() (*int32, bool)`

GetRetryBacklogOk returns a tuple with the RetryBacklog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryBacklog

`func (o *OperatorConsumerDeliverySummary) SetRetryBacklog(v int32)`

SetRetryBacklog sets RetryBacklog field to given value.


### GetExhaustedFailures

`func (o *OperatorConsumerDeliverySummary) GetExhaustedFailures() int32`

GetExhaustedFailures returns the ExhaustedFailures field if non-nil, zero value otherwise.

### GetExhaustedFailuresOk

`func (o *OperatorConsumerDeliverySummary) GetExhaustedFailuresOk() (*int32, bool)`

GetExhaustedFailuresOk returns a tuple with the ExhaustedFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExhaustedFailures

`func (o *OperatorConsumerDeliverySummary) SetExhaustedFailures(v int32)`

SetExhaustedFailures sets ExhaustedFailures field to given value.


### GetLocked

`func (o *OperatorConsumerDeliverySummary) GetLocked() int32`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *OperatorConsumerDeliverySummary) GetLockedOk() (*int32, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *OperatorConsumerDeliverySummary) SetLocked(v int32)`

SetLocked sets Locked field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


