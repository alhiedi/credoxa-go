# LifecycleAlertActionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**LifecycleAlertActionActionEnum**](LifecycleAlertActionActionEnum.md) |  | 
**Note** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewLifecycleAlertActionRequest

`func NewLifecycleAlertActionRequest(action LifecycleAlertActionActionEnum, ) *LifecycleAlertActionRequest`

NewLifecycleAlertActionRequest instantiates a new LifecycleAlertActionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleAlertActionRequestWithDefaults

`func NewLifecycleAlertActionRequestWithDefaults() *LifecycleAlertActionRequest`

NewLifecycleAlertActionRequestWithDefaults instantiates a new LifecycleAlertActionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *LifecycleAlertActionRequest) GetAction() LifecycleAlertActionActionEnum`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *LifecycleAlertActionRequest) GetActionOk() (*LifecycleAlertActionActionEnum, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *LifecycleAlertActionRequest) SetAction(v LifecycleAlertActionActionEnum)`

SetAction sets Action field to given value.


### GetNote

`func (o *LifecycleAlertActionRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *LifecycleAlertActionRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *LifecycleAlertActionRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *LifecycleAlertActionRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


