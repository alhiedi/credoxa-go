# RegionalFailoverReconciliationAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**ActionType** | **string** |  | 
**ActionOrder** | **int64** |  | 
**Safety** | **string** |  | 
**DriftType** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**IdempotencyKey** | **string** |  | 
**Parameters** | Pointer to **interface{}** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Attempt** | Pointer to **int64** |  | [optional] 
**ApprovedBy** | Pointer to **string** |  | [optional] 
**ApprovedAt** | Pointer to **NullableTime** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRegionalFailoverReconciliationAction

`func NewRegionalFailoverReconciliationAction(id string, actionType string, actionOrder int64, safety string, driftType string, idempotencyKey string, createdAt time.Time, updatedAt time.Time, ) *RegionalFailoverReconciliationAction`

NewRegionalFailoverReconciliationAction instantiates a new RegionalFailoverReconciliationAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverReconciliationActionWithDefaults

`func NewRegionalFailoverReconciliationActionWithDefaults() *RegionalFailoverReconciliationAction`

NewRegionalFailoverReconciliationActionWithDefaults instantiates a new RegionalFailoverReconciliationAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverReconciliationAction) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverReconciliationAction) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverReconciliationAction) SetId(v string)`

SetId sets Id field to given value.


### GetActionType

`func (o *RegionalFailoverReconciliationAction) GetActionType() string`

GetActionType returns the ActionType field if non-nil, zero value otherwise.

### GetActionTypeOk

`func (o *RegionalFailoverReconciliationAction) GetActionTypeOk() (*string, bool)`

GetActionTypeOk returns a tuple with the ActionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionType

`func (o *RegionalFailoverReconciliationAction) SetActionType(v string)`

SetActionType sets ActionType field to given value.


### GetActionOrder

`func (o *RegionalFailoverReconciliationAction) GetActionOrder() int64`

GetActionOrder returns the ActionOrder field if non-nil, zero value otherwise.

### GetActionOrderOk

`func (o *RegionalFailoverReconciliationAction) GetActionOrderOk() (*int64, bool)`

GetActionOrderOk returns a tuple with the ActionOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionOrder

`func (o *RegionalFailoverReconciliationAction) SetActionOrder(v int64)`

SetActionOrder sets ActionOrder field to given value.


### GetSafety

`func (o *RegionalFailoverReconciliationAction) GetSafety() string`

GetSafety returns the Safety field if non-nil, zero value otherwise.

### GetSafetyOk

`func (o *RegionalFailoverReconciliationAction) GetSafetyOk() (*string, bool)`

GetSafetyOk returns a tuple with the Safety field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafety

`func (o *RegionalFailoverReconciliationAction) SetSafety(v string)`

SetSafety sets Safety field to given value.


### GetDriftType

`func (o *RegionalFailoverReconciliationAction) GetDriftType() string`

GetDriftType returns the DriftType field if non-nil, zero value otherwise.

### GetDriftTypeOk

`func (o *RegionalFailoverReconciliationAction) GetDriftTypeOk() (*string, bool)`

GetDriftTypeOk returns a tuple with the DriftType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriftType

`func (o *RegionalFailoverReconciliationAction) SetDriftType(v string)`

SetDriftType sets DriftType field to given value.


### GetDescription

`func (o *RegionalFailoverReconciliationAction) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RegionalFailoverReconciliationAction) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RegionalFailoverReconciliationAction) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RegionalFailoverReconciliationAction) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *RegionalFailoverReconciliationAction) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *RegionalFailoverReconciliationAction) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *RegionalFailoverReconciliationAction) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetParameters

`func (o *RegionalFailoverReconciliationAction) GetParameters() interface{}`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *RegionalFailoverReconciliationAction) GetParametersOk() (*interface{}, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *RegionalFailoverReconciliationAction) SetParameters(v interface{})`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *RegionalFailoverReconciliationAction) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### SetParametersNil

`func (o *RegionalFailoverReconciliationAction) SetParametersNil(b bool)`

 SetParametersNil sets the value for Parameters to be an explicit nil

### UnsetParameters
`func (o *RegionalFailoverReconciliationAction) UnsetParameters()`

UnsetParameters ensures that no value is present for Parameters, not even an explicit nil
### GetStatus

`func (o *RegionalFailoverReconciliationAction) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionalFailoverReconciliationAction) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionalFailoverReconciliationAction) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RegionalFailoverReconciliationAction) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAttempt

`func (o *RegionalFailoverReconciliationAction) GetAttempt() int64`

GetAttempt returns the Attempt field if non-nil, zero value otherwise.

### GetAttemptOk

`func (o *RegionalFailoverReconciliationAction) GetAttemptOk() (*int64, bool)`

GetAttemptOk returns a tuple with the Attempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempt

`func (o *RegionalFailoverReconciliationAction) SetAttempt(v int64)`

SetAttempt sets Attempt field to given value.

### HasAttempt

`func (o *RegionalFailoverReconciliationAction) HasAttempt() bool`

HasAttempt returns a boolean if a field has been set.

### GetApprovedBy

`func (o *RegionalFailoverReconciliationAction) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *RegionalFailoverReconciliationAction) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *RegionalFailoverReconciliationAction) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *RegionalFailoverReconciliationAction) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.

### GetApprovedAt

`func (o *RegionalFailoverReconciliationAction) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *RegionalFailoverReconciliationAction) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *RegionalFailoverReconciliationAction) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *RegionalFailoverReconciliationAction) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### SetApprovedAtNil

`func (o *RegionalFailoverReconciliationAction) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *RegionalFailoverReconciliationAction) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetStartedAt

`func (o *RegionalFailoverReconciliationAction) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RegionalFailoverReconciliationAction) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RegionalFailoverReconciliationAction) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RegionalFailoverReconciliationAction) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RegionalFailoverReconciliationAction) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RegionalFailoverReconciliationAction) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RegionalFailoverReconciliationAction) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RegionalFailoverReconciliationAction) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RegionalFailoverReconciliationAction) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RegionalFailoverReconciliationAction) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RegionalFailoverReconciliationAction) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RegionalFailoverReconciliationAction) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetMessage

`func (o *RegionalFailoverReconciliationAction) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionalFailoverReconciliationAction) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionalFailoverReconciliationAction) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegionalFailoverReconciliationAction) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetEvidence

`func (o *RegionalFailoverReconciliationAction) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *RegionalFailoverReconciliationAction) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *RegionalFailoverReconciliationAction) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *RegionalFailoverReconciliationAction) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *RegionalFailoverReconciliationAction) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *RegionalFailoverReconciliationAction) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetCreatedAt

`func (o *RegionalFailoverReconciliationAction) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RegionalFailoverReconciliationAction) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RegionalFailoverReconciliationAction) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RegionalFailoverReconciliationAction) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RegionalFailoverReconciliationAction) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RegionalFailoverReconciliationAction) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


