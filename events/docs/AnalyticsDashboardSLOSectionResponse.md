# AnalyticsDashboardSLOSectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**[]AnalyticsDashboardSLO**](AnalyticsDashboardSLO.md) |  | 
**Meta** | [**AnalyticsDashboardMeta**](AnalyticsDashboardMeta.md) |  | 

## Methods

### NewAnalyticsDashboardSLOSectionResponse

`func NewAnalyticsDashboardSLOSectionResponse(success bool, data []AnalyticsDashboardSLO, meta AnalyticsDashboardMeta, ) *AnalyticsDashboardSLOSectionResponse`

NewAnalyticsDashboardSLOSectionResponse instantiates a new AnalyticsDashboardSLOSectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDashboardSLOSectionResponseWithDefaults

`func NewAnalyticsDashboardSLOSectionResponseWithDefaults() *AnalyticsDashboardSLOSectionResponse`

NewAnalyticsDashboardSLOSectionResponseWithDefaults instantiates a new AnalyticsDashboardSLOSectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AnalyticsDashboardSLOSectionResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsDashboardSLOSectionResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsDashboardSLOSectionResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *AnalyticsDashboardSLOSectionResponse) GetData() []AnalyticsDashboardSLO`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnalyticsDashboardSLOSectionResponse) GetDataOk() (*[]AnalyticsDashboardSLO, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnalyticsDashboardSLOSectionResponse) SetData(v []AnalyticsDashboardSLO)`

SetData sets Data field to given value.


### GetMeta

`func (o *AnalyticsDashboardSLOSectionResponse) GetMeta() AnalyticsDashboardMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *AnalyticsDashboardSLOSectionResponse) GetMetaOk() (*AnalyticsDashboardMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *AnalyticsDashboardSLOSectionResponse) SetMeta(v AnalyticsDashboardMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


