# AnalyticsLeaseCheckpointActionData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Operation** | [**AnalyticsLeaseCheckpointOperation**](AnalyticsLeaseCheckpointOperation.md) |  | 
**IdempotentReplay** | **bool** |  | 

## Methods

### NewAnalyticsLeaseCheckpointActionData

`func NewAnalyticsLeaseCheckpointActionData(operation AnalyticsLeaseCheckpointOperation, idempotentReplay bool, ) *AnalyticsLeaseCheckpointActionData`

NewAnalyticsLeaseCheckpointActionData instantiates a new AnalyticsLeaseCheckpointActionData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsLeaseCheckpointActionDataWithDefaults

`func NewAnalyticsLeaseCheckpointActionDataWithDefaults() *AnalyticsLeaseCheckpointActionData`

NewAnalyticsLeaseCheckpointActionDataWithDefaults instantiates a new AnalyticsLeaseCheckpointActionData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperation

`func (o *AnalyticsLeaseCheckpointActionData) GetOperation() AnalyticsLeaseCheckpointOperation`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsLeaseCheckpointActionData) GetOperationOk() (*AnalyticsLeaseCheckpointOperation, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsLeaseCheckpointActionData) SetOperation(v AnalyticsLeaseCheckpointOperation)`

SetOperation sets Operation field to given value.


### GetIdempotentReplay

`func (o *AnalyticsLeaseCheckpointActionData) GetIdempotentReplay() bool`

GetIdempotentReplay returns the IdempotentReplay field if non-nil, zero value otherwise.

### GetIdempotentReplayOk

`func (o *AnalyticsLeaseCheckpointActionData) GetIdempotentReplayOk() (*bool, bool)`

GetIdempotentReplayOk returns a tuple with the IdempotentReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotentReplay

`func (o *AnalyticsLeaseCheckpointActionData) SetIdempotentReplay(v bool)`

SetIdempotentReplay sets IdempotentReplay field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


