# RegionalFailoverVerificationOutcome

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Outcome** | [**OutcomeEnum**](OutcomeEnum.md) |  | 
**Result** | Pointer to [**NullableRegionalFailoverVerificationResultResponse**](RegionalFailoverVerificationResultResponse.md) |  | [optional] 
**Dispatch** | Pointer to [**NullableRegionalFailoverVerificationDispatchResponse**](RegionalFailoverVerificationDispatchResponse.md) |  | [optional] 

## Methods

### NewRegionalFailoverVerificationOutcome

`func NewRegionalFailoverVerificationOutcome(outcome OutcomeEnum, ) *RegionalFailoverVerificationOutcome`

NewRegionalFailoverVerificationOutcome instantiates a new RegionalFailoverVerificationOutcome object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverVerificationOutcomeWithDefaults

`func NewRegionalFailoverVerificationOutcomeWithDefaults() *RegionalFailoverVerificationOutcome`

NewRegionalFailoverVerificationOutcomeWithDefaults instantiates a new RegionalFailoverVerificationOutcome object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutcome

`func (o *RegionalFailoverVerificationOutcome) GetOutcome() OutcomeEnum`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *RegionalFailoverVerificationOutcome) GetOutcomeOk() (*OutcomeEnum, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *RegionalFailoverVerificationOutcome) SetOutcome(v OutcomeEnum)`

SetOutcome sets Outcome field to given value.


### GetResult

`func (o *RegionalFailoverVerificationOutcome) GetResult() RegionalFailoverVerificationResultResponse`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *RegionalFailoverVerificationOutcome) GetResultOk() (*RegionalFailoverVerificationResultResponse, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *RegionalFailoverVerificationOutcome) SetResult(v RegionalFailoverVerificationResultResponse)`

SetResult sets Result field to given value.

### HasResult

`func (o *RegionalFailoverVerificationOutcome) HasResult() bool`

HasResult returns a boolean if a field has been set.

### SetResultNil

`func (o *RegionalFailoverVerificationOutcome) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *RegionalFailoverVerificationOutcome) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetDispatch

`func (o *RegionalFailoverVerificationOutcome) GetDispatch() RegionalFailoverVerificationDispatchResponse`

GetDispatch returns the Dispatch field if non-nil, zero value otherwise.

### GetDispatchOk

`func (o *RegionalFailoverVerificationOutcome) GetDispatchOk() (*RegionalFailoverVerificationDispatchResponse, bool)`

GetDispatchOk returns a tuple with the Dispatch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDispatch

`func (o *RegionalFailoverVerificationOutcome) SetDispatch(v RegionalFailoverVerificationDispatchResponse)`

SetDispatch sets Dispatch field to given value.

### HasDispatch

`func (o *RegionalFailoverVerificationOutcome) HasDispatch() bool`

HasDispatch returns a boolean if a field has been set.

### SetDispatchNil

`func (o *RegionalFailoverVerificationOutcome) SetDispatchNil(b bool)`

 SetDispatchNil sets the value for Dispatch to be an explicit nil

### UnsetDispatch
`func (o *RegionalFailoverVerificationOutcome) UnsetDispatch()`

UnsetDispatch ensures that no value is present for Dispatch, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


