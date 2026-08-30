# FailoverSafetyDecision

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**TopologyId** | **string** |  | 
**TopologyName** | **string** |  | 
**SourceRegionId** | **string** |  | 
**SourceRegionCode** | **string** |  | 
**TargetRegionId** | **string** |  | 
**TargetRegionCode** | **string** |  | 
**PolicyId** | **string** |  | 
**PolicyRevision** | **int32** |  | 
**TopologyRevision** | **int32** |  | 
**AuthorityEpoch** | **int32** |  | 
**FencingToken** | **string** |  | 
**Decision** | **string** |  | 
**ReasonCode** | **string** |  | 
**ReportFingerprint** | **string** |  | 
**ApprovalStatus** | **string** |  | 
**OverrideApplied** | **bool** |  | 
**OperatorId** | **string** |  | 
**OperatorReason** | **string** |  | 
**EvaluatedAt** | **time.Time** |  | 
**ResolvedAt** | **NullableTime** |  | 
**Revision** | **int32** |  | 
**Report** | **interface{}** |  | 
**Metadata** | **interface{}** |  | 
**RuleEvidence** | [**[]FailoverSafetyRuleEvidence**](FailoverSafetyRuleEvidence.md) |  | [readonly] 
**Events** | [**[]FailoverSafetyDecisionEvent**](FailoverSafetyDecisionEvent.md) |  | [readonly] 

## Methods

### NewFailoverSafetyDecision

`func NewFailoverSafetyDecision(id string, organizationId string, topologyId string, topologyName string, sourceRegionId string, sourceRegionCode string, targetRegionId string, targetRegionCode string, policyId string, policyRevision int32, topologyRevision int32, authorityEpoch int32, fencingToken string, decision string, reasonCode string, reportFingerprint string, approvalStatus string, overrideApplied bool, operatorId string, operatorReason string, evaluatedAt time.Time, resolvedAt NullableTime, revision int32, report interface{}, metadata interface{}, ruleEvidence []FailoverSafetyRuleEvidence, events []FailoverSafetyDecisionEvent, ) *FailoverSafetyDecision`

NewFailoverSafetyDecision instantiates a new FailoverSafetyDecision object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFailoverSafetyDecisionWithDefaults

`func NewFailoverSafetyDecisionWithDefaults() *FailoverSafetyDecision`

NewFailoverSafetyDecisionWithDefaults instantiates a new FailoverSafetyDecision object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FailoverSafetyDecision) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FailoverSafetyDecision) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FailoverSafetyDecision) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *FailoverSafetyDecision) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *FailoverSafetyDecision) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *FailoverSafetyDecision) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *FailoverSafetyDecision) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *FailoverSafetyDecision) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *FailoverSafetyDecision) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetTopologyName

`func (o *FailoverSafetyDecision) GetTopologyName() string`

GetTopologyName returns the TopologyName field if non-nil, zero value otherwise.

### GetTopologyNameOk

`func (o *FailoverSafetyDecision) GetTopologyNameOk() (*string, bool)`

GetTopologyNameOk returns a tuple with the TopologyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyName

`func (o *FailoverSafetyDecision) SetTopologyName(v string)`

SetTopologyName sets TopologyName field to given value.


### GetSourceRegionId

`func (o *FailoverSafetyDecision) GetSourceRegionId() string`

GetSourceRegionId returns the SourceRegionId field if non-nil, zero value otherwise.

### GetSourceRegionIdOk

`func (o *FailoverSafetyDecision) GetSourceRegionIdOk() (*string, bool)`

GetSourceRegionIdOk returns a tuple with the SourceRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRegionId

`func (o *FailoverSafetyDecision) SetSourceRegionId(v string)`

SetSourceRegionId sets SourceRegionId field to given value.


### GetSourceRegionCode

`func (o *FailoverSafetyDecision) GetSourceRegionCode() string`

GetSourceRegionCode returns the SourceRegionCode field if non-nil, zero value otherwise.

### GetSourceRegionCodeOk

`func (o *FailoverSafetyDecision) GetSourceRegionCodeOk() (*string, bool)`

GetSourceRegionCodeOk returns a tuple with the SourceRegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRegionCode

`func (o *FailoverSafetyDecision) SetSourceRegionCode(v string)`

SetSourceRegionCode sets SourceRegionCode field to given value.


### GetTargetRegionId

