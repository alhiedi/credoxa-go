# AnalyticsLeaseCheckpointOperation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Operation** | **string** |  | 
**Status** | **string** |  | 
**OrganizationId** | **string** |  | 
**ProjectionId** | **NullableString** |  | 
**TargetResourceType** | **string** |  | 
**TargetResourceId** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**PreviousState** | **interface{}** |  | 
**ResultingState** | **interface{}** |  | 
**DispatchEvidence** | **interface{}** |  | 
**OperationFingerprint** | **string** |  | 
**CompletedAt** | **NullableTime** |  | 

## Methods

### NewAnalyticsLeaseCheckpointOperation

`func NewAnalyticsLeaseCheckpointOperation(id string, operation string, status string, organizationId string, projectionId NullableString, targetResourceType string, targetResourceId string, idempotencyKey string, previousState interface{}, resultingState interface{}, dispatchEvidence interface{}, operationFingerprint string, completedAt NullableTime, ) *AnalyticsLeaseCheckpointOperation`

NewAnalyticsLeaseCheckpointOperation instantiates a new AnalyticsLeaseCheckpointOperation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsLeaseCheckpointOperationWithDefaults

`func NewAnalyticsLeaseCheckpointOperationWithDefaults() *AnalyticsLeaseCheckpointOperation`

NewAnalyticsLeaseCheckpointOperationWithDefaults instantiates a new AnalyticsLeaseCheckpointOperation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnalyticsLeaseCheckpointOperation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnalyticsLeaseCheckpointOperation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnalyticsLeaseCheckpointOperation) SetId(v string)`

SetId sets Id field to given value.


### GetOperation

`func (o *AnalyticsLeaseCheckpointOperation) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsLeaseCheckpointOperation) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsLeaseCheckpointOperation) SetOperation(v string)`

SetOperation sets Operation field to given value.


### GetStatus

`func (o *AnalyticsLeaseCheckpointOperation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AnalyticsLeaseCheckpointOperation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AnalyticsLeaseCheckpointOperation) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOrganizationId

`func (o *AnalyticsLeaseCheckpointOperation) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AnalyticsLeaseCheckpointOperation) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AnalyticsLeaseCheckpointOperation) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectionId

`func (o *AnalyticsLeaseCheckpointOperation) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsLeaseCheckpointOperation) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsLeaseCheckpointOperation) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### SetProjectionIdNil

`func (o *AnalyticsLeaseCheckpointOperation) SetProjectionIdNil(b bool)`

 SetProjectionIdNil sets the value for ProjectionId to be an explicit nil

### UnsetProjectionId
`func (o *AnalyticsLeaseCheckpointOperation) UnsetProjectionId()`

UnsetProjectionId ensures that no value is present for ProjectionId, not even an explicit nil
### GetTargetResourceType

`func (o *AnalyticsLeaseCheckpointOperation) GetTargetResourceType() string`

GetTargetResourceType returns the TargetResourceType field if non-nil, zero value otherwise.

### GetTargetResourceTypeOk

`func (o *AnalyticsLeaseCheckpointOperation) GetTargetResourceTypeOk() (*string, bool)`

GetTargetResourceTypeOk returns a tuple with the TargetResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResourceType

`func (o *AnalyticsLeaseCheckpointOperation) SetTargetResourceType(v string)`

SetTargetResourceType sets TargetResourceType field to given value.


### GetTargetResourceId

`func (o *AnalyticsLeaseCheckpointOperation) GetTargetResourceId() string`

GetTargetResourceId returns the TargetResourceId field if non-nil, zero value otherwise.

### GetTargetResourceIdOk

`func (o *AnalyticsLeaseCheckpointOperation) GetTargetResourceIdOk() (*string, bool)`

GetTargetResourceIdOk returns a tuple with the TargetResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResourceId

`func (o *AnalyticsLeaseCheckpointOperation) SetTargetResourceId(v string)`

SetTargetResourceId sets TargetResourceId field to given value.


### GetIdempotencyKey

