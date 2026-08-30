# ReplayCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TargetConsumerId** | **string** |  | 
**Reason** | Pointer to **string** |  | [optional] [default to ""]
**EventTypes** | Pointer to **[]string** |  | [optional] 
**Sources** | Pointer to **[]string** |  | [optional] 
**SubjectPrefix** | Pointer to **string** |  | [optional] [default to ""]
**OccurredFrom** | Pointer to **NullableTime** |  | [optional] 
**OccurredUntil** | Pointer to **NullableTime** |  | [optional] 
**ReceivedFrom** | Pointer to **NullableTime** |  | [optional] 
**ReceivedUntil** | Pointer to **NullableTime** |  | [optional] 
**BatchSize** | Pointer to **int32** |  | [optional] [default to 100]

## Methods

### NewReplayCreateRequest

`func NewReplayCreateRequest(targetConsumerId string, ) *ReplayCreateRequest`

NewReplayCreateRequest instantiates a new ReplayCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReplayCreateRequestWithDefaults

`func NewReplayCreateRequestWithDefaults() *ReplayCreateRequest`

NewReplayCreateRequestWithDefaults instantiates a new ReplayCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTargetConsumerId

`func (o *ReplayCreateRequest) GetTargetConsumerId() string`

GetTargetConsumerId returns the TargetConsumerId field if non-nil, zero value otherwise.

### GetTargetConsumerIdOk

`func (o *ReplayCreateRequest) GetTargetConsumerIdOk() (*string, bool)`

GetTargetConsumerIdOk returns a tuple with the TargetConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetConsumerId

`func (o *ReplayCreateRequest) SetTargetConsumerId(v string)`

SetTargetConsumerId sets TargetConsumerId field to given value.


### GetReason

`func (o *ReplayCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ReplayCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ReplayCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *ReplayCreateRequest) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetEventTypes

`func (o *ReplayCreateRequest) GetEventTypes() []string`

GetEventTypes returns the EventTypes field if non-nil, zero value otherwise.

### GetEventTypesOk

`func (o *ReplayCreateRequest) GetEventTypesOk() (*[]string, bool)`

GetEventTypesOk returns a tuple with the EventTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypes

`func (o *ReplayCreateRequest) SetEventTypes(v []string)`

SetEventTypes sets EventTypes field to given value.

### HasEventTypes

`func (o *ReplayCreateRequest) HasEventTypes() bool`

HasEventTypes returns a boolean if a field has been set.

### GetSources

`func (o *ReplayCreateRequest) GetSources() []string`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ReplayCreateRequest) GetSourcesOk() (*[]string, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ReplayCreateRequest) SetSources(v []string)`

SetSources sets Sources field to given value.

### HasSources

