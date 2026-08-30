# RegionHealthSignalRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegionId** | **string** |  | 
**CheckType** | [**RequiredChecksEnum**](RequiredChecksEnum.md) |  | 
**Status** | [**RegionHealthSignalStatusEnum**](RegionHealthSignalStatusEnum.md) |  | 
**ObservedAt** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**LatencyMs** | Pointer to **NullableInt32** |  | [optional] 
**Value** | Pointer to **NullableFloat64** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] [default to ""]
**Source** | Pointer to **string** |  | [optional] [default to ""]
**Required** | Pointer to **bool** |  | [optional] [default to true]
**Weight** | Pointer to **int32** |  | [optional] [default to 100]
**Evidence** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewRegionHealthSignalRequest

`func NewRegionHealthSignalRequest(regionId string, checkType RequiredChecksEnum, status RegionHealthSignalStatusEnum, observedAt time.Time, expiresAt time.Time, ) *RegionHealthSignalRequest`

NewRegionHealthSignalRequest instantiates a new RegionHealthSignalRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionHealthSignalRequestWithDefaults

`func NewRegionHealthSignalRequestWithDefaults() *RegionHealthSignalRequest`

NewRegionHealthSignalRequestWithDefaults instantiates a new RegionHealthSignalRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegionId

`func (o *RegionHealthSignalRequest) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *RegionHealthSignalRequest) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *RegionHealthSignalRequest) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.


### GetCheckType

`func (o *RegionHealthSignalRequest) GetCheckType() RequiredChecksEnum`

GetCheckType returns the CheckType field if non-nil, zero value otherwise.

### GetCheckTypeOk

`func (o *RegionHealthSignalRequest) GetCheckTypeOk() (*RequiredChecksEnum, bool)`

GetCheckTypeOk returns a tuple with the CheckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckType

`func (o *RegionHealthSignalRequest) SetCheckType(v RequiredChecksEnum)`

SetCheckType sets CheckType field to given value.


### GetStatus

`func (o *RegionHealthSignalRequest) GetStatus() RegionHealthSignalStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionHealthSignalRequest) GetStatusOk() (*RegionHealthSignalStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionHealthSignalRequest) SetStatus(v RegionHealthSignalStatusEnum)`

SetStatus sets Status field to given value.


### GetObservedAt

`func (o *RegionHealthSignalRequest) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *RegionHealthSignalRequest) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *RegionHealthSignalRequest) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetExpiresAt

`func (o *RegionHealthSignalRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *RegionHealthSignalRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *RegionHealthSignalRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetLatencyMs

`func (o *RegionHealthSignalRequest) GetLatencyMs() int32`

GetLatencyMs returns the LatencyMs field if non-nil, zero value otherwise.

### GetLatencyMsOk

`func (o *RegionHealthSignalRequest) GetLatencyMsOk() (*int32, bool)`

GetLatencyMsOk returns a tuple with the LatencyMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatencyMs

`func (o *RegionHealthSignalRequest) SetLatencyMs(v int32)`

SetLatencyMs sets LatencyMs field to given value.

### HasLatencyMs

`func (o *RegionHealthSignalRequest) HasLatencyMs() bool`

HasLatencyMs returns a boolean if a field has been set.

### SetLatencyMsNil

`func (o *RegionHealthSignalRequest) SetLatencyMsNil(b bool)`

 SetLatencyMsNil sets the value for LatencyMs to be an explicit nil

### UnsetLatencyMs
`func (o *RegionHealthSignalRequest) UnsetLatencyMs()`

UnsetLatencyMs ensures that no value is present for LatencyMs, not even an explicit nil
### GetValue

`func (o *RegionHealthSignalRequest) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *RegionHealthSignalRequest) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *RegionHealthSignalRequest) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *RegionHealthSignalRequest) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *RegionHealthSignalRequest) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *RegionHealthSignalRequest) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetMessage

`func (o *RegionHealthSignalRequest) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionHealthSignalRequest) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionHealthSignalRequest) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegionHealthSignalRequest) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetSource

`func (o *RegionHealthSignalRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RegionHealthSignalRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RegionHealthSignalRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *RegionHealthSignalRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetRequired

`func (o *RegionHealthSignalRequest) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *RegionHealthSignalRequest) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *RegionHealthSignalRequest) SetRequired(v bool)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *RegionHealthSignalRequest) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetWeight

`func (o *RegionHealthSignalRequest) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *RegionHealthSignalRequest) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *RegionHealthSignalRequest) SetWeight(v int32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *RegionHealthSignalRequest) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetEvidence

`func (o *RegionHealthSignalRequest) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *RegionHealthSignalRequest) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *RegionHealthSignalRequest) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *RegionHealthSignalRequest) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *RegionHealthSignalRequest) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *RegionHealthSignalRequest) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


