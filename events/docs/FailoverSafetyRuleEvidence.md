# FailoverSafetyRuleEvidence

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sequence** | **int32** |  | 
**Rule** | **string** |  | 
**Status** | **string** |  | 
**ReasonCode** | **string** |  | 
**Message** | **string** |  | 
**Mandatory** | **bool** |  | 
**Evidence** | **interface{}** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewFailoverSafetyRuleEvidence

`func NewFailoverSafetyRuleEvidence(sequence int32, rule string, status string, reasonCode string, message string, mandatory bool, evidence interface{}, createdAt time.Time, ) *FailoverSafetyRuleEvidence`

NewFailoverSafetyRuleEvidence instantiates a new FailoverSafetyRuleEvidence object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFailoverSafetyRuleEvidenceWithDefaults

`func NewFailoverSafetyRuleEvidenceWithDefaults() *FailoverSafetyRuleEvidence`

NewFailoverSafetyRuleEvidenceWithDefaults instantiates a new FailoverSafetyRuleEvidence object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSequence

`func (o *FailoverSafetyRuleEvidence) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *FailoverSafetyRuleEvidence) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *FailoverSafetyRuleEvidence) SetSequence(v int32)`

SetSequence sets Sequence field to given value.


### GetRule

`func (o *FailoverSafetyRuleEvidence) GetRule() string`

GetRule returns the Rule field if non-nil, zero value otherwise.

### GetRuleOk

`func (o *FailoverSafetyRuleEvidence) GetRuleOk() (*string, bool)`

GetRuleOk returns a tuple with the Rule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRule

`func (o *FailoverSafetyRuleEvidence) SetRule(v string)`

SetRule sets Rule field to given value.


### GetStatus

`func (o *FailoverSafetyRuleEvidence) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *FailoverSafetyRuleEvidence) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *FailoverSafetyRuleEvidence) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReasonCode

`func (o *FailoverSafetyRuleEvidence) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *FailoverSafetyRuleEvidence) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *FailoverSafetyRuleEvidence) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.


### GetMessage

`func (o *FailoverSafetyRuleEvidence) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FailoverSafetyRuleEvidence) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FailoverSafetyRuleEvidence) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetMandatory

`func (o *FailoverSafetyRuleEvidence) GetMandatory() bool`

GetMandatory returns the Mandatory field if non-nil, zero value otherwise.

### GetMandatoryOk

`func (o *FailoverSafetyRuleEvidence) GetMandatoryOk() (*bool, bool)`

GetMandatoryOk returns a tuple with the Mandatory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMandatory

`func (o *FailoverSafetyRuleEvidence) SetMandatory(v bool)`

SetMandatory sets Mandatory field to given value.


### GetEvidence

`func (o *FailoverSafetyRuleEvidence) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *FailoverSafetyRuleEvidence) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *FailoverSafetyRuleEvidence) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.


### SetEvidenceNil

`func (o *FailoverSafetyRuleEvidence) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *FailoverSafetyRuleEvidence) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetCreatedAt

`func (o *FailoverSafetyRuleEvidence) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FailoverSafetyRuleEvidence) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FailoverSafetyRuleEvidence) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


