# DisasterRecoveryComplianceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReportId** | **string** |  | 
**OrganizationId** | **string** |  | 
**DrillId** | **string** |  | 
**ObjectiveId** | **string** |  | 
**TopologyId** | **string** |  | 
**WorkloadName** | **string** |  | 
**ObjectiveRevision** | **int32** |  | 
**Outcome** | **string** |  | 
**RemediationMode** | **string** |  | 
**RecoveryPointAgeSeconds** | **NullableInt32** |  | 
**ObservedDataLossSeconds** | **NullableInt32** |  | 
**ObservedRecoveryTimeSeconds** | **NullableInt32** |  | 
**EvaluatedAt** | **time.Time** |  | 
**ContextFingerprint** | **string** |  | 
**ReportFingerprint** | **string** |  | 
**Summary** | **string** |  | 
**Metadata** | **interface{}** |  | 
**Checks** | [**[]DisasterRecoveryComplianceCheck**](DisasterRecoveryComplianceCheck.md) |  | 

## Methods

### NewDisasterRecoveryComplianceResponse

`func NewDisasterRecoveryComplianceResponse(reportId string, organizationId string, drillId string, objectiveId string, topologyId string, workloadName string, objectiveRevision int32, outcome string, remediationMode string, recoveryPointAgeSeconds NullableInt32, observedDataLossSeconds NullableInt32, observedRecoveryTimeSeconds NullableInt32, evaluatedAt time.Time, contextFingerprint string, reportFingerprint string, summary string, metadata interface{}, checks []DisasterRecoveryComplianceCheck, ) *DisasterRecoveryComplianceResponse`

NewDisasterRecoveryComplianceResponse instantiates a new DisasterRecoveryComplianceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisasterRecoveryComplianceResponseWithDefaults

`func NewDisasterRecoveryComplianceResponseWithDefaults() *DisasterRecoveryComplianceResponse`

NewDisasterRecoveryComplianceResponseWithDefaults instantiates a new DisasterRecoveryComplianceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReportId

`func (o *DisasterRecoveryComplianceResponse) GetReportId() string`

GetReportId returns the ReportId field if non-nil, zero value otherwise.

### GetReportIdOk

`func (o *DisasterRecoveryComplianceResponse) GetReportIdOk() (*string, bool)`

GetReportIdOk returns a tuple with the ReportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportId

`func (o *DisasterRecoveryComplianceResponse) SetReportId(v string)`

SetReportId sets ReportId field to given value.


### GetOrganizationId

`func (o *DisasterRecoveryComplianceResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DisasterRecoveryComplianceResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DisasterRecoveryComplianceResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetDrillId

`func (o *DisasterRecoveryComplianceResponse) GetDrillId() string`

GetDrillId returns the DrillId field if non-nil, zero value otherwise.

### GetDrillIdOk

`func (o *DisasterRecoveryComplianceResponse) GetDrillIdOk() (*string, bool)`

GetDrillIdOk returns a tuple with the DrillId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrillId

`func (o *DisasterRecoveryComplianceResponse) SetDrillId(v string)`

SetDrillId sets DrillId field to given value.


### GetObjectiveId

`func (o *DisasterRecoveryComplianceResponse) GetObjectiveId() string`

GetObjectiveId returns the ObjectiveId field if non-nil, zero value otherwise.

### GetObjectiveIdOk

`func (o *DisasterRecoveryComplianceResponse) GetObjectiveIdOk() (*string, bool)`

GetObjectiveIdOk returns a tuple with the ObjectiveId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectiveId

`func (o *DisasterRecoveryComplianceResponse) SetObjectiveId(v string)`

SetObjectiveId sets ObjectiveId field to given value.


### GetTopologyId

`func (o *DisasterRecoveryComplianceResponse) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *DisasterRecoveryComplianceResponse) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *DisasterRecoveryComplianceResponse) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetWorkloadName

`func (o *DisasterRecoveryComplianceResponse) GetWorkloadName() string`

GetWorkloadName returns the WorkloadName field if non-nil, zero value otherwise.

