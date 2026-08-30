# LifecycleExecutionControlRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**LifecycleExecutionControlActionEnum**](LifecycleExecutionControlActionEnum.md) |  | 
**Note** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewLifecycleExecutionControlRequest

`func NewLifecycleExecutionControlRequest(action LifecycleExecutionControlActionEnum, ) *LifecycleExecutionControlRequest`

NewLifecycleExecutionControlRequest instantiates a new LifecycleExecutionControlRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleExecutionControlRequestWithDefaults

`func NewLifecycleExecutionControlRequestWithDefaults() *LifecycleExecutionControlRequest`

NewLifecycleExecutionControlRequestWithDefaults instantiates a new LifecycleExecutionControlRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *LifecycleExecutionControlRequest) GetAction() LifecycleExecutionControlActionEnum`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *LifecycleExecutionControlRequest) GetActionOk() (*LifecycleExecutionControlActionEnum, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *LifecycleExecutionControlRequest) SetAction(v LifecycleExecutionControlActionEnum)`

SetAction sets Action field to given value.


### GetNote

`func (o *LifecycleExecutionControlRequest) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *LifecycleExecutionControlRequest) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *LifecycleExecutionControlRequest) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *LifecycleExecutionControlRequest) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


