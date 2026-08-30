# LifecycleReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**ReportId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**ReportType** | [**LifecycleReportReportTypeEnum**](LifecycleReportReportTypeEnum.md) |  | 
**Status** | Pointer to [**LifecycleReportStatusEnum**](LifecycleReportStatusEnum.md) |  | [optional] 
**RequestedBy** | **string** |  | 
**RequestedAt** | Pointer to **time.Time** |  | [optional] 
**GeneratedAt** | Pointer to **NullableTime** |  | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**Generation** | Pointer to **int64** |  | [optional] [default to 1]
**IdempotencyKey** | **string** |  | 
**ContentType** | Pointer to **string** |  | [optional] 
**Filename** | Pointer to **string** |  | [optional] 
**Manifest** | Pointer to **interface{}** |  | [optional] 
**EvidencePayload** | Pointer to **interface{}** |  | [optional] 
**CanonicalDigest** | Pointer to **string** |  | [optional] 
**SignatureAlgorithm** | Pointer to **string** |  | [optional] 
**SignatureKeyId** | Pointer to **string** |  | [optional] 
**Signature** | Pointer to **string** |  | [optional] 
**RecordCount** | Pointer to **int64** |  | [optional] 
**ByteCount** | Pointer to **int64** |  | [optional] 
**FailureCode** | Pointer to **string** |  | [optional] 
**FailureMessage** | Pointer to **string** |  | [optional] 
**AuditEvidence** | Pointer to **interface{}** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewLifecycleReport

`func NewLifecycleReport(id string, reportId string, organizationId string, reportType LifecycleReportReportTypeEnum, requestedBy string, idempotencyKey string, createdAt time.Time, updatedAt time.Time, ) *LifecycleReport`

NewLifecycleReport instantiates a new LifecycleReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleReportWithDefaults

`func NewLifecycleReportWithDefaults() *LifecycleReport`

NewLifecycleReportWithDefaults instantiates a new LifecycleReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LifecycleReport) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LifecycleReport) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LifecycleReport) SetId(v string)`

SetId sets Id field to given value.


### GetReportId

`func (o *LifecycleReport) GetReportId() string`

GetReportId returns the ReportId field if non-nil, zero value otherwise.

### GetReportIdOk

`func (o *LifecycleReport) GetReportIdOk() (*string, bool)`

GetReportIdOk returns a tuple with the ReportId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportId

`func (o *LifecycleReport) SetReportId(v string)`

SetReportId sets ReportId field to given value.


### GetOrganizationId

`func (o *LifecycleReport) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleReport) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleReport) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetReportType

`func (o *LifecycleReport) GetReportType() LifecycleReportReportTypeEnum`

GetReportType returns the ReportType field if non-nil, zero value otherwise.

### GetReportTypeOk

`func (o *LifecycleReport) GetReportTypeOk() (*LifecycleReportReportTypeEnum, bool)`

GetReportTypeOk returns a tuple with the ReportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportType

`func (o *LifecycleReport) SetReportType(v LifecycleReportReportTypeEnum)`

SetReportType sets ReportType field to given value.


### GetStatus

`func (o *LifecycleReport) GetStatus() LifecycleReportStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LifecycleReport) GetStatusOk() (*LifecycleReportStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LifecycleReport) SetStatus(v LifecycleReportStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LifecycleReport) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetRequestedBy

`func (o *LifecycleReport) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *LifecycleReport) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *LifecycleReport) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetRequestedAt

`func (o *LifecycleReport) GetRequestedAt() time.Time`

GetRequestedAt returns the RequestedAt field if non-nil, zero value otherwise.

### GetRequestedAtOk

`func (o *LifecycleReport) GetRequestedAtOk() (*time.Time, bool)`

GetRequestedAtOk returns a tuple with the RequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedAt

`func (o *LifecycleReport) SetRequestedAt(v time.Time)`

SetRequestedAt sets RequestedAt field to given value.

### HasRequestedAt

`func (o *LifecycleReport) HasRequestedAt() bool`

HasRequestedAt returns a boolean if a field has been set.

### GetGeneratedAt

