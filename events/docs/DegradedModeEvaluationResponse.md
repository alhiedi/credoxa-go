# DegradedModeEvaluationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **string** |  | 
**Intent** | **string** |  | 
**Allowed** | **bool** |  | 
**Code** | **string** |  | 
**Reason** | **string** |  | 
**Degraded** | **bool** |  | 
**ContinuityOnly** | **bool** |  | 
**OverrideApplied** | **bool** |  | 
**ReconciliationRequired** | **bool** |  | 
**AuthFreshness** | **string** |  | 
**BillingFreshness** | **string** |  | 
**OverrideId** | **NullableString** |  | 

## Methods

### NewDegradedModeEvaluationResponse

`func NewDegradedModeEvaluationResponse(organizationId string, intent string, allowed bool, code string, reason string, degraded bool, continuityOnly bool, overrideApplied bool, reconciliationRequired bool, authFreshness string, billingFreshness string, overrideId NullableString, ) *DegradedModeEvaluationResponse`

NewDegradedModeEvaluationResponse instantiates a new DegradedModeEvaluationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDegradedModeEvaluationResponseWithDefaults

`func NewDegradedModeEvaluationResponseWithDefaults() *DegradedModeEvaluationResponse`

NewDegradedModeEvaluationResponseWithDefaults instantiates a new DegradedModeEvaluationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *DegradedModeEvaluationResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DegradedModeEvaluationResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DegradedModeEvaluationResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetIntent

`func (o *DegradedModeEvaluationResponse) GetIntent() string`

GetIntent returns the Intent field if non-nil, zero value otherwise.

### GetIntentOk

`func (o *DegradedModeEvaluationResponse) GetIntentOk() (*string, bool)`

GetIntentOk returns a tuple with the Intent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntent

`func (o *DegradedModeEvaluationResponse) SetIntent(v string)`

SetIntent sets Intent field to given value.


### GetAllowed

`func (o *DegradedModeEvaluationResponse) GetAllowed() bool`

GetAllowed returns the Allowed field if non-nil, zero value otherwise.

### GetAllowedOk

`func (o *DegradedModeEvaluationResponse) GetAllowedOk() (*bool, bool)`

GetAllowedOk returns a tuple with the Allowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowed

`func (o *DegradedModeEvaluationResponse) SetAllowed(v bool)`

SetAllowed sets Allowed field to given value.


### GetCode

`func (o *DegradedModeEvaluationResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *DegradedModeEvaluationResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *DegradedModeEvaluationResponse) SetCode(v string)`

SetCode sets Code field to given value.


### GetReason

`func (o *DegradedModeEvaluationResponse) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *DegradedModeEvaluationResponse) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *DegradedModeEvaluationResponse) SetReason(v string)`

SetReason sets Reason field to given value.


### GetDegraded

`func (o *DegradedModeEvaluationResponse) GetDegraded() bool`

GetDegraded returns the Degraded field if non-nil, zero value otherwise.

### GetDegradedOk

`func (o *DegradedModeEvaluationResponse) GetDegradedOk() (*bool, bool)`

GetDegradedOk returns a tuple with the Degraded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDegraded

`func (o *DegradedModeEvaluationResponse) SetDegraded(v bool)`

SetDegraded sets Degraded field to given value.


### GetContinuityOnly

`func (o *DegradedModeEvaluationResponse) GetContinuityOnly() bool`

GetContinuityOnly returns the ContinuityOnly field if non-nil, zero value otherwise.

### GetContinuityOnlyOk

`func (o *DegradedModeEvaluationResponse) GetContinuityOnlyOk() (*bool, bool)`

GetContinuityOnlyOk returns a tuple with the ContinuityOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinuityOnly

`func (o *DegradedModeEvaluationResponse) SetContinuityOnly(v bool)`

SetContinuityOnly sets ContinuityOnly field to given value.


### GetOverrideApplied

`func (o *DegradedModeEvaluationResponse) GetOverrideApplied() bool`

GetOverrideApplied returns the OverrideApplied field if non-nil, zero value otherwise.

### GetOverrideAppliedOk

`func (o *DegradedModeEvaluationResponse) GetOverrideAppliedOk() (*bool, bool)`

GetOverrideAppliedOk returns a tuple with the OverrideApplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideApplied

`func (o *DegradedModeEvaluationResponse) SetOverrideApplied(v bool)`

SetOverrideApplied sets OverrideApplied field to given value.


### GetReconciliationRequired

`func (o *DegradedModeEvaluationResponse) GetReconciliationRequired() bool`

GetReconciliationRequired returns the ReconciliationRequired field if non-nil, zero value otherwise.

### GetReconciliationRequiredOk

`func (o *DegradedModeEvaluationResponse) GetReconciliationRequiredOk() (*bool, bool)`

GetReconciliationRequiredOk returns a tuple with the ReconciliationRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconciliationRequired

`func (o *DegradedModeEvaluationResponse) SetReconciliationRequired(v bool)`

SetReconciliationRequired sets ReconciliationRequired field to given value.


### GetAuthFreshness

`func (o *DegradedModeEvaluationResponse) GetAuthFreshness() string`

GetAuthFreshness returns the AuthFreshness field if non-nil, zero value otherwise.

### GetAuthFreshnessOk

`func (o *DegradedModeEvaluationResponse) GetAuthFreshnessOk() (*string, bool)`

GetAuthFreshnessOk returns a tuple with the AuthFreshness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthFreshness

`func (o *DegradedModeEvaluationResponse) SetAuthFreshness(v string)`

SetAuthFreshness sets AuthFreshness field to given value.


### GetBillingFreshness

`func (o *DegradedModeEvaluationResponse) GetBillingFreshness() string`

GetBillingFreshness returns the BillingFreshness field if non-nil, zero value otherwise.

### GetBillingFreshnessOk

`func (o *DegradedModeEvaluationResponse) GetBillingFreshnessOk() (*string, bool)`

GetBillingFreshnessOk returns a tuple with the BillingFreshness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingFreshness

`func (o *DegradedModeEvaluationResponse) SetBillingFreshness(v string)`

SetBillingFreshness sets BillingFreshness field to given value.


### GetOverrideId

`func (o *DegradedModeEvaluationResponse) GetOverrideId() string`

GetOverrideId returns the OverrideId field if non-nil, zero value otherwise.

### GetOverrideIdOk

`func (o *DegradedModeEvaluationResponse) GetOverrideIdOk() (*string, bool)`

GetOverrideIdOk returns a tuple with the OverrideId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideId

`func (o *DegradedModeEvaluationResponse) SetOverrideId(v string)`

SetOverrideId sets OverrideId field to given value.


### SetOverrideIdNil

`func (o *DegradedModeEvaluationResponse) SetOverrideIdNil(b bool)`

 SetOverrideIdNil sets the value for OverrideId to be an explicit nil

### UnsetOverrideId
`func (o *DegradedModeEvaluationResponse) UnsetOverrideId()`

UnsetOverrideId ensures that no value is present for OverrideId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


