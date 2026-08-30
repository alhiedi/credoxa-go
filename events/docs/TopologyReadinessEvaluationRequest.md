# TopologyReadinessEvaluationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequiredChecks** | Pointer to [**[]RequiredChecksEnum**](RequiredChecksEnum.md) |  | [optional] 
**MinimumScore** | Pointer to **float64** |  | [optional] [default to 0.8]
**DegradedScore** | Pointer to **float64** |  | [optional] [default to 0.5]
**MaximumSignalAgeSeconds** | Pointer to **int32** |  | [optional] [default to 120]
**MaximumReplicationLagSeconds** | Pointer to **int32** |  | [optional] [default to 120]
**AllowUnknownOptionalChecks** | Pointer to **bool** |  | [optional] [default to true]
**TopologyId** | **string** |  | 

## Methods

### NewTopologyReadinessEvaluationRequest

`func NewTopologyReadinessEvaluationRequest(topologyId string, ) *TopologyReadinessEvaluationRequest`

NewTopologyReadinessEvaluationRequest instantiates a new TopologyReadinessEvaluationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopologyReadinessEvaluationRequestWithDefaults

`func NewTopologyReadinessEvaluationRequestWithDefaults() *TopologyReadinessEvaluationRequest`

NewTopologyReadinessEvaluationRequestWithDefaults instantiates a new TopologyReadinessEvaluationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequiredChecks

`func (o *TopologyReadinessEvaluationRequest) GetRequiredChecks() []RequiredChecksEnum`

GetRequiredChecks returns the RequiredChecks field if non-nil, zero value otherwise.

### GetRequiredChecksOk

`func (o *TopologyReadinessEvaluationRequest) GetRequiredChecksOk() (*[]RequiredChecksEnum, bool)`

GetRequiredChecksOk returns a tuple with the RequiredChecks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredChecks

`func (o *TopologyReadinessEvaluationRequest) SetRequiredChecks(v []RequiredChecksEnum)`

SetRequiredChecks sets RequiredChecks field to given value.

### HasRequiredChecks

`func (o *TopologyReadinessEvaluationRequest) HasRequiredChecks() bool`

HasRequiredChecks returns a boolean if a field has been set.

### GetMinimumScore

`func (o *TopologyReadinessEvaluationRequest) GetMinimumScore() float64`

GetMinimumScore returns the MinimumScore field if non-nil, zero value otherwise.

### GetMinimumScoreOk

`func (o *TopologyReadinessEvaluationRequest) GetMinimumScoreOk() (*float64, bool)`

GetMinimumScoreOk returns a tuple with the MinimumScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumScore

`func (o *TopologyReadinessEvaluationRequest) SetMinimumScore(v float64)`

SetMinimumScore sets MinimumScore field to given value.

### HasMinimumScore

`func (o *TopologyReadinessEvaluationRequest) HasMinimumScore() bool`

HasMinimumScore returns a boolean if a field has been set.

### GetDegradedScore

`func (o *TopologyReadinessEvaluationRequest) GetDegradedScore() float64`

GetDegradedScore returns the DegradedScore field if non-nil, zero value otherwise.

### GetDegradedScoreOk

`func (o *TopologyReadinessEvaluationRequest) GetDegradedScoreOk() (*float64, bool)`

GetDegradedScoreOk returns a tuple with the DegradedScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDegradedScore

`func (o *TopologyReadinessEvaluationRequest) SetDegradedScore(v float64)`

SetDegradedScore sets DegradedScore field to given value.

### HasDegradedScore

`func (o *TopologyReadinessEvaluationRequest) HasDegradedScore() bool`

HasDegradedScore returns a boolean if a field has been set.

### GetMaximumSignalAgeSeconds

`func (o *TopologyReadinessEvaluationRequest) GetMaximumSignalAgeSeconds() int32`

GetMaximumSignalAgeSeconds returns the MaximumSignalAgeSeconds field if non-nil, zero value otherwise.

### GetMaximumSignalAgeSecondsOk

`func (o *TopologyReadinessEvaluationRequest) GetMaximumSignalAgeSecondsOk() (*int32, bool)`

GetMaximumSignalAgeSecondsOk returns a tuple with the MaximumSignalAgeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumSignalAgeSeconds

`func (o *TopologyReadinessEvaluationRequest) SetMaximumSignalAgeSeconds(v int32)`

SetMaximumSignalAgeSeconds sets MaximumSignalAgeSeconds field to given value.

### HasMaximumSignalAgeSeconds

`func (o *TopologyReadinessEvaluationRequest) HasMaximumSignalAgeSeconds() bool`

HasMaximumSignalAgeSeconds returns a boolean if a field has been set.

### GetMaximumReplicationLagSeconds

`func (o *TopologyReadinessEvaluationRequest) GetMaximumReplicationLagSeconds() int32`

GetMaximumReplicationLagSeconds returns the MaximumReplicationLagSeconds field if non-nil, zero value otherwise.

### GetMaximumReplicationLagSecondsOk

`func (o *TopologyReadinessEvaluationRequest) GetMaximumReplicationLagSecondsOk() (*int32, bool)`

GetMaximumReplicationLagSecondsOk returns a tuple with the MaximumReplicationLagSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumReplicationLagSeconds

`func (o *TopologyReadinessEvaluationRequest) SetMaximumReplicationLagSeconds(v int32)`

SetMaximumReplicationLagSeconds sets MaximumReplicationLagSeconds field to given value.

### HasMaximumReplicationLagSeconds

`func (o *TopologyReadinessEvaluationRequest) HasMaximumReplicationLagSeconds() bool`

HasMaximumReplicationLagSeconds returns a boolean if a field has been set.

### GetAllowUnknownOptionalChecks

`func (o *TopologyReadinessEvaluationRequest) GetAllowUnknownOptionalChecks() bool`

GetAllowUnknownOptionalChecks returns the AllowUnknownOptionalChecks field if non-nil, zero value otherwise.

### GetAllowUnknownOptionalChecksOk

`func (o *TopologyReadinessEvaluationRequest) GetAllowUnknownOptionalChecksOk() (*bool, bool)`

GetAllowUnknownOptionalChecksOk returns a tuple with the AllowUnknownOptionalChecks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowUnknownOptionalChecks

`func (o *TopologyReadinessEvaluationRequest) SetAllowUnknownOptionalChecks(v bool)`

SetAllowUnknownOptionalChecks sets AllowUnknownOptionalChecks field to given value.

### HasAllowUnknownOptionalChecks

`func (o *TopologyReadinessEvaluationRequest) HasAllowUnknownOptionalChecks() bool`

HasAllowUnknownOptionalChecks returns a boolean if a field has been set.

### GetTopologyId

`func (o *TopologyReadinessEvaluationRequest) GetTopologyId() string`

GetTopologyId returns the TopologyId field if non-nil, zero value otherwise.

### GetTopologyIdOk

`func (o *TopologyReadinessEvaluationRequest) GetTopologyIdOk() (*string, bool)`

GetTopologyIdOk returns a tuple with the TopologyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopologyId

`func (o *TopologyReadinessEvaluationRequest) SetTopologyId(v string)`

SetTopologyId sets TopologyId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


