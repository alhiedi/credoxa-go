# LifecycleDashboard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **string** |  | 
**GeneratedAt** | **time.Time** |  | 
**Policies** | [**LifecyclePolicySummary**](LifecyclePolicySummary.md) |  | 
**LegalHolds** | [**LifecycleLegalHoldSummary**](LifecycleLegalHoldSummary.md) |  | 
**Executions** | [**LifecycleExecutionSummary**](LifecycleExecutionSummary.md) |  | 
**Backlog** | [**LifecycleBacklogSummary**](LifecycleBacklogSummary.md) |  | 
**Evidence** | [**LifecycleEvidenceSummary**](LifecycleEvidenceSummary.md) |  | 
**SloIndicators** | [**[]LifecycleSLOIndicator**](LifecycleSLOIndicator.md) |  | 

## Methods

### NewLifecycleDashboard

`func NewLifecycleDashboard(organizationId string, generatedAt time.Time, policies LifecyclePolicySummary, legalHolds LifecycleLegalHoldSummary, executions LifecycleExecutionSummary, backlog LifecycleBacklogSummary, evidence LifecycleEvidenceSummary, sloIndicators []LifecycleSLOIndicator, ) *LifecycleDashboard`

NewLifecycleDashboard instantiates a new LifecycleDashboard object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleDashboardWithDefaults

`func NewLifecycleDashboardWithDefaults() *LifecycleDashboard`

NewLifecycleDashboardWithDefaults instantiates a new LifecycleDashboard object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *LifecycleDashboard) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleDashboard) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleDashboard) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetGeneratedAt

`func (o *LifecycleDashboard) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *LifecycleDashboard) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *LifecycleDashboard) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPolicies

`func (o *LifecycleDashboard) GetPolicies() LifecyclePolicySummary`

GetPolicies returns the Policies field if non-nil, zero value otherwise.

### GetPoliciesOk

`func (o *LifecycleDashboard) GetPoliciesOk() (*LifecyclePolicySummary, bool)`

GetPoliciesOk returns a tuple with the Policies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicies

`func (o *LifecycleDashboard) SetPolicies(v LifecyclePolicySummary)`

SetPolicies sets Policies field to given value.


### GetLegalHolds

`func (o *LifecycleDashboard) GetLegalHolds() LifecycleLegalHoldSummary`

GetLegalHolds returns the LegalHolds field if non-nil, zero value otherwise.

### GetLegalHoldsOk

`func (o *LifecycleDashboard) GetLegalHoldsOk() (*LifecycleLegalHoldSummary, bool)`

GetLegalHoldsOk returns a tuple with the LegalHolds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalHolds

`func (o *LifecycleDashboard) SetLegalHolds(v LifecycleLegalHoldSummary)`

SetLegalHolds sets LegalHolds field to given value.


### GetExecutions

`func (o *LifecycleDashboard) GetExecutions() LifecycleExecutionSummary`

GetExecutions returns the Executions field if non-nil, zero value otherwise.

### GetExecutionsOk

`func (o *LifecycleDashboard) GetExecutionsOk() (*LifecycleExecutionSummary, bool)`

GetExecutionsOk returns a tuple with the Executions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutions

`func (o *LifecycleDashboard) SetExecutions(v LifecycleExecutionSummary)`

SetExecutions sets Executions field to given value.


### GetBacklog

`func (o *LifecycleDashboard) GetBacklog() LifecycleBacklogSummary`

GetBacklog returns the Backlog field if non-nil, zero value otherwise.

### GetBacklogOk

`func (o *LifecycleDashboard) GetBacklogOk() (*LifecycleBacklogSummary, bool)`

GetBacklogOk returns a tuple with the Backlog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBacklog

`func (o *LifecycleDashboard) SetBacklog(v LifecycleBacklogSummary)`

SetBacklog sets Backlog field to given value.


### GetEvidence

`func (o *LifecycleDashboard) GetEvidence() LifecycleEvidenceSummary`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *LifecycleDashboard) GetEvidenceOk() (*LifecycleEvidenceSummary, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *LifecycleDashboard) SetEvidence(v LifecycleEvidenceSummary)`

SetEvidence sets Evidence field to given value.


### GetSloIndicators

`func (o *LifecycleDashboard) GetSloIndicators() []LifecycleSLOIndicator`

GetSloIndicators returns the SloIndicators field if non-nil, zero value otherwise.

### GetSloIndicatorsOk

`func (o *LifecycleDashboard) GetSloIndicatorsOk() (*[]LifecycleSLOIndicator, bool)`

GetSloIndicatorsOk returns a tuple with the SloIndicators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSloIndicators

`func (o *LifecycleDashboard) SetSloIndicators(v []LifecycleSLOIndicator)`

SetSloIndicators sets SloIndicators field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


