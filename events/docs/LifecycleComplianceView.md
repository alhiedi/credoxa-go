# LifecycleComplianceView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **string** |  | 
**ActivePolicyVersions** | **int32** |  | 
**ActiveLegalHolds** | **int32** |  | 
**FailedExecutions** | **int32** |  | 
**DeadLetteredCandidates** | **int32** |  | 
**PurgeEvidenceGap** | **int32** |  | 
**Compliant** | **bool** |  | 

## Methods

### NewLifecycleComplianceView

`func NewLifecycleComplianceView(organizationId string, activePolicyVersions int32, activeLegalHolds int32, failedExecutions int32, deadLetteredCandidates int32, purgeEvidenceGap int32, compliant bool, ) *LifecycleComplianceView`

NewLifecycleComplianceView instantiates a new LifecycleComplianceView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleComplianceViewWithDefaults

`func NewLifecycleComplianceViewWithDefaults() *LifecycleComplianceView`

NewLifecycleComplianceViewWithDefaults instantiates a new LifecycleComplianceView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *LifecycleComplianceView) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleComplianceView) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleComplianceView) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetActivePolicyVersions

`func (o *LifecycleComplianceView) GetActivePolicyVersions() int32`

GetActivePolicyVersions returns the ActivePolicyVersions field if non-nil, zero value otherwise.

### GetActivePolicyVersionsOk

`func (o *LifecycleComplianceView) GetActivePolicyVersionsOk() (*int32, bool)`

GetActivePolicyVersionsOk returns a tuple with the ActivePolicyVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivePolicyVersions

`func (o *LifecycleComplianceView) SetActivePolicyVersions(v int32)`

SetActivePolicyVersions sets ActivePolicyVersions field to given value.


### GetActiveLegalHolds

`func (o *LifecycleComplianceView) GetActiveLegalHolds() int32`

GetActiveLegalHolds returns the ActiveLegalHolds field if non-nil, zero value otherwise.

### GetActiveLegalHoldsOk

`func (o *LifecycleComplianceView) GetActiveLegalHoldsOk() (*int32, bool)`

GetActiveLegalHoldsOk returns a tuple with the ActiveLegalHolds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveLegalHolds

`func (o *LifecycleComplianceView) SetActiveLegalHolds(v int32)`

SetActiveLegalHolds sets ActiveLegalHolds field to given value.


### GetFailedExecutions

`func (o *LifecycleComplianceView) GetFailedExecutions() int32`

GetFailedExecutions returns the FailedExecutions field if non-nil, zero value otherwise.

### GetFailedExecutionsOk

`func (o *LifecycleComplianceView) GetFailedExecutionsOk() (*int32, bool)`

GetFailedExecutionsOk returns a tuple with the FailedExecutions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedExecutions

`func (o *LifecycleComplianceView) SetFailedExecutions(v int32)`

SetFailedExecutions sets FailedExecutions field to given value.


### GetDeadLetteredCandidates

`func (o *LifecycleComplianceView) GetDeadLetteredCandidates() int32`

GetDeadLetteredCandidates returns the DeadLetteredCandidates field if non-nil, zero value otherwise.

### GetDeadLetteredCandidatesOk

`func (o *LifecycleComplianceView) GetDeadLetteredCandidatesOk() (*int32, bool)`

GetDeadLetteredCandidatesOk returns a tuple with the DeadLetteredCandidates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetteredCandidates

`func (o *LifecycleComplianceView) SetDeadLetteredCandidates(v int32)`

SetDeadLetteredCandidates sets DeadLetteredCandidates field to given value.


### GetPurgeEvidenceGap

`func (o *LifecycleComplianceView) GetPurgeEvidenceGap() int32`

GetPurgeEvidenceGap returns the PurgeEvidenceGap field if non-nil, zero value otherwise.

### GetPurgeEvidenceGapOk

`func (o *LifecycleComplianceView) GetPurgeEvidenceGapOk() (*int32, bool)`

GetPurgeEvidenceGapOk returns a tuple with the PurgeEvidenceGap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurgeEvidenceGap

`func (o *LifecycleComplianceView) SetPurgeEvidenceGap(v int32)`

SetPurgeEvidenceGap sets PurgeEvidenceGap field to given value.


### GetCompliant

`func (o *LifecycleComplianceView) GetCompliant() bool`

GetCompliant returns the Compliant field if non-nil, zero value otherwise.

### GetCompliantOk

`func (o *LifecycleComplianceView) GetCompliantOk() (*bool, bool)`

GetCompliantOk returns a tuple with the Compliant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompliant

`func (o *LifecycleComplianceView) SetCompliant(v bool)`

SetCompliant sets Compliant field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


