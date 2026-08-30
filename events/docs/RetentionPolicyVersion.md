# RetentionPolicyVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Version** | **int64** |  | 
**Status** | Pointer to [**LifecycleDefinitionStatusEnum**](LifecycleDefinitionStatusEnum.md) |  | [optional] 
**Fingerprint** | **string** |  | 
**CatalogFingerprint** | Pointer to **string** |  | [optional] 
**CompositionFingerprint** | Pointer to **string** |  | [optional] 
**DefaultClassification** | Pointer to **string** |  | [optional] 
**EffectiveFrom** | **time.Time** |  | 
**CreatedBy** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**Policy** | **string** |  | 

## Methods

### NewRetentionPolicyVersion

`func NewRetentionPolicyVersion(id string, organizationId string, version int64, fingerprint string, effectiveFrom time.Time, createdBy string, createdAt time.Time, policy string, ) *RetentionPolicyVersion`

NewRetentionPolicyVersion instantiates a new RetentionPolicyVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetentionPolicyVersionWithDefaults

`func NewRetentionPolicyVersionWithDefaults() *RetentionPolicyVersion`

NewRetentionPolicyVersionWithDefaults instantiates a new RetentionPolicyVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RetentionPolicyVersion) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RetentionPolicyVersion) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RetentionPolicyVersion) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RetentionPolicyVersion) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RetentionPolicyVersion) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RetentionPolicyVersion) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetVersion

`func (o *RetentionPolicyVersion) GetVersion() int64`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *RetentionPolicyVersion) GetVersionOk() (*int64, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *RetentionPolicyVersion) SetVersion(v int64)`

SetVersion sets Version field to given value.


### GetStatus

`func (o *RetentionPolicyVersion) GetStatus() LifecycleDefinitionStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RetentionPolicyVersion) GetStatusOk() (*LifecycleDefinitionStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RetentionPolicyVersion) SetStatus(v LifecycleDefinitionStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RetentionPolicyVersion) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetFingerprint

`func (o *RetentionPolicyVersion) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *RetentionPolicyVersion) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *RetentionPolicyVersion) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetCatalogFingerprint

`func (o *RetentionPolicyVersion) GetCatalogFingerprint() string`

GetCatalogFingerprint returns the CatalogFingerprint field if non-nil, zero value otherwise.

### GetCatalogFingerprintOk

`func (o *RetentionPolicyVersion) GetCatalogFingerprintOk() (*string, bool)`

GetCatalogFingerprintOk returns a tuple with the CatalogFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogFingerprint

`func (o *RetentionPolicyVersion) SetCatalogFingerprint(v string)`

SetCatalogFingerprint sets CatalogFingerprint field to given value.

### HasCatalogFingerprint

`func (o *RetentionPolicyVersion) HasCatalogFingerprint() bool`

HasCatalogFingerprint returns a boolean if a field has been set.

### GetCompositionFingerprint

`func (o *RetentionPolicyVersion) GetCompositionFingerprint() string`

GetCompositionFingerprint returns the CompositionFingerprint field if non-nil, zero value otherwise.

### GetCompositionFingerprintOk

`func (o *RetentionPolicyVersion) GetCompositionFingerprintOk() (*string, bool)`

GetCompositionFingerprintOk returns a tuple with the CompositionFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionFingerprint

`func (o *RetentionPolicyVersion) SetCompositionFingerprint(v string)`

SetCompositionFingerprint sets CompositionFingerprint field to given value.

### HasCompositionFingerprint

`func (o *RetentionPolicyVersion) HasCompositionFingerprint() bool`

HasCompositionFingerprint returns a boolean if a field has been set.

### GetDefaultClassification

`func (o *RetentionPolicyVersion) GetDefaultClassification() string`

GetDefaultClassification returns the DefaultClassification field if non-nil, zero value otherwise.

### GetDefaultClassificationOk

`func (o *RetentionPolicyVersion) GetDefaultClassificationOk() (*string, bool)`

GetDefaultClassificationOk returns a tuple with the DefaultClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultClassification

`func (o *RetentionPolicyVersion) SetDefaultClassification(v string)`

SetDefaultClassification sets DefaultClassification field to given value.

### HasDefaultClassification

`func (o *RetentionPolicyVersion) HasDefaultClassification() bool`

HasDefaultClassification returns a boolean if a field has been set.

### GetEffectiveFrom

`func (o *RetentionPolicyVersion) GetEffectiveFrom() time.Time`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *RetentionPolicyVersion) GetEffectiveFromOk() (*time.Time, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *RetentionPolicyVersion) SetEffectiveFrom(v time.Time)`

SetEffectiveFrom sets EffectiveFrom field to given value.


### GetCreatedBy

`func (o *RetentionPolicyVersion) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *RetentionPolicyVersion) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *RetentionPolicyVersion) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetDescription

`func (o *RetentionPolicyVersion) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RetentionPolicyVersion) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RetentionPolicyVersion) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *RetentionPolicyVersion) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetMetadata

`func (o *RetentionPolicyVersion) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RetentionPolicyVersion) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RetentionPolicyVersion) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RetentionPolicyVersion) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *RetentionPolicyVersion) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *RetentionPolicyVersion) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCreatedAt

`func (o *RetentionPolicyVersion) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RetentionPolicyVersion) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RetentionPolicyVersion) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetPolicy

`func (o *RetentionPolicyVersion) GetPolicy() string`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *RetentionPolicyVersion) GetPolicyOk() (*string, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *RetentionPolicyVersion) SetPolicy(v string)`

SetPolicy sets Policy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


