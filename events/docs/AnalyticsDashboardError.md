# AnalyticsDashboardError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Message** | **string** |  | 
**Details** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAnalyticsDashboardError

`func NewAnalyticsDashboardError(code string, message string, ) *AnalyticsDashboardError`

NewAnalyticsDashboardError instantiates a new AnalyticsDashboardError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDashboardErrorWithDefaults

`func NewAnalyticsDashboardErrorWithDefaults() *AnalyticsDashboardError`

NewAnalyticsDashboardErrorWithDefaults instantiates a new AnalyticsDashboardError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *AnalyticsDashboardError) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *AnalyticsDashboardError) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *AnalyticsDashboardError) SetCode(v string)`

SetCode sets Code field to given value.


### GetMessage

`func (o *AnalyticsDashboardError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *AnalyticsDashboardError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *AnalyticsDashboardError) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetDetails

`func (o *AnalyticsDashboardError) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AnalyticsDashboardError) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AnalyticsDashboardError) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AnalyticsDashboardError) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


