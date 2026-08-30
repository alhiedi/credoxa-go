# AnalyticsQueryRequestRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Projection** | [**AnalyticsProjectionSelectorRequest**](AnalyticsProjectionSelectorRequest.md) |  | 
**StartAt** | **time.Time** |  | 
**EndAt** | **time.Time** |  | 
**Metrics** | Pointer to **[]string** |  | [optional] 
**DimensionFilters** | Pointer to **interface{}** |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] [default to 100]
**Cursor** | Pointer to **string** |  | [optional] [default to ""]
**SortDirection** | Pointer to [**SortDirectionEnum**](SortDirectionEnum.md) |  | [optional] [default to SORTDIRECTIONENUM_ASCENDING]
**IncludeStale** | Pointer to **bool** |  | [optional] [default to false]
**MaximumStalenessSeconds** | Pointer to **int32** |  | [optional] [default to 900]
**BypassCache** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewAnalyticsQueryRequestRequest

`func NewAnalyticsQueryRequestRequest(projection AnalyticsProjectionSelectorRequest, startAt time.Time, endAt time.Time, ) *AnalyticsQueryRequestRequest`

NewAnalyticsQueryRequestRequest instantiates a new AnalyticsQueryRequestRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsQueryRequestRequestWithDefaults

`func NewAnalyticsQueryRequestRequestWithDefaults() *AnalyticsQueryRequestRequest`

NewAnalyticsQueryRequestRequestWithDefaults instantiates a new AnalyticsQueryRequestRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjection

`func (o *AnalyticsQueryRequestRequest) GetProjection() AnalyticsProjectionSelectorRequest`

GetProjection returns the Projection field if non-nil, zero value otherwise.

### GetProjectionOk

`func (o *AnalyticsQueryRequestRequest) GetProjectionOk() (*AnalyticsProjectionSelectorRequest, bool)`

GetProjectionOk returns a tuple with the Projection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjection

`func (o *AnalyticsQueryRequestRequest) SetProjection(v AnalyticsProjectionSelectorRequest)`

SetProjection sets Projection field to given value.


### GetStartAt

`func (o *AnalyticsQueryRequestRequest) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *AnalyticsQueryRequestRequest) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *AnalyticsQueryRequestRequest) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.


### GetEndAt

`func (o *AnalyticsQueryRequestRequest) GetEndAt() time.Time`

GetEndAt returns the EndAt field if non-nil, zero value otherwise.

### GetEndAtOk

`func (o *AnalyticsQueryRequestRequest) GetEndAtOk() (*time.Time, bool)`

GetEndAtOk returns a tuple with the EndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndAt

`func (o *AnalyticsQueryRequestRequest) SetEndAt(v time.Time)`

SetEndAt sets EndAt field to given value.


### GetMetrics

`func (o *AnalyticsQueryRequestRequest) GetMetrics() []string`

GetMetrics returns the Metrics field if non-nil, zero value otherwise.

### GetMetricsOk

`func (o *AnalyticsQueryRequestRequest) GetMetricsOk() (*[]string, bool)`

GetMetricsOk returns a tuple with the Metrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetrics

`func (o *AnalyticsQueryRequestRequest) SetMetrics(v []string)`

SetMetrics sets Metrics field to given value.

### HasMetrics

`func (o *AnalyticsQueryRequestRequest) HasMetrics() bool`

HasMetrics returns a boolean if a field has been set.

### GetDimensionFilters

`func (o *AnalyticsQueryRequestRequest) GetDimensionFilters() interface{}`

GetDimensionFilters returns the DimensionFilters field if non-nil, zero value otherwise.

### GetDimensionFiltersOk

`func (o *AnalyticsQueryRequestRequest) GetDimensionFiltersOk() (*interface{}, bool)`

GetDimensionFiltersOk returns a tuple with the DimensionFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensionFilters

`func (o *AnalyticsQueryRequestRequest) SetDimensionFilters(v interface{})`

SetDimensionFilters sets DimensionFilters field to given value.

### HasDimensionFilters

`func (o *AnalyticsQueryRequestRequest) HasDimensionFilters() bool`

HasDimensionFilters returns a boolean if a field has been set.

### SetDimensionFiltersNil

`func (o *AnalyticsQueryRequestRequest) SetDimensionFiltersNil(b bool)`

 SetDimensionFiltersNil sets the value for DimensionFilters to be an explicit nil

### UnsetDimensionFilters
`func (o *AnalyticsQueryRequestRequest) UnsetDimensionFilters()`

UnsetDimensionFilters ensures that no value is present for DimensionFilters, not even an explicit nil
### GetLimit

`func (o *AnalyticsQueryRequestRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AnalyticsQueryRequestRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AnalyticsQueryRequestRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AnalyticsQueryRequestRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetCursor

`func (o *AnalyticsQueryRequestRequest) GetCursor() string`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *AnalyticsQueryRequestRequest) GetCursorOk() (*string, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *AnalyticsQueryRequestRequest) SetCursor(v string)`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *AnalyticsQueryRequestRequest) HasCursor() bool`

