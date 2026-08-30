# DegradedModeOverride

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OverrideId** | **string** |  | 
**OrganizationId** | **string** |  | 
**Status** | **string** |  | 
**AllowedIntents** | **[]string** |  | 
**Authorities** | **[]string** |  | 
**Reason** | **string** |  | 
**ApprovedBy** | **string** |  | 
**ApprovalReference** | **string** |  | 
**EffectiveFrom** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**RevokedAt** | **NullableTime** |  | 
**RevokedBy** | **NullableString** |  | 
**RevocationReason** | **NullableString** |  | 
**Metadata** | **interface{}** |  | 
**Revision** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewDegradedModeOverride

`func NewDegradedModeOverride(overrideId string, organizationId string, status string, allowedIntents []string, authorities []string, reason string, approvedBy string, approvalReference string, effectiveFrom time.Time, expiresAt time.Time, revokedAt NullableTime, revokedBy NullableString, revocationReason NullableString, metadata interface{}, revision int32, createdAt time.Time, updatedAt time.Time, ) *DegradedModeOverride`

NewDegradedModeOverride instantiates a new DegradedModeOverride object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDegradedModeOverrideWithDefaults

`func NewDegradedModeOverrideWithDefaults() *DegradedModeOverride`

NewDegradedModeOverrideWithDefaults instantiates a new DegradedModeOverride object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOverrideId

`func (o *DegradedModeOverride) GetOverrideId() string`

GetOverrideId returns the OverrideId field if non-nil, zero value otherwise.

### GetOverrideIdOk

`func (o *DegradedModeOverride) GetOverrideIdOk() (*string, bool)`

GetOverrideIdOk returns a tuple with the OverrideId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrideId

`func (o *DegradedModeOverride) SetOverrideId(v string)`

SetOverrideId sets OverrideId field to given value.


### GetOrganizationId

`func (o *DegradedModeOverride) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DegradedModeOverride) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DegradedModeOverride) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetStatus

`func (o *DegradedModeOverride) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DegradedModeOverride) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DegradedModeOverride) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAllowedIntents

`func (o *DegradedModeOverride) GetAllowedIntents() []string`

GetAllowedIntents returns the AllowedIntents field if non-nil, zero value otherwise.

### GetAllowedIntentsOk

`func (o *DegradedModeOverride) GetAllowedIntentsOk() (*[]string, bool)`

GetAllowedIntentsOk returns a tuple with the AllowedIntents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedIntents

`func (o *DegradedModeOverride) SetAllowedIntents(v []string)`

SetAllowedIntents sets AllowedIntents field to given value.


### GetAuthorities

`func (o *DegradedModeOverride) GetAuthorities() []string`

GetAuthorities returns the Authorities field if non-nil, zero value otherwise.

### GetAuthoritiesOk

`func (o *DegradedModeOverride) GetAuthoritiesOk() (*[]string, bool)`

GetAuthoritiesOk returns a tuple with the Authorities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorities

`func (o *DegradedModeOverride) SetAuthorities(v []string)`

SetAuthorities sets Authorities field to given value.


### GetReason

`func (o *DegradedModeOverride) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *DegradedModeOverride) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *DegradedModeOverride) SetReason(v string)`

SetReason sets Reason field to given value.


### GetApprovedBy

`func (o *DegradedModeOverride) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *DegradedModeOverride) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *DegradedModeOverride) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.


### GetApprovalReference

`func (o *DegradedModeOverride) GetApprovalReference() string`

GetApprovalReference returns the ApprovalReference field if non-nil, zero value otherwise.

### GetApprovalReferenceOk

`func (o *DegradedModeOverride) GetApprovalReferenceOk() (*string, bool)`

GetApprovalReferenceOk returns a tuple with the ApprovalReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalReference

`func (o *DegradedModeOverride) SetApprovalReference(v string)`

SetApprovalReference sets ApprovalReference field to given value.


### GetEffectiveFrom

`func (o *DegradedModeOverride) GetEffectiveFrom() time.Time`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *DegradedModeOverride) GetEffectiveFromOk() (*time.Time, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *DegradedModeOverride) SetEffectiveFrom(v time.Time)`

SetEffectiveFrom sets EffectiveFrom field to given value.


### GetExpiresAt

`func (o *DegradedModeOverride) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *DegradedModeOverride) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *DegradedModeOverride) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetRevokedAt

`func (o *DegradedModeOverride) GetRevokedAt() time.Time`

GetRevokedAt returns the RevokedAt field if non-nil, zero value otherwise.

### GetRevokedAtOk

`func (o *DegradedModeOverride) GetRevokedAtOk() (*time.Time, bool)`

GetRevokedAtOk returns a tuple with the RevokedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedAt

`func (o *DegradedModeOverride) SetRevokedAt(v time.Time)`

SetRevokedAt sets RevokedAt field to given value.


### SetRevokedAtNil

`func (o *DegradedModeOverride) SetRevokedAtNil(b bool)`

 SetRevokedAtNil sets the value for RevokedAt to be an explicit nil

### UnsetRevokedAt
`func (o *DegradedModeOverride) UnsetRevokedAt()`

UnsetRevokedAt ensures that no value is present for RevokedAt, not even an explicit nil
### GetRevokedBy

`func (o *DegradedModeOverride) GetRevokedBy() string`

GetRevokedBy returns the RevokedBy field if non-nil, zero value otherwise.

### GetRevokedByOk

`func (o *DegradedModeOverride) GetRevokedByOk() (*string, bool)`

GetRevokedByOk returns a tuple with the RevokedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevokedBy

`func (o *DegradedModeOverride) SetRevokedBy(v string)`

SetRevokedBy sets RevokedBy field to given value.


### SetRevokedByNil

`func (o *DegradedModeOverride) SetRevokedByNil(b bool)`

 SetRevokedByNil sets the value for RevokedBy to be an explicit nil

### UnsetRevokedBy
`func (o *DegradedModeOverride) UnsetRevokedBy()`

UnsetRevokedBy ensures that no value is present for RevokedBy, not even an explicit nil
### GetRevocationReason

`func (o *DegradedModeOverride) GetRevocationReason() string`

GetRevocationReason returns the RevocationReason field if non-nil, zero value otherwise.

### GetRevocationReasonOk

`func (o *DegradedModeOverride) GetRevocationReasonOk() (*string, bool)`

GetRevocationReasonOk returns a tuple with the RevocationReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevocationReason

`func (o *DegradedModeOverride) SetRevocationReason(v string)`

SetRevocationReason sets RevocationReason field to given value.


### SetRevocationReasonNil

`func (o *DegradedModeOverride) SetRevocationReasonNil(b bool)`

 SetRevocationReasonNil sets the value for RevocationReason to be an explicit nil

### UnsetRevocationReason
`func (o *DegradedModeOverride) UnsetRevocationReason()`

UnsetRevocationReason ensures that no value is present for RevocationReason, not even an explicit nil
### GetMetadata

`func (o *DegradedModeOverride) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DegradedModeOverride) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DegradedModeOverride) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *DegradedModeOverride) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DegradedModeOverride) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetRevision

`func (o *DegradedModeOverride) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *DegradedModeOverride) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *DegradedModeOverride) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetCreatedAt

`func (o *DegradedModeOverride) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DegradedModeOverride) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DegradedModeOverride) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *DegradedModeOverride) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DegradedModeOverride) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DegradedModeOverride) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


