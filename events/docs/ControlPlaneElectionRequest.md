# ControlPlaneElectionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopologyId** | **string** |  | 
**HeartbeatTimeoutSeconds** | Pointer to **int32** |  | [optional] [default to 30]
**LeaseDurationSeconds** | Pointer to **int32** |  | [optional] [default to 60]

## Methods

### NewControlPlaneElectionRequest

`func NewControlPlaneElectionRequest(topologyId string, ) *ControlPlaneElectionRequest`

NewControlPlaneElectionRequest instantiates a new ControlPlaneElectionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlaneElectionRequestWithDefaults

`func NewControlPlaneElectionRequestWithDefaults() *ControlPlaneElectionRequest`

NewControlPlaneElectionRequestWithDefaults instantiates a new ControlPlaneElectionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopologyId

`func (o *ControlPlaneElectionRequest) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *ControlPlaneElectionRequest) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *ControlPlaneElectionRequest) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetHeartbeatTimeoutSeconds

`func (o *ControlPlaneElectionRequest) GetHeartbeatTimeoutSeconds() int32`

GetHeartbeatTimeoutSeconds returns the HeartbeatTimeoutSeconds field if non-nil, zero value otherwise.

### GetHeartbeatTimeoutSecondsOk

`func (o *ControlPlaneElectionRequest) GetHeartbeatTimeoutSecondsOk() (*int32, bool)`

GetHeartbeatTimeoutSecondsOk returns a tuple with the HeartbeatTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeartbeatTimeoutSeconds

`func (o *ControlPlaneElectionRequest) SetHeartbeatTimeoutSeconds(v int32)`

SetHeartbeatTimeoutSeconds sets HeartbeatTimeoutSeconds field to given value.

### HasHeartbeatTimeoutSeconds

`func (o *ControlPlaneElectionRequest) HasHeartbeatTimeoutSeconds() bool`

HasHeartbeatTimeoutSeconds returns a boolean if a field has been set.

### GetLeaseDurationSeconds

`func (o *ControlPlaneElectionRequest) GetLeaseDurationSeconds() int32`

GetLeaseDurationSeconds returns the LeaseDurationSeconds field if non-nil, zero value otherwise.

### GetLeaseDurationSecondsOk

`func (o *ControlPlaneElectionRequest) GetLeaseDurationSecondsOk() (*int32, bool)`

GetLeaseDurationSecondsOk returns a tuple with the LeaseDurationSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseDurationSeconds

`func (o *ControlPlaneElectionRequest) SetLeaseDurationSeconds(v int32)`

SetLeaseDurationSeconds sets LeaseDurationSeconds field to given value.

### HasLeaseDurationSeconds

`func (o *ControlPlaneElectionRequest) HasLeaseDurationSeconds() bool`

HasLeaseDurationSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


