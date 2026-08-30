# LifecycleReportActionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**LifecycleReportActionActionEnum**](LifecycleReportActionActionEnum.md) |  | 
**Reason** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewLifecycleReportActionRequest

`func NewLifecycleReportActionRequest(action LifecycleReportActionActionEnum, ) *LifecycleReportActionRequest`

NewLifecycleReportActionRequest instantiates a new LifecycleReportActionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleReportActionRequestWithDefaults

`func NewLifecycleReportActionRequestWithDefaults() *LifecycleReportActionRequest`

NewLifecycleReportActionRequestWithDefaults instantiates a new LifecycleReportActionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *LifecycleReportActionRequest) GetAction() LifecycleReportActionActionEnum`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *LifecycleReportActionRequest) GetActionOk() (*LifecycleReportActionActionEnum, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *LifecycleReportActionRequest) SetAction(v LifecycleReportActionActionEnum)`

SetAction sets Action field to given value.


### GetReason

`func (o *LifecycleReportActionRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *LifecycleReportActionRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *LifecycleReportActionRequest) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *LifecycleReportActionRequest) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


