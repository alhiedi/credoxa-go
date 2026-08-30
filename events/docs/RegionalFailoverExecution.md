# RegionalFailoverExecution

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**TopologyId** | **string** |  | [readonly] 
**TopologyName** | **string** |  | [readonly] 
**SourceRegionId** | **string** |  | [readonly] 
**SourceRegionCode** | **string** |  | [readonly] 
**TargetRegionId** | **string** |  | [readonly] 
**TargetRegionCode** | **string** |  | [readonly] 
**SafetyDecisionId** | **string** |  | [readonly] 
**ExecutionFingerprint** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] 
**ExpectedTopologyRevision** | **int64** |  | 
**ExpectedAuthorityRegionId** | **string** |  | 
**ExpectedAuthorityEpoch** | **int64** |  | 
**ExpectedFencingToken** | **string** |  | 
**ResultingAuthorityRegionId** | Pointer to **NullableString** |  | [optional] 
**ResultingAuthorityEpoch** | Pointer to **NullableInt64** |  | [optional] 
**ResultingFencingToken** | Pointer to **NullableString** |  | [optional] 
**RequestedBy** | **string** |  | 
**RequestReason** | **string** |  | 
**RequestedAt** | **time.Time** |  | 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**FailureStage** | Pointer to **string** |  | [optional] 
**FailureReason** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**Stages** | [**[]RegionalFailoverStage**](RegionalFailoverStage.md) |  | [readonly] 
**Events** | [**[]RegionalFailoverExecutionEvent**](RegionalFailoverExecutionEvent.md) |  | [readonly] 

## Methods

### NewRegionalFailoverExecution

`func NewRegionalFailoverExecution(id string, organizationId string, topologyId string, topologyName string, sourceRegionId string, sourceRegionCode string, targetRegionId string, targetRegionCode string, safetyDecisionId string, executionFingerprint string, expectedTopologyRevision int64, expectedAuthorityRegionId string, expectedAuthorityEpoch int64, expectedFencingToken string, requestedBy string, requestReason string, requestedAt time.Time, stages []RegionalFailoverStage, events []RegionalFailoverExecutionEvent, ) *RegionalFailoverExecution`

NewRegionalFailoverExecution instantiates a new RegionalFailoverExecution object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverExecutionWithDefaults

`func NewRegionalFailoverExecutionWithDefaults() *RegionalFailoverExecution`

NewRegionalFailoverExecutionWithDefaults instantiates a new RegionalFailoverExecution object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverExecution) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverExecution) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverExecution) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RegionalFailoverExecution) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RegionalFailoverExecution) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RegionalFailoverExecution) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetTopologyId

