# AnalyticsDeadLetterRecoveryOperation

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

## Methods

### NewAnalyticsDeadLetterRecoveryOperation

`func NewAnalyticsDeadLetterRecoveryOperation(id string, operation string, status string, organizationId string, projectionId NullableString, targetResourceType string, targetResourceId string, idempotencyKey string, previousState interface{}, resultingState interface{}, dispatchEvidence interface{}, operationFingerprint string, ) *AnalyticsDeadLetterRecoveryOperation`

NewAnalyticsDeadLetterRecoveryOperation instantiates a new AnalyticsDeadLetterRecoveryOperation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDeadLetterRecoveryOperationWithDefaults

`func NewAnalyticsDeadLetterRecoveryOperationWithDefaults() *AnalyticsDeadLetterRecoveryOperation`

NewAnalyticsDeadLetterRecoveryOperationWithDefaults instantiates a new AnalyticsDeadLetterRecoveryOperation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AnalyticsDeadLetterRecoveryOperation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnalyticsDeadLetterRecoveryOperation) SetId(v string)`

SetId sets Id field to given value.


### GetOperation

`func (o *AnalyticsDeadLetterRecoveryOperation) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *AnalyticsDeadLetterRecoveryOperation) SetOperation(v string)`

SetOperation sets Operation field to given value.


### GetStatus

`func (o *AnalyticsDeadLetterRecoveryOperation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AnalyticsDeadLetterRecoveryOperation) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOrganizationId

`func (o *AnalyticsDeadLetterRecoveryOperation) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AnalyticsDeadLetterRecoveryOperation) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectionId

`func (o *AnalyticsDeadLetterRecoveryOperation) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsDeadLetterRecoveryOperation) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### SetProjectionIdNil

`func (o *AnalyticsDeadLetterRecoveryOperation) SetProjectionIdNil(b bool)`

 SetProjectionIdNil sets the value for ProjectionId to be an explicit nil

### UnsetProjectionId
`func (o *AnalyticsDeadLetterRecoveryOperation) UnsetProjectionId()`

UnsetProjectionId ensures that no value is present for ProjectionId, not even an explicit nil
### GetTargetResourceType

`func (o *AnalyticsDeadLetterRecoveryOperation) GetTargetResourceType() string`

GetTargetResourceType returns the TargetResourceType field if non-nil, zero value otherwise.

### GetTargetResourceTypeOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetTargetResourceTypeOk() (*string, bool)`

GetTargetResourceTypeOk returns a tuple with the TargetResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResourceType

`func (o *AnalyticsDeadLetterRecoveryOperation) SetTargetResourceType(v string)`

SetTargetResourceType sets TargetResourceType field to given value.


### GetTargetResourceId

`func (o *AnalyticsDeadLetterRecoveryOperation) GetTargetResourceId() string`

GetTargetResourceId returns the TargetResourceId field if non-nil, zero value otherwise.

### GetTargetResourceIdOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetTargetResourceIdOk() (*string, bool)`

GetTargetResourceIdOk returns a tuple with the TargetResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResourceId

`func (o *AnalyticsDeadLetterRecoveryOperation) SetTargetResourceId(v string)`

SetTargetResourceId sets TargetResourceId field to given value.


### GetIdempotencyKey

`func (o *AnalyticsDeadLetterRecoveryOperation) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *AnalyticsDeadLetterRecoveryOperation) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetPreviousState

`func (o *AnalyticsDeadLetterRecoveryOperation) GetPreviousState() interface{}`

GetPreviousState returns the PreviousState field if non-nil, zero value otherwise.

### GetPreviousStateOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetPreviousStateOk() (*interface{}, bool)`

GetPreviousStateOk returns a tuple with the PreviousState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousState

`func (o *AnalyticsDeadLetterRecoveryOperation) SetPreviousState(v interface{})`

SetPreviousState sets PreviousState field to given value.


### SetPreviousStateNil

`func (o *AnalyticsDeadLetterRecoveryOperation) SetPreviousStateNil(b bool)`

 SetPreviousStateNil sets the value for PreviousState to be an explicit nil

### UnsetPreviousState
`func (o *AnalyticsDeadLetterRecoveryOperation) UnsetPreviousState()`

UnsetPreviousState ensures that no value is present for PreviousState, not even an explicit nil
### GetResultingState

`func (o *AnalyticsDeadLetterRecoveryOperation) GetResultingState() interface{}`

GetResultingState returns the ResultingState field if non-nil, zero value otherwise.

### GetResultingStateOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetResultingStateOk() (*interface{}, bool)`

GetResultingStateOk returns a tuple with the ResultingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingState

`func (o *AnalyticsDeadLetterRecoveryOperation) SetResultingState(v interface{})`

SetResultingState sets ResultingState field to given value.


### SetResultingStateNil

`func (o *AnalyticsDeadLetterRecoveryOperation) SetResultingStateNil(b bool)`

 SetResultingStateNil sets the value for ResultingState to be an explicit nil

### UnsetResultingState
`func (o *AnalyticsDeadLetterRecoveryOperation) UnsetResultingState()`

UnsetResultingState ensures that no value is present for ResultingState, not even an explicit nil
### GetDispatchEvidence

`func (o *AnalyticsDeadLetterRecoveryOperation) GetDispatchEvidence() interface{}`

GetDispatchEvidence returns the DispatchEvidence field if non-nil, zero value otherwise.

### GetDispatchEvidenceOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetDispatchEvidenceOk() (*interface{}, bool)`

GetDispatchEvidenceOk returns a tuple with the DispatchEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDispatchEvidence

`func (o *AnalyticsDeadLetterRecoveryOperation) SetDispatchEvidence(v interface{})`

SetDispatchEvidence sets DispatchEvidence field to given value.


### SetDispatchEvidenceNil

`func (o *AnalyticsDeadLetterRecoveryOperation) SetDispatchEvidenceNil(b bool)`

 SetDispatchEvidenceNil sets the value for DispatchEvidence to be an explicit nil

### UnsetDispatchEvidence
`func (o *AnalyticsDeadLetterRecoveryOperation) UnsetDispatchEvidence()`

UnsetDispatchEvidence ensures that no value is present for DispatchEvidence, not even an explicit nil
### GetOperationFingerprint

`func (o *AnalyticsDeadLetterRecoveryOperation) GetOperationFingerprint() string`

GetOperationFingerprint returns the OperationFingerprint field if non-nil, zero value otherwise.

### GetOperationFingerprintOk

`func (o *AnalyticsDeadLetterRecoveryOperation) GetOperationFingerprintOk() (*string, bool)`

GetOperationFingerprintOk returns a tuple with the OperationFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationFingerprint

`func (o *AnalyticsDeadLetterRecoveryOperation) SetOperationFingerprint(v string)`

SetOperationFingerprint sets OperationFingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


