# RegionReadinessEvaluationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequiredChecks** | Pointer to [**[]RequiredChecksEnum**](RequiredChecksEnum.md) |  | [optional] 
**MinimumScore** | Pointer to **float64** |  | [optional] [default to 0.8]
**DegradedScore** | Pointer to **float64** |  | [optional] [default to 0.5]
**MaximumSignalAgeSeconds** | Pointer to **int32** |  | [optional] [default to 120]
**MaximumReplicationLagSeconds** | Pointer to **int32** |  | [optional] [default to 120]
**AllowUnknownOptionalChecks** | Pointer to **bool** |  | [optional] [default to true]
**RegionId** | **string** |  | 

## Methods

### NewRegionReadinessEvaluationRequest

`func NewRegionReadinessEvaluationRequest(regionId string, ) *RegionReadinessEvaluationRequest`

NewRegionReadinessEvaluationRequest instantiates a new RegionReadinessEvaluationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionReadinessEvaluationRequestWithDefaults

`func NewRegionReadinessEvaluationRequestWithDefaults() *RegionReadinessEvaluationRequest`

NewRegionReadinessEvaluationRequestWithDefaults instantiates a new RegionReadinessEvaluationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequiredChecks

`func (o *RegionReadinessEvaluationRequest) GetRequiredChecks() []RequiredChecksEnum`

GetRequiredChecks returns the RequiredChecks field if non-nil, zero value otherwise.

### GetRequiredChecksOk

`func (o *RegionReadinessEvaluationRequest) GetRequiredChecksOk() (*[]RequiredChecksEnum, bool)`

GetRequiredChecksOk returns a tuple with the RequiredChecks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredChecks

`func (o *RegionReadinessEvaluationRequest) SetRequiredChecks(v []RequiredChecksEnum)`

SetRequiredChecks sets RequiredChecks field to given value.

### HasRequiredChecks

`func (o *RegionReadinessEvaluationRequest) HasRequiredChecks() bool`

HasRequiredChecks returns a boolean if a field has been set.

### GetMinimumScore

`func (o *RegionReadinessEvaluationRequest) GetMinimumScore() float64`

GetMinimumScore returns the MinimumScore field if non-nil, zero value otherwise.

### GetMinimumScoreOk

`func (o *RegionReadinessEvaluationRequest) GetMinimumScoreOk() (*float64, bool)`

GetMinimumScoreOk returns a tuple with the MinimumScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumScore

`func (o *RegionReadinessEvaluationRequest) SetMinimumScore(v float64)`

SetMinimumScore sets MinimumScore field to given value.

### HasMinimumScore

`func (o *RegionReadinessEvaluationRequest) HasMinimumScore() bool`

HasMinimumScore returns a boolean if a field has been set.

### GetDegradedScore

`func (o *RegionReadinessEvaluationRequest) GetDegradedScore() float64`

GetDegradedScore returns the DegradedScore field if non-nil, zero value otherwise.

### GetDegradedScoreOk

`func (o *RegionReadinessEvaluationRequest) GetDegradedScoreOk() (*float64, bool)`

GetDegradedScoreOk returns a tuple with the DegradedScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDegradedScore

`func (o *RegionReadinessEvaluationRequest) SetDegradedScore(v float64)`

SetDegradedScore sets DegradedScore field to given value.

### HasDegradedScore

`func (o *RegionReadinessEvaluationRequest) HasDegradedScore() bool`

HasDegradedScore returns a boolean if a field has been set.

### GetMaximumSignalAgeSeconds

`func (o *RegionReadinessEvaluationRequest) GetMaximumSignalAgeSeconds() int32`

GetMaximumSignalAgeSeconds returns the MaximumSignalAgeSeconds field if non-nil, zero value otherwise.

### GetMaximumSignalAgeSecondsOk

`func (o *RegionReadinessEvaluationRequest) GetMaximumSignalAgeSecondsOk() (*int32, bool)`

GetMaximumSignalAgeSecondsOk returns a tuple with the MaximumSignalAgeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumSignalAgeSeconds

`func (o *RegionReadinessEvaluationRequest) SetMaximumSignalAgeSeconds(v int32)`

SetMaximumSignalAgeSeconds sets MaximumSignalAgeSeconds field to given value.

### HasMaximumSignalAgeSeconds

`func (o *RegionReadinessEvaluationRequest) HasMaximumSignalAgeSeconds() bool`

HasMaximumSignalAgeSeconds returns a boolean if a field has been set.

### GetMaximumReplicationLagSeconds

`func (o *RegionReadinessEvaluationRequest) GetMaximumReplicationLagSeconds() int32`

GetMaximumReplicationLagSeconds returns the MaximumReplicationLagSeconds field if non-nil, zero value otherwise.

### GetMaximumReplicationLagSecondsOk

`func (o *RegionReadinessEvaluationRequest) GetMaximumReplicationLagSecondsOk() (*int32, bool)`

GetMaximumReplicationLagSecondsOk returns a tuple with the MaximumReplicationLagSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumReplicationLagSeconds

`func (o *RegionReadinessEvaluationRequest) SetMaximumReplicationLagSeconds(v int32)`

SetMaximumReplicationLagSeconds sets MaximumReplicationLagSeconds field to given value.

### HasMaximumReplicationLagSeconds

`func (o *RegionReadinessEvaluationRequest) HasMaximumReplicationLagSeconds() bool`

HasMaximumReplicationLagSeconds returns a boolean if a field has been set.

### GetAllowUnknownOptionalChecks

`func (o *RegionReadinessEvaluationRequest) GetAllowUnknownOptionalChecks() bool`

GetAllowUnknownOptionalChecks returns the AllowUnknownOptionalChecks field if non-nil, zero value otherwise.

### GetAllowUnknownOptionalChecksOk

`func (o *RegionReadinessEvaluationRequest) GetAllowUnknownOptionalChecksOk() (*bool, bool)`

GetAllowUnknownOptionalChecksOk returns a tuple with the AllowUnknownOptionalChecks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowUnknownOptionalChecks

`func (o *RegionReadinessEvaluationRequest) SetAllowUnknownOptionalChecks(v bool)`

SetAllowUnknownOptionalChecks sets AllowUnknownOptionalChecks field to given value.

### HasAllowUnknownOptionalChecks

`func (o *RegionReadinessEvaluationRequest) HasAllowUnknownOptionalChecks() bool`

HasAllowUnknownOptionalChecks returns a boolean if a field has been set.

### GetRegionId

`func (o *RegionReadinessEvaluationRequest) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *RegionReadinessEvaluationRequest) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *RegionReadinessEvaluationRequest) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