`func (o *ReplayCreateRequest) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetSubjectPrefix

`func (o *ReplayCreateRequest) GetSubjectPrefix() string`

GetSubjectPrefix returns the SubjectPrefix field if non-nil, zero value otherwise.

### GetSubjectPrefixOk

`func (o *ReplayCreateRequest) GetSubjectPrefixOk() (*string, bool)`

GetSubjectPrefixOk returns a tuple with the SubjectPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectPrefix

`func (o *ReplayCreateRequest) SetSubjectPrefix(v string)`

SetSubjectPrefix sets SubjectPrefix field to given value.

### HasSubjectPrefix

`func (o *ReplayCreateRequest) HasSubjectPrefix() bool`

HasSubjectPrefix returns a boolean if a field has been set.

### GetOccurredFrom

`func (o *ReplayCreateRequest) GetOccurredFrom() time.Time`

GetOccurredFrom returns the OccurredFrom field if non-nil, zero value otherwise.

### GetOccurredFromOk

`func (o *ReplayCreateRequest) GetOccurredFromOk() (*time.Time, bool)`

GetOccurredFromOk returns a tuple with the OccurredFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredFrom

`func (o *ReplayCreateRequest) SetOccurredFrom(v time.Time)`

SetOccurredFrom sets OccurredFrom field to given value.

### HasOccurredFrom

`func (o *ReplayCreateRequest) HasOccurredFrom() bool`

HasOccurredFrom returns a boolean if a field has been set.

### SetOccurredFromNil

`func (o *ReplayCreateRequest) SetOccurredFromNil(b bool)`

 SetOccurredFromNil sets the value for OccurredFrom to be an explicit nil

### UnsetOccurredFrom
`func (o *ReplayCreateRequest) UnsetOccurredFrom()`

UnsetOccurredFrom ensures that no value is present for OccurredFrom, not even an explicit nil
### GetOccurredUntil

`func (o *ReplayCreateRequest) GetOccurredUntil() time.Time`

GetOccurredUntil returns the OccurredUntil field if non-nil, zero value otherwise.

### GetOccurredUntilOk

`func (o *ReplayCreateRequest) GetOccurredUntilOk() (*time.Time, bool)`

GetOccurredUntilOk returns a tuple with the OccurredUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredUntil

`func (o *ReplayCreateRequest) SetOccurredUntil(v time.Time)`

SetOccurredUntil sets OccurredUntil field to given value.

### HasOccurredUntil

`func (o *ReplayCreateRequest) HasOccurredUntil() bool`

HasOccurredUntil returns a boolean if a field has been set.

### SetOccurredUntilNil

`func (o *ReplayCreateRequest) SetOccurredUntilNil(b bool)`

 SetOccurredUntilNil sets the value for OccurredUntil to be an explicit nil

### UnsetOccurredUntil
`func (o *ReplayCreateRequest) UnsetOccurredUntil()`

UnsetOccurredUntil ensures that no value is present for OccurredUntil, not even an explicit nil
### GetReceivedFrom

`func (o *ReplayCreateRequest) GetReceivedFrom() time.Time`

GetReceivedFrom returns the ReceivedFrom field if non-nil, zero value otherwise.

### GetReceivedFromOk

`func (o *ReplayCreateRequest) GetReceivedFromOk() (*time.Time, bool)`

GetReceivedFromOk returns a tuple with the ReceivedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedFrom

`func (o *ReplayCreateRequest) SetReceivedFrom(v time.Time)`

SetReceivedFrom sets ReceivedFrom field to given value.

### HasReceivedFrom

`func (o *ReplayCreateRequest) HasReceivedFrom() bool`

HasReceivedFrom returns a boolean if a field has been set.

### SetReceivedFromNil

`func (o *ReplayCreateRequest) SetReceivedFromNil(b bool)`

 SetReceivedFromNil sets the value for ReceivedFrom to be an explicit nil

### UnsetReceivedFrom
`func (o *ReplayCreateRequest) UnsetReceivedFrom()`

UnsetReceivedFrom ensures that no value is present for ReceivedFrom, not even an explicit nil
### GetReceivedUntil

`func (o *ReplayCreateRequest) GetReceivedUntil() time.Time`

GetReceivedUntil returns the ReceivedUntil field if non-nil, zero value otherwise.

### GetReceivedUntilOk

`func (o *ReplayCreateRequest) GetReceivedUntilOk() (*time.Time, bool)`

GetReceivedUntilOk returns a tuple with the ReceivedUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedUntil

`func (o *ReplayCreateRequest) SetReceivedUntil(v time.Time)`

SetReceivedUntil sets ReceivedUntil field to given value.

### HasReceivedUntil

`func (o *ReplayCreateRequest) HasReceivedUntil() bool`

HasReceivedUntil returns a boolean if a field has been set.

### SetReceivedUntilNil

`func (o *ReplayCreateRequest) SetReceivedUntilNil(b bool)`

 SetReceivedUntilNil sets the value for ReceivedUntil to be an explicit nil

### UnsetReceivedUntil
`func (o *ReplayCreateRequest) UnsetReceivedUntil()`

UnsetReceivedUntil ensures that no value is present for ReceivedUntil, not even an explicit nil
### GetBatchSize

`func (o *ReplayCreateRequest) GetBatchSize() int32`

GetBatchSize returns the BatchSize field if non-nil, zero value otherwise.

### GetBatchSizeOk

`func (o *ReplayCreateRequest) GetBatchSizeOk() (*int32, bool)`

GetBatchSizeOk returns a tuple with the BatchSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchSize

`func (o *ReplayCreateRequest) SetBatchSize(v int32)`

SetBatchSize sets BatchSize field to given value.

### HasBatchSize

`func (o *ReplayCreateRequest) HasBatchSize() bool`

HasBatchSize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