`func (o *AnalyticsLeaseCheckpointOperation) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *AnalyticsLeaseCheckpointOperation) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *AnalyticsLeaseCheckpointOperation) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetPreviousState

`func (o *AnalyticsLeaseCheckpointOperation) GetPreviousState() interface{}`

GetPreviousState returns the PreviousState field if non-nil, zero value otherwise.

### GetPreviousStateOk

`func (o *AnalyticsLeaseCheckpointOperation) GetPreviousStateOk() (*interface{}, bool)`

GetPreviousStateOk returns a tuple with the PreviousState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousState

`func (o *AnalyticsLeaseCheckpointOperation) SetPreviousState(v interface{})`

SetPreviousState sets PreviousState field to given value.


### SetPreviousStateNil

`func (o *AnalyticsLeaseCheckpointOperation) SetPreviousStateNil(b bool)`

 SetPreviousStateNil sets the value for PreviousState to be an explicit nil

### UnsetPreviousState
`func (o *AnalyticsLeaseCheckpointOperation) UnsetPreviousState()`

UnsetPreviousState ensures that no value is present for PreviousState, not even an explicit nil
### GetResultingState

`func (o *AnalyticsLeaseCheckpointOperation) GetResultingState() interface{}`

GetResultingState returns the ResultingState field if non-nil, zero value otherwise.

### GetResultingStateOk

`func (o *AnalyticsLeaseCheckpointOperation) GetResultingStateOk() (*interface{}, bool)`

GetResultingStateOk returns a tuple with the ResultingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingState

`func (o *AnalyticsLeaseCheckpointOperation) SetResultingState(v interface{})`

SetResultingState sets ResultingState field to given value.


### SetResultingStateNil

`func (o *AnalyticsLeaseCheckpointOperation) SetResultingStateNil(b bool)`

 SetResultingStateNil sets the value for ResultingState to be an explicit nil

### UnsetResultingState
`func (o *AnalyticsLeaseCheckpointOperation) UnsetResultingState()`

UnsetResultingState ensures that no value is present for ResultingState, not even an explicit nil
### GetDispatchEvidence

`func (o *AnalyticsLeaseCheckpointOperation) GetDispatchEvidence() interface{}`

GetDispatchEvidence returns the DispatchEvidence field if non-nil, zero value otherwise.

### GetDispatchEvidenceOk

`func (o *AnalyticsLeaseCheckpointOperation) GetDispatchEvidenceOk() (*interface{}, bool)`

GetDispatchEvidenceOk returns a tuple with the DispatchEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDispatchEvidence

`func (o *AnalyticsLeaseCheckpointOperation) SetDispatchEvidence(v interface{})`

SetDispatchEvidence sets DispatchEvidence field to given value.


### SetDispatchEvidenceNil

`func (o *AnalyticsLeaseCheckpointOperation) SetDispatchEvidenceNil(b bool)`

 SetDispatchEvidenceNil sets the value for DispatchEvidence to be an explicit nil

### UnsetDispatchEvidence
`func (o *AnalyticsLeaseCheckpointOperation) UnsetDispatchEvidence()`

UnsetDispatchEvidence ensures that no value is present for DispatchEvidence, not even an explicit nil
### GetOperationFingerprint

`func (o *AnalyticsLeaseCheckpointOperation) GetOperationFingerprint() string`

GetOperationFingerprint returns the OperationFingerprint field if non-nil, zero value otherwise.

### GetOperationFingerprintOk

`func (o *AnalyticsLeaseCheckpointOperation) GetOperationFingerprintOk() (*string, bool)`

GetOperationFingerprintOk returns a tuple with the OperationFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationFingerprint

`func (o *AnalyticsLeaseCheckpointOperation) SetOperationFingerprint(v string)`

SetOperationFingerprint sets OperationFingerprint field to given value.


### GetCompletedAt

`func (o *AnalyticsLeaseCheckpointOperation) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AnalyticsLeaseCheckpointOperation) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AnalyticsLeaseCheckpointOperation) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *AnalyticsLeaseCheckpointOperation) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AnalyticsLeaseCheckpointOperation) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


