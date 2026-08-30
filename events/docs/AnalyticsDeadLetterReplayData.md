# AnalyticsDeadLetterReplayData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Operation** | [**AnalyticsDeadLetterRecoveryOperation**](AnalyticsDeadLetterRecoveryOperation.md) |  | 
**IdempotentReplay** | **bool** |  | 

## Methods

### NewAnalyticsDeadLetterReplayData

`func NewAnalyticsDeadLetterReplayData(operation AnalyticsDeadLetterRecoveryOperation, idempotentReplay bool, ) *AnalyticsDeadLetterReplayData`

NewAnalyticsDeadLetterReplayData instantiates a new AnalyticsDeadLetterReplayData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDeadLetterReplayDataWithDefaults

`func NewAnalyticsDeadLetterReplayDataWithDefaults() *AnalyticsDeadLetterReplayData`

NewAnalyticsDeadLetterReplayDataWithDefaults instantiates a new AnalyticsDeadLetterReplayData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperation

`func (o *AnalyticsDeadLetterReplayData) GetOperation() AnalyticsDeadLetterRecoveryOperation`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsDeadLetterReplayData) GetOperationOk() (*AnalyticsDeadLetterRecoveryOperation, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsDeadLetterReplayData) SetOperation(v AnalyticsDeadLetterRecoveryOperation)`

SetOperation sets Operation field to given value.


### GetIdempotentReplay

`func (o *AnalyticsDeadLetterReplayData) GetIdempotentReplay() bool`

GetIdempotentReplay returns the IdempotentReplay field if non-nil, zero value otherwise.

### GetIdempotentReplayOk

`func (o *AnalyticsDeadLetterReplayData) GetIdempotentReplayOk() (*bool, bool)`

GetIdempotentReplayOk returns a tuple with the IdempotentReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotentReplay

`func (o *AnalyticsDeadLetterReplayData) SetIdempotentReplay(v bool)`

SetIdempotentReplay sets IdempotentReplay field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


