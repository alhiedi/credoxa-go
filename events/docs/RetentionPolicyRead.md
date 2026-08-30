# RetentionPolicyRead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**Scope** | [**RetentionPolicyReadScopeEnum**](RetentionPolicyReadScopeEnum.md) |  | 
**EventTypeId** | **NullableString** |  | [readonly] 
**EventTypeName** | **NullableString** |  | [readonly] 
**Source** | **string** |  | 
**ArchiveAfterDays** | Pointer to **NullableInt64** |  | [optional] 
**DeleteAfterDays** | Pointer to **NullableInt64** |  | [optional] 
**RetainForever** | Pointer to **bool** |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRetentionPolicyRead

`func NewRetentionPolicyRead(id string, name string, scope RetentionPolicyReadScopeEnum, eventTypeId NullableString, eventTypeName NullableString, source string, createdAt time.Time, updatedAt time.Time, ) *RetentionPolicyRead`

NewRetentionPolicyRead instantiates a new RetentionPolicyRead object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetentionPolicyReadWithDefaults

`func NewRetentionPolicyReadWithDefaults() *RetentionPolicyRead`

NewRetentionPolicyReadWithDefaults instantiates a new RetentionPolicyRead object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RetentionPolicyRead) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RetentionPolicyRead) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RetentionPolicyRead) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RetentionPolicyRead) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RetentionPolicyRead) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RetentionPolicyRead) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *RetentionPolicyRead) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *RetentionPolicyRead) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *RetentionPolicyRead) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetName

`func (o *RetentionPolicyRead) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RetentionPolicyRead) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RetentionPolicyRead) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *RetentionPolicyRead) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RetentionPolicyRead) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RetentionPolicyRead) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RetentionPolicyRead) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetScope

`func (o *RetentionPolicyRead) GetScope() RetentionPolicyReadScopeEnum`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *RetentionPolicyRead) GetScopeOk() (*RetentionPolicyReadScopeEnum, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *RetentionPolicyRead) SetScope(v RetentionPolicyReadScopeEnum)`

SetScope sets Scope field to given value.


### GetEventTypeId

`func (o *RetentionPolicyRead) GetEventTypeId() string`

GetEventTypeId returns the EventTypeId field if non-nil, zero value otherwise.

### GetEventTypeIdOk

`func (o *RetentionPolicyRead) GetEventTypeIdOk() (*string, bool)`

GetEventTypeIdOk returns a tuple with the EventTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypeId

`func (o *RetentionPolicyRead) SetEventTypeId(v string)`

SetEventTypeId sets EventTypeId field to given value.


### SetEventTypeIdNil

`func (o *RetentionPolicyRead) SetEventTypeIdNil(b bool)`

 SetEventTypeIdNil sets the value for EventTypeId to be an explicit nil

### UnsetEventTypeId
`func (o *RetentionPolicyRead) UnsetEventTypeId()`

UnsetEventTypeId ensures that no value is present for EventTypeId, not even an explicit nil
### GetEventTypeName

`func (o *RetentionPolicyRead) GetEventTypeName() string`

GetEventTypeName returns the EventTypeName field if non-nil, zero value otherwise.

### GetEventTypeNameOk

`func (o *RetentionPolicyRead) GetEventTypeNameOk() (*string, bool)`

GetEventTypeNameOk returns a tuple with the EventTypeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypeName

`func (o *RetentionPolicyRead) SetEventTypeName(v string)`

SetEventTypeName sets EventTypeName field to given value.


### SetEventTypeNameNil

`func (o *RetentionPolicyRead) SetEventTypeNameNil(b bool)`

 SetEventTypeNameNil sets the value for EventTypeName to be an explicit nil

### UnsetEventTypeName
`func (o *RetentionPolicyRead) UnsetEventTypeName()`

UnsetEventTypeName ensures that no value is present for EventTypeName, not even an explicit nil
### GetSource

`func (o *RetentionPolicyRead) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RetentionPolicyRead) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RetentionPolicyRead) SetSource(v string)`

SetSource sets Source field to given value.


### GetArchiveAfterDays

`func (o *RetentionPolicyRead) GetArchiveAfterDays() int64`

GetArchiveAfterDays returns the ArchiveAfterDays field if non-nil, zero value otherwise.

### GetArchiveAfterDaysOk

`func (o *RetentionPolicyRead) GetArchiveAfterDaysOk() (*int64, bool)`

GetArchiveAfterDaysOk returns a tuple with the ArchiveAfterDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveAfterDays

`func (o *RetentionPolicyRead) SetArchiveAfterDays(v int64)`

SetArchiveAfterDays sets ArchiveAfterDays field to given value.

### HasArchiveAfterDays

`func (o *RetentionPolicyRead) HasArchiveAfterDays() bool`

HasArchiveAfterDays returns a boolean if a field has been set.

### SetArchiveAfterDaysNil

`func (o *RetentionPolicyRead) SetArchiveAfterDaysNil(b bool)`

 SetArchiveAfterDaysNil sets the value for ArchiveAfterDays to be an explicit nil

### UnsetArchiveAfterDays
`func (o *RetentionPolicyRead) UnsetArchiveAfterDays()`

UnsetArchiveAfterDays ensures that no value is present for ArchiveAfterDays, not even an explicit nil
### GetDeleteAfterDays

`func (o *RetentionPolicyRead) GetDeleteAfterDays() int64`

GetDeleteAfterDays returns the DeleteAfterDays field if non-nil, zero value otherwise.

### GetDeleteAfterDaysOk

`func (o *RetentionPolicyRead) GetDeleteAfterDaysOk() (*int64, bool)`

GetDeleteAfterDaysOk returns a tuple with the DeleteAfterDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteAfterDays

`func (o *RetentionPolicyRead) SetDeleteAfterDays(v int64)`

SetDeleteAfterDays sets DeleteAfterDays field to given value.

### HasDeleteAfterDays

`func (o *RetentionPolicyRead) HasDeleteAfterDays() bool`

HasDeleteAfterDays returns a boolean if a field has been set.

### SetDeleteAfterDaysNil

`func (o *RetentionPolicyRead) SetDeleteAfterDaysNil(b bool)`

 SetDeleteAfterDaysNil sets the value for DeleteAfterDays to be an explicit nil

### UnsetDeleteAfterDays
`func (o *RetentionPolicyRead) UnsetDeleteAfterDays()`

UnsetDeleteAfterDays ensures that no value is present for DeleteAfterDays, not even an explicit nil
### GetRetainForever

`func (o *RetentionPolicyRead) GetRetainForever() bool`

GetRetainForever returns the RetainForever field if non-nil, zero value otherwise.

### GetRetainForeverOk

`func (o *RetentionPolicyRead) GetRetainForeverOk() (*bool, bool)`

GetRetainForeverOk returns a tuple with the RetainForever field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetainForever

`func (o *RetentionPolicyRead) SetRetainForever(v bool)`

SetRetainForever sets RetainForever field to given value.

### HasRetainForever

`func (o *RetentionPolicyRead) HasRetainForever() bool`

HasRetainForever returns a boolean if a field has been set.

### GetIsEnabled

`func (o *RetentionPolicyRead) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *RetentionPolicyRead) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *RetentionPolicyRead) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *RetentionPolicyRead) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetCreatedAt

`func (o *RetentionPolicyRead) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RetentionPolicyRead) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RetentionPolicyRead) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RetentionPolicyRead) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RetentionPolicyRead) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RetentionPolicyRead) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


