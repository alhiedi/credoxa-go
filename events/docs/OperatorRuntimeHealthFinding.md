# OperatorRuntimeHealthFinding

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reason** | **string** |  | 
**Severity** | **int32** |  | 
**Message** | **string** |  | 
**Recommendation** | Pointer to **NullableString** |  | [optional] 
**Context** | **interface{}** |  | 

## Methods

### NewOperatorRuntimeHealthFinding

`func NewOperatorRuntimeHealthFinding(reason string, severity int32, message string, context interface{}, ) *OperatorRuntimeHealthFinding`

NewOperatorRuntimeHealthFinding instantiates a new OperatorRuntimeHealthFinding object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeHealthFindingWithDefaults

`func NewOperatorRuntimeHealthFindingWithDefaults() *OperatorRuntimeHealthFinding`

NewOperatorRuntimeHealthFindingWithDefaults instantiates a new OperatorRuntimeHealthFinding object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReason

`func (o *OperatorRuntimeHealthFinding) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *OperatorRuntimeHealthFinding) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *OperatorRuntimeHealthFinding) SetReason(v string)`

SetReason sets Reason field to given value.


### GetSeverity

`func (o *OperatorRuntimeHealthFinding) GetSeverity() int32`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeHealthFinding) GetSeverityOk() (*int32, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeHealthFinding) SetSeverity(v int32)`

SetSeverity sets Severity field to given value.


### GetMessage

`func (o *OperatorRuntimeHealthFinding) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *OperatorRuntimeHealthFinding) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *OperatorRuntimeHealthFinding) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRecommendation

`func (o *OperatorRuntimeHealthFinding) GetRecommendation() string`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *OperatorRuntimeHealthFinding) GetRecommendationOk() (*string, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *OperatorRuntimeHealthFinding) SetRecommendation(v string)`

SetRecommendation sets Recommendation field to given value.

### HasRecommendation

`func (o *OperatorRuntimeHealthFinding) HasRecommendation() bool`

HasRecommendation returns a boolean if a field has been set.

### SetRecommendationNil

`func (o *OperatorRuntimeHealthFinding) SetRecommendationNil(b bool)`

 SetRecommendationNil sets the value for Recommendation to be an explicit nil

### UnsetRecommendation
`func (o *OperatorRuntimeHealthFinding) UnsetRecommendation()`

UnsetRecommendation ensures that no value is present for Recommendation, not even an explicit nil
### GetContext

`func (o *OperatorRuntimeHealthFinding) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *OperatorRuntimeHealthFinding) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *OperatorRuntimeHealthFinding) SetContext(v interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *OperatorRuntimeHealthFinding) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *OperatorRuntimeHealthFinding) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


