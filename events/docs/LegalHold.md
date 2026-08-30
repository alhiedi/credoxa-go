# LegalHold

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**HoldId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**Status** | Pointer to [**ScheduledActiveReleaseStatusEnum**](ScheduledActiveReleaseStatusEnum.md) |  | [optional] 
**ScopeKind** | [**ScopeKindEnum**](ScopeKindEnum.md) |  | 
**ScopeValue** | Pointer to **NullableString** |  | [optional] 
**Reason** | **string** |  | 
**AuthorityReference** | **string** |  | 
**EffectiveFrom** | **time.Time** |  | 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**ReleasedAt** | Pointer to **NullableTime** |  | [optional] 
**ReleasedBy** | Pointer to **string** |  | [optional] 
**ReleaseReason** | Pointer to **string** |  | [optional] 
**CreatedBy** | **string** |  | 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**Fingerprint** | **string** |  | 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewLegalHold

`func NewLegalHold(id string, holdId string, organizationId string, scopeKind ScopeKindEnum, reason string, authorityReference string, effectiveFrom time.Time, createdBy string, fingerprint string, createdAt time.Time, updatedAt time.Time, ) *LegalHold`

NewLegalHold instantiates a new LegalHold object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLegalHoldWithDefaults

`func NewLegalHoldWithDefaults() *LegalHold`

NewLegalHoldWithDefaults instantiates a new LegalHold object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LegalHold) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LegalHold) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LegalHold) SetId(v string)`

SetId sets Id field to given value.


### GetHoldId

`func (o *LegalHold) GetHoldId() string`

GetHoldId returns the HoldId field if non-nil, zero value otherwise.

### GetHoldIdOk

`func (o *LegalHold) GetHoldIdOk() (*string, bool)`

GetHoldIdOk returns a tuple with the HoldId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoldId

`func (o *LegalHold) SetHoldId(v string)`

SetHoldId sets HoldId field to given value.


### GetOrganizationId

`func (o *LegalHold) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LegalHold) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LegalHold) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetStatus

`func (o *LegalHold) GetStatus() ScheduledActiveReleaseStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LegalHold) GetStatusOk() (*ScheduledActiveReleaseStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LegalHold) SetStatus(v ScheduledActiveReleaseStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LegalHold) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetScopeKind

`func (o *LegalHold) GetScopeKind() ScopeKindEnum`

GetScopeKind returns the ScopeKind field if non-nil, zero value otherwise.

### GetScopeKindOk

`func (o *LegalHold) GetScopeKindOk() (*ScopeKindEnum, bool)`

GetScopeKindOk returns a tuple with the ScopeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeKind

`func (o *LegalHold) SetScopeKind(v ScopeKindEnum)`

SetScopeKind sets ScopeKind field to given value.


### GetScopeValue

`func (o *LegalHold) GetScopeValue() string`

GetScopeValue returns the ScopeValue field if non-nil, zero value otherwise.

### GetScopeValueOk

`func (o *LegalHold) GetScopeValueOk() (*string, bool)`

GetScopeValueOk returns a tuple with the ScopeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeValue

`func (o *LegalHold) SetScopeValue(v string)`

SetScopeValue sets ScopeValue field to given value.

### HasScopeValue

`func (o *LegalHold) HasScopeValue() bool`

HasScopeValue returns a boolean if a field has been set.

### SetScopeValueNil

`func (o *LegalHold) SetScopeValueNil(b bool)`

 SetScopeValueNil sets the value for ScopeValue to be an explicit nil

### UnsetScopeValue
`func (o *LegalHold) UnsetScopeValue()`

UnsetScopeValue ensures that no value is present for ScopeValue, not even an explicit nil
### GetReason

`func (o *LegalHold) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *LegalHold) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *LegalHold) SetReason(v string)`

SetReason sets Reason field to given value.


### GetAuthorityReference

`func (o *LegalHold) GetAuthorityReference() string`

GetAuthorityReference returns the AuthorityReference field if non-nil, zero value otherwise.

### GetAuthorityReferenceOk

`func (o *LegalHold) GetAuthorityReferenceOk() (*string, bool)`

GetAuthorityReferenceOk returns a tuple with the AuthorityReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorityReference

`func (o *LegalHold) SetAuthorityReference(v string)`

SetAuthorityReference sets AuthorityReference field to given value.


### GetEffectiveFrom

`func (o *LegalHold) GetEffectiveFrom() time.Time`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *LegalHold) GetEffectiveFromOk() (*time.Time, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *LegalHold) SetEffectiveFrom(v time.Time)`

SetEffectiveFrom sets EffectiveFrom field to given value.


### GetExpiresAt

`func (o *LegalHold) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *LegalHold) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *LegalHold) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *LegalHold) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *LegalHold) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *LegalHold) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetReleasedAt

`func (o *LegalHold) GetReleasedAt() time.Time`

GetReleasedAt returns the ReleasedAt field if non-nil, zero value otherwise.

### GetReleasedAtOk

`func (o *LegalHold) GetReleasedAtOk() (*time.Time, bool)`

GetReleasedAtOk returns a tuple with the ReleasedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedAt

`func (o *LegalHold) SetReleasedAt(v time.Time)`

SetReleasedAt sets ReleasedAt field to given value.

### HasReleasedAt

`func (o *LegalHold) HasReleasedAt() bool`

HasReleasedAt returns a boolean if a field has been set.

### SetReleasedAtNil

`func (o *LegalHold) SetReleasedAtNil(b bool)`

 SetReleasedAtNil sets the value for ReleasedAt to be an explicit nil

### UnsetReleasedAt
`func (o *LegalHold) UnsetReleasedAt()`

UnsetReleasedAt ensures that no value is present for ReleasedAt, not even an explicit nil
### GetReleasedBy

`func (o *LegalHold) GetReleasedBy() string`

GetReleasedBy returns the ReleasedBy field if non-nil, zero value otherwise.

### GetReleasedByOk

`func (o *LegalHold) GetReleasedByOk() (*string, bool)`

GetReleasedByOk returns a tuple with the ReleasedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedBy

`func (o *LegalHold) SetReleasedBy(v string)`

SetReleasedBy sets ReleasedBy field to given value.

### HasReleasedBy

`func (o *LegalHold) HasReleasedBy() bool`

HasReleasedBy returns a boolean if a field has been set.

### GetReleaseReason

`func (o *LegalHold) GetReleaseReason() string`

GetReleaseReason returns the ReleaseReason field if non-nil, zero value otherwise.

### GetReleaseReasonOk

`func (o *LegalHold) GetReleaseReasonOk() (*string, bool)`

GetReleaseReasonOk returns a tuple with the ReleaseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseReason

`func (o *LegalHold) SetReleaseReason(v string)`

SetReleaseReason sets ReleaseReason field to given value.

### HasReleaseReason

`func (o *LegalHold) HasReleaseReason() bool`

HasReleaseReason returns a boolean if a field has been set.

### GetCreatedBy

`func (o *LegalHold) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *LegalHold) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *LegalHold) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetMetadata

`func (o *LegalHold) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LegalHold) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LegalHold) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LegalHold) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *LegalHold) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *LegalHold) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetFingerprint

`func (o *LegalHold) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *LegalHold) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *LegalHold) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.


### GetRevision

`func (o *LegalHold) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *LegalHold) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *LegalHold) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *LegalHold) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *LegalHold) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LegalHold) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LegalHold) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *LegalHold) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LegalHold) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LegalHold) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


