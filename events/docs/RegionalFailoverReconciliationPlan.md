# RegionalFailoverReconciliationPlan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**VerificationId** | **string** |  | [readonly] 
**ExecutionId** | **string** |  | [readonly] 
**VerificationFingerprint** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] 
**AutomaticActionCount** | Pointer to **int64** |  | [optional] 
**ApprovalRequiredActionCount** | Pointer to **int64** |  | [optional] 
**ManualActionCount** | Pointer to **int64** |  | [optional] 
**ApprovedBy** | Pointer to **string** |  | [optional] 
**ApprovedAt** | Pointer to **NullableTime** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**FailureReason** | Pointer to **string** |  | [optional] 
**Actions** | [**[]RegionalFailoverReconciliationAction**](RegionalFailoverReconciliationAction.md) |  | [readonly] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRegionalFailoverReconciliationPlan

`func NewRegionalFailoverReconciliationPlan(id string, organizationId string, verificationId string, executionId string, verificationFingerprint string, actions []RegionalFailoverReconciliationAction, createdAt time.Time, updatedAt time.Time, ) *RegionalFailoverReconciliationPlan`

NewRegionalFailoverReconciliationPlan instantiates a new RegionalFailoverReconciliationPlan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverReconciliationPlanWithDefaults

`func NewRegionalFailoverReconciliationPlanWithDefaults() *RegionalFailoverReconciliationPlan`

NewRegionalFailoverReconciliationPlanWithDefaults instantiates a new RegionalFailoverReconciliationPlan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverReconciliationPlan) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverReconciliationPlan) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverReconciliationPlan) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RegionalFailoverReconciliationPlan) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RegionalFailoverReconciliationPlan) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RegionalFailoverReconciliationPlan) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetVerificationId

`func (o *RegionalFailoverReconciliationPlan) GetVerificationId() string`

GetVerificationId returns the VerificationId field if non-nil, zero value otherwise.

### GetVerificationIdOk

`func (o *RegionalFailoverReconciliationPlan) GetVerificationIdOk() (*string, bool)`

GetVerificationIdOk returns a tuple with the VerificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationId

`func (o *RegionalFailoverReconciliationPlan) SetVerificationId(v string)`

SetVerificationId sets VerificationId field to given value.


### GetExecutionId

`func (o *RegionalFailoverReconciliationPlan) GetExecutionId() string`

GetExecutionId returns the ExecutionId field if non-nil, zero value otherwise.

### GetExecutionIdOk

`func (o *RegionalFailoverReconciliationPlan) GetExecutionIdOk() (*string, bool)`

GetExecutionIdOk returns a tuple with the ExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionId

`func (o *RegionalFailoverReconciliationPlan) SetExecutionId(v string)`

SetExecutionId sets ExecutionId field to given value.


### GetVerificationFingerprint

`func (o *RegionalFailoverReconciliationPlan) GetVerificationFingerprint() string`

GetVerificationFingerprint returns the VerificationFingerprint field if non-nil, zero value otherwise.

### GetVerificationFingerprintOk

`func (o *RegionalFailoverReconciliationPlan) GetVerificationFingerprintOk() (*string, bool)`

GetVerificationFingerprintOk returns a tuple with the VerificationFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationFingerprint

`func (o *RegionalFailoverReconciliationPlan) SetVerificationFingerprint(v string)`

SetVerificationFingerprint sets VerificationFingerprint field to given value.


### GetStatus

