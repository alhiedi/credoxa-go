# AnalyticsDashboardJSONSectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | **interface{}** |  | 
**Meta** | [**AnalyticsDashboardMeta**](AnalyticsDashboardMeta.md) |  | 

## Methods

### NewAnalyticsDashboardJSONSectionResponse

`func NewAnalyticsDashboardJSONSectionResponse(success bool, data interface{}, meta AnalyticsDashboardMeta, ) *AnalyticsDashboardJSONSectionResponse`

NewAnalyticsDashboardJSONSectionResponse instantiates a new AnalyticsDashboardJSONSectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDashboardJSONSectionResponseWithDefaults

`func NewAnalyticsDashboardJSONSectionResponseWithDefaults() *AnalyticsDashboardJSONSectionResponse`

NewAnalyticsDashboardJSONSectionResponseWithDefaults instantiates a new AnalyticsDashboardJSONSectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AnalyticsDashboardJSONSectionResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsDashboardJSONSectionResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsDashboardJSONSectionResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *AnalyticsDashboardJSONSectionResponse) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnalyticsDashboardJSONSectionResponse) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnalyticsDashboardJSONSectionResponse) SetData(v interface{})`

SetData sets Data field to given value.


### SetDataNil

`func (o *AnalyticsDashboardJSONSectionResponse) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *AnalyticsDashboardJSONSectionResponse) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetMeta

`func (o *AnalyticsDashboardJSONSectionResponse) GetMeta() AnalyticsDashboardMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *AnalyticsDashboardJSONSectionResponse) GetMetaOk() (*AnalyticsDashboardMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *AnalyticsDashboardJSONSectionResponse) SetMeta(v AnalyticsDashboardMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