`func (o *LifecycleReport) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *LifecycleReport) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *LifecycleReport) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.

### HasGeneratedAt

`func (o *LifecycleReport) HasGeneratedAt() bool`

HasGeneratedAt returns a boolean if a field has been set.

### SetGeneratedAtNil

`func (o *LifecycleReport) SetGeneratedAtNil(b bool)`

 SetGeneratedAtNil sets the value for GeneratedAt to be an explicit nil

### UnsetGeneratedAt
`func (o *LifecycleReport) UnsetGeneratedAt()`

UnsetGeneratedAt ensures that no value is present for GeneratedAt, not even an explicit nil
### GetExpiresAt

`func (o *LifecycleReport) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *LifecycleReport) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *LifecycleReport) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *LifecycleReport) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *LifecycleReport) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *LifecycleReport) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetGeneration

`func (o *LifecycleReport) GetGeneration() int64`

GetGeneration returns the Generation field if non-nil, zero value otherwise.

### GetGenerationOk

`func (o *LifecycleReport) GetGenerationOk() (*int64, bool)`

GetGenerationOk returns a tuple with the Generation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneration

`func (o *LifecycleReport) SetGeneration(v int64)`

SetGeneration sets Generation field to given value.

### HasGeneration

`func (o *LifecycleReport) HasGeneration() bool`

HasGeneration returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *LifecycleReport) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *LifecycleReport) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *LifecycleReport) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetContentType

`func (o *LifecycleReport) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *LifecycleReport) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *LifecycleReport) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *LifecycleReport) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### GetFilename

`func (o *LifecycleReport) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *LifecycleReport) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *LifecycleReport) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *LifecycleReport) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### GetManifest

`func (o *LifecycleReport) GetManifest() interface{}`

GetManifest returns the Manifest field if non-nil, zero value otherwise.

### GetManifestOk

`func (o *LifecycleReport) GetManifestOk() (*interface{}, bool)`

GetManifestOk returns a tuple with the Manifest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifest

`func (o *LifecycleReport) SetManifest(v interface{})`

SetManifest sets Manifest field to given value.

### HasManifest

`func (o *LifecycleReport) HasManifest() bool`

HasManifest returns a boolean if a field has been set.

### SetManifestNil

`func (o *LifecycleReport) SetManifestNil(b bool)`

 SetManifestNil sets the value for Manifest to be an explicit nil

### UnsetManifest
`func (o *LifecycleReport) UnsetManifest()`

UnsetManifest ensures that no value is present for Manifest, not even an explicit nil
### GetEvidencePayload

`func (o *LifecycleReport) GetEvidencePayload() interface{}`

GetEvidencePayload returns the EvidencePayload field if non-nil, zero value otherwise.

### GetEvidencePayloadOk

`func (o *LifecycleReport) GetEvidencePayloadOk() (*interface{}, bool)`

GetEvidencePayloadOk returns a tuple with the EvidencePayload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidencePayload

`func (o *LifecycleReport) SetEvidencePayload(v interface{})`

SetEvidencePayload sets EvidencePayload field to given value.

### HasEvidencePayload

`func (o *LifecycleReport) HasEvidencePayload() bool`

HasEvidencePayload returns a boolean if a field has been set.

### SetEvidencePayloadNil

`func (o *LifecycleReport) SetEvidencePayloadNil(b bool)`

 SetEvidencePayloadNil sets the value for EvidencePayload to be an explicit nil

### UnsetEvidencePayload
`func (o *LifecycleReport) UnsetEvidencePayload()`

UnsetEvidencePayload ensures that no value is present for EvidencePayload, not even an explicit nil
### GetCanonicalDigest

`func (o *LifecycleReport) GetCanonicalDigest() string`

GetCanonicalDigest returns the CanonicalDigest field if non-nil, zero value otherwise.

### GetCanonicalDigestOk

`func (o *LifecycleReport) GetCanonicalDigestOk() (*string, bool)`

GetCanonicalDigestOk returns a tuple with the CanonicalDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalDigest

`func (o *LifecycleReport) SetCanonicalDigest(v string)`

SetCanonicalDigest sets CanonicalDigest field to given value.

### HasCanonicalDigest

`func (o *LifecycleReport) HasCanonicalDigest() bool`

HasCanonicalDigest returns a boolean if a field has been set.

### GetSignatureAlgorithm

`func (o *LifecycleReport) GetSignatureAlgorithm() string`

GetSignatureAlgorithm returns the SignatureAlgorithm field if non-nil, zero value otherwise.

### GetSignatureAlgorithmOk

`func (o *LifecycleReport) GetSignatureAlgorithmOk() (*string, bool)`

GetSignatureAlgorithmOk returns a tuple with the SignatureAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureAlgorithm

`func (o *LifecycleReport) SetSignatureAlgorithm(v string)`

