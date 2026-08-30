# LifecycleLegalHoldSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**Active** | **int32** |  | 
**Released** | **int32** |  | 
**StatusCounts** | **map[string]int32** |  | 
**OldestActiveCreatedAt** | **NullableTime** |  | 

## Methods

### NewLifecycleLegalHoldSummary

`func NewLifecycleLegalHoldSummary(total int32, active int32, released int32, statusCounts map[string]int32, oldestActiveCreatedAt NullableTime, ) *LifecycleLegalHoldSummary`

NewLifecycleLegalHoldSummary instantiates a new LifecycleLegalHoldSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleLegalHoldSummaryWithDefaults

`func NewLifecycleLegalHoldSummaryWithDefaults() *LifecycleLegalHoldSummary`

NewLifecycleLegalHoldSummaryWithDefaults instantiates a new LifecycleLegalHoldSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *LifecycleLegalHoldSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *LifecycleLegalHoldSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *LifecycleLegalHoldSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetActive

`func (o *LifecycleLegalHoldSummary) GetActive() int32`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *LifecycleLegalHoldSummary) GetActiveOk() (*int32, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *LifecycleLegalHoldSummary) SetActive(v int32)`

SetActive sets Active field to given value.


### GetReleased

`func (o *LifecycleLegalHoldSummary) GetReleased() int32`

GetReleased returns the Released field if non-nil, zero value otherwise.

### GetReleasedOk

`func (o *LifecycleLegalHoldSummary) GetReleasedOk() (*int32, bool)`

GetReleasedOk returns a tuple with the Released field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleased

`func (o *LifecycleLegalHoldSummary) SetReleased(v int32)`

SetReleased sets Released field to given value.


### GetStatusCounts

`func (o *LifecycleLegalHoldSummary) GetStatusCounts() map[string]int32`

GetStatusCounts returns the StatusCounts field if non-nil, zero value otherwise.

### GetStatusCountsOk

`func (o *LifecycleLegalHoldSummary) GetStatusCountsOk() (*map[string]int32, bool)`

GetStatusCountsOk returns a tuple with the StatusCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCounts

`func (o *LifecycleLegalHoldSummary) SetStatusCounts(v map[string]int32)`

SetStatusCounts sets StatusCounts field to given value.


### GetOldestActiveCreatedAt

`func (o *LifecycleLegalHoldSummary) GetOldestActiveCreatedAt() time.Time`

GetOldestActiveCreatedAt returns the OldestActiveCreatedAt field if non-nil, zero value otherwise.

### GetOldestActiveCreatedAtOk

`func (o *LifecycleLegalHoldSummary) GetOldestActiveCreatedAtOk() (*time.Time, bool)`

GetOldestActiveCreatedAtOk returns a tuple with the OldestActiveCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldestActiveCreatedAt

`func (o *LifecycleLegalHoldSummary) SetOldestActiveCreatedAt(v time.Time)`

SetOldestActiveCreatedAt sets OldestActiveCreatedAt field to given value.


### SetOldestActiveCreatedAtNil

`func (o *LifecycleLegalHoldSummary) SetOldestActiveCreatedAtNil(b bool)`

 SetOldestActiveCreatedAtNil sets the value for OldestActiveCreatedAt to be an explicit nil

### UnsetOldestActiveCreatedAt
`func (o *LifecycleLegalHoldSummary) UnsetOldestActiveCreatedAt()`

UnsetOldestActiveCreatedAt ensures that no value is present for OldestActiveCreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


