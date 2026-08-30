# LifecycleBacklogView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **string** |  | 
**ArchiveBatches** | **int32** |  | 
**PurgeBatches** | **int32** |  | 
**PendingArchiveBatches** | **int32** |  | 
**PendingPurgeBatches** | **int32** |  | 
**RetryablePurgeCandidates** | **int32** |  | 
**DeadLetteredPurgeCandidates** | **int32** |  | 
**ActivePurgeLeases** | **int32** |  | 
**ExpiredPurgeLeases** | **int32** |  | 

## Methods

### NewLifecycleBacklogView

`func NewLifecycleBacklogView(organizationId string, archiveBatches int32, purgeBatches int32, pendingArchiveBatches int32, pendingPurgeBatches int32, retryablePurgeCandidates int32, deadLetteredPurgeCandidates int32, activePurgeLeases int32, expiredPurgeLeases int32, ) *LifecycleBacklogView`

NewLifecycleBacklogView instantiates a new LifecycleBacklogView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleBacklogViewWithDefaults

`func NewLifecycleBacklogViewWithDefaults() *LifecycleBacklogView`

NewLifecycleBacklogViewWithDefaults instantiates a new LifecycleBacklogView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *LifecycleBacklogView) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LifecycleBacklogView) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LifecycleBacklogView) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetArchiveBatches

`func (o *LifecycleBacklogView) GetArchiveBatches() int32`

GetArchiveBatches returns the ArchiveBatches field if non-nil, zero value otherwise.

### GetArchiveBatchesOk

`func (o *LifecycleBacklogView) GetArchiveBatchesOk() (*int32, bool)`

GetArchiveBatchesOk returns a tuple with the ArchiveBatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveBatches

`func (o *LifecycleBacklogView) SetArchiveBatches(v int32)`

SetArchiveBatches sets ArchiveBatches field to given value.


### GetPurgeBatches

`func (o *LifecycleBacklogView) GetPurgeBatches() int32`

GetPurgeBatches returns the PurgeBatches field if non-nil, zero value otherwise.

### GetPurgeBatchesOk

`func (o *LifecycleBacklogView) GetPurgeBatchesOk() (*int32, bool)`

GetPurgeBatchesOk returns a tuple with the PurgeBatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurgeBatches

`func (o *LifecycleBacklogView) SetPurgeBatches(v int32)`

SetPurgeBatches sets PurgeBatches field to given value.


### GetPendingArchiveBatches

`func (o *LifecycleBacklogView) GetPendingArchiveBatches() int32`

GetPendingArchiveBatches returns the PendingArchiveBatches field if non-nil, zero value otherwise.

### GetPendingArchiveBatchesOk

`func (o *LifecycleBacklogView) GetPendingArchiveBatchesOk() (*int32, bool)`

GetPendingArchiveBatchesOk returns a tuple with the PendingArchiveBatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingArchiveBatches

`func (o *LifecycleBacklogView) SetPendingArchiveBatches(v int32)`

SetPendingArchiveBatches sets PendingArchiveBatches field to given value.


### GetPendingPurgeBatches

`func (o *LifecycleBacklogView) GetPendingPurgeBatches() int32`

GetPendingPurgeBatches returns the PendingPurgeBatches field if non-nil, zero value otherwise.

### GetPendingPurgeBatchesOk

`func (o *LifecycleBacklogView) GetPendingPurgeBatchesOk() (*int32, bool)`

GetPendingPurgeBatchesOk returns a tuple with the PendingPurgeBatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingPurgeBatches

`func (o *LifecycleBacklogView) SetPendingPurgeBatches(v int32)`

SetPendingPurgeBatches sets PendingPurgeBatches field to given value.


### GetRetryablePurgeCandidates

`func (o *LifecycleBacklogView) GetRetryablePurgeCandidates() int32`

GetRetryablePurgeCandidates returns the RetryablePurgeCandidates field if non-nil, zero value otherwise.

### GetRetryablePurgeCandidatesOk

`func (o *LifecycleBacklogView) GetRetryablePurgeCandidatesOk() (*int32, bool)`

GetRetryablePurgeCandidatesOk returns a tuple with the RetryablePurgeCandidates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryablePurgeCandidates

`func (o *LifecycleBacklogView) SetRetryablePurgeCandidates(v int32)`

SetRetryablePurgeCandidates sets RetryablePurgeCandidates field to given value.


### GetDeadLetteredPurgeCandidates

`func (o *LifecycleBacklogView) GetDeadLetteredPurgeCandidates() int32`

GetDeadLetteredPurgeCandidates returns the DeadLetteredPurgeCandidates field if non-nil, zero value otherwise.

### GetDeadLetteredPurgeCandidatesOk

`func (o *LifecycleBacklogView) GetDeadLetteredPurgeCandidatesOk() (*int32, bool)`

GetDeadLetteredPurgeCandidatesOk returns a tuple with the DeadLetteredPurgeCandidates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadLetteredPurgeCandidates

`func (o *LifecycleBacklogView) SetDeadLetteredPurgeCandidates(v int32)`

SetDeadLetteredPurgeCandidates sets DeadLetteredPurgeCandidates field to given value.


### GetActivePurgeLeases

`func (o *LifecycleBacklogView) GetActivePurgeLeases() int32`

GetActivePurgeLeases returns the ActivePurgeLeases field if non-nil, zero value otherwise.

### GetActivePurgeLeasesOk

`func (o *LifecycleBacklogView) GetActivePurgeLeasesOk() (*int32, bool)`

GetActivePurgeLeasesOk returns a tuple with the ActivePurgeLeases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivePurgeLeases

`func (o *LifecycleBacklogView) SetActivePurgeLeases(v int32)`

SetActivePurgeLeases sets ActivePurgeLeases field to given value.


### GetExpiredPurgeLeases

`func (o *LifecycleBacklogView) GetExpiredPurgeLeases() int32`

GetExpiredPurgeLeases returns the ExpiredPurgeLeases field if non-nil, zero value otherwise.

### GetExpiredPurgeLeasesOk

`func (o *LifecycleBacklogView) GetExpiredPurgeLeasesOk() (*int32, bool)`

GetExpiredPurgeLeasesOk returns a tuple with the ExpiredPurgeLeases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiredPurgeLeases

`func (o *LifecycleBacklogView) SetExpiredPurgeLeases(v int32)`

SetExpiredPurgeLeases sets ExpiredPurgeLeases field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