`func (o *RegionalFailoverExecution) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *RegionalFailoverExecution) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *RegionalFailoverExecution) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetTopologyName

`func (o *RegionalFailoverExecution) GetTopologyName() string`

GetTopologyName returns the TopologyName field if non-nil, zero value otherwise.

### GetTopologyNameOk

`func (o *RegionalFailoverExecution) GetTopologyNameOk() (*string, bool)`

GetTopologyNameOk returns a tuple with the TopologyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyName

`func (o *RegionalFailoverExecution) SetTopologyName(v string)`

SetTopologyName sets TopologyName field to given value.


### GetSourceRegionId

`func (o *RegionalFailoverExecution) GetSourceRegionId() string`

GetSourceRegionId returns the SourceRegionId field if non-nil, zero value otherwise.

### GetSourceRegionIdOk

`func (o *RegionalFailoverExecution) GetSourceRegionIdOk() (*string, bool)`

GetSourceRegionIdOk returns a tuple with the SourceRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRegionId

`func (o *RegionalFailoverExecution) SetSourceRegionId(v string)`

SetSourceRegionId sets SourceRegionId field to given value.


### GetSourceRegionCode

`func (o *RegionalFailoverExecution) GetSourceRegionCode() string`

GetSourceRegionCode returns the SourceRegionCode field if non-nil, zero value otherwise.

### GetSourceRegionCodeOk

`func (o *RegionalFailoverExecution) GetSourceRegionCodeOk() (*string, bool)`

GetSourceRegionCodeOk returns a tuple with the SourceRegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRegionCode

`func (o *RegionalFailoverExecution) SetSourceRegionCode(v string)`

SetSourceRegionCode sets SourceRegionCode field to given value.


### GetTargetRegionId

`func (o *RegionalFailoverExecution) GetTargetRegionId() string`

GetTargetRegionId returns the TargetRegionId field if non-nil, zero value otherwise.

### GetTargetRegionIdOk

`func (o *RegionalFailoverExecution) GetTargetRegionIdOk() (*string, bool)`

GetTargetRegionIdOk returns a tuple with the TargetRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRegionId

`func (o *RegionalFailoverExecution) SetTargetRegionId(v string)`

SetTargetRegionId sets TargetRegionId field to given value.


### GetTargetRegionCode

`func (o *RegionalFailoverExecution) GetTargetRegionCode() string`

GetTargetRegionCode returns the TargetRegionCode field if non-nil, zero value otherwise.

### GetTargetRegionCodeOk

`func (o *RegionalFailoverExecution) GetTargetRegionCodeOk() (*string, bool)`

GetTargetRegionCodeOk returns a tuple with the TargetRegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRegionCode

`func (o *RegionalFailoverExecution) SetTargetRegionCode(v string)`

SetTargetRegionCode sets TargetRegionCode field to given value.


### GetSafetyDecisionId

`func (o *RegionalFailoverExecution) GetSafetyDecisionId() string`

GetSafetyDecisionId returns the SafetyDecisionId field if non-nil, zero value otherwise.

### GetSafetyDecisionIdOk

`func (o *RegionalFailoverExecution) GetSafetyDecisionIdOk() (*string, bool)`

GetSafetyDecisionIdOk returns a tuple with the SafetyDecisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyDecisionId

`func (o *RegionalFailoverExecution) SetSafetyDecisionId(v string)`

SetSafetyDecisionId sets SafetyDecisionId field to given value.


### GetExecutionFingerprint

`func (o *RegionalFailoverExecution) GetExecutionFingerprint() string`

GetExecutionFingerprint returns the ExecutionFingerprint field if non-nil, zero value otherwise.

### GetExecutionFingerprintOk

`func (o *RegionalFailoverExecution) GetExecutionFingerprintOk() (*string, bool)`

GetExecutionFingerprintOk returns a tuple with the ExecutionFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionFingerprint

`func (o *RegionalFailoverExecution) SetExecutionFingerprint(v string)`

SetExecutionFingerprint sets ExecutionFingerprint field to given value.


### GetStatus

`func (o *RegionalFailoverExecution) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionalFailoverExecution) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionalFailoverExecution) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RegionalFailoverExecution) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetExpectedTopologyRevision

`func (o *RegionalFailoverExecution) GetExpectedTopologyRevision() int64`

GetExpectedTopologyRevision returns the ExpectedTopologyRevision field if non-nil, zero value otherwise.

### GetExpectedTopologyRevisionOk

`func (o *RegionalFailoverExecution) GetExpectedTopologyRevisionOk() (*int64, bool)`

GetExpectedTopologyRevisionOk returns a tuple with the ExpectedTopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedTopologyRevision

`func (o *RegionalFailoverExecution) SetExpectedTopologyRevision(v int64)`

SetExpectedTopologyRevision sets ExpectedTopologyRevision field to given value.


### GetExpectedAuthorityRegionId

`func (o *RegionalFailoverExecution) GetExpectedAuthorityRegionId() string`

GetExpectedAuthorityRegionId returns the ExpectedAuthorityRegionId field if non-nil, zero value otherwise.

### GetExpectedAuthorityRegionIdOk

`func (o *RegionalFailoverExecution) GetExpectedAuthorityRegionIdOk() (*string, bool)`

GetExpectedAuthorityRegionIdOk returns a tuple with the ExpectedAuthorityRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedAuthorityRegionId

`func (o *RegionalFailoverExecution) SetExpectedAuthorityRegionId(v string)`

SetExpectedAuthorityRegionId sets ExpectedAuthorityRegionId field to given value.


### GetExpectedAuthorityEpoch

`func (o *RegionalFailoverExecution) GetExpectedAuthorityEpoch() int64`

GetExpectedAuthorityEpoch returns the ExpectedAuthorityEpoch field if non-nil, zero value otherwise.

### GetExpectedAuthorityEpochOk

