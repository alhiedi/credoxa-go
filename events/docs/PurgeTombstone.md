# PurgeTombstone

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**TombstoneId** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**CandidateId** | **string** |  | 
**ArchiveExecutionId** | **string** |  | 
**ArchiveBatchId** | **string** |  | 
**ArchiveManifestId** | **string** |  | 
**ArchiveManifestChecksum** | **string** |  | 
**ArchiveCandidateChecksum** | **string** |  | 
**ArchiveStorageReference** | **string** |  | 
**ArchiveVerifiedAt** | **time.Time** |  | 
**ArchiveProjectionFingerprint** | **string** |  | 
**ArchiveGeneration** | **int64** |  | 
**PolicyFingerprint** | **string** |  | 
**PurgeDecisionCode** | **string** |  | 
**PurgeDecisionFingerprint** | **string** |  | 
**LeaseId** | **string** |  | 
**LeaseTokenFingerprint** | **string** |  | 
**FencingGeneration** | **int64** |  | 
**LeaseOwnerId** | **string** |  | 
**DeletionFingerprint** | **string** |  | 
**DeletionReason** | **string** |  | 
**DeletedBy** | **string** |  | 
**DeletedAt** | **time.Time** |  | 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**Execution** | **string** |  | 
**Batch** | **string** |  | 
**PurgeLease** | **string** |  | 

## Methods

### NewPurgeTombstone

`func NewPurgeTombstone(id string, tombstoneId string, organizationId string, candidateId string, archiveExecutionId string, archiveBatchId string, archiveManifestId string, archiveManifestChecksum string, archiveCandidateChecksum string, archiveStorageReference string, archiveVerifiedAt time.Time, archiveProjectionFingerprint string, archiveGeneration int64, policyFingerprint string, purgeDecisionCode string, purgeDecisionFingerprint string, leaseId string, leaseTokenFingerprint string, fencingGeneration int64, leaseOwnerId string, deletionFingerprint string, deletionReason string, deletedBy string, deletedAt time.Time, createdAt time.Time, execution string, batch string, purgeLease string, ) *PurgeTombstone`

NewPurgeTombstone instantiates a new PurgeTombstone object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurgeTombstoneWithDefaults

`func NewPurgeTombstoneWithDefaults() *PurgeTombstone`

NewPurgeTombstoneWithDefaults instantiates a new PurgeTombstone object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PurgeTombstone) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PurgeTombstone) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PurgeTombstone) SetId(v string)`

SetId sets Id field to given value.


### GetTombstoneId

`func (o *PurgeTombstone) GetTombstoneId() string`

GetTombstoneId returns the TombstoneId field if non-nil, zero value otherwise.

### GetTombstoneIdOk

`func (o *PurgeTombstone) GetTombstoneIdOk() (*string, bool)`

GetTombstoneIdOk returns a tuple with the TombstoneId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTombstoneId

`func (o *PurgeTombstone) SetTombstoneId(v string)`

SetTombstoneId sets TombstoneId field to given value.


### GetOrganizationId

`func (o *PurgeTombstone) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *PurgeTombstone) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *PurgeTombstone) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetCandidateId

`func (o *PurgeTombstone) GetCandidateId() string`

GetCandidateId returns the CandidateId field if non-nil, zero value otherwise.

### GetCandidateIdOk

`func (o *PurgeTombstone) GetCandidateIdOk() (*string, bool)`

GetCandidateIdOk returns a tuple with the CandidateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCandidateId

`func (o *PurgeTombstone) SetCandidateId(v string)`

SetCandidateId sets CandidateId field to given value.


### GetArchiveExecutionId

`func (o *PurgeTombstone) GetArchiveExecutionId() string`

GetArchiveExecutionId returns the ArchiveExecutionId field if non-nil, zero value otherwise.

### GetArchiveExecutionIdOk

`func (o *PurgeTombstone) GetArchiveExecutionIdOk() (*string, bool)`

GetArchiveExecutionIdOk returns a tuple with the ArchiveExecutionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveExecutionId

`func (o *PurgeTombstone) SetArchiveExecutionId(v string)`

SetArchiveExecutionId sets ArchiveExecutionId field to given value.