### GetWorkloadNameOk

`func (o *DisasterRecoveryComplianceResponse) GetWorkloadNameOk() (*string, bool)`

GetWorkloadNameOk returns a tuple with the WorkloadName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkloadName

`func (o *DisasterRecoveryComplianceResponse) SetWorkloadName(v string)`

SetWorkloadName sets WorkloadName field to given value.


### GetObjectiveRevision

`func (o *DisasterRecoveryComplianceResponse) GetObjectiveRevision() int32`

GetObjectiveRevision returns the ObjectiveRevision field if non-nil, zero value otherwise.

### GetObjectiveRevisionOk

`func (o *DisasterRecoveryComplianceResponse) GetObjectiveRevisionOk() (*int32, bool)`

GetObjectiveRevisionOk returns a tuple with the ObjectiveRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectiveRevision

`func (o *DisasterRecoveryComplianceResponse) SetObjectiveRevision(v int32)`

SetObjectiveRevision sets ObjectiveRevision field to given value.


### GetOutcome

`func (o *DisasterRecoveryComplianceResponse) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *DisasterRecoveryComplianceResponse) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *DisasterRecoveryComplianceResponse) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetRemediationMode

`func (o *DisasterRecoveryComplianceResponse) GetRemediationMode() string`

GetRemediationMode returns the RemediationMode field if non-nil, zero value otherwise.

### GetRemediationModeOk

`func (o *DisasterRecoveryComplianceResponse) GetRemediationModeOk() (*string, bool)`

GetRemediationModeOk returns a tuple with the RemediationMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemediationMode

`func (o *DisasterRecoveryComplianceResponse) SetRemediationMode(v string)`

SetRemediationMode sets RemediationMode field to given value.


### GetRecoveryPointAgeSeconds

`func (o *DisasterRecoveryComplianceResponse) GetRecoveryPointAgeSeconds() int32`

GetRecoveryPointAgeSeconds returns the RecoveryPointAgeSeconds field if non-nil, zero value otherwise.

### GetRecoveryPointAgeSecondsOk

`func (o *DisasterRecoveryComplianceResponse) GetRecoveryPointAgeSecondsOk() (*int32, bool)`

GetRecoveryPointAgeSecondsOk returns a tuple with the RecoveryPointAgeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecoveryPointAgeSeconds

`func (o *DisasterRecoveryComplianceResponse) SetRecoveryPointAgeSeconds(v int32)`

SetRecoveryPointAgeSeconds sets RecoveryPointAgeSeconds field to given value.


### SetRecoveryPointAgeSecondsNil

`func (o *DisasterRecoveryComplianceResponse) SetRecoveryPointAgeSecondsNil(b bool)`

 SetRecoveryPointAgeSecondsNil sets the value for RecoveryPointAgeSeconds to be an explicit nil

### UnsetRecoveryPointAgeSeconds
`func (o *DisasterRecoveryComplianceResponse) UnsetRecoveryPointAgeSeconds()`

UnsetRecoveryPointAgeSeconds ensures that no value is present for RecoveryPointAgeSeconds, not even an explicit nil
### GetObservedDataLossSeconds

`func (o *DisasterRecoveryComplianceResponse) GetObservedDataLossSeconds() int32`

GetObservedDataLossSeconds returns the ObservedDataLossSeconds field if non-nil, zero value otherwise.

### GetObservedDataLossSecondsOk

`func (o *DisasterRecoveryComplianceResponse) GetObservedDataLossSecondsOk() (*int32, bool)`

GetObservedDataLossSecondsOk returns a tuple with the ObservedDataLossSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedDataLossSeconds

`func (o *DisasterRecoveryComplianceResponse) SetObservedDataLossSeconds(v int32)`

SetObservedDataLossSeconds sets ObservedDataLossSeconds field to given value.


### SetObservedDataLossSecondsNil

`func (o *DisasterRecoveryComplianceResponse) SetObservedDataLossSecondsNil(b bool)`

 SetObservedDataLossSecondsNil sets the value for ObservedDataLossSeconds to be an explicit nil

### UnsetObservedDataLossSeconds
`func (o *DisasterRecoveryComplianceResponse) UnsetObservedDataLossSeconds()`

UnsetObservedDataLossSeconds ensures that no value is present for ObservedDataLossSeconds, not even an explicit nil
### GetObservedRecoveryTimeSeconds

`func (o *DisasterRecoveryComplianceResponse) GetObservedRecoveryTimeSeconds() int32`

GetObservedRecoveryTimeSeconds returns the ObservedRecoveryTimeSeconds field if non-nil, zero value otherwise.

### GetObservedRecoveryTimeSecondsOk

`func (o *DisasterRecoveryComplianceResponse) GetObservedRecoveryTimeSecondsOk() (*int32, bool)`

GetObservedRecoveryTimeSecondsOk returns a tuple with the ObservedRecoveryTimeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedRecoveryTimeSeconds

`func (o *DisasterRecoveryComplianceResponse) SetObservedRecoveryTimeSeconds(v int32)`

SetObservedRecoveryTimeSeconds sets ObservedRecoveryTimeSeconds field to given value.


### SetObservedRecoveryTimeSecondsNil

`func (o *DisasterRecoveryComplianceResponse) SetObservedRecoveryTimeSecondsNil(b bool)`

 SetObservedRecoveryTimeSecondsNil sets the value for ObservedRecoveryTimeSeconds to be an explicit nil

### UnsetObservedRecoveryTimeSeconds
`func (o *DisasterRecoveryComplianceResponse) UnsetObservedRecoveryTimeSeconds()`

UnsetObservedRecoveryTimeSeconds ensures that no value is present for ObservedRecoveryTimeSeconds, not even an explicit nil
### GetEvaluatedAt

`func (o *DisasterRecoveryComplianceResponse) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *DisasterRecoveryComplianceResponse) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *DisasterRecoveryComplianceResponse) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.


