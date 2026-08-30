# DegradedModeOverrideCreateRequestRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **string** |  | 
**AllowedIntents** | **[]string** |  | 
**Authorities** | **[]string** |  | 
**Reason** | **string** |  | 
**ApprovedBy** | **string** |  | 
**ApprovalReference** | Pointer to **string** |  | [optional] 
**EffectiveFrom** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**Metadata** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewDegradedModeOverrideCreateRequestRequest

`func NewDegradedModeOverrideCreateRequestRequest(organizationId string, allowedIntents []string, authorities []string, reason string, approvedBy string, effectiveFrom time.Time, expiresAt time.Time, ) *DegradedModeOverrideCreateRequestRequest`

NewDegradedModeOverrideCreateRequestRequest instantiates a new DegradedModeOverrideCreateRequestRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDegradedModeOverrideCreateRequestRequestWithDefaults

`func NewDegradedModeOverrideCreateRequestRequestWithDefaults() *DegradedModeOverrideCreateRequestRequest`

NewDegradedModeOverrideCreateRequestRequestWithDefaults instantiates a new DegradedModeOverrideCreateRequestRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *DegradedModeOverrideCreateRequestRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DegradedModeOverrideCreateRequestRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetAllowedIntents

`func (o *DegradedModeOverrideCreateRequestRequest) GetAllowedIntents() []string`

GetAllowedIntents returns the AllowedIntents field if non-nil, zero value otherwise.

### GetAllowedIntentsOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetAllowedIntentsOk() (*[]string, bool)`

GetAllowedIntentsOk returns a tuple with the AllowedIntents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedIntents

`func (o *DegradedModeOverrideCreateRequestRequest) SetAllowedIntents(v []string)`

SetAllowedIntents sets AllowedIntents field to given value.


### GetAuthorities

`func (o *DegradedModeOverrideCreateRequestRequest) GetAuthorities() []string`

GetAuthorities returns the Authorities field if non-nil, zero value otherwise.

### GetAuthoritiesOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetAuthoritiesOk() (*[]string, bool)`

GetAuthoritiesOk returns a tuple with the Authorities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorities

`func (o *DegradedModeOverrideCreateRequestRequest) SetAuthorities(v []string)`

SetAuthorities sets Authorities field to given value.


### GetReason

`func (o *DegradedModeOverrideCreateRequestRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *DegradedModeOverrideCreateRequestRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetApprovedBy

`func (o *DegradedModeOverrideCreateRequestRequest) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *DegradedModeOverrideCreateRequestRequest) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.


### GetApprovalReference

`func (o *DegradedModeOverrideCreateRequestRequest) GetApprovalReference() string`

GetApprovalReference returns the ApprovalReference field if non-nil, zero value otherwise.

### GetApprovalReferenceOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetApprovalReferenceOk() (*string, bool)`

GetApprovalReferenceOk returns a tuple with the ApprovalReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalReference

`func (o *DegradedModeOverrideCreateRequestRequest) SetApprovalReference(v string)`

SetApprovalReference sets ApprovalReference field to given value.

### HasApprovalReference

`func (o *DegradedModeOverrideCreateRequestRequest) HasApprovalReference() bool`

HasApprovalReference returns a boolean if a field has been set.

### GetEffectiveFrom

`func (o *DegradedModeOverrideCreateRequestRequest) GetEffectiveFrom() time.Time`

GetEffectiveFrom returns the EffectiveFrom field if non-nil, zero value otherwise.

### GetEffectiveFromOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetEffectiveFromOk() (*time.Time, bool)`

GetEffectiveFromOk returns a tuple with the EffectiveFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveFrom

`func (o *DegradedModeOverrideCreateRequestRequest) SetEffectiveFrom(v time.Time)`

SetEffectiveFrom sets EffectiveFrom field to given value.


### GetExpiresAt

`func (o *DegradedModeOverrideCreateRequestRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *DegradedModeOverrideCreateRequestRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetMetadata

`func (o *DegradedModeOverrideCreateRequestRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DegradedModeOverrideCreateRequestRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DegradedModeOverrideCreateRequestRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DegradedModeOverrideCreateRequestRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *DegradedModeOverrideCreateRequestRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *DegradedModeOverrideCreateRequestRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