### GetArchiveBatchId

`func (o *PurgeTombstone) GetArchiveBatchId() string`

GetArchiveBatchId returns the ArchiveBatchId field if non-nil, zero value otherwise.

### GetArchiveBatchIdOk

`func (o *PurgeTombstone) GetArchiveBatchIdOk() (*string, bool)`

GetArchiveBatchIdOk returns a tuple with the ArchiveBatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveBatchId

`func (o *PurgeTombstone) SetArchiveBatchId(v string)`

SetArchiveBatchId sets ArchiveBatchId field to given value.


### GetArchiveManifestId

`func (o *PurgeTombstone) GetArchiveManifestId() string`

GetArchiveManifestId returns the ArchiveManifestId field if non-nil, zero value otherwise.

### GetArchiveManifestIdOk

`func (o *PurgeTombstone) GetArchiveManifestIdOk() (*string, bool)`

GetArchiveManifestIdOk returns a tuple with the ArchiveManifestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveManifestId

`func (o *PurgeTombstone) SetArchiveManifestId(v string)`

SetArchiveManifestId sets ArchiveManifestId field to given value.


### GetArchiveManifestChecksum

`func (o *PurgeTombstone) GetArchiveManifestChecksum() string`

GetArchiveManifestChecksum returns the ArchiveManifestChecksum field if non-nil, zero value otherwise.

### GetArchiveManifestChecksumOk

`func (o *PurgeTombstone) GetArchiveManifestChecksumOk() (*string, bool)`

GetArchiveManifestChecksumOk returns a tuple with the ArchiveManifestChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveManifestChecksum

`func (o *PurgeTombstone) SetArchiveManifestChecksum(v string)`

SetArchiveManifestChecksum sets ArchiveManifestChecksum field to given value.


### GetArchiveCandidateChecksum

`func (o *PurgeTombstone) GetArchiveCandidateChecksum() string`

GetArchiveCandidateChecksum returns the ArchiveCandidateChecksum field if non-nil, zero value otherwise.

### GetArchiveCandidateChecksumOk

`func (o *PurgeTombstone) GetArchiveCandidateChecksumOk() (*string, bool)`

GetArchiveCandidateChecksumOk returns a tuple with the ArchiveCandidateChecksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveCandidateChecksum

`func (o *PurgeTombstone) SetArchiveCandidateChecksum(v string)`

SetArchiveCandidateChecksum sets ArchiveCandidateChecksum field to given value.


### GetArchiveStorageReference

`func (o *PurgeTombstone) GetArchiveStorageReference() string`

GetArchiveStorageReference returns the ArchiveStorageReference field if non-nil, zero value otherwise.

### GetArchiveStorageReferenceOk

`func (o *PurgeTombstone) GetArchiveStorageReferenceOk() (*string, bool)`

GetArchiveStorageReferenceOk returns a tuple with the ArchiveStorageReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveStorageReference

`func (o *PurgeTombstone) SetArchiveStorageReference(v string)`

SetArchiveStorageReference sets ArchiveStorageReference field to given value.


### GetArchiveVerifiedAt

`func (o *PurgeTombstone) GetArchiveVerifiedAt() time.Time`

GetArchiveVerifiedAt returns the ArchiveVerifiedAt field if non-nil, zero value otherwise.

### GetArchiveVerifiedAtOk

`func (o *PurgeTombstone) GetArchiveVerifiedAtOk() (*time.Time, bool)`

GetArchiveVerifiedAtOk returns a tuple with the ArchiveVerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveVerifiedAt

`func (o *PurgeTombstone) SetArchiveVerifiedAt(v time.Time)`

SetArchiveVerifiedAt sets ArchiveVerifiedAt field to given value.


### GetArchiveProjectionFingerprint

`func (o *PurgeTombstone) GetArchiveProjectionFingerprint() string`

GetArchiveProjectionFingerprint returns the ArchiveProjectionFingerprint field if non-nil, zero value otherwise.

### GetArchiveProjectionFingerprintOk

`func (o *PurgeTombstone) GetArchiveProjectionFingerprintOk() (*string, bool)`

