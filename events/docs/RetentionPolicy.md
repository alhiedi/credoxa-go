# RetentionPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**PolicyId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Name** | **string** |  | 
**Status** | Pointer to [**LifecycleDefinitionStatusEnum**](LifecycleDefinitionStatusEnum.md) |  | [optional] 
**CurrentVersion** | Pointer to **int64** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**ActiveVersion** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRetentionPolicy

`func NewRetentionPolicy(id string, policyId string, organizationId string, name string, createdAt time.Time, updatedAt time.Time, ) *RetentionPolicy`

NewRetentionPolicy instantiates a new RetentionPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetentionPolicyWithDefaults

`func NewRetentionPolicyWithDefaults() *RetentionPolicy`

NewRetentionPolicyWithDefaults instantiates a new RetentionPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RetentionPolicy) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RetentionPolicy) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RetentionPolicy) SetId(v string)`

SetId sets Id field to given value.


### GetPolicyId

`func (o *RetentionPolicy) GetPolicyId() string`

GetPolicyId returns the PolicyId field if non-nil, zero value otherwise.

### GetPolicyIdOk

`func (o *RetentionPolicy) GetPolicyIdOk() (*string, bool)`

GetPolicyIdOk returns a tuple with the PolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyId

`func (o *RetentionPolicy) SetPolicyId(v string)`

SetPolicyId sets PolicyId field to given value.


### GetOrganizationId

`func (o *RetentionPolicy) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RetentionPolicy) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RetentionPolicy) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetName

`func (o *RetentionPolicy) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RetentionPolicy) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RetentionPolicy) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *RetentionPolicy) GetStatus() LifecycleDefinitionStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RetentionPolicy) GetStatusOk() (*LifecycleDefinitionStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RetentionPolicy) SetStatus(v LifecycleDefinitionStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RetentionPolicy) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCurrentVersion

`func (o *RetentionPolicy) GetCurrentVersion() int64`

GetCurrentVersion returns the CurrentVersion field if non-nil, zero value otherwise.

### GetCurrentVersionOk

`func (o *RetentionPolicy) GetCurrentVersionOk() (*int64, bool)`

GetCurrentVersionOk returns a tuple with the CurrentVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentVersion

`func (o *RetentionPolicy) SetCurrentVersion(v int64)`

SetCurrentVersion sets CurrentVersion field to given value.

### HasCurrentVersion

`func (o *RetentionPolicy) HasCurrentVersion() bool`

HasCurrentVersion returns a boolean if a field has been set.

### GetDescription

`func (o *RetentionPolicy) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RetentionPolicy) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RetentionPolicy) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RetentionPolicy) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetMetadata

`func (o *RetentionPolicy) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RetentionPolicy) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RetentionPolicy) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RetentionPolicy) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *RetentionPolicy) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *RetentionPolicy) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *RetentionPolicy) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RetentionPolicy) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RetentionPolicy) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RetentionPolicy) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RetentionPolicy) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RetentionPolicy) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetActiveVersion

`func (o *RetentionPolicy) GetActiveVersion() string`

GetActiveVersion returns the ActiveVersion field if non-nil, zero value otherwise.

### GetActiveVersionOk

`func (o *RetentionPolicy) GetActiveVersionOk() (*string, bool)`

GetActiveVersionOk returns a tuple with the ActiveVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveVersion

`func (o *RetentionPolicy) SetActiveVersion(v string)`

SetActiveVersion sets ActiveVersion field to given value.

### HasActiveVersion

`func (o *RetentionPolicy) HasActiveVersion() bool`

HasActiveVersion returns a boolean if a field has been set.

### SetActiveVersionNil

`func (o *RetentionPolicy) SetActiveVersionNil(b bool)`

 SetActiveVersionNil sets the value for ActiveVersion to be an explicit nil

### UnsetActiveVersion
`func (o *RetentionPolicy) UnsetActiveVersion()`

UnsetActiveVersion ensures that no value is present for ActiveVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


