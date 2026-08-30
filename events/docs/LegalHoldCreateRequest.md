# LegalHoldCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
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

## Methods

### NewLegalHoldCreateRequest

`func NewLegalHoldCreateRequest(organizationId string, scopeKind ScopeKindEnum, reason string, authorityReference string, effectiveFrom time.Time, createdBy string, fingerprint string, ) *LegalHoldCreateRequest`

NewLegalHoldCreateRequest instantiates a new LegalHoldCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLegalHoldCreateRequestWithDefaults

`func NewLegalHoldCreateRequestWithDefaults() *LegalHoldCreateRequest`

NewLegalHoldCreateRequestWithDefaults instantiates a new LegalHoldCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *LegalHoldCreateRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LegalHoldCreateRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LegalHoldCreateRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetStatus

`func (o *LegalHoldCreateRequest) GetStatus() ScheduledActiveReleaseStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LegalHoldCreateRequest) GetStatusOk() (*ScheduledActiveReleaseStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LegalHoldCreateRequest) SetStatus(v ScheduledActiveReleaseStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LegalHoldCreateRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetScopeKind

`func (o *LegalHoldCreateRequest) GetScopeKind() ScopeKindEnum`

GetScopeKind returns the ScopeKind field if non-nil, zero value otherwise.

### GetScopeKindOk

`func (o *LegalHoldCreateRequest) GetScopeKindOk() (*ScopeKindEnum, bool)`

GetScopeKindOk returns a tuple with the ScopeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeKind

`func (o *LegalHoldCreateRequest) SetScopeKind(v ScopeKindEnum)`

SetScopeKind sets ScopeKind field to given value.


### GetScopeValue

`func (o *LegalHoldCreateRequest) GetScopeValue() string`

GetScopeValue returns the ScopeValue field if non-nil, zero value otherwise.

### GetScopeValueOk

`func (o *LegalHoldCreateRequest) GetScopeValueOk() (*string, bool)`

GetScopeValueOk returns a tuple with the ScopeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeValue

`func (o *LegalHoldCreateRequest) SetScopeValue(v string)`

SetScopeValue sets ScopeValue field to given value.

### HasScopeValue

`func (o *LegalHoldCreateRequest) HasScopeValue() bool`

HasScopeValue returns a boolean if a field has been set.

### SetScopeValueNil

`func (o *LegalHoldCreateRequest) SetScopeValueNil(b bool)`

 SetScopeValueNil sets the value for ScopeValue to be an explicit nil

### UnsetScopeValue
`func (o *LegalHoldCreateRequest) UnsetScopeValue()`

UnsetScopeValue ensures that no value is present for ScopeValue, not even an explicit nil
### GetReason

`func (o *LegalHoldCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *LegalHoldCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *LegalHoldCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetAuthorityReference

`func (o *LegalHoldCreateRequest) GetAuthorityReference() string`

GetAuthorityReference returns the AuthorityReference field if non-nil, zero value otherwise.

### GetAuthorityReferenceOk

`func (o *LegalHoldCreateRequest) GetAuthorityReferenceOk() (*string, bool)`

GetAuthorityReferenceOk returns a tuple with the AuthorityReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorityReference

`func (o *LegalHoldCreateRequest) SetAuthorityReference(v string)`

SetAuthorityReference sets AuthorityReference field to given value.


### GetEffectiveFrom

`func (o *LegalHoldCreateRequest) GetEffectiveFrom() time.Time`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *LegalHoldCreateRequest) GetEffectiveFromOk() (*time.Time, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *LegalHoldCreateRequest) SetEffectiveFrom(v time.Time)`

SetEffectiveFrom sets EffectiveFrom field to given value.


### GetExpiresAt

`func (o *LegalHoldCreateRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *LegalHoldCreateRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *LegalHoldCreateRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *LegalHoldCreateRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *LegalHoldCreateRequest) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *LegalHoldCreateRequest) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetReleasedAt

`func (o *LegalHoldCreateRequest) GetReleasedAt() time.Time`

GetReleasedAt returns the ReleasedAt field if non-nil, zero value otherwise.

### GetReleasedAtOk

`func (o *LegalHoldCreateRequest) GetReleasedAtOk() (*time.Time, bool)`

GetReleasedAtOk returns a tuple with the ReleasedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedAt

`func (o *LegalHoldCreateRequest) SetReleasedAt(v time.Time)`

SetReleasedAt sets ReleasedAt field to given value.

### HasReleasedAt

`func (o *LegalHoldCreateRequest) HasReleasedAt() bool`

HasReleasedAt returns a boolean if a field has been set.

### SetReleasedAtNil

`func (o *LegalHoldCreateRequest) SetReleasedAtNil(b bool)`

 SetReleasedAtNil sets the value for ReleasedAt to be an explicit nil

### UnsetReleasedAt
`func (o *LegalHoldCreateRequest) UnsetReleasedAt()`

UnsetReleasedAt ensures that no value is present for ReleasedAt, not even an explicit nil
### GetReleasedBy

`func (o *LegalHoldCreateRequest) GetReleasedBy() string`

GetReleasedBy returns the ReleasedBy field if non-nil, zero value otherwise.

### GetReleasedByOk

`func (o *LegalHoldCreateRequest) GetReleasedByOk() (*string, bool)`

GetReleasedByOk returns a tuple with the ReleasedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedBy

`func (o *LegalHoldCreateRequest) SetReleasedBy(v string)`

SetReleasedBy sets ReleasedBy field to given value.

### HasReleasedBy

`func (o *LegalHoldCreateRequest) HasReleasedBy() bool`

HasReleasedBy returns a boolean if a field has been set.

### GetReleaseReason

`func (o *LegalHoldCreateRequest) GetReleaseReason() string`

GetReleaseReason returns the ReleaseReason field if non-nil, zero value otherwise.

### GetReleaseReasonOk

`func (o *LegalHoldCreateRequest) GetReleaseReasonOk() (*string, bool)`

GetReleaseReasonOk returns a tuple with the ReleaseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseReason

`func (o *LegalHoldCreateRequest) SetReleaseReason(v string)`

SetReleaseReason sets ReleaseReason field to given value.

### HasReleaseReason

`func (o *LegalHoldCreateRequest) HasReleaseReason() bool`

HasReleaseReason returns a boolean if a field has been set.

### GetCreatedBy

`func (o *LegalHoldCreateRequest) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *LegalHoldCreateRequest) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *LegalHoldCreateRequest) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetMetadata

`func (o *LegalHoldCreateRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LegalHoldCreateRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LegalHoldCreateRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LegalHoldCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *LegalHoldCreateRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *LegalHoldCreateRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetFingerprint

`func (o *LegalHoldCreateRequest) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *LegalHoldCreateRequest) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *LegalHoldCreateRequest) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


