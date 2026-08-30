# OperatorArchiveSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**Counts** | **map[string]int32** |  | 
**Backlog** | **int32** |  | 
**RetryableFailures** | **int32** |  | 
**RecentFailures** | [**[]OperatorArchiveFailure**](OperatorArchiveFailure.md) |  | 

## Methods

### NewOperatorArchiveSummary

`func NewOperatorArchiveSummary(total int32, counts map[string]int32, backlog int32, retryableFailures int32, recentFailures []OperatorArchiveFailure, ) *OperatorArchiveSummary`

NewOperatorArchiveSummary instantiates a new OperatorArchiveSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorArchiveSummaryWithDefaults

`func NewOperatorArchiveSummaryWithDefaults() *OperatorArchiveSummary`

NewOperatorArchiveSummaryWithDefaults instantiates a new OperatorArchiveSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OperatorArchiveSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OperatorArchiveSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OperatorArchiveSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetCounts

`func (o *OperatorArchiveSummary) GetCounts() map[string]int32`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *OperatorArchiveSummary) GetCountsOk() (*map[string]int32, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *OperatorArchiveSummary) SetCounts(v map[string]int32)`

SetCounts sets Counts field to given value.


### GetBacklog

`func (o *OperatorArchiveSummary) GetBacklog() int32`

GetBacklog returns the Backlog field if non-nil, zero value otherwise.

### GetBacklogOk

`func (o *OperatorArchiveSummary) GetBacklogOk() (*int32, bool)`

GetBacklogOk returns a tuple with the Backlog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBacklog

`func (o *OperatorArchiveSummary) SetBacklog(v int32)`

SetBacklog sets Backlog field to given value.


### GetRetryableFailures

`func (o *OperatorArchiveSummary) GetRetryableFailures() int32`

GetRetryableFailures returns the RetryableFailures field if non-nil, zero value otherwise.

### GetRetryableFailuresOk

`func (o *OperatorArchiveSummary) GetRetryableFailuresOk() (*int32, bool)`

GetRetryableFailuresOk returns a tuple with the RetryableFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryableFailures

`func (o *OperatorArchiveSummary) SetRetryableFailures(v int32)`

SetRetryableFailures sets RetryableFailures field to given value.


### GetRecentFailures

`func (o *OperatorArchiveSummary) GetRecentFailures() []OperatorArchiveFailure`

GetRecentFailures returns the RecentFailures field if non-nil, zero value otherwise.

### GetRecentFailuresOk

`func (o *OperatorArchiveSummary) GetRecentFailuresOk() (*[]OperatorArchiveFailure, bool)`

GetRecentFailuresOk returns a tuple with the RecentFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentFailures

`func (o *OperatorArchiveSummary) SetRecentFailures(v []OperatorArchiveFailure)`

SetRecentFailures sets RecentFailures field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