HasCursor returns a boolean if a field has been set.

### GetSortDirection

`func (o *AnalyticsQueryRequestRequest) GetSortDirection() SortDirectionEnum`

GetSortDirection returns the SortDirection field if non-nil, zero value otherwise.

### GetSortDirectionOk

`func (o *AnalyticsQueryRequestRequest) GetSortDirectionOk() (*SortDirectionEnum, bool)`

GetSortDirectionOk returns a tuple with the SortDirection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortDirection

`func (o *AnalyticsQueryRequestRequest) SetSortDirection(v SortDirectionEnum)`

SetSortDirection sets SortDirection field to given value.

### HasSortDirection

`func (o *AnalyticsQueryRequestRequest) HasSortDirection() bool`

HasSortDirection returns a boolean if a field has been set.

### GetIncludeStale

`func (o *AnalyticsQueryRequestRequest) GetIncludeStale() bool`

GetIncludeStale returns the IncludeStale field if non-nil, zero value otherwise.

### GetIncludeStaleOk

`func (o *AnalyticsQueryRequestRequest) GetIncludeStaleOk() (*bool, bool)`

GetIncludeStaleOk returns a tuple with the IncludeStale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeStale

`func (o *AnalyticsQueryRequestRequest) SetIncludeStale(v bool)`

SetIncludeStale sets IncludeStale field to given value.

### HasIncludeStale

`func (o *AnalyticsQueryRequestRequest) HasIncludeStale() bool`

HasIncludeStale returns a boolean if a field has been set.

### GetMaximumStalenessSeconds

`func (o *AnalyticsQueryRequestRequest) GetMaximumStalenessSeconds() int32`

GetMaximumStalenessSeconds returns the MaximumStalenessSeconds field if non-nil, zero value otherwise.

### GetMaximumStalenessSecondsOk

`func (o *AnalyticsQueryRequestRequest) GetMaximumStalenessSecondsOk() (*int32, bool)`

GetMaximumStalenessSecondsOk returns a tuple with the MaximumStalenessSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumStalenessSeconds

`func (o *AnalyticsQueryRequestRequest) SetMaximumStalenessSeconds(v int32)`

SetMaximumStalenessSeconds sets MaximumStalenessSeconds field to given value.

### HasMaximumStalenessSeconds

`func (o *AnalyticsQueryRequestRequest) HasMaximumStalenessSeconds() bool`

HasMaximumStalenessSeconds returns a boolean if a field has been set.

### GetBypassCache

`func (o *AnalyticsQueryRequestRequest) GetBypassCache() bool`

GetBypassCache returns the BypassCache field if non-nil, zero value otherwise.

### GetBypassCacheOk

`func (o *AnalyticsQueryRequestRequest) GetBypassCacheOk() (*bool, bool)`

GetBypassCacheOk returns a tuple with the BypassCache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBypassCache

`func (o *AnalyticsQueryRequestRequest) SetBypassCache(v bool)`

SetBypassCache sets BypassCache field to given value.

### HasBypassCache

`func (o *AnalyticsQueryRequestRequest) HasBypassCache() bool`

HasBypassCache returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


