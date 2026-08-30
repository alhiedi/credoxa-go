# PatchedRetentionPolicyWriteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] [default to ""]
**Scope** | Pointer to [**RetentionPolicyWriteScopeEnum**](RetentionPolicyWriteScopeEnum.md) |  | [optional] 
**EventTypeId** | Pointer to **NullableString** |  | [optional] 
**Source** | Pointer to **string** |  | [optional] [default to ""]
**ArchiveAfterDays** | Pointer to **NullableInt32** |  | [optional] 
**DeleteAfterDays** | Pointer to **NullableInt32** |  | [optional] 
**RetainForever** | Pointer to **bool** |  | [optional] [default to false]
**IsEnabled** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewPatchedRetentionPolicyWriteRequest

`func NewPatchedRetentionPolicyWriteRequest() *PatchedRetentionPolicyWriteRequest`

NewPatchedRetentionPolicyWriteRequest instantiates a new PatchedRetentionPolicyWriteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchedRetentionPolicyWriteRequestWithDefaults

`func NewPatchedRetentionPolicyWriteRequestWithDefaults() *PatchedRetentionPolicyWriteRequest`

NewPatchedRetentionPolicyWriteRequestWithDefaults instantiates a new PatchedRetentionPolicyWriteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PatchedRetentionPolicyWriteRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PatchedRetentionPolicyWriteRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PatchedRetentionPolicyWriteRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PatchedRetentionPolicyWriteRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *PatchedRetentionPolicyWriteRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PatchedRetentionPolicyWriteRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PatchedRetentionPolicyWriteRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PatchedRetentionPolicyWriteRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetScope

`func (o *PatchedRetentionPolicyWriteRequest) GetScope() RetentionPolicyWriteScopeEnum`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *PatchedRetentionPolicyWriteRequest) GetScopeOk() (*RetentionPolicyWriteScopeEnum, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *PatchedRetentionPolicyWriteRequest) SetScope(v RetentionPolicyWriteScopeEnum)`

SetScope sets Scope field to given value.

### HasScope

`func (o *PatchedRetentionPolicyWriteRequest) HasScope() bool`

HasScope returns a boolean if a field has been set.

### GetEventTypeId

`func (o *PatchedRetentionPolicyWriteRequest) GetEventTypeId() string`

GetEventTypeId returns the EventTypeId field if non-nil, zero value otherwise.

### GetEventTypeIdOk

`func (o *PatchedRetentionPolicyWriteRequest) GetEventTypeIdOk() (*string, bool)`

GetEventTypeIdOk returns a tuple with the EventTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypeId

`func (o *PatchedRetentionPolicyWriteRequest) SetEventTypeId(v string)`

SetEventTypeId sets EventTypeId field to given value.

### HasEventTypeId

`func (o *PatchedRetentionPolicyWriteRequest) HasEventTypeId() bool`

HasEventTypeId returns a boolean if a field has been set.

### SetEventTypeIdNil

`func (o *PatchedRetentionPolicyWriteRequest) SetEventTypeIdNil(b bool)`

 SetEventTypeIdNil sets the value for EventTypeId to be an explicit nil

### UnsetEventTypeId
`func (o *PatchedRetentionPolicyWriteRequest) UnsetEventTypeId()`

UnsetEventTypeId ensures that no value is present for EventTypeId, not even an explicit nil
### GetSource

`func (o *PatchedRetentionPolicyWriteRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PatchedRetentionPolicyWriteRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PatchedRetentionPolicyWriteRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *PatchedRetentionPolicyWriteRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetArchiveAfterDays

`func (o *PatchedRetentionPolicyWriteRequest) GetArchiveAfterDays() int32`

GetArchiveAfterDays returns the ArchiveAfterDays field if non-nil, zero value otherwise.

### GetArchiveAfterDaysOk

`func (o *PatchedRetentionPolicyWriteRequest) GetArchiveAfterDaysOk() (*int32, bool)`

GetArchiveAfterDaysOk returns a tuple with the ArchiveAfterDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveAfterDays

`func (o *PatchedRetentionPolicyWriteRequest) SetArchiveAfterDays(v int32)`

SetArchiveAfterDays sets ArchiveAfterDays field to given value.

### HasArchiveAfterDays

`func (o *PatchedRetentionPolicyWriteRequest) HasArchiveAfterDays() bool`

HasArchiveAfterDays returns a boolean if a field has been set.

### SetArchiveAfterDaysNil

`func (o *PatchedRetentionPolicyWriteRequest) SetArchiveAfterDaysNil(b bool)`

 SetArchiveAfterDaysNil sets the value for ArchiveAfterDays to be an explicit nil

### UnsetArchiveAfterDays
`func (o *PatchedRetentionPolicyWriteRequest) UnsetArchiveAfterDays()`

UnsetArchiveAfterDays ensures that no value is present for ArchiveAfterDays, not even an explicit nil
### GetDeleteAfterDays

`func (o *PatchedRetentionPolicyWriteRequest) GetDeleteAfterDays() int32`

GetDeleteAfterDays returns the DeleteAfterDays field if non-nil, zero value otherwise.

### GetDeleteAfterDaysOk

`func (o *PatchedRetentionPolicyWriteRequest) GetDeleteAfterDaysOk() (*int32, bool)`

GetDeleteAfterDaysOk returns a tuple with the DeleteAfterDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteAfterDays

`func (o *PatchedRetentionPolicyWriteRequest) SetDeleteAfterDays(v int32)`

SetDeleteAfterDays sets DeleteAfterDays field to given value.

### HasDeleteAfterDays

`func (o *PatchedRetentionPolicyWriteRequest) HasDeleteAfterDays() bool`

HasDeleteAfterDays returns a boolean if a field has been set.

### SetDeleteAfterDaysNil

`func (o *PatchedRetentionPolicyWriteRequest) SetDeleteAfterDaysNil(b bool)`

 SetDeleteAfterDaysNil sets the value for DeleteAfterDays to be an explicit nil

### UnsetDeleteAfterDays
`func (o *PatchedRetentionPolicyWriteRequest) UnsetDeleteAfterDays()`

UnsetDeleteAfterDays ensures that no value is present for DeleteAfterDays, not even an explicit nil
### GetRetainForever

`func (o *PatchedRetentionPolicyWriteRequest) GetRetainForever() bool`

GetRetainForever returns the RetainForever field if non-nil, zero value otherwise.

### GetRetainForeverOk

`func (o *PatchedRetentionPolicyWriteRequest) GetRetainForeverOk() (*bool, bool)`

GetRetainForeverOk returns a tuple with the RetainForever field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetainForever

`func (o *PatchedRetentionPolicyWriteRequest) SetRetainForever(v bool)`

SetRetainForever sets RetainForever field to given value.

### HasRetainForever

`func (o *PatchedRetentionPolicyWriteRequest) HasRetainForever() bool`

HasRetainForever returns a boolean if a field has been set.

### GetIsEnabled

`func (o *PatchedRetentionPolicyWriteRequest) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *PatchedRetentionPolicyWriteRequest) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *PatchedRetentionPolicyWriteRequest) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *PatchedRetentionPolicyWriteRequest) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


