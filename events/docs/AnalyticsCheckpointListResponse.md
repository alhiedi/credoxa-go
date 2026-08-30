# AnalyticsCheckpointListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**AnalyticsCheckpointListData**](AnalyticsCheckpointListData.md) |  | 

## Methods

### NewAnalyticsCheckpointListResponse

`func NewAnalyticsCheckpointListResponse(success bool, data AnalyticsCheckpointListData, ) *AnalyticsCheckpointListResponse`

NewAnalyticsCheckpointListResponse instantiates a new AnalyticsCheckpointListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsCheckpointListResponseWithDefaults

`func NewAnalyticsCheckpointListResponseWithDefaults() *AnalyticsCheckpointListResponse`

NewAnalyticsCheckpointListResponseWithDefaults instantiates a new AnalyticsCheckpointListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AnalyticsCheckpointListResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsCheckpointListResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsCheckpointListResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *AnalyticsCheckpointListResponse) GetData() AnalyticsCheckpointListData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnalyticsCheckpointListResponse) GetDataOk() (*AnalyticsCheckpointListData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnalyticsCheckpointListResponse) SetData(v AnalyticsCheckpointListData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