GetArchiveProjectionFingerprintOk returns a tuple with the ArchiveProjectionFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveProjectionFingerprint

`func (o *PurgeTombstone) SetArchiveProjectionFingerprint(v string)`

SetArchiveProjectionFingerprint sets ArchiveProjectionFingerprint field to given value.


### GetArchiveGeneration

`func (o *PurgeTombstone) GetArchiveGeneration() int64`

GetArchiveGeneration returns the ArchiveGeneration field if non-nil, zero value otherwise.

### GetArchiveGenerationOk

`func (o *PurgeTombstone) GetArchiveGenerationOk() (*int64, bool)`

GetArchiveGenerationOk returns a tuple with the ArchiveGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveGeneration

`func (o *PurgeTombstone) SetArchiveGeneration(v int64)`

SetArchiveGeneration sets ArchiveGeneration field to given value.


### GetPolicyFingerprint

`func (o *PurgeTombstone) GetPolicyFingerprint() string`

GetPolicyFingerprint returns the PolicyFingerprint field if non-nil, zero value otherwise.

### GetPolicyFingerprintOk

`func (o *PurgeTombstone) GetPolicyFingerprintOk() (*string, bool)`

GetPolicyFingerprintOk returns a tuple with the PolicyFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyFingerprint

`func (o *PurgeTombstone) SetPolicyFingerprint(v string)`

SetPolicyFingerprint sets PolicyFingerprint field to given value.


### GetPurgeDecisionCode

`func (o *PurgeTombstone) GetPurgeDecisionCode() string`

GetPurgeDecisionCode returns the PurgeDecisionCode field if non-nil, zero value otherwise.

### GetPurgeDecisionCodeOk

`func (o *PurgeTombstone) GetPurgeDecisionCodeOk() (*string, bool)`

GetPurgeDecisionCodeOk returns a tuple with the PurgeDecisionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurgeDecisionCode

`func (o *PurgeTombstone) SetPurgeDecisionCode(v string)`

SetPurgeDecisionCode sets PurgeDecisionCode field to given value.


### GetPurgeDecisionFingerprint

`func (o *PurgeTombstone) GetPurgeDecisionFingerprint() string`

GetPurgeDecisionFingerprint returns the PurgeDecisionFingerprint field if non-nil, zero value otherwise.

### GetPurgeDecisionFingerprintOk

`func (o *PurgeTombstone) GetPurgeDecisionFingerprintOk() (*string, bool)`

GetPurgeDecisionFingerprintOk returns a tuple with the PurgeDecisionFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurgeDecisionFingerprint

`func (o *PurgeTombstone) SetPurgeDecisionFingerprint(v string)`

SetPurgeDecisionFingerprint sets PurgeDecisionFingerprint field to given value.


### GetLeaseId

`func (o *PurgeTombstone) GetLeaseId() string`

GetLeaseId returns the LeaseId field if non-nil, zero value otherwise.

### GetLeaseIdOk

`func (o *PurgeTombstone) GetLeaseIdOk() (*string, bool)`

GetLeaseIdOk returns a tuple with the LeaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseId

`func (o *PurgeTombstone) SetLeaseId(v string)`

SetLeaseId sets LeaseId field to given value.


### GetLeaseTokenFingerprint

`func (o *PurgeTombstone) GetLeaseTokenFingerprint() string`

GetLeaseTokenFingerprint returns the LeaseTokenFingerprint field if non-nil, zero value otherwise.

### GetLeaseTokenFingerprintOk

`func (o *PurgeTombstone) GetLeaseTokenFingerprintOk() (*string, bool)`

GetLeaseTokenFingerprintOk returns a tuple with the LeaseTokenFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseTokenFingerprint

`func (o *PurgeTombstone) SetLeaseTokenFingerprint(v string)`

SetLeaseTokenFingerprint sets LeaseTokenFingerprint field to given value.


### GetFencingGeneration

`func (o *PurgeTombstone) GetFencingGeneration() int64`

GetFencingGeneration returns the FencingGeneration field if non-nil, zero value otherwise.

### GetFencingGenerationOk

`func (o *PurgeTombstone) GetFencingGenerationOk() (*int64, bool)`

