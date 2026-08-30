# LifecycleSLOIndicator

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**State** | [**LifecycleSLOIndicatorStateEnum**](LifecycleSLOIndicatorStateEnum.md) |  | 
**CurrentValue** | **float64** |  | 
**TargetValue** | **float64** |  | 
**Unit** | **string** |  | 
**Evidence** | **map[string]interface{}** |  | 

## Methods

### NewLifecycleSLOIndicator

`func NewLifecycleSLOIndicator(code string, state LifecycleSLOIndicatorStateEnum, currentValue float64, targetValue float64, unit string, evidence map[string]interface{}, ) *LifecycleSLOIndicator`

NewLifecycleSLOIndicator instantiates a new LifecycleSLOIndicator object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleSLOIndicatorWithDefaults

`func NewLifecycleSLOIndicatorWithDefaults() *LifecycleSLOIndicator`

NewLifecycleSLOIndicatorWithDefaults instantiates a new LifecycleSLOIndicator object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *LifecycleSLOIndicator) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *LifecycleSLOIndicator) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *LifecycleSLOIndicator) SetCode(v string)`

SetCode sets Code field to given value.


### GetState

`func (o *LifecycleSLOIndicator) GetState() LifecycleSLOIndicatorStateEnum`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *LifecycleSLOIndicator) GetStateOk() (*LifecycleSLOIndicatorStateEnum, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *LifecycleSLOIndicator) SetState(v LifecycleSLOIndicatorStateEnum)`

SetState sets State field to given value.


### GetCurrentValue

`func (o *LifecycleSLOIndicator) GetCurrentValue() float64`

GetCurrentValue returns the CurrentValue field if non-nil, zero value otherwise.

### GetCurrentValueOk

`func (o *LifecycleSLOIndicator) GetCurrentValueOk() (*float64, bool)`

GetCurrentValueOk returns a tuple with the CurrentValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentValue

`func (o *LifecycleSLOIndicator) SetCurrentValue(v float64)`

SetCurrentValue sets CurrentValue field to given value.


### GetTargetValue

`func (o *LifecycleSLOIndicator) GetTargetValue() float64`

GetTargetValue returns the TargetValue field if non-nil, zero value otherwise.

### GetTargetValueOk

`func (o *LifecycleSLOIndicator) GetTargetValueOk() (*float64, bool)`

GetTargetValueOk returns a tuple with the TargetValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetValue

`func (o *LifecycleSLOIndicator) SetTargetValue(v float64)`

SetTargetValue sets TargetValue field to given value.


### GetUnit

`func (o *LifecycleSLOIndicator) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *LifecycleSLOIndicator) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *LifecycleSLOIndicator) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetEvidence

`func (o *LifecycleSLOIndicator) GetEvidence() map[string]interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *LifecycleSLOIndicator) GetEvidenceOk() (*map[string]interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *LifecycleSLOIndicator) SetEvidence(v map[string]interface{})`

SetEvidence sets Evidence field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


