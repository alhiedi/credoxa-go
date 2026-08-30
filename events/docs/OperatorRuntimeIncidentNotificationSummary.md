# OperatorRuntimeIncidentNotificationSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CapturedAt** | **time.Time** |  | 
**Counts** | **map[string]int32** |  | 
**OldestPending** | **map[string]interface{}** |  | 
**OldestFailed** | **map[string]interface{}** |  | 

## Methods

### NewOperatorRuntimeIncidentNotificationSummary

`func NewOperatorRuntimeIncidentNotificationSummary(capturedAt time.Time, counts map[string]int32, oldestPending map[string]interface{}, oldestFailed map[string]interface{}, ) *OperatorRuntimeIncidentNotificationSummary`

NewOperatorRuntimeIncidentNotificationSummary instantiates a new OperatorRuntimeIncidentNotificationSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentNotificationSummaryWithDefaults

`func NewOperatorRuntimeIncidentNotificationSummaryWithDefaults() *OperatorRuntimeIncidentNotificationSummary`

NewOperatorRuntimeIncidentNotificationSummaryWithDefaults instantiates a new OperatorRuntimeIncidentNotificationSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCapturedAt

`func (o *OperatorRuntimeIncidentNotificationSummary) GetCapturedAt() time.Time`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *OperatorRuntimeIncidentNotificationSummary) GetCapturedAtOk() (*time.Time, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *OperatorRuntimeIncidentNotificationSummary) SetCapturedAt(v time.Time)`

SetCapturedAt sets CapturedAt field to given value.


### GetCounts

`func (o *OperatorRuntimeIncidentNotificationSummary) GetCounts() map[string]int32`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *OperatorRuntimeIncidentNotificationSummary) GetCountsOk() (*map[string]int32, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *OperatorRuntimeIncidentNotificationSummary) SetCounts(v map[string]int32)`

SetCounts sets Counts field to given value.


### GetOldestPending

`func (o *OperatorRuntimeIncidentNotificationSummary) GetOldestPending() map[string]interface{}`

GetOldestPending returns the OldestPending field if non-nil, zero value otherwise.

### GetOldestPendingOk

`func (o *OperatorRuntimeIncidentNotificationSummary) GetOldestPendingOk() (*map[string]interface{}, bool)`

GetOldestPendingOk returns a tuple with the OldestPending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldestPending

`func (o *OperatorRuntimeIncidentNotificationSummary) SetOldestPending(v map[string]interface{})`

SetOldestPending sets OldestPending field to given value.


### GetOldestFailed

`func (o *OperatorRuntimeIncidentNotificationSummary) GetOldestFailed() map[string]interface{}`

GetOldestFailed returns the OldestFailed field if non-nil, zero value otherwise.

### GetOldestFailedOk

`func (o *OperatorRuntimeIncidentNotificationSummary) GetOldestFailedOk() (*map[string]interface{}, bool)`

GetOldestFailedOk returns a tuple with the OldestFailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldestFailed

`func (o *OperatorRuntimeIncidentNotificationSummary) SetOldestFailed(v map[string]interface{})`

SetOldestFailed sets OldestFailed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