`func (o *RegionalFailoverExecution) GetExpectedAuthorityEpochOk() (*int64, bool)`

GetExpectedAuthorityEpochOk returns a tuple with the ExpectedAuthorityEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedAuthorityEpoch

`func (o *RegionalFailoverExecution) SetExpectedAuthorityEpoch(v int64)`

SetExpectedAuthorityEpoch sets ExpectedAuthorityEpoch field to given value.


### GetExpectedFencingToken

`func (o *RegionalFailoverExecution) GetExpectedFencingToken() string`

GetExpectedFencingToken returns the ExpectedFencingToken field if non-nil, zero value otherwise.

### GetExpectedFencingTokenOk

`func (o *RegionalFailoverExecution) GetExpectedFencingTokenOk() (*string, bool)`

GetExpectedFencingTokenOk returns a tuple with the ExpectedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingToken

`func (o *RegionalFailoverExecution) SetExpectedFencingToken(v string)`

SetExpectedFencingToken sets ExpectedFencingToken field to given value.


### GetResultingAuthorityRegionId

`func (o *RegionalFailoverExecution) GetResultingAuthorityRegionId() string`

GetResultingAuthorityRegionId returns the ResultingAuthorityRegionId field if non-nil, zero value otherwise.

### GetResultingAuthorityRegionIdOk

`func (o *RegionalFailoverExecution) GetResultingAuthorityRegionIdOk() (*string, bool)`

GetResultingAuthorityRegionIdOk returns a tuple with the ResultingAuthorityRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingAuthorityRegionId

`func (o *RegionalFailoverExecution) SetResultingAuthorityRegionId(v string)`

SetResultingAuthorityRegionId sets ResultingAuthorityRegionId field to given value.

### HasResultingAuthorityRegionId

`func (o *RegionalFailoverExecution) HasResultingAuthorityRegionId() bool`

HasResultingAuthorityRegionId returns a boolean if a field has been set.

### SetResultingAuthorityRegionIdNil

`func (o *RegionalFailoverExecution) SetResultingAuthorityRegionIdNil(b bool)`

 SetResultingAuthorityRegionIdNil sets the value for ResultingAuthorityRegionId to be an explicit nil

### UnsetResultingAuthorityRegionId
`func (o *RegionalFailoverExecution) UnsetResultingAuthorityRegionId()`

UnsetResultingAuthorityRegionId ensures that no value is present for ResultingAuthorityRegionId, not even an explicit nil
### GetResultingAuthorityEpoch

`func (o *RegionalFailoverExecution) GetResultingAuthorityEpoch() int64`

GetResultingAuthorityEpoch returns the ResultingAuthorityEpoch field if non-nil, zero value otherwise.

### GetResultingAuthorityEpochOk

`func (o *RegionalFailoverExecution) GetResultingAuthorityEpochOk() (*int64, bool)`

GetResultingAuthorityEpochOk returns a tuple with the ResultingAuthorityEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingAuthorityEpoch

`func (o *RegionalFailoverExecution) SetResultingAuthorityEpoch(v int64)`

SetResultingAuthorityEpoch sets ResultingAuthorityEpoch field to given value.

### HasResultingAuthorityEpoch

`func (o *RegionalFailoverExecution) HasResultingAuthorityEpoch() bool`

HasResultingAuthorityEpoch returns a boolean if a field has been set.

### SetResultingAuthorityEpochNil

`func (o *RegionalFailoverExecution) SetResultingAuthorityEpochNil(b bool)`

 SetResultingAuthorityEpochNil sets the value for ResultingAuthorityEpoch to be an explicit nil

### UnsetResultingAuthorityEpoch
`func (o *RegionalFailoverExecution) UnsetResultingAuthorityEpoch()`

UnsetResultingAuthorityEpoch ensures that no value is present for ResultingAuthorityEpoch, not even an explicit nil
### GetResultingFencingToken

`func (o *RegionalFailoverExecution) GetResultingFencingToken() string`

GetResultingFencingToken returns the ResultingFencingToken field if non-nil, zero value otherwise.

### GetResultingFencingTokenOk

`func (o *RegionalFailoverExecution) GetResultingFencingTokenOk() (*string, bool)`

GetResultingFencingTokenOk returns a tuple with the ResultingFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingFencingToken

`func (o *RegionalFailoverExecution) SetResultingFencingToken(v string)`

