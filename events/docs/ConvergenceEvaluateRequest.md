# ConvergenceEvaluateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TopologyId** | **string** |  | 
**HeartbeatTimeoutSeconds** | Pointer to **int32** |  | [optional] [default to 30]

## Methods

### NewConvergenceEvaluateRequest

`func NewConvergenceEvaluateRequest(topologyId string, ) *ConvergenceEvaluateRequest`

NewConvergenceEvaluateRequest instantiates a new ConvergenceEvaluateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConvergenceEvaluateRequestWithDefaults

`func NewConvergenceEvaluateRequestWithDefaults() *ConvergenceEvaluateRequest`

NewConvergenceEvaluateRequestWithDefaults instantiates a new ConvergenceEvaluateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopologyId

`func (o *ConvergenceEvaluateRequest) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *ConvergenceEvaluateRequest) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *ConvergenceEvaluateRequest) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.


### GetHeartbeatTimeoutSeconds

`func (o *ConvergenceEvaluateRequest) GetHeartbeatTimeoutSeconds() int32`

GetHeartbeatTimeoutSeconds returns the HeartbeatTimeoutSeconds field if non-nil, zero value otherwise.

### GetHeartbeatTimeoutSecondsOk

`func (o *ConvergenceEvaluateRequest) GetHeartbeatTimeoutSecondsOk() (*int32, bool)`

GetHeartbeatTimeoutSecondsOk returns a tuple with the HeartbeatTimeoutSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeartbeatTimeoutSeconds

`func (o *ConvergenceEvaluateRequest) SetHeartbeatTimeoutSeconds(v int32)`

SetHeartbeatTimeoutSeconds sets HeartbeatTimeoutSeconds field to given value.

### HasHeartbeatTimeoutSeconds

`func (o *ConvergenceEvaluateRequest) HasHeartbeatTimeoutSeconds() bool`

HasHeartbeatTimeoutSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


