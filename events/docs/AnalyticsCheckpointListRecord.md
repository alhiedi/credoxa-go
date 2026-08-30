# AnalyticsCheckpointListRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**ProjectionId** | **string** |  | 
**CursorOccurredAt** | **NullableTime** |  | 
**CursorEventId** | **NullableString** |  | 
**FencingGeneration** | **int32** |  | 
**Revision** | **int32** |  | 
**Drift** | **string** |  | 

## Methods

### NewAnalyticsCheckpointListRecord

`func NewAnalyticsCheckpointListRecord(id string, organizationId string, projectionId string, cursorOccurredAt NullableTime, cursorEventId NullableString, fencingGeneration int32, revision int32, drift string, ) *AnalyticsCheckpointListRecord`

NewAnalyticsCheckpointListRecord instantiates a new AnalyticsCheckpointListRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsCheckpointListRecordWithDefaults

`func NewAnalyticsCheckpointListRecordWithDefaults() *AnalyticsCheckpointListRecord`

NewAnalyticsCheckpointListRecordWithDefaults instantiates a new AnalyticsCheckpointListRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnalyticsCheckpointListRecord) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnalyticsCheckpointListRecord) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnalyticsCheckpointListRecord) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *AnalyticsCheckpointListRecord) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AnalyticsCheckpointListRecord) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AnalyticsCheckpointListRecord) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectionId

`func (o *AnalyticsCheckpointListRecord) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsCheckpointListRecord) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsCheckpointListRecord) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetCursorOccurredAt

`func (o *AnalyticsCheckpointListRecord) GetCursorOccurredAt() time.Time`

GetCursorOccurredAt returns the CursorOccurredAt field if non-nil, zero value otherwise.

### GetCursorOccurredAtOk

`func (o *AnalyticsCheckpointListRecord) GetCursorOccurredAtOk() (*time.Time, bool)`

GetCursorOccurredAtOk returns a tuple with the CursorOccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorOccurredAt

`func (o *AnalyticsCheckpointListRecord) SetCursorOccurredAt(v time.Time)`

SetCursorOccurredAt sets CursorOccurredAt field to given value.


### SetCursorOccurredAtNil

`func (o *AnalyticsCheckpointListRecord) SetCursorOccurredAtNil(b bool)`

 SetCursorOccurredAtNil sets the value for CursorOccurredAt to be an explicit nil

### UnsetCursorOccurredAt
`func (o *AnalyticsCheckpointListRecord) UnsetCursorOccurredAt()`

UnsetCursorOccurredAt ensures that no value is present for CursorOccurredAt, not even an explicit nil
### GetCursorEventId

`func (o *AnalyticsCheckpointListRecord) GetCursorEventId() string`

GetCursorEventId returns the CursorEventId field if non-nil, zero value otherwise.

### GetCursorEventIdOk

`func (o *AnalyticsCheckpointListRecord) GetCursorEventIdOk() (*string, bool)`

GetCursorEventIdOk returns a tuple with the CursorEventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursorEventId

`func (o *AnalyticsCheckpointListRecord) SetCursorEventId(v string)`

SetCursorEventId sets CursorEventId field to given value.


### SetCursorEventIdNil

`func (o *AnalyticsCheckpointListRecord) SetCursorEventIdNil(b bool)`

 SetCursorEventIdNil sets the value for CursorEventId to be an explicit nil

### UnsetCursorEventId
`func (o *AnalyticsCheckpointListRecord) UnsetCursorEventId()`

UnsetCursorEventId ensures that no value is present for CursorEventId, not even an explicit nil
### GetFencingGeneration

`func (o *AnalyticsCheckpointListRecord) GetFencingGeneration() int32`

GetFencingGeneration returns the FencingGeneration field if non-nil, zero value otherwise.

### GetFencingGenerationOk

`func (o *AnalyticsCheckpointListRecord) GetFencingGenerationOk() (*int32, bool)`

GetFencingGenerationOk returns a tuple with the FencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFencingGeneration

`func (o *AnalyticsCheckpointListRecord) SetFencingGeneration(v int32)`

SetFencingGeneration sets FencingGeneration field to given value.


### GetRevision

`func (o *AnalyticsCheckpointListRecord) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *AnalyticsCheckpointListRecord) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *AnalyticsCheckpointListRecord) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetDrift

`func (o *AnalyticsCheckpointListRecord) GetDrift() string`

GetDrift returns the Drift field if non-nil, zero value otherwise.

### GetDriftOk

`func (o *AnalyticsCheckpointListRecord) GetDriftOk() (*string, bool)`

GetDriftOk returns a tuple with the Drift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrift

`func (o *AnalyticsCheckpointListRecord) SetDrift(v string)`

SetDrift sets Drift field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