SetSignatureAlgorithm sets SignatureAlgorithm field to given value.

### HasSignatureAlgorithm

`func (o *LifecycleReport) HasSignatureAlgorithm() bool`

HasSignatureAlgorithm returns a boolean if a field has been set.

### GetSignatureKeyId

`func (o *LifecycleReport) GetSignatureKeyId() string`

GetSignatureKeyId returns the SignatureKeyId field if non-nil, zero value otherwise.

### GetSignatureKeyIdOk

`func (o *LifecycleReport) GetSignatureKeyIdOk() (*string, bool)`

GetSignatureKeyIdOk returns a tuple with the SignatureKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureKeyId

`func (o *LifecycleReport) SetSignatureKeyId(v string)`

SetSignatureKeyId sets SignatureKeyId field to given value.

### HasSignatureKeyId

`func (o *LifecycleReport) HasSignatureKeyId() bool`

HasSignatureKeyId returns a boolean if a field has been set.

### GetSignature

`func (o *LifecycleReport) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *LifecycleReport) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *LifecycleReport) SetSignature(v string)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *LifecycleReport) HasSignature() bool`

HasSignature returns a boolean if a field has been set.

### GetRecordCount

`func (o *LifecycleReport) GetRecordCount() int64`

GetRecordCount returns the RecordCount field if non-nil, zero value otherwise.

### GetRecordCountOk

`func (o *LifecycleReport) GetRecordCountOk() (*int64, bool)`

GetRecordCountOk returns a tuple with the RecordCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordCount

`func (o *LifecycleReport) SetRecordCount(v int64)`

SetRecordCount sets RecordCount field to given value.

### HasRecordCount

`func (o *LifecycleReport) HasRecordCount() bool`

HasRecordCount returns a boolean if a field has been set.

### GetByteCount

`func (o *LifecycleReport) GetByteCount() int64`

GetByteCount returns the ByteCount field if non-nil, zero value otherwise.

### GetByteCountOk

`func (o *LifecycleReport) GetByteCountOk() (*int64, bool)`

GetByteCountOk returns a tuple with the ByteCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByteCount

`func (o *LifecycleReport) SetByteCount(v int64)`

SetByteCount sets ByteCount field to given value.

### HasByteCount

`func (o *LifecycleReport) HasByteCount() bool`

HasByteCount returns a boolean if a field has been set.

### GetFailureCode

`func (o *LifecycleReport) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *LifecycleReport) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *LifecycleReport) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *LifecycleReport) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### GetFailureMessage

`func (o *LifecycleReport) GetFailureMessage() string`

GetFailureMessage returns the FailureMessage field if non-nil, zero value otherwise.

### GetFailureMessageOk

`func (o *LifecycleReport) GetFailureMessageOk() (*string, bool)`

GetFailureMessageOk returns a tuple with the FailureMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureMessage

`func (o *LifecycleReport) SetFailureMessage(v string)`

SetFailureMessage sets FailureMessage field to given value.

### HasFailureMessage

`func (o *LifecycleReport) HasFailureMessage() bool`

HasFailureMessage returns a boolean if a field has been set.

### GetAuditEvidence

`func (o *LifecycleReport) GetAuditEvidence() interface{}`

GetAuditEvidence returns the AuditEvidence field if non-nil, zero value otherwise.

### GetAuditEvidenceOk

`func (o *LifecycleReport) GetAuditEvidenceOk() (*interface{}, bool)`

GetAuditEvidenceOk returns a tuple with the AuditEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditEvidence

`func (o *LifecycleReport) SetAuditEvidence(v interface{})`

SetAuditEvidence sets AuditEvidence field to given value.

### HasAuditEvidence

`func (o *LifecycleReport) HasAuditEvidence() bool`

HasAuditEvidence returns a boolean if a field has been set.

### SetAuditEvidenceNil

`func (o *LifecycleReport) SetAuditEvidenceNil(b bool)`

 SetAuditEvidenceNil sets the value for AuditEvidence to be an explicit nil

### UnsetAuditEvidence
`func (o *LifecycleReport) UnsetAuditEvidence()`

UnsetAuditEvidence ensures that no value is present for AuditEvidence, not even an explicit nil
### GetRevision

`func (o *LifecycleReport) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *LifecycleReport) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *LifecycleReport) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *LifecycleReport) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *LifecycleReport) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LifecycleReport) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LifecycleReport) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *LifecycleReport) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LifecycleReport) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LifecycleReport) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


