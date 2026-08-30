# AnalyticsCheckpointListData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | [**[]AnalyticsCheckpointListRecord**](AnalyticsCheckpointListRecord.md) |  | 
**Count** | **int32** |  | 

## Methods

### NewAnalyticsCheckpointListData

`func NewAnalyticsCheckpointListData(results []AnalyticsCheckpointListRecord, count int32, ) *AnalyticsCheckpointListData`

NewAnalyticsCheckpointListData instantiates a new AnalyticsCheckpointListData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsCheckpointListDataWithDefaults

`func NewAnalyticsCheckpointListDataWithDefaults() *AnalyticsCheckpointListData`

NewAnalyticsCheckpointListDataWithDefaults instantiates a new AnalyticsCheckpointListData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *AnalyticsCheckpointListData) GetResults() []AnalyticsCheckpointListRecord`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *AnalyticsCheckpointListData) GetResultsOk() (*[]AnalyticsCheckpointListRecord, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *AnalyticsCheckpointListData) SetResults(v []AnalyticsCheckpointListRecord)`

SetResults sets Results field to given value.


### GetCount

`func (o *AnalyticsCheckpointListData) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *AnalyticsCheckpointListData) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *AnalyticsCheckpointListData) SetCount(v int32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


