# RuntimeGovernanceOverrideCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mode** | [**ModeEnum**](ModeEnum.md) |  | 
**Reason** | **string** |  | 
**DurationSeconds** | **int32** |  | 
**OverrideId** | Pointer to **string** |  | [optional] 

## Methods

### NewRuntimeGovernanceOverrideCreateRequest

`func NewRuntimeGovernanceOverrideCreateRequest(mode ModeEnum, reason string, durationSeconds int32, ) *RuntimeGovernanceOverrideCreateRequest`

NewRuntimeGovernanceOverrideCreateRequest instantiates a new RuntimeGovernanceOverrideCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeGovernanceOverrideCreateRequestWithDefaults

`func NewRuntimeGovernanceOverrideCreateRequestWithDefaults() *RuntimeGovernanceOverrideCreateRequest`

NewRuntimeGovernanceOverrideCreateRequestWithDefaults instantiates a new RuntimeGovernanceOverrideCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMode

`func (o *RuntimeGovernanceOverrideCreateRequest) GetMode() ModeEnum`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *RuntimeGovernanceOverrideCreateRequest) GetModeOk() (*ModeEnum, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *RuntimeGovernanceOverrideCreateRequest) SetMode(v ModeEnum)`

SetMode sets Mode field to given value.


### GetReason

`func (o *RuntimeGovernanceOverrideCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RuntimeGovernanceOverrideCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RuntimeGovernanceOverrideCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetDurationSeconds

`func (o *RuntimeGovernanceOverrideCreateRequest) GetDurationSeconds() int32`

GetDurationSeconds returns the DurationSeconds field if non-nil, zero value otherwise.

### GetDurationSecondsOk

`func (o *RuntimeGovernanceOverrideCreateRequest) GetDurationSecondsOk() (*int32, bool)`

GetDurationSecondsOk returns a tuple with the DurationSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationSeconds

`func (o *RuntimeGovernanceOverrideCreateRequest) SetDurationSeconds(v int32)`

SetDurationSeconds sets DurationSeconds field to given value.


### GetOverrideId

`func (o *RuntimeGovernanceOverrideCreateRequest) GetOverrideId() string`

GetOverrideId returns the OverrideId field if non-nil, zero value otherwise.

### GetOverrideIdOk

`func (o *RuntimeGovernanceOverrideCreateRequest) GetOverrideIdOk() (*string, bool)`

GetOverrideIdOk returns a tuple with the OverrideId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideId

`func (o *RuntimeGovernanceOverrideCreateRequest) SetOverrideId(v string)`

SetOverrideId sets OverrideId field to given value.

### HasOverrideId

`func (o *RuntimeGovernanceOverrideCreateRequest) HasOverrideId() bool`

HasOverrideId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


