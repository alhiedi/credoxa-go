# RegionalFailoverVerification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**ExecutionId** | **string** |  | [readonly] 
**TopologyId** | **string** |  | [readonly] 
**SourceRegionId** | **string** |  | [readonly] 
**TargetRegionId** | **string** |  | [readonly] 
**ContextFingerprint** | **string** |  | 
**ReportFingerprint** | **string** |  | 
**Status** | **string** |  | 
**TopologyRevision** | **int64** |  | 
**ExpectedAuthorityRegionId** | **string** |  | 
**ExpectedAuthorityEpoch** | **int64** |  | 
**ExpectedFencingToken** | **string** |  | 
**ObservedAuthorityRegionId** | **string** |  | 
**ObservedAuthorityEpoch** | **int64** |  | 
**ObservedFencingToken** | **string** |  | 
**ObservedAt** | **time.Time** |  | 
**VerifiedAt** | **time.Time** |  | 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**Checks** | [**[]RegionalFailoverVerificationCheck**](RegionalFailoverVerificationCheck.md) |  | [readonly] 
**Drifts** | [**[]RegionalFailoverDrift**](RegionalFailoverDrift.md) |  | [readonly] 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRegionalFailoverVerification

`func NewRegionalFailoverVerification(id string, organizationId string, executionId string, topologyId string, sourceRegionId string, targetRegionId string, contextFingerprint string, reportFingerprint string, status string, topologyRevision int64, expectedAuthorityRegionId string, expectedAuthorityEpoch int64, expectedFencingToken string, observedAuthorityRegionId string, observedAuthorityEpoch int64, observedFencingToken string, observedAt time.Time, verifiedAt time.Time, checks []RegionalFailoverVerificationCheck, drifts []RegionalFailoverDrift, createdAt time.Time, ) *RegionalFailoverVerification`

NewRegionalFailoverVerification instantiates a new RegionalFailoverVerification object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverVerificationWithDefaults

`func NewRegionalFailoverVerificationWithDefaults() *RegionalFailoverVerification`

NewRegionalFailoverVerificationWithDefaults instantiates a new RegionalFailoverVerification object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverVerification) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverVerification) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverVerification) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RegionalFailoverVerification) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RegionalFailoverVerification) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RegionalFailoverVerification) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetExecutionId

`func (o *RegionalFailoverVerification) GetExecutionId() string`

GetExecutionId returns the ExecutionId field if non-nil, zero value otherwise.

### GetExecutionIdOk

`func (o *RegionalFailoverVerification) GetExecutionIdOk() (*string, bool)`

GetExecutionIdOk returns a tuple with the ExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionId

`func (o *RegionalFailoverVerification) SetExecutionId(v string)`

SetExecutionId sets ExecutionId field to given value.


### GetTopologyId