`func (o *FailoverSafetyDecision) GetTargetRegionId() string`

GetTargetRegionId returns the TargetRegionId field if non-nil, zero value otherwise.

### GetTargetRegionIdOk

`func (o *FailoverSafetyDecision) GetTargetRegionIdOk() (*string, bool)`

GetTargetRegionIdOk returns a tuple with the TargetRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRegionId

`func (o *FailoverSafetyDecision) SetTargetRegionId(v string)`

SetTargetRegionId sets TargetRegionId field to given value.


### GetTargetRegionCode

`func (o *FailoverSafetyDecision) GetTargetRegionCode() string`

GetTargetRegionCode returns the TargetRegionCode field if non-nil, zero value otherwise.

### GetTargetRegionCodeOk

`func (o *FailoverSafetyDecision) GetTargetRegionCodeOk() (*string, bool)`

GetTargetRegionCodeOk returns a tuple with the TargetRegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRegionCode

`func (o *FailoverSafetyDecision) SetTargetRegionCode(v string)`

SetTargetRegionCode sets TargetRegionCode field to given value.


### GetPolicyId

`func (o *FailoverSafetyDecision) GetPolicyId() string`

GetPolicyId returns the PolicyId field if non-nil, zero value otherwise.

### GetPolicyIdOk

`func (o *FailoverSafetyDecision) GetPolicyIdOk() (*string, bool)`

GetPolicyIdOk returns a tuple with the PolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyId

`func (o *FailoverSafetyDecision) SetPolicyId(v string)`

SetPolicyId sets PolicyId field to given value.


### GetPolicyRevision

`func (o *FailoverSafetyDecision) GetPolicyRevision() int32`

GetPolicyRevision returns the PolicyRevision field if non-nil, zero value otherwise.

### GetPolicyRevisionOk

`func (o *FailoverSafetyDecision) GetPolicyRevisionOk() (*int32, bool)`

GetPolicyRevisionOk returns a tuple with the PolicyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyRevision

`func (o *FailoverSafetyDecision) SetPolicyRevision(v int32)`

SetPolicyRevision sets PolicyRevision field to given value.


### GetTopologyRevision

`func (o *FailoverSafetyDecision) GetTopologyRevision() int32`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *FailoverSafetyDecision) GetTopologyRevisionOk() (*int32, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *FailoverSafetyDecision) SetTopologyRevision(v int32)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetAuthorityEpoch

`func (o *FailoverSafetyDecision) GetAuthorityEpoch() int32`

GetAuthorityEpoch returns the AuthorityEpoch field if non-nil, zero value otherwise.

### GetAuthorityEpochOk

`func (o *FailoverSafetyDecision) GetAuthorityEpochOk() (*int32, bool)`

GetAuthorityEpochOk returns a tuple with the AuthorityEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorityEpoch

`func (o *FailoverSafetyDecision) SetAuthorityEpoch(v int32)`

SetAuthorityEpoch sets AuthorityEpoch field to given value.


### GetFencingToken

`func (o *FailoverSafetyDecision) GetFencingToken() string`

GetFencingToken returns the FencingToken field if non-nil, zero value otherwise.

### GetFencingTokenOk

`func (o *FailoverSafetyDecision) GetFencingTokenOk() (*string, bool)`

GetFencingTokenOk returns a tuple with the FencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFencingToken

`func (o *FailoverSafetyDecision) SetFencingToken(v string)`

SetFencingToken sets FencingToken field to given value.


### GetDecision

`func (o *FailoverSafetyDecision) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *FailoverSafetyDecision) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *FailoverSafetyDecision) SetDecision(v string)`

SetDecision sets Decision field to given value.


### GetReasonCode

