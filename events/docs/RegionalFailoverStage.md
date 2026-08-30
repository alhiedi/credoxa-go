# RegionalFailoverStage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Stage** | **string** |  | 
**StageOrder** | **int64** |  | 
**Status** | Pointer to **string** |  | [optional] 
**Attempt** | Pointer to **int64** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**ExternalReference** | Pointer to **string** |  | [optional] 

## Methods

### NewRegionalFailoverStage

`func NewRegionalFailoverStage(id string, stage string, stageOrder int64, ) *RegionalFailoverStage`

NewRegionalFailoverStage instantiates a new RegionalFailoverStage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverStageWithDefaults

`func NewRegionalFailoverStageWithDefaults() *RegionalFailoverStage`

NewRegionalFailoverStageWithDefaults instantiates a new RegionalFailoverStage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverStage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverStage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverStage) SetId(v string)`

SetId sets Id field to given value.


### GetStage

`func (o *RegionalFailoverStage) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *RegionalFailoverStage) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *RegionalFailoverStage) SetStage(v string)`

SetStage sets Stage field to given value.


### GetStageOrder

`func (o *RegionalFailoverStage) GetStageOrder() int64`

GetStageOrder returns the StageOrder field if non-nil, zero value otherwise.

### GetStageOrderOk

`func (o *RegionalFailoverStage) GetStageOrderOk() (*int64, bool)`

GetStageOrderOk returns a tuple with the StageOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageOrder

`func (o *RegionalFailoverStage) SetStageOrder(v int64)`

SetStageOrder sets StageOrder field to given value.


### GetStatus

`func (o *RegionalFailoverStage) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionalFailoverStage) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionalFailoverStage) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RegionalFailoverStage) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAttempt

`func (o *RegionalFailoverStage) GetAttempt() int64`

GetAttempt returns the Attempt field if non-nil, zero value otherwise.

### GetAttemptOk

`func (o *RegionalFailoverStage) GetAttemptOk() (*int64, bool)`

GetAttemptOk returns a tuple with the Attempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempt

`func (o *RegionalFailoverStage) SetAttempt(v int64)`

SetAttempt sets Attempt field to given value.

### HasAttempt

`func (o *RegionalFailoverStage) HasAttempt() bool`

HasAttempt returns a boolean if a field has been set.

### GetStartedAt

`func (o *RegionalFailoverStage) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *RegionalFailoverStage) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *RegionalFailoverStage) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *RegionalFailoverStage) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *RegionalFailoverStage) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *RegionalFailoverStage) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *RegionalFailoverStage) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *RegionalFailoverStage) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *RegionalFailoverStage) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *RegionalFailoverStage) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *RegionalFailoverStage) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *RegionalFailoverStage) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetMessage

`func (o *RegionalFailoverStage) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionalFailoverStage) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionalFailoverStage) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegionalFailoverStage) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetEvidence

`func (o *RegionalFailoverStage) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *RegionalFailoverStage) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *RegionalFailoverStage) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *RegionalFailoverStage) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *RegionalFailoverStage) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *RegionalFailoverStage) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetExternalReference

`func (o *RegionalFailoverStage) GetExternalReference() string`

GetExternalReference returns the ExternalReference field if non-nil, zero value otherwise.

### GetExternalReferenceOk

`func (o *RegionalFailoverStage) GetExternalReferenceOk() (*string, bool)`

GetExternalReferenceOk returns a tuple with the ExternalReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalReference

`func (o *RegionalFailoverStage) SetExternalReference(v string)`

SetExternalReference sets ExternalReference field to given value.

### HasExternalReference

`func (o *RegionalFailoverStage) HasExternalReference() bool`

HasExternalReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


