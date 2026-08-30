# AnalyticsQueryAPIResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | **interface{}** |  | 
**Meta** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewAnalyticsQueryAPIResponse

`func NewAnalyticsQueryAPIResponse(success bool, data interface{}, ) *AnalyticsQueryAPIResponse`

NewAnalyticsQueryAPIResponse instantiates a new AnalyticsQueryAPIResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsQueryAPIResponseWithDefaults

`func NewAnalyticsQueryAPIResponseWithDefaults() *AnalyticsQueryAPIResponse`

NewAnalyticsQueryAPIResponseWithDefaults instantiates a new AnalyticsQueryAPIResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AnalyticsQueryAPIResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsQueryAPIResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsQueryAPIResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *AnalyticsQueryAPIResponse) GetData() interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AnalyticsQueryAPIResponse) GetDataOk() (*interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AnalyticsQueryAPIResponse) SetData(v interface{})`

SetData sets Data field to given value.


### SetDataNil

`func (o *AnalyticsQueryAPIResponse) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *AnalyticsQueryAPIResponse) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetMeta

`func (o *AnalyticsQueryAPIResponse) GetMeta() interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *AnalyticsQueryAPIResponse) GetMetaOk() (*interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *AnalyticsQueryAPIResponse) SetMeta(v interface{})`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *AnalyticsQueryAPIResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *AnalyticsQueryAPIResponse) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *AnalyticsQueryAPIResponse) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


