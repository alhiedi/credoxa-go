# AnalyticsDeadLetterPreviewData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Eligible** | **bool** |  | 
**ResourceType** | **string** |  | 
**ResourceId** | **string** |  | 
**OrganizationId** | **string** |  | 
**ProjectionId** | **NullableString** |  | 
**CurrentStatus** | **string** |  | 
**ResultingStatus** | **string** |  | 
**Revision** | **int32** |  | 
**GenerationMatches** | **bool** |  | 
**Warnings** | **[]string** |  | 

## Methods

### NewAnalyticsDeadLetterPreviewData

`func NewAnalyticsDeadLetterPreviewData(eligible bool, resourceType string, resourceId string, organizationId string, projectionId NullableString, currentStatus string, resultingStatus string, revision int32, generationMatches bool, warnings []string, ) *AnalyticsDeadLetterPreviewData`

NewAnalyticsDeadLetterPreviewData instantiates a new AnalyticsDeadLetterPreviewData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDeadLetterPreviewDataWithDefaults

`func NewAnalyticsDeadLetterPreviewDataWithDefaults() *AnalyticsDeadLetterPreviewData`

NewAnalyticsDeadLetterPreviewDataWithDefaults instantiates a new AnalyticsDeadLetterPreviewData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEligible

`func (o *AnalyticsDeadLetterPreviewData) GetEligible() bool`

GetEligible returns the Eligible field if non-nil, zero value otherwise.

### GetEligibleOk

`func (o *AnalyticsDeadLetterPreviewData) GetEligibleOk() (*bool, bool)`

GetEligibleOk returns a tuple with the Eligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEligible

`func (o *AnalyticsDeadLetterPreviewData) SetEligible(v bool)`

SetEligible sets Eligible field to given value.


### GetResourceType

`func (o *AnalyticsDeadLetterPreviewData) GetResourceType() string`

GetResourceType returns the ResourceType field if non-nil, zero value otherwise.

### GetResourceTypeOk

`func (o *AnalyticsDeadLetterPreviewData) GetResourceTypeOk() (*string, bool)`

GetResourceTypeOk returns a tuple with the ResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceType

`func (o *AnalyticsDeadLetterPreviewData) SetResourceType(v string)`

SetResourceType sets ResourceType field to given value.


### GetResourceId

`func (o *AnalyticsDeadLetterPreviewData) GetResourceId() string`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *AnalyticsDeadLetterPreviewData) GetResourceIdOk() (*string, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *AnalyticsDeadLetterPreviewData) SetResourceId(v string)`

SetResourceId sets ResourceId field to given value.


### GetOrganizationId

`func (o *AnalyticsDeadLetterPreviewData) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AnalyticsDeadLetterPreviewData) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AnalyticsDeadLetterPreviewData) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectionId

`func (o *AnalyticsDeadLetterPreviewData) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsDeadLetterPreviewData) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsDeadLetterPreviewData) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### SetProjectionIdNil

`func (o *AnalyticsDeadLetterPreviewData) SetProjectionIdNil(b bool)`

 SetProjectionIdNil sets the value for ProjectionId to be an explicit nil

### UnsetProjectionId
`func (o *AnalyticsDeadLetterPreviewData) UnsetProjectionId()`

UnsetProjectionId ensures that no value is present for ProjectionId, not even an explicit nil
### GetCurrentStatus

`func (o *AnalyticsDeadLetterPreviewData) GetCurrentStatus() string`

GetCurrentStatus returns the CurrentStatus field if non-nil, zero value otherwise.

### GetCurrentStatusOk

`func (o *AnalyticsDeadLetterPreviewData) GetCurrentStatusOk() (*string, bool)`

GetCurrentStatusOk returns a tuple with the CurrentStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStatus

`func (o *AnalyticsDeadLetterPreviewData) SetCurrentStatus(v string)`

SetCurrentStatus sets CurrentStatus field to given value.


### GetResultingStatus

`func (o *AnalyticsDeadLetterPreviewData) GetResultingStatus() string`

GetResultingStatus returns the ResultingStatus field if non-nil, zero value otherwise.

### GetResultingStatusOk

`func (o *AnalyticsDeadLetterPreviewData) GetResultingStatusOk() (*string, bool)`

GetResultingStatusOk returns a tuple with the ResultingStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingStatus

`func (o *AnalyticsDeadLetterPreviewData) SetResultingStatus(v string)`

SetResultingStatus sets ResultingStatus field to given value.


### GetRevision

`func (o *AnalyticsDeadLetterPreviewData) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *AnalyticsDeadLetterPreviewData) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *AnalyticsDeadLetterPreviewData) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetGenerationMatches

`func (o *AnalyticsDeadLetterPreviewData) GetGenerationMatches() bool`

GetGenerationMatches returns the GenerationMatches field if non-nil, zero value otherwise.

### GetGenerationMatchesOk

`func (o *AnalyticsDeadLetterPreviewData) GetGenerationMatchesOk() (*bool, bool)`

GetGenerationMatchesOk returns a tuple with the GenerationMatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerationMatches

`func (o *AnalyticsDeadLetterPreviewData) SetGenerationMatches(v bool)`

SetGenerationMatches sets GenerationMatches field to given value.


### GetWarnings

`func (o *AnalyticsDeadLetterPreviewData) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *AnalyticsDeadLetterPreviewData) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *AnalyticsDeadLetterPreviewData) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


