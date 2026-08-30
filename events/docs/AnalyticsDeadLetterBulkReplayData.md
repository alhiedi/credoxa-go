# AnalyticsDeadLetterBulkReplayData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Operation** | [**NullableAnalyticsDeadLetterRecoveryOperation**](AnalyticsDeadLetterRecoveryOperation.md) |  | 
**RequestedCount** | **int32** |  | 
**EligibleCount** | **int32** |  | 
**ReplayedCount** | **int32** |  | 
**ConflictCount** | **int32** |  | 
**DryRun** | **bool** |  | 
**IdempotentReplay** | **bool** |  | 
**Results** | [**[]AnalyticsDeadLetterBulkReplayItem**](AnalyticsDeadLetterBulkReplayItem.md) |  | 

## Methods

### NewAnalyticsDeadLetterBulkReplayData

`func NewAnalyticsDeadLetterBulkReplayData(operation NullableAnalyticsDeadLetterRecoveryOperation, requestedCount int32, eligibleCount int32, replayedCount int32, conflictCount int32, dryRun bool, idempotentReplay bool, results []AnalyticsDeadLetterBulkReplayItem, ) *AnalyticsDeadLetterBulkReplayData`

NewAnalyticsDeadLetterBulkReplayData instantiates a new AnalyticsDeadLetterBulkReplayData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDeadLetterBulkReplayDataWithDefaults

`func NewAnalyticsDeadLetterBulkReplayDataWithDefaults() *AnalyticsDeadLetterBulkReplayData`

NewAnalyticsDeadLetterBulkReplayDataWithDefaults instantiates a new AnalyticsDeadLetterBulkReplayData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperation

`func (o *AnalyticsDeadLetterBulkReplayData) GetOperation() AnalyticsDeadLetterRecoveryOperation`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetOperationOk() (*AnalyticsDeadLetterRecoveryOperation, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsDeadLetterBulkReplayData) SetOperation(v AnalyticsDeadLetterRecoveryOperation)`

SetOperation sets Operation field to given value.


### SetOperationNil

`func (o *AnalyticsDeadLetterBulkReplayData) SetOperationNil(b bool)`

 SetOperationNil sets the value for Operation to be an explicit nil

### UnsetOperation
`func (o *AnalyticsDeadLetterBulkReplayData) UnsetOperation()`

UnsetOperation ensures that no value is present for Operation, not even an explicit nil
### GetRequestedCount

`func (o *AnalyticsDeadLetterBulkReplayData) GetRequestedCount() int32`

GetRequestedCount returns the RequestedCount field if non-nil, zero value otherwise.

### GetRequestedCountOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetRequestedCountOk() (*int32, bool)`

GetRequestedCountOk returns a tuple with the RequestedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedCount

`func (o *AnalyticsDeadLetterBulkReplayData) SetRequestedCount(v int32)`

SetRequestedCount sets RequestedCount field to given value.


### GetEligibleCount

`func (o *AnalyticsDeadLetterBulkReplayData) GetEligibleCount() int32`

GetEligibleCount returns the EligibleCount field if non-nil, zero value otherwise.

### GetEligibleCountOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetEligibleCountOk() (*int32, bool)`

GetEligibleCountOk returns a tuple with the EligibleCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEligibleCount

`func (o *AnalyticsDeadLetterBulkReplayData) SetEligibleCount(v int32)`

SetEligibleCount sets EligibleCount field to given value.


### GetReplayedCount

`func (o *AnalyticsDeadLetterBulkReplayData) GetReplayedCount() int32`

GetReplayedCount returns the ReplayedCount field if non-nil, zero value otherwise.

### GetReplayedCountOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetReplayedCountOk() (*int32, bool)`

GetReplayedCountOk returns a tuple with the ReplayedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplayedCount

`func (o *AnalyticsDeadLetterBulkReplayData) SetReplayedCount(v int32)`

SetReplayedCount sets ReplayedCount field to given value.


### GetConflictCount

`func (o *AnalyticsDeadLetterBulkReplayData) GetConflictCount() int32`

GetConflictCount returns the ConflictCount field if non-nil, zero value otherwise.

### GetConflictCountOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetConflictCountOk() (*int32, bool)`

GetConflictCountOk returns a tuple with the ConflictCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConflictCount

`func (o *AnalyticsDeadLetterBulkReplayData) SetConflictCount(v int32)`

SetConflictCount sets ConflictCount field to given value.


### GetDryRun

`func (o *AnalyticsDeadLetterBulkReplayData) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *AnalyticsDeadLetterBulkReplayData) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.


### GetIdempotentReplay

`func (o *AnalyticsDeadLetterBulkReplayData) GetIdempotentReplay() bool`

GetIdempotentReplay returns the IdempotentReplay field if non-nil, zero value otherwise.

### GetIdempotentReplayOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetIdempotentReplayOk() (*bool, bool)`

GetIdempotentReplayOk returns a tuple with the IdempotentReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotentReplay

`func (o *AnalyticsDeadLetterBulkReplayData) SetIdempotentReplay(v bool)`

SetIdempotentReplay sets IdempotentReplay field to given value.


### GetResults

`func (o *AnalyticsDeadLetterBulkReplayData) GetResults() []AnalyticsDeadLetterBulkReplayItem`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *AnalyticsDeadLetterBulkReplayData) GetResultsOk() (*[]AnalyticsDeadLetterBulkReplayItem, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *AnalyticsDeadLetterBulkReplayData) SetResults(v []AnalyticsDeadLetterBulkReplayItem)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