`func (o *RegionalFailoverVerification) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *RegionalFailoverVerification) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *RegionalFailoverVerification) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetSourceRegionId

`func (o *RegionalFailoverVerification) GetSourceRegionId() string`

GetSourceRegionId returns the SourceRegionId field if non-nil, zero value otherwise.

### GetSourceRegionIdOk

`func (o *RegionalFailoverVerification) GetSourceRegionIdOk() (*string, bool)`

GetSourceRegionIdOk returns a tuple with the SourceRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRegionId

`func (o *RegionalFailoverVerification) SetSourceRegionId(v string)`

SetSourceRegionId sets SourceRegionId field to given value.


### GetTargetRegionId

`func (o *RegionalFailoverVerification) GetTargetRegionId() string`

GetTargetRegionId returns the TargetRegionId field if non-nil, zero value otherwise.

### GetTargetRegionIdOk

`func (o *RegionalFailoverVerification) GetTargetRegionIdOk() (*string, bool)`

GetTargetRegionIdOk returns a tuple with the TargetRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetRegionId

`func (o *RegionalFailoverVerification) SetTargetRegionId(v string)`

SetTargetRegionId sets TargetRegionId field to given value.


### GetContextFingerprint

`func (o *RegionalFailoverVerification) GetContextFingerprint() string`

GetContextFingerprint returns the ContextFingerprint field if non-nil, zero value otherwise.

### GetContextFingerprintOk

`func (o *RegionalFailoverVerification) GetContextFingerprintOk() (*string, bool)`

GetContextFingerprintOk returns a tuple with the ContextFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextFingerprint

`func (o *RegionalFailoverVerification) SetContextFingerprint(v string)`

SetContextFingerprint sets ContextFingerprint field to given value.


### GetReportFingerprint

`func (o *RegionalFailoverVerification) GetReportFingerprint() string`

GetReportFingerprint returns the ReportFingerprint field if non-nil, zero value otherwise.

### GetReportFingerprintOk

`func (o *RegionalFailoverVerification) GetReportFingerprintOk() (*string, bool)`

GetReportFingerprintOk returns a tuple with the ReportFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportFingerprint

`func (o *RegionalFailoverVerification) SetReportFingerprint(v string)`

SetReportFingerprint sets ReportFingerprint field to given value.


### GetStatus

`func (o *RegionalFailoverVerification) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionalFailoverVerification) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionalFailoverVerification) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTopologyRevision

`func (o *RegionalFailoverVerification) GetTopologyRevision() int64`

GetTopologyRevision returns the TopologyRevision field if non-nil, zero value otherwise.

### GetTopologyRevisionOk

`func (o *RegionalFailoverVerification) GetTopologyRevisionOk() (*int64, bool)`

GetTopologyRevisionOk returns a tuple with the TopologyRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyRevision

`func (o *RegionalFailoverVerification) SetTopologyRevision(v int64)`

SetTopologyRevision sets TopologyRevision field to given value.


### GetExpectedAuthorityRegionId

`func (o *RegionalFailoverVerification) GetExpectedAuthorityRegionId() string`

GetExpectedAuthorityRegionId returns the ExpectedAuthorityRegionId field if non-nil, zero value otherwise.

### GetExpectedAuthorityRegionIdOk

`func (o *RegionalFailoverVerification) GetExpectedAuthorityRegionIdOk() (*string, bool)`

GetExpectedAuthorityRegionIdOk returns a tuple with the ExpectedAuthorityRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedAuthorityRegionId

`func (o *RegionalFailoverVerification) SetExpectedAuthorityRegionId(v string)`

SetExpectedAuthorityRegionId sets ExpectedAuthorityRegionId field to given value.


### GetExpectedAuthorityEpoch

`func (o *RegionalFailoverVerification) GetExpectedAuthorityEpoch() int64`

GetExpectedAuthorityEpoch returns the ExpectedAuthorityEpoch field if non-nil, zero value otherwise.

### GetExpectedAuthorityEpochOk

`func (o *RegionalFailoverVerification) GetExpectedAuthorityEpochOk() (*int64, bool)`

GetExpectedAuthorityEpochOk returns a tuple with the ExpectedAuthorityEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedAuthorityEpoch

`func (o *RegionalFailoverVerification) SetExpectedAuthorityEpoch(v int64)`

SetExpectedAuthorityEpoch sets ExpectedAuthorityEpoch field to given value.


### GetExpectedFencingToken

`func (o *RegionalFailoverVerification) GetExpectedFencingToken() string`

GetExpectedFencingToken returns the ExpectedFencingToken field if non-nil, zero value otherwise.

### GetExpectedFencingTokenOk

`func (o *RegionalFailoverVerification) GetExpectedFencingTokenOk() (*string, bool)`

GetExpectedFencingTokenOk returns a tuple with the ExpectedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingToken

`func (o *RegionalFailoverVerification) SetExpectedFencingToken(v string)`

SetExpectedFencingToken sets ExpectedFencingToken field to given value.


### GetObservedAuthorityRegionId

`func (o *RegionalFailoverVerification) GetObservedAuthorityRegionId() string`

