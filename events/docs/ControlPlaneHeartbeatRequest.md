# ControlPlaneHeartbeatRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControllerId** | **string** |  | 
**State** | Pointer to [**RegionalControlPlaneStateEnum**](RegionalControlPlaneStateEnum.md) |  | [optional] 

## Methods

### NewControlPlaneHeartbeatRequest

`func NewControlPlaneHeartbeatRequest(controllerId string, ) *ControlPlaneHeartbeatRequest`

NewControlPlaneHeartbeatRequest instantiates a new ControlPlaneHeartbeatRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlaneHeartbeatRequestWithDefaults

`func NewControlPlaneHeartbeatRequestWithDefaults() *ControlPlaneHeartbeatRequest`

NewControlPlaneHeartbeatRequestWithDefaults instantiates a new ControlPlaneHeartbeatRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControllerId

`func (o *ControlPlaneHeartbeatRequest) GetControllerId() string`

GetControllerId returns the ControllerId field if non-nil, zero value otherwise.

### GetControllerIdOk

`func (o *ControlPlaneHeartbeatRequest) GetControllerIdOk() (*string, bool)`

GetControllerIdOk returns a tuple with the ControllerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerId

`func (o *ControlPlaneHeartbeatRequest) SetControllerId(v string)`

SetControllerId sets ControllerId field to given value.


### GetState

`func (o *ControlPlaneHeartbeatRequest) GetState() RegionalControlPlaneStateEnum`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ControlPlaneHeartbeatRequest) GetStateOk() (*RegionalControlPlaneStateEnum, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ControlPlaneHeartbeatRequest) SetState(v RegionalControlPlaneStateEnum)`

SetState sets State field to given value.

### HasState

`func (o *ControlPlaneHeartbeatRequest) HasState() bool`

HasState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