GetFencingGenerationOk returns a tuple with the FencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFencingGeneration

`func (o *PurgeTombstone) SetFencingGeneration(v int64)`

SetFencingGeneration sets FencingGeneration field to given value.


### GetLeaseOwnerId

`func (o *PurgeTombstone) GetLeaseOwnerId() string`

GetLeaseOwnerId returns the LeaseOwnerId field if non-nil, zero value otherwise.

### GetLeaseOwnerIdOk

`func (o *PurgeTombstone) GetLeaseOwnerIdOk() (*string, bool)`

GetLeaseOwnerIdOk returns a tuple with the LeaseOwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseOwnerId

`func (o *PurgeTombstone) SetLeaseOwnerId(v string)`

SetLeaseOwnerId sets LeaseOwnerId field to given value.


### GetDeletionFingerprint

`func (o *PurgeTombstone) GetDeletionFingerprint() string`

GetDeletionFingerprint returns the DeletionFingerprint field if non-nil, zero value otherwise.

### GetDeletionFingerprintOk

`func (o *PurgeTombstone) GetDeletionFingerprintOk() (*string, bool)`

GetDeletionFingerprintOk returns a tuple with the DeletionFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionFingerprint

`func (o *PurgeTombstone) SetDeletionFingerprint(v string)`

SetDeletionFingerprint sets DeletionFingerprint field to given value.


### GetDeletionReason

`func (o *PurgeTombstone) GetDeletionReason() string`

GetDeletionReason returns the DeletionReason field if non-nil, zero value otherwise.

### GetDeletionReasonOk

`func (o *PurgeTombstone) GetDeletionReasonOk() (*string, bool)`

GetDeletionReasonOk returns a tuple with the DeletionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionReason

`func (o *PurgeTombstone) SetDeletionReason(v string)`

SetDeletionReason sets DeletionReason field to given value.


### GetDeletedBy

`func (o *PurgeTombstone) GetDeletedBy() string`

GetDeletedBy returns the DeletedBy field if non-nil, zero value otherwise.

### GetDeletedByOk

`func (o *PurgeTombstone) GetDeletedByOk() (*string, bool)`

GetDeletedByOk returns a tuple with the DeletedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedBy

`func (o *PurgeTombstone) SetDeletedBy(v string)`

SetDeletedBy sets DeletedBy field to given value.


### GetDeletedAt

`func (o *PurgeTombstone) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *PurgeTombstone) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *PurgeTombstone) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### GetEvidence

`func (o *PurgeTombstone) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *PurgeTombstone) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *PurgeTombstone) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *PurgeTombstone) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *PurgeTombstone) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *PurgeTombstone) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetRevision

`func (o *PurgeTombstone) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *PurgeTombstone) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *PurgeTombstone) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *PurgeTombstone) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PurgeTombstone) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PurgeTombstone) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PurgeTombstone) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExecution

`func (o *PurgeTombstone) GetExecution() string`

GetExecution returns the Execution field if non-nil, zero value otherwise.

### GetExecutionOk

`func (o *PurgeTombstone) GetExecutionOk() (*string, bool)`

GetExecutionOk returns a tuple with the Execution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecution

`func (o *PurgeTombstone) SetExecution(v string)`

SetExecution sets Execution field to given value.


### GetBatch

`func (o *PurgeTombstone) GetBatch() string`

GetBatch returns the Batch field if non-nil, zero value otherwise.

### GetBatchOk

`func (o *PurgeTombstone) GetBatchOk() (*string, bool)`

GetBatchOk returns a tuple with the Batch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatch

`func (o *PurgeTombstone) SetBatch(v string)`

SetBatch sets Batch field to given value.


### GetPurgeLease

`func (o *PurgeTombstone) GetPurgeLease() string`

GetPurgeLease returns the PurgeLease field if non-nil, zero value otherwise.

### GetPurgeLeaseOk

`func (o *PurgeTombstone) GetPurgeLeaseOk() (*string, bool)`

GetPurgeLeaseOk returns a tuple with the PurgeLease field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurgeLease

`func (o *PurgeTombstone) SetPurgeLease(v string)`

SetPurgeLease sets PurgeLease field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