GetObservedAuthorityRegionId returns the ObservedAuthorityRegionId field if non-nil, zero value otherwise.

### GetObservedAuthorityRegionIdOk

`func (o *RegionalFailoverVerification) GetObservedAuthorityRegionIdOk() (*string, bool)`

GetObservedAuthorityRegionIdOk returns a tuple with the ObservedAuthorityRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAuthorityRegionId

`func (o *RegionalFailoverVerification) SetObservedAuthorityRegionId(v string)`

SetObservedAuthorityRegionId sets ObservedAuthorityRegionId field to given value.


### GetObservedAuthorityEpoch

`func (o *RegionalFailoverVerification) GetObservedAuthorityEpoch() int64`

GetObservedAuthorityEpoch returns the ObservedAuthorityEpoch field if non-nil, zero value otherwise.

### GetObservedAuthorityEpochOk

`func (o *RegionalFailoverVerification) GetObservedAuthorityEpochOk() (*int64, bool)`

GetObservedAuthorityEpochOk returns a tuple with the ObservedAuthorityEpoch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAuthorityEpoch

`func (o *RegionalFailoverVerification) SetObservedAuthorityEpoch(v int64)`

SetObservedAuthorityEpoch sets ObservedAuthorityEpoch field to given value.


### GetObservedFencingToken

`func (o *RegionalFailoverVerification) GetObservedFencingToken() string`

GetObservedFencingToken returns the ObservedFencingToken field if non-nil, zero value otherwise.

### GetObservedFencingTokenOk

`func (o *RegionalFailoverVerification) GetObservedFencingTokenOk() (*string, bool)`

GetObservedFencingTokenOk returns a tuple with the ObservedFencingToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedFencingToken

`func (o *RegionalFailoverVerification) SetObservedFencingToken(v string)`

SetObservedFencingToken sets ObservedFencingToken field to given value.


### GetObservedAt

`func (o *RegionalFailoverVerification) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *RegionalFailoverVerification) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *RegionalFailoverVerification) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetVerifiedAt

`func (o *RegionalFailoverVerification) GetVerifiedAt() time.Time`

GetVerifiedAt returns the VerifiedAt field if non-nil, zero value otherwise.

### GetVerifiedAtOk

`func (o *RegionalFailoverVerification) GetVerifiedAtOk() (*time.Time, bool)`

GetVerifiedAtOk returns a tuple with the VerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedAt

`func (o *RegionalFailoverVerification) SetVerifiedAt(v time.Time)`

SetVerifiedAt sets VerifiedAt field to given value.


### GetMetadata

`func (o *RegionalFailoverVerification) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RegionalFailoverVerification) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RegionalFailoverVerification) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RegionalFailoverVerification) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *RegionalFailoverVerification) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *RegionalFailoverVerification) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetChecks

`func (o *RegionalFailoverVerification) GetChecks() []RegionalFailoverVerificationCheck`

GetChecks returns the Checks field if non-nil, zero value otherwise.

### GetChecksOk

`func (o *RegionalFailoverVerification) GetChecksOk() (*[]RegionalFailoverVerificationCheck, bool)`

GetChecksOk returns a tuple with the Checks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecks

`func (o *RegionalFailoverVerification) SetChecks(v []RegionalFailoverVerificationCheck)`

SetChecks sets Checks field to given value.


### GetDrifts

`func (o *RegionalFailoverVerification) GetDrifts() []RegionalFailoverDrift`

GetDrifts returns the Drifts field if non-nil, zero value otherwise.

### GetDriftsOk

`func (o *RegionalFailoverVerification) GetDriftsOk() (*[]RegionalFailoverDrift, bool)`

GetDriftsOk returns a tuple with the Drifts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrifts

`func (o *RegionalFailoverVerification) SetDrifts(v []RegionalFailoverDrift)`

SetDrifts sets Drifts field to given value.


### GetCreatedAt

`func (o *RegionalFailoverVerification) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RegionalFailoverVerification) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RegionalFailoverVerification) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