`func (o *RegionalFailoverReconciliationPlan) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionalFailoverReconciliationPlan) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionalFailoverReconciliationPlan) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RegionalFailoverReconciliationPlan) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAutomaticActionCount

`func (o *RegionalFailoverReconciliationPlan) GetAutomaticActionCount() int64`

GetAutomaticActionCount returns the AutomaticActionCount field if non-nil, zero value otherwise.

### GetAutomaticActionCountOk

`func (o *RegionalFailoverReconciliationPlan) GetAutomaticActionCountOk() (*int64, bool)`

GetAutomaticActionCountOk returns a tuple with the AutomaticActionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomaticActionCount

`func (o *RegionalFailoverReconciliationPlan) SetAutomaticActionCount(v int64)`

SetAutomaticActionCount sets AutomaticActionCount field to given value.

### HasAutomaticActionCount

`func (o *RegionalFailoverReconciliationPlan) HasAutomaticActionCount() bool`

HasAutomaticActionCount returns a boolean if a field has been set.

### GetApprovalRequiredActionCount

`func (o *RegionalFailoverReconciliationPlan) GetApprovalRequiredActionCount() int64`

GetApprovalRequiredActionCount returns the ApprovalRequiredActionCount field if non-nil, zero value otherwise.

### GetApprovalRequiredActionCountOk

`func (o *RegionalFailoverReconciliationPlan) GetApprovalRequiredActionCountOk() (*int64, bool)`

GetApprovalRequiredActionCountOk returns a tuple with the ApprovalRequiredActionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalRequiredActionCount

`func (o *RegionalFailoverReconciliationPlan) SetApprovalRequiredActionCount(v int64)`

SetApprovalRequiredActionCount sets ApprovalRequiredActionCount field to given value.

### HasApprovalRequiredActionCount

`func (o *RegionalFailoverReconciliationPlan) HasApprovalRequiredActionCount() bool`

HasApprovalRequiredActionCount returns a boolean if a field has been set.

### GetManualActionCount

`func (o *RegionalFailoverReconciliationPlan) GetManualActionCount() int64`

GetManualActionCount returns the ManualActionCount field if non-nil, zero value otherwise.

### GetManualActionCountOk

`func (o *RegionalFailoverReconciliationPlan) GetManualActionCountOk() (*int64, bool)`

GetManualActionCountOk returns a tuple with the ManualActionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualActionCount

`func (o *RegionalFailoverReconciliationPlan) SetManualActionCount(v int64)`

SetManualActionCount sets ManualActionCount field to given value.

### HasManualActionCount

`func (o *RegionalFailoverReconciliationPlan) HasManualActionCount() bool`

HasManualActionCount returns a boolean if a field has been set.

### GetApprovedBy

`func (o *RegionalFailoverReconciliationPlan) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *RegionalFailoverReconciliationPlan) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *RegionalFailoverReconciliationPlan) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *RegionalFailoverReconciliationPlan) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.

### GetApprovedAt

`func (o *RegionalFailoverReconciliationPlan) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *RegionalFailoverReconciliationPlan) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *RegionalFailoverReconciliationPlan) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *RegionalFailoverReconciliationPlan) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### SetApprovedAtNil

`func (o *RegionalFailoverReconciliationPlan) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *RegionalFailoverReconciliationPlan) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetStartedAt

`func (o *RegionalFailoverReconciliationPlan) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RegionalFailoverReconciliationPlan) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RegionalFailoverReconciliationPlan) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RegionalFailoverReconciliationPlan) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RegionalFailoverReconciliationPlan) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RegionalFailoverReconciliationPlan) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RegionalFailoverReconciliationPlan) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RegionalFailoverReconciliationPlan) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RegionalFailoverReconciliationPlan) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RegionalFailoverReconciliationPlan) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RegionalFailoverReconciliationPlan) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RegionalFailoverReconciliationPlan) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetFailureReason

`func (o *RegionalFailoverReconciliationPlan) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *RegionalFailoverReconciliationPlan) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *RegionalFailoverReconciliationPlan) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *RegionalFailoverReconciliationPlan) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### GetActions

`func (o *RegionalFailoverReconciliationPlan) GetActions() []RegionalFailoverReconciliationAction`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *RegionalFailoverReconciliationPlan) GetActionsOk() (*[]RegionalFailoverReconciliationAction, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *RegionalFailoverReconciliationPlan) SetActions(v []RegionalFailoverReconciliationAction)`

SetActions sets Actions field to given value.


### GetCreatedAt

`func (o *RegionalFailoverReconciliationPlan) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RegionalFailoverReconciliationPlan) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RegionalFailoverReconciliationPlan) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RegionalFailoverReconciliationPlan) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RegionalFailoverReconciliationPlan) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RegionalFailoverReconciliationPlan) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


