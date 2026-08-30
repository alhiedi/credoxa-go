# RegionalFailoverVerificationResultResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Verification** | [**RegionalFailoverVerification**](RegionalFailoverVerification.md) |  | 
**ReconciliationPlan** | [**RegionalFailoverReconciliationPlan**](RegionalFailoverReconciliationPlan.md) |  | 

## Methods

### NewRegionalFailoverVerificationResultResponse

`func NewRegionalFailoverVerificationResultResponse(verification RegionalFailoverVerification, reconciliationPlan RegionalFailoverReconciliationPlan, ) *RegionalFailoverVerificationResultResponse`

NewRegionalFailoverVerificationResultResponse instantiates a new RegionalFailoverVerificationResultResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverVerificationResultResponseWithDefaults

`func NewRegionalFailoverVerificationResultResponseWithDefaults() *RegionalFailoverVerificationResultResponse`

NewRegionalFailoverVerificationResultResponseWithDefaults instantiates a new RegionalFailoverVerificationResultResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVerification

`func (o *RegionalFailoverVerificationResultResponse) GetVerification() RegionalFailoverVerification`

GetVerification returns the Verification field if non-nil, zero value otherwise.

### GetVerificationOk

`func (o *RegionalFailoverVerificationResultResponse) GetVerificationOk() (*RegionalFailoverVerification, bool)`

GetVerificationOk returns a tuple with the Verification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerification

`func (o *RegionalFailoverVerificationResultResponse) SetVerification(v RegionalFailoverVerification)`

SetVerification sets Verification field to given value.


### GetReconciliationPlan

`func (o *RegionalFailoverVerificationResultResponse) GetReconciliationPlan() RegionalFailoverReconciliationPlan`

GetReconciliationPlan returns the ReconciliationPlan field if non-nil, zero value otherwise.

### GetReconciliationPlanOk

`func (o *RegionalFailoverVerificationResultResponse) GetReconciliationPlanOk() (*RegionalFailoverReconciliationPlan, bool)`

GetReconciliationPlanOk returns a tuple with the ReconciliationPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconciliationPlan

`func (o *RegionalFailoverVerificationResultResponse) SetReconciliationPlan(v RegionalFailoverReconciliationPlan)`

SetReconciliationPlan sets ReconciliationPlan field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


