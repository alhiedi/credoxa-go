# AnalyticsRebuildPreviewData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Eligible** | **bool** |  | 
**Operation** | **string** |  | 
**JobId** | **string** |  | 
**ProjectionId** | **string** |  | 
**CurrentStatus** | **string** |  | 
**ResultingStatus** | **string** |  | 
**CurrentRevision** | **int32** |  | 
**RevisionMatches** | **bool** |  | 
**GenerationMatches** | **bool** |  | 
**ActiveLeaseConflict** | **bool** |  | 
**AttemptLimitExhausted** | **bool** |  | 
**Warnings** | **[]string** |  | 

## Methods

### NewAnalyticsRebuildPreviewData

`func NewAnalyticsRebuildPreviewData(eligible bool, operation string, jobId string, projectionId string, currentStatus string, resultingStatus string, currentRevision int32, revisionMatches bool, generationMatches bool, activeLeaseConflict bool, attemptLimitExhausted bool, warnings []string, ) *AnalyticsRebuildPreviewData`

NewAnalyticsRebuildPreviewData instantiates a new AnalyticsRebuildPreviewData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsRebuildPreviewDataWithDefaults

`func NewAnalyticsRebuildPreviewDataWithDefaults() *AnalyticsRebuildPreviewData`

NewAnalyticsRebuildPreviewDataWithDefaults instantiates a new AnalyticsRebuildPreviewData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEligible

`func (o *AnalyticsRebuildPreviewData) GetEligible() bool`

GetEligible returns the Eligible field if non-nil, zero value otherwise.

### GetEligibleOk

`func (o *AnalyticsRebuildPreviewData) GetEligibleOk() (*bool, bool)`

GetEligibleOk returns a tuple with the Eligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEligible

`func (o *AnalyticsRebuildPreviewData) SetEligible(v bool)`

SetEligible sets Eligible field to given value.


### GetOperation

`func (o *AnalyticsRebuildPreviewData) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsRebuildPreviewData) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsRebuildPreviewData) SetOperation(v string)`

SetOperation sets Operation field to given value.


### GetJobId

`func (o *AnalyticsRebuildPreviewData) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *AnalyticsRebuildPreviewData) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *AnalyticsRebuildPreviewData) SetJobId(v string)`

SetJobId sets JobId field to given value.


### GetProjectionId

`func (o *AnalyticsRebuildPreviewData) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsRebuildPreviewData) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsRebuildPreviewData) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetCurrentStatus

`func (o *AnalyticsRebuildPreviewData) GetCurrentStatus() string`

GetCurrentStatus returns the CurrentStatus field if non-nil, zero value otherwise.

### GetCurrentStatusOk

`func (o *AnalyticsRebuildPreviewData) GetCurrentStatusOk() (*string, bool)`

GetCurrentStatusOk returns a tuple with the CurrentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStatus

`func (o *AnalyticsRebuildPreviewData) SetCurrentStatus(v string)`

SetCurrentStatus sets CurrentStatus field to given value.


### GetResultingStatus

`func (o *AnalyticsRebuildPreviewData) GetResultingStatus() string`

GetResultingStatus returns the ResultingStatus field if non-nil, zero value otherwise.

### GetResultingStatusOk

`func (o *AnalyticsRebuildPreviewData) GetResultingStatusOk() (*string, bool)`

GetResultingStatusOk returns a tuple with the ResultingStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingStatus

`func (o *AnalyticsRebuildPreviewData) SetResultingStatus(v string)`

SetResultingStatus sets ResultingStatus field to given value.


### GetCurrentRevision

`func (o *AnalyticsRebuildPreviewData) GetCurrentRevision() int32`

GetCurrentRevision returns the CurrentRevision field if non-nil, zero value otherwise.

### GetCurrentRevisionOk

`func (o *AnalyticsRebuildPreviewData) GetCurrentRevisionOk() (*int32, bool)`

GetCurrentRevisionOk returns a tuple with the CurrentRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentRevision

`func (o *AnalyticsRebuildPreviewData) SetCurrentRevision(v int32)`

SetCurrentRevision sets CurrentRevision field to given value.


### GetRevisionMatches

`func (o *AnalyticsRebuildPreviewData) GetRevisionMatches() bool`

GetRevisionMatches returns the RevisionMatches field if non-nil, zero value otherwise.

### GetRevisionMatchesOk

`func (o *AnalyticsRebuildPreviewData) GetRevisionMatchesOk() (*bool, bool)`

GetRevisionMatchesOk returns a tuple with the RevisionMatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionMatches

`func (o *AnalyticsRebuildPreviewData) SetRevisionMatches(v bool)`

SetRevisionMatches sets RevisionMatches field to given value.


### GetGenerationMatches

`func (o *AnalyticsRebuildPreviewData) GetGenerationMatches() bool`

GetGenerationMatches returns the GenerationMatches field if non-nil, zero value otherwise.

### GetGenerationMatchesOk

`func (o *AnalyticsRebuildPreviewData) GetGenerationMatchesOk() (*bool, bool)`

GetGenerationMatchesOk returns a tuple with the GenerationMatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerationMatches

`func (o *AnalyticsRebuildPreviewData) SetGenerationMatches(v bool)`

SetGenerationMatches sets GenerationMatches field to given value.


### GetActiveLeaseConflict

`func (o *AnalyticsRebuildPreviewData) GetActiveLeaseConflict() bool`

GetActiveLeaseConflict returns the ActiveLeaseConflict field if non-nil, zero value otherwise.

### GetActiveLeaseConflictOk

`func (o *AnalyticsRebuildPreviewData) GetActiveLeaseConflictOk() (*bool, bool)`

GetActiveLeaseConflictOk returns a tuple with the ActiveLeaseConflict field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveLeaseConflict

`func (o *AnalyticsRebuildPreviewData) SetActiveLeaseConflict(v bool)`

SetActiveLeaseConflict sets ActiveLeaseConflict field to given value.


### GetAttemptLimitExhausted

`func (o *AnalyticsRebuildPreviewData) GetAttemptLimitExhausted() bool`

GetAttemptLimitExhausted returns the AttemptLimitExhausted field if non-nil, zero value otherwise.

### GetAttemptLimitExhaustedOk

`func (o *AnalyticsRebuildPreviewData) GetAttemptLimitExhaustedOk() (*bool, bool)`

GetAttemptLimitExhaustedOk returns a tuple with the AttemptLimitExhausted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptLimitExhausted

`func (o *AnalyticsRebuildPreviewData) SetAttemptLimitExhausted(v bool)`

SetAttemptLimitExhausted sets AttemptLimitExhausted field to given value.


### GetWarnings

`func (o *AnalyticsRebuildPreviewData) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *AnalyticsRebuildPreviewData) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *AnalyticsRebuildPreviewData) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


