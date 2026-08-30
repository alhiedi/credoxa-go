# OperatorRuntimeDashboardAlert

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Severity** | [**OperatorRuntimeDashboardAlertSeverityEnum**](OperatorRuntimeDashboardAlertSeverityEnum.md) |  | 
**Title** | **string** |  | 
**Message** | **string** |  | 
**Recommendation** | **string** |  | 
**Value** | **float64** |  | 
**Context** | **interface{}** |  | 

## Methods

### NewOperatorRuntimeDashboardAlert

`func NewOperatorRuntimeDashboardAlert(code string, severity OperatorRuntimeDashboardAlertSeverityEnum, title string, message string, recommendation string, value float64, context interface{}, ) *OperatorRuntimeDashboardAlert`

NewOperatorRuntimeDashboardAlert instantiates a new OperatorRuntimeDashboardAlert object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeDashboardAlertWithDefaults

`func NewOperatorRuntimeDashboardAlertWithDefaults() *OperatorRuntimeDashboardAlert`

NewOperatorRuntimeDashboardAlertWithDefaults instantiates a new OperatorRuntimeDashboardAlert object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *OperatorRuntimeDashboardAlert) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *OperatorRuntimeDashboardAlert) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *OperatorRuntimeDashboardAlert) SetCode(v string)`

SetCode sets Code field to given value.


### GetSeverity

`func (o *OperatorRuntimeDashboardAlert) GetSeverity() OperatorRuntimeDashboardAlertSeverityEnum`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeDashboardAlert) GetSeverityOk() (*OperatorRuntimeDashboardAlertSeverityEnum, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeDashboardAlert) SetSeverity(v OperatorRuntimeDashboardAlertSeverityEnum)`

SetSeverity sets Severity field to given value.


### GetTitle

`func (o *OperatorRuntimeDashboardAlert) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OperatorRuntimeDashboardAlert) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OperatorRuntimeDashboardAlert) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetMessage

`func (o *OperatorRuntimeDashboardAlert) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *OperatorRuntimeDashboardAlert) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *OperatorRuntimeDashboardAlert) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRecommendation

`func (o *OperatorRuntimeDashboardAlert) GetRecommendation() string`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *OperatorRuntimeDashboardAlert) GetRecommendationOk() (*string, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *OperatorRuntimeDashboardAlert) SetRecommendation(v string)`

SetRecommendation sets Recommendation field to given value.


### GetValue

`func (o *OperatorRuntimeDashboardAlert) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *OperatorRuntimeDashboardAlert) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *OperatorRuntimeDashboardAlert) SetValue(v float64)`

SetValue sets Value field to given value.


### GetContext

`func (o *OperatorRuntimeDashboardAlert) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *OperatorRuntimeDashboardAlert) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *OperatorRuntimeDashboardAlert) SetContext(v interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *OperatorRuntimeDashboardAlert) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *OperatorRuntimeDashboardAlert) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


