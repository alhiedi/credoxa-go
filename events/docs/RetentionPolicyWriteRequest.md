# RetentionPolicyWriteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] [default to ""]
**Scope** | [**RetentionPolicyWriteScopeEnum**](RetentionPolicyWriteScopeEnum.md) |  | 
**EventTypeId** | Pointer to **NullableString** |  | [optional] 
**Source** | Pointer to **string** |  | [optional] [default to ""]
**ArchiveAfterDays** | Pointer to **NullableInt32** |  | [optional] 
**DeleteAfterDays** | Pointer to **NullableInt32** |  | [optional] 
**RetainForever** | Pointer to **bool** |  | [optional] [default to false]
**IsEnabled** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewRetentionPolicyWriteRequest

`func NewRetentionPolicyWriteRequest(name string, scope RetentionPolicyWriteScopeEnum, ) *RetentionPolicyWriteRequest`

NewRetentionPolicyWriteRequest instantiates a new RetentionPolicyWriteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetentionPolicyWriteRequestWithDefaults

`func NewRetentionPolicyWriteRequestWithDefaults() *RetentionPolicyWriteRequest`

NewRetentionPolicyWriteRequestWithDefaults instantiates a new RetentionPolicyWriteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *RetentionPolicyWriteRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RetentionPolicyWriteRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RetentionPolicyWriteRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *RetentionPolicyWriteRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RetentionPolicyWriteRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RetentionPolicyWriteRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RetentionPolicyWriteRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetScope

`func (o *RetentionPolicyWriteRequest) GetScope() RetentionPolicyWriteScopeEnum`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *RetentionPolicyWriteRequest) GetScopeOk() (*RetentionPolicyWriteScopeEnum, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *RetentionPolicyWriteRequest) SetScope(v RetentionPolicyWriteScopeEnum)`

SetScope sets Scope field to given value.


### GetEventTypeId

`func (o *RetentionPolicyWriteRequest) GetEventTypeId() string`

GetEventTypeId returns the EventTypeId field if non-nil, zero value otherwise.

### GetEventTypeIdOk

`func (o *RetentionPolicyWriteRequest) GetEventTypeIdOk() (*string, bool)`

GetEventTypeIdOk returns a tuple with the EventTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypeId

`func (o *RetentionPolicyWriteRequest) SetEventTypeId(v string)`

SetEventTypeId sets EventTypeId field to given value.

### HasEventTypeId

`func (o *RetentionPolicyWriteRequest) HasEventTypeId() bool`

HasEventTypeId returns a boolean if a field has been set.

### SetEventTypeIdNil

`func (o *RetentionPolicyWriteRequest) SetEventTypeIdNil(b bool)`

 SetEventTypeIdNil sets the value for EventTypeId to be an explicit nil

### UnsetEventTypeId
`func (o *RetentionPolicyWriteRequest) UnsetEventTypeId()`

UnsetEventTypeId ensures that no value is present for EventTypeId, not even an explicit nil
### GetSource

`func (o *RetentionPolicyWriteRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RetentionPolicyWriteRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RetentionPolicyWriteRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *RetentionPolicyWriteRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetArchiveAfterDays

`func (o *RetentionPolicyWriteRequest) GetArchiveAfterDays() int32`

GetArchiveAfterDays returns the ArchiveAfterDays field if non-nil, zero value otherwise.

### GetArchiveAfterDaysOk

`func (o *RetentionPolicyWriteRequest) GetArchiveAfterDaysOk() (*int32, bool)`

GetArchiveAfterDaysOk returns a tuple with the ArchiveAfterDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveAfterDays

`func (o *RetentionPolicyWriteRequest) SetArchiveAfterDays(v int32)`

SetArchiveAfterDays sets ArchiveAfterDays field to given value.

### HasArchiveAfterDays

`func (o *RetentionPolicyWriteRequest) HasArchiveAfterDays() bool`

HasArchiveAfterDays returns a boolean if a field has been set.

### SetArchiveAfterDaysNil

`func (o *RetentionPolicyWriteRequest) SetArchiveAfterDaysNil(b bool)`

 SetArchiveAfterDaysNil sets the value for ArchiveAfterDays to be an explicit nil

### UnsetArchiveAfterDays
`func (o *RetentionPolicyWriteRequest) UnsetArchiveAfterDays()`

UnsetArchiveAfterDays ensures that no value is present for ArchiveAfterDays, not even an explicit nil
### GetDeleteAfterDays

`func (o *RetentionPolicyWriteRequest) GetDeleteAfterDays() int32`

GetDeleteAfterDays returns the DeleteAfterDays field if non-nil, zero value otherwise.

### GetDeleteAfterDaysOk

`func (o *RetentionPolicyWriteRequest) GetDeleteAfterDaysOk() (*int32, bool)`

GetDeleteAfterDaysOk returns a tuple with the DeleteAfterDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteAfterDays

`func (o *RetentionPolicyWriteRequest) SetDeleteAfterDays(v int32)`

SetDeleteAfterDays sets DeleteAfterDays field to given value.

### HasDeleteAfterDays

`func (o *RetentionPolicyWriteRequest) HasDeleteAfterDays() bool`

HasDeleteAfterDays returns a boolean if a field has been set.

### SetDeleteAfterDaysNil

`func (o *RetentionPolicyWriteRequest) SetDeleteAfterDaysNil(b bool)`

 SetDeleteAfterDaysNil sets the value for DeleteAfterDays to be an explicit nil

### UnsetDeleteAfterDays
`func (o *RetentionPolicyWriteRequest) UnsetDeleteAfterDays()`

UnsetDeleteAfterDays ensures that no value is present for DeleteAfterDays, not even an explicit nil
### GetRetainForever

`func (o *RetentionPolicyWriteRequest) GetRetainForever() bool`

GetRetainForever returns the RetainForever field if non-nil, zero value otherwise.

### GetRetainForeverOk

`func (o *RetentionPolicyWriteRequest) GetRetainForeverOk() (*bool, bool)`

GetRetainForeverOk returns a tuple with the RetainForever field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetainForever

`func (o *RetentionPolicyWriteRequest) SetRetainForever(v bool)`

SetRetainForever sets RetainForever field to given value.

### HasRetainForever

`func (o *RetentionPolicyWriteRequest) HasRetainForever() bool`

HasRetainForever returns a boolean if a field has been set.

### GetIsEnabled

`func (o *RetentionPolicyWriteRequest) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *RetentionPolicyWriteRequest) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *RetentionPolicyWriteRequest) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *RetentionPolicyWriteRequest) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