### GetContextFingerprint

`func (o *DisasterRecoveryComplianceResponse) GetContextFingerprint() string`

GetContextFingerprint returns the ContextFingerprint field if non-nil, zero value otherwise.

### GetContextFingerprintOk

`func (o *DisasterRecoveryComplianceResponse) GetContextFingerprintOk() (*string, bool)`

GetContextFingerprintOk returns a tuple with the ContextFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextFingerprint

`func (o *DisasterRecoveryComplianceResponse) SetContextFingerprint(v string)`

SetContextFingerprint sets ContextFingerprint field to given value.


### GetReportFingerprint

`func (o *DisasterRecoveryComplianceResponse) GetReportFingerprint() string`

GetReportFingerprint returns the ReportFingerprint field if non-nil, zero value otherwise.

### GetReportFingerprintOk

`func (o *DisasterRecoveryComplianceResponse) GetReportFingerprintOk() (*string, bool)`

GetReportFingerprintOk returns a tuple with the ReportFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportFingerprint

`func (o *DisasterRecoveryComplianceResponse) SetReportFingerprint(v string)`

SetReportFingerprint sets ReportFingerprint field to given value.


### GetSummary

`func (o *DisasterRecoveryComplianceResponse) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *DisasterRecoveryComplianceResponse) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *DisasterRecoveryComplianceResponse) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetMetadata

`func (o *DisasterRecoveryComplianceResponse) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DisasterRecoveryComplianceResponse) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DisasterRecoveryComplianceResponse) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *DisasterRecoveryComplianceResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DisasterRecoveryComplianceResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetChecks

`func (o *DisasterRecoveryComplianceResponse) GetChecks() []DisasterRecoveryComplianceCheck`

GetChecks returns the Checks field if non-nil, zero value otherwise.

### GetChecksOk

`func (o *DisasterRecoveryComplianceResponse) GetChecksOk() (*[]DisasterRecoveryComplianceCheck, bool)`

GetChecksOk returns a tuple with the Checks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecks

`func (o *DisasterRecoveryComplianceResponse) SetChecks(v []DisasterRecoveryComplianceCheck)`

SetChecks sets Checks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


