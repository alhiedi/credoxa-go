# RegionalFailoverVerificationCheck

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**CheckType** | **string** |  | 
**Status** | **string** |  | 
**Mandatory** | **bool** |  | 
**ReasonCode** | **string** |  | 
**Message** | Pointer to **string** |  | [optional] 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRegionalFailoverVerificationCheck

`func NewRegionalFailoverVerificationCheck(id string, checkType string, status string, mandatory bool, reasonCode string, createdAt time.Time, ) *RegionalFailoverVerificationCheck`

NewRegionalFailoverVerificationCheck instantiates a new RegionalFailoverVerificationCheck object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverVerificationCheckWithDefaults

`func NewRegionalFailoverVerificationCheckWithDefaults() *RegionalFailoverVerificationCheck`

NewRegionalFailoverVerificationCheckWithDefaults instantiates a new RegionalFailoverVerificationCheck object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverVerificationCheck) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverVerificationCheck) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverVerificationCheck) SetId(v string)`

SetId sets Id field to given value.


### GetCheckType

`func (o *RegionalFailoverVerificationCheck) GetCheckType() string`

GetCheckType returns the CheckType field if non-nil, zero value otherwise.

### GetCheckTypeOk

`func (o *RegionalFailoverVerificationCheck) GetCheckTypeOk() (*string, bool)`

GetCheckTypeOk returns a tuple with the CheckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckType

`func (o *RegionalFailoverVerificationCheck) SetCheckType(v string)`

SetCheckType sets CheckType field to given value.


### GetStatus

`func (o *RegionalFailoverVerificationCheck) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionalFailoverVerificationCheck) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionalFailoverVerificationCheck) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetMandatory

`func (o *RegionalFailoverVerificationCheck) GetMandatory() bool`

GetMandatory returns the Mandatory field if non-nil, zero value otherwise.

### GetMandatoryOk

`func (o *RegionalFailoverVerificationCheck) GetMandatoryOk() (*bool, bool)`

GetMandatoryOk returns a tuple with the Mandatory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMandatory

`func (o *RegionalFailoverVerificationCheck) SetMandatory(v bool)`

SetMandatory sets Mandatory field to given value.


### GetReasonCode

`func (o *RegionalFailoverVerificationCheck) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *RegionalFailoverVerificationCheck) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *RegionalFailoverVerificationCheck) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.


### GetMessage

`func (o *RegionalFailoverVerificationCheck) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionalFailoverVerificationCheck) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionalFailoverVerificationCheck) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegionalFailoverVerificationCheck) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetEvidence

`func (o *RegionalFailoverVerificationCheck) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *RegionalFailoverVerificationCheck) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *RegionalFailoverVerificationCheck) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *RegionalFailoverVerificationCheck) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *RegionalFailoverVerificationCheck) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *RegionalFailoverVerificationCheck) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetCreatedAt

`func (o *RegionalFailoverVerificationCheck) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RegionalFailoverVerificationCheck) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RegionalFailoverVerificationCheck) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


