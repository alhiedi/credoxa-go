# AnalyticsRebuildActionData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OperationId** | **string** |  | 
**Operation** | **string** |  | 
**Status** | **string** |  | 
**PreviousState** | **interface{}** |  | 
**ResultingState** | **interface{}** |  | 
**IdempotentReplay** | **bool** |  | 

## Methods

### NewAnalyticsRebuildActionData

`func NewAnalyticsRebuildActionData(operationId string, operation string, status string, previousState interface{}, resultingState interface{}, idempotentReplay bool, ) *AnalyticsRebuildActionData`

NewAnalyticsRebuildActionData instantiates a new AnalyticsRebuildActionData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsRebuildActionDataWithDefaults

`func NewAnalyticsRebuildActionDataWithDefaults() *AnalyticsRebuildActionData`

NewAnalyticsRebuildActionDataWithDefaults instantiates a new AnalyticsRebuildActionData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperationId

`func (o *AnalyticsRebuildActionData) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *AnalyticsRebuildActionData) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *AnalyticsRebuildActionData) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.


### GetOperation

`func (o *AnalyticsRebuildActionData) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsRebuildActionData) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsRebuildActionData) SetOperation(v string)`

SetOperation sets Operation field to given value.


### GetStatus

`func (o *AnalyticsRebuildActionData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AnalyticsRebuildActionData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AnalyticsRebuildActionData) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPreviousState

`func (o *AnalyticsRebuildActionData) GetPreviousState() interface{}`

GetPreviousState returns the PreviousState field if non-nil, zero value otherwise.

### GetPreviousStateOk

`func (o *AnalyticsRebuildActionData) GetPreviousStateOk() (*interface{}, bool)`

GetPreviousStateOk returns a tuple with the PreviousState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousState

`func (o *AnalyticsRebuildActionData) SetPreviousState(v interface{})`

SetPreviousState sets PreviousState field to given value.


### SetPreviousStateNil

`func (o *AnalyticsRebuildActionData) SetPreviousStateNil(b bool)`

 SetPreviousStateNil sets the value for PreviousState to be an explicit nil

### UnsetPreviousState
`func (o *AnalyticsRebuildActionData) UnsetPreviousState()`

UnsetPreviousState ensures that no value is present for PreviousState, not even an explicit nil
### GetResultingState

`func (o *AnalyticsRebuildActionData) GetResultingState() interface{}`

GetResultingState returns the ResultingState field if non-nil, zero value otherwise.

### GetResultingStateOk

`func (o *AnalyticsRebuildActionData) GetResultingStateOk() (*interface{}, bool)`

GetResultingStateOk returns a tuple with the ResultingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingState

`func (o *AnalyticsRebuildActionData) SetResultingState(v interface{})`

SetResultingState sets ResultingState field to given value.


### SetResultingStateNil

`func (o *AnalyticsRebuildActionData) SetResultingStateNil(b bool)`

 SetResultingStateNil sets the value for ResultingState to be an explicit nil

### UnsetResultingState
`func (o *AnalyticsRebuildActionData) UnsetResultingState()`

UnsetResultingState ensures that no value is present for ResultingState, not even an explicit nil
### GetIdempotentReplay

`func (o *AnalyticsRebuildActionData) GetIdempotentReplay() bool`

GetIdempotentReplay returns the IdempotentReplay field if non-nil, zero value otherwise.

### GetIdempotentReplayOk

`func (o *AnalyticsRebuildActionData) GetIdempotentReplayOk() (*bool, bool)`

GetIdempotentReplayOk returns a tuple with the IdempotentReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotentReplay

`func (o *AnalyticsRebuildActionData) SetIdempotentReplay(v bool)`

SetIdempotentReplay sets IdempotentReplay field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


