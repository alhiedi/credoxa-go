# DeadLetterActionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**DeadLetterActionActionEnum**](DeadLetterActionActionEnum.md) |  | 
**Note** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewDeadLetterActionRequest

`func NewDeadLetterActionRequest(action DeadLetterActionActionEnum, ) *DeadLetterActionRequest`

NewDeadLetterActionRequest instantiates a new DeadLetterActionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeadLetterActionRequestWithDefaults

`func NewDeadLetterActionRequestWithDefaults() *DeadLetterActionRequest`

NewDeadLetterActionRequestWithDefaults instantiates a new DeadLetterActionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *DeadLetterActionRequest) GetAction() DeadLetterActionActionEnum`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *DeadLetterActionRequest) GetActionOk() (*DeadLetterActionActionEnum, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *DeadLetterActionRequest) SetAction(v DeadLetterActionActionEnum)`

SetAction sets Action field to given value.


### GetNote

`func (o *DeadLetterActionRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *DeadLetterActionRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *DeadLetterActionRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *DeadLetterActionRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