SetResultingFencingToken sets ResultingFencingToken field to given value.

### HasResultingFencingToken

`func (o *RegionalFailoverExecution) HasResultingFencingToken() bool`

HasResultingFencingToken returns a boolean if a field has been set.

### SetResultingFencingTokenNil

`func (o *RegionalFailoverExecution) SetResultingFencingTokenNil(b bool)`

 SetResultingFencingTokenNil sets the value for ResultingFencingToken to be an explicit nil

### UnsetResultingFencingToken
`func (o *RegionalFailoverExecution) UnsetResultingFencingToken()`

UnsetResultingFencingToken ensures that no value is present for ResultingFencingToken, not even an explicit nil
### GetRequestedBy

`func (o *RegionalFailoverExecution) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *RegionalFailoverExecution) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *RegionalFailoverExecution) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetRequestReason

`func (o *RegionalFailoverExecution) GetRequestReason() string`

GetRequestReason returns the RequestReason field if non-nil, zero value otherwise.

### GetRequestReasonOk

`func (o *RegionalFailoverExecution) GetRequestReasonOk() (*string, bool)`

GetRequestReasonOk returns a tuple with the RequestReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestReason

`func (o *RegionalFailoverExecution) SetRequestReason(v string)`

SetRequestReason sets RequestReason field to given value.


### GetRequestedAt

`func (o *RegionalFailoverExecution) GetRequestedAt() time.Time`

GetRequestedAt returns the RequestedAt field if non-nil, zero value otherwise.

### GetRequestedAtOk

`func (o *RegionalFailoverExecution) GetRequestedAtOk() (*time.Time, bool)`

GetRequestedAtOk returns a tuple with the RequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedAt

`func (o *RegionalFailoverExecution) SetRequestedAt(v time.Time)`

SetRequestedAt sets RequestedAt field to given value.


### GetStartedAt

`func (o *RegionalFailoverExecution) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RegionalFailoverExecution) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RegionalFailoverExecution) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RegionalFailoverExecution) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RegionalFailoverExecution) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RegionalFailoverExecution) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RegionalFailoverExecution) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RegionalFailoverExecution) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RegionalFailoverExecution) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RegionalFailoverExecution) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RegionalFailoverExecution) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RegionalFailoverExecution) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetFailureStage

`func (o *RegionalFailoverExecution) GetFailureStage() string`

GetFailureStage returns the FailureStage field if non-nil, zero value otherwise.

### GetFailureStageOk

`func (o *RegionalFailoverExecution) GetFailureStageOk() (*string, bool)`

GetFailureStageOk returns a tuple with the FailureStage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureStage

`func (o *RegionalFailoverExecution) SetFailureStage(v string)`

SetFailureStage sets FailureStage field to given value.

### HasFailureStage

`func (o *RegionalFailoverExecution) HasFailureStage() bool`

HasFailureStage returns a boolean if a field has been set.

### GetFailureReason

`func (o *RegionalFailoverExecution) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *RegionalFailoverExecution) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *RegionalFailoverExecution) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *RegionalFailoverExecution) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### GetMetadata

`func (o *RegionalFailoverExecution) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RegionalFailoverExecution) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RegionalFailoverExecution) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RegionalFailoverExecution) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *RegionalFailoverExecution) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *RegionalFailoverExecution) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRevision

`func (o *RegionalFailoverExecution) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *RegionalFailoverExecution) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *RegionalFailoverExecution) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *RegionalFailoverExecution) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetStages

`func (o *RegionalFailoverExecution) GetStages() []RegionalFailoverStage`

GetStages returns the Stages field if non-nil, zero value otherwise.

### GetStagesOk

`func (o *RegionalFailoverExecution) GetStagesOk() (*[]RegionalFailoverStage, bool)`

GetStagesOk returns a tuple with the Stages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStages

`func (o *RegionalFailoverExecution) SetStages(v []RegionalFailoverStage)`

SetStages sets Stages field to given value.


### GetEvents

`func (o *RegionalFailoverExecution) GetEvents() []RegionalFailoverExecutionEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *RegionalFailoverExecution) GetEventsOk() (*[]RegionalFailoverExecutionEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *RegionalFailoverExecution) SetEvents(v []RegionalFailoverExecutionEvent)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