`func (o *FailoverSafetyDecision) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *FailoverSafetyDecision) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *FailoverSafetyDecision) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.


### GetReportFingerprint

`func (o *FailoverSafetyDecision) GetReportFingerprint() string`

GetReportFingerprint returns the ReportFingerprint field if non-nil, zero value otherwise.

### GetReportFingerprintOk

`func (o *FailoverSafetyDecision) GetReportFingerprintOk() (*string, bool)`

GetReportFingerprintOk returns a tuple with the ReportFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportFingerprint

`func (o *FailoverSafetyDecision) SetReportFingerprint(v string)`

SetReportFingerprint sets ReportFingerprint field to given value.


### GetApprovalStatus

`func (o *FailoverSafetyDecision) GetApprovalStatus() string`

GetApprovalStatus returns the ApprovalStatus field if non-nil, zero value otherwise.

### GetApprovalStatusOk

`func (o *FailoverSafetyDecision) GetApprovalStatusOk() (*string, bool)`

GetApprovalStatusOk returns a tuple with the ApprovalStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalStatus

`func (o *FailoverSafetyDecision) SetApprovalStatus(v string)`

SetApprovalStatus sets ApprovalStatus field to given value.


### GetOverrideApplied

`func (o *FailoverSafetyDecision) GetOverrideApplied() bool`

GetOverrideApplied returns the OverrideApplied field if non-nil, zero value otherwise.

### GetOverrideAppliedOk

`func (o *FailoverSafetyDecision) GetOverrideAppliedOk() (*bool, bool)`

GetOverrideAppliedOk returns a tuple with the OverrideApplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideApplied

`func (o *FailoverSafetyDecision) SetOverrideApplied(v bool)`

SetOverrideApplied sets OverrideApplied field to given value.


### GetOperatorId

`func (o *FailoverSafetyDecision) GetOperatorId() string`

GetOperatorId returns the OperatorId field if non-nil, zero value otherwise.

### GetOperatorIdOk

`func (o *FailoverSafetyDecision) GetOperatorIdOk() (*string, bool)`

GetOperatorIdOk returns a tuple with the OperatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorId

`func (o *FailoverSafetyDecision) SetOperatorId(v string)`

SetOperatorId sets OperatorId field to given value.


### GetOperatorReason

`func (o *FailoverSafetyDecision) GetOperatorReason() string`

GetOperatorReason returns the OperatorReason field if non-nil, zero value otherwise.

### GetOperatorReasonOk

`func (o *FailoverSafetyDecision) GetOperatorReasonOk() (*string, bool)`

GetOperatorReasonOk returns a tuple with the OperatorReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorReason

`func (o *FailoverSafetyDecision) SetOperatorReason(v string)`

SetOperatorReason sets OperatorReason field to given value.


### GetEvaluatedAt

`func (o *FailoverSafetyDecision) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *FailoverSafetyDecision) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *FailoverSafetyDecision) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.


### GetResolvedAt

`func (o *FailoverSafetyDecision) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *FailoverSafetyDecision) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *FailoverSafetyDecision) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.


### SetResolvedAtNil

`func (o *FailoverSafetyDecision) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *FailoverSafetyDecision) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetRevision

`func (o *FailoverSafetyDecision) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *FailoverSafetyDecision) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *FailoverSafetyDecision) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetReport

`func (o *FailoverSafetyDecision) GetReport() interface{}`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *FailoverSafetyDecision) GetReportOk() (*interface{}, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *FailoverSafetyDecision) SetReport(v interface{})`

SetReport sets Report field to given value.


### SetReportNil

`func (o *FailoverSafetyDecision) SetReportNil(b bool)`

 SetReportNil sets the value for Report to be an explicit nil

### UnsetReport
`func (o *FailoverSafetyDecision) UnsetReport()`

UnsetReport ensures that no value is present for Report, not even an explicit nil
### GetMetadata

`func (o *FailoverSafetyDecision) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *FailoverSafetyDecision) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *FailoverSafetyDecision) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *FailoverSafetyDecision) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *FailoverSafetyDecision) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRuleEvidence

`func (o *FailoverSafetyDecision) GetRuleEvidence() []FailoverSafetyRuleEvidence`

GetRuleEvidence returns the RuleEvidence field if non-nil, zero value otherwise.

### GetRuleEvidenceOk

`func (o *FailoverSafetyDecision) GetRuleEvidenceOk() (*[]FailoverSafetyRuleEvidence, bool)`

GetRuleEvidenceOk returns a tuple with the RuleEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleEvidence

`func (o *FailoverSafetyDecision) SetRuleEvidence(v []FailoverSafetyRuleEvidence)`

SetRuleEvidence sets RuleEvidence field to given value.


### GetEvents

`func (o *FailoverSafetyDecision) GetEvents() []FailoverSafetyDecisionEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *FailoverSafetyDecision) GetEventsOk() (*[]FailoverSafetyDecisionEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *FailoverSafetyDecision) SetEvents(v []FailoverSafetyDecisionEvent)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


