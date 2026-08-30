# RegionalFailoverReconciliationExecutionOutcome

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Outcome** | [**OutcomeEnum**](OutcomeEnum.md) |  | 
**Result** | Pointer to [**NullableRegionalFailoverReconciliationPlan**](RegionalFailoverReconciliationPlan.md) |  | [optional] 
**Dispatch** | Pointer to [**NullableRegionalFailoverReconciliationDispatchResponse**](RegionalFailoverReconciliationDispatchResponse.md) |  | [optional] 

## Methods

### NewRegionalFailoverReconciliationExecutionOutcome

`func NewRegionalFailoverReconciliationExecutionOutcome(outcome OutcomeEnum, ) *RegionalFailoverReconciliationExecutionOutcome`

NewRegionalFailoverReconciliationExecutionOutcome instantiates a new RegionalFailoverReconciliationExecutionOutcome object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverReconciliationExecutionOutcomeWithDefaults

`func NewRegionalFailoverReconciliationExecutionOutcomeWithDefaults() *RegionalFailoverReconciliationExecutionOutcome`

NewRegionalFailoverReconciliationExecutionOutcomeWithDefaults instantiates a new RegionalFailoverReconciliationExecutionOutcome object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutcome

`func (o *RegionalFailoverReconciliationExecutionOutcome) GetOutcome() OutcomeEnum`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *RegionalFailoverReconciliationExecutionOutcome) GetOutcomeOk() (*OutcomeEnum, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *RegionalFailoverReconciliationExecutionOutcome) SetOutcome(v OutcomeEnum)`

SetOutcome sets Outcome field to given value.


### GetResult

`func (o *RegionalFailoverReconciliationExecutionOutcome) GetResult() RegionalFailoverReconciliationPlan`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *RegionalFailoverReconciliationExecutionOutcome) GetResultOk() (*RegionalFailoverReconciliationPlan, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *RegionalFailoverReconciliationExecutionOutcome) SetResult(v RegionalFailoverReconciliationPlan)`

SetResult sets Result field to given value.

### HasResult

`func (o *RegionalFailoverReconciliationExecutionOutcome) HasResult() bool`

HasResult returns a boolean if a field has been set.

### SetResultNil

`func (o *RegionalFailoverReconciliationExecutionOutcome) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *RegionalFailoverReconciliationExecutionOutcome) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetDispatch

`func (o *RegionalFailoverReconciliationExecutionOutcome) GetDispatch() RegionalFailoverReconciliationDispatchResponse`

GetDispatch returns the Dispatch field if non-nil, zero value otherwise.

### GetDispatchOk

`func (o *RegionalFailoverReconciliationExecutionOutcome) GetDispatchOk() (*RegionalFailoverReconciliationDispatchResponse, bool)`

GetDispatchOk returns a tuple with the Dispatch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDispatch

`func (o *RegionalFailoverReconciliationExecutionOutcome) SetDispatch(v RegionalFailoverReconciliationDispatchResponse)`

SetDispatch sets Dispatch field to given value.

### HasDispatch

`func (o *RegionalFailoverReconciliationExecutionOutcome) HasDispatch() bool`

HasDispatch returns a boolean if a field has been set.

### SetDispatchNil

`func (o *RegionalFailoverReconciliationExecutionOutcome) SetDispatchNil(b bool)`

 SetDispatchNil sets the value for Dispatch to be an explicit nil

### UnsetDispatch
`func (o *RegionalFailoverReconciliationExecutionOutcome) UnsetDispatch()`

UnsetDispatch ensures that no value is present for Dispatch, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


