# AnalyticsDashboardValidationErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | **interface{}** |  | 
**Error** | [**AnalyticsDashboardError**](AnalyticsDashboardError.md) |  | 
**Meta** | [**AnalyticsDashboardMeta**](AnalyticsDashboardMeta.md) |  | 

## Methods

### NewAnalyticsDashboardValidationErrorResponse

`func NewAnalyticsDashboardValidationErrorResponse(success bool, data interface{}, error_ AnalyticsDashboardError, meta AnalyticsDashboardMeta, ) *AnalyticsDashboardValidationErrorResponse`

NewAnalyticsDashboardValidationErrorResponse instantiates a new AnalyticsDashboardValidationErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDashboardValidationErrorResponseWithDefaults

`func NewAnalyticsDashboardValidationErrorResponseWithDefaults() *AnalyticsDashboardValidationErrorResponse`

NewAnalyticsDashboardValidationErrorResponseWithDefaults instantiates a new AnalyticsDashboardValidationErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AnalyticsDashboardValidationErrorResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsDashboardValidationErrorResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsDashboardValidationErrorResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *AnalyticsDashboardValidationErrorResponse) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnalyticsDashboardValidationErrorResponse) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnalyticsDashboardValidationErrorResponse) SetData(v interface{})`

SetData sets Data field to given value.


### SetDataNil

`func (o *AnalyticsDashboardValidationErrorResponse) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *AnalyticsDashboardValidationErrorResponse) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetError

`func (o *AnalyticsDashboardValidationErrorResponse) GetError() AnalyticsDashboardError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AnalyticsDashboardValidationErrorResponse) GetErrorOk() (*AnalyticsDashboardError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AnalyticsDashboardValidationErrorResponse) SetError(v AnalyticsDashboardError)`

SetError sets Error field to given value.


### GetMeta

`func (o *AnalyticsDashboardValidationErrorResponse) GetMeta() AnalyticsDashboardMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *AnalyticsDashboardValidationErrorResponse) GetMetaOk() (*AnalyticsDashboardMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *AnalyticsDashboardValidationErrorResponse) SetMeta(v AnalyticsDashboardMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


