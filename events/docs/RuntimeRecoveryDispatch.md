# RuntimeRecoveryDispatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**TaskName** | Pointer to **string** |  | [optional] 
**QueueName** | Pointer to **string** |  | [optional] 
**RoutingKey** | Pointer to **string** |  | [optional] 
**Status** | Pointer to [**RuntimeRecoveryDispatchStatusEnum**](RuntimeRecoveryDispatchStatusEnum.md) |  | [optional] 
**AvailableAt** | Pointer to **time.Time** |  | [optional] 
**PublishedAt** | Pointer to **NullableTime** |  | [optional] 
**ClaimedBy** | Pointer to **NullableString** |  | [optional] 
**ClaimedAt** | Pointer to **NullableTime** |  | [optional] 
**ClaimExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**AttemptCount** | Pointer to **int64** |  | [optional] 
**LastError** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRuntimeRecoveryDispatch

`func NewRuntimeRecoveryDispatch(id string, createdAt time.Time, updatedAt time.Time, ) *RuntimeRecoveryDispatch`

NewRuntimeRecoveryDispatch instantiates a new RuntimeRecoveryDispatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRuntimeRecoveryDispatchWithDefaults

`func NewRuntimeRecoveryDispatchWithDefaults() *RuntimeRecoveryDispatch`

NewRuntimeRecoveryDispatchWithDefaults instantiates a new RuntimeRecoveryDispatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RuntimeRecoveryDispatch) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RuntimeRecoveryDispatch) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RuntimeRecoveryDispatch) SetId(v string)`

SetId sets Id field to given value.


### GetTaskName

`func (o *RuntimeRecoveryDispatch) GetTaskName() string`

GetTaskName returns the TaskName field if non-nil, zero value otherwise.

### GetTaskNameOk

`func (o *RuntimeRecoveryDispatch) GetTaskNameOk() (*string, bool)`

GetTaskNameOk returns a tuple with the TaskName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskName

`func (o *RuntimeRecoveryDispatch) SetTaskName(v string)`

SetTaskName sets TaskName field to given value.

### HasTaskName

`func (o *RuntimeRecoveryDispatch) HasTaskName() bool`

HasTaskName returns a boolean if a field has been set.

### GetQueueName

`func (o *RuntimeRecoveryDispatch) GetQueueName() string`

GetQueueName returns the QueueName field if non-nil, zero value otherwise.

### GetQueueNameOk

`func (o *RuntimeRecoveryDispatch) GetQueueNameOk() (*string, bool)`

GetQueueNameOk returns a tuple with the QueueName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueueName

`func (o *RuntimeRecoveryDispatch) SetQueueName(v string)`

SetQueueName sets QueueName field to given value.

### HasQueueName

`func (o *RuntimeRecoveryDispatch) HasQueueName() bool`

HasQueueName returns a boolean if a field has been set.

### GetRoutingKey

`func (o *RuntimeRecoveryDispatch) GetRoutingKey() string`

GetRoutingKey returns the RoutingKey field if non-nil, zero value otherwise.

### GetRoutingKeyOk

`func (o *RuntimeRecoveryDispatch) GetRoutingKeyOk() (*string, bool)`

GetRoutingKeyOk returns a tuple with the RoutingKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingKey

`func (o *RuntimeRecoveryDispatch) SetRoutingKey(v string)`

SetRoutingKey sets RoutingKey field to given value.

### HasRoutingKey

`func (o *RuntimeRecoveryDispatch) HasRoutingKey() bool`

HasRoutingKey returns a boolean if a field has been set.

### GetStatus

`func (o *RuntimeRecoveryDispatch) GetStatus() RuntimeRecoveryDispatchStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RuntimeRecoveryDispatch) GetStatusOk() (*RuntimeRecoveryDispatchStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RuntimeRecoveryDispatch) SetStatus(v RuntimeRecoveryDispatchStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RuntimeRecoveryDispatch) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAvailableAt

`func (o *RuntimeRecoveryDispatch) GetAvailableAt() time.Time`

GetAvailableAt returns the AvailableAt field if non-nil, zero value otherwise.

### GetAvailableAtOk

`func (o *RuntimeRecoveryDispatch) GetAvailableAtOk() (*time.Time, bool)`

GetAvailableAtOk returns a tuple with the AvailableAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableAt

`func (o *RuntimeRecoveryDispatch) SetAvailableAt(v time.Time)`

SetAvailableAt sets AvailableAt field to given value.

### HasAvailableAt

`func (o *RuntimeRecoveryDispatch) HasAvailableAt() bool`

HasAvailableAt returns a boolean if a field has been set.

### GetPublishedAt

`func (o *RuntimeRecoveryDispatch) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *RuntimeRecoveryDispatch) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *RuntimeRecoveryDispatch) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *RuntimeRecoveryDispatch) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### SetPublishedAtNil

`func (o *RuntimeRecoveryDispatch) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *RuntimeRecoveryDispatch) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetClaimedBy

`func (o *RuntimeRecoveryDispatch) GetClaimedBy() string`

GetClaimedBy returns the ClaimedBy field if non-nil, zero value otherwise.

### GetClaimedByOk

`func (o *RuntimeRecoveryDispatch) GetClaimedByOk() (*string, bool)`

GetClaimedByOk returns a tuple with the ClaimedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimedBy

`func (o *RuntimeRecoveryDispatch) SetClaimedBy(v string)`

SetClaimedBy sets ClaimedBy field to given value.

### HasClaimedBy

`func (o *RuntimeRecoveryDispatch) HasClaimedBy() bool`

HasClaimedBy returns a boolean if a field has been set.

### SetClaimedByNil

`func (o *RuntimeRecoveryDispatch) SetClaimedByNil(b bool)`

 SetClaimedByNil sets the value for ClaimedBy to be an explicit nil

### UnsetClaimedBy
`func (o *RuntimeRecoveryDispatch) UnsetClaimedBy()`

UnsetClaimedBy ensures that no value is present for ClaimedBy, not even an explicit nil
### GetClaimedAt

`func (o *RuntimeRecoveryDispatch) GetClaimedAt() time.Time`

GetClaimedAt returns the ClaimedAt field if non-nil, zero value otherwise.

### GetClaimedAtOk

`func (o *RuntimeRecoveryDispatch) GetClaimedAtOk() (*time.Time, bool)`

GetClaimedAtOk returns a tuple with the ClaimedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimedAt

`func (o *RuntimeRecoveryDispatch) SetClaimedAt(v time.Time)`

SetClaimedAt sets ClaimedAt field to given value.

### HasClaimedAt

`func (o *RuntimeRecoveryDispatch) HasClaimedAt() bool`

HasClaimedAt returns a boolean if a field has been set.

### SetClaimedAtNil

`func (o *RuntimeRecoveryDispatch) SetClaimedAtNil(b bool)`

 SetClaimedAtNil sets the value for ClaimedAt to be an explicit nil

### UnsetClaimedAt
`func (o *RuntimeRecoveryDispatch) UnsetClaimedAt()`

UnsetClaimedAt ensures that no value is present for ClaimedAt, not even an explicit nil
### GetClaimExpiresAt

`func (o *RuntimeRecoveryDispatch) GetClaimExpiresAt() time.Time`

GetClaimExpiresAt returns the ClaimExpiresAt field if non-nil, zero value otherwise.

### GetClaimExpiresAtOk

`func (o *RuntimeRecoveryDispatch) GetClaimExpiresAtOk() (*time.Time, bool)`

GetClaimExpiresAtOk returns a tuple with the ClaimExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimExpiresAt

`func (o *RuntimeRecoveryDispatch) SetClaimExpiresAt(v time.Time)`

SetClaimExpiresAt sets ClaimExpiresAt field to given value.

### HasClaimExpiresAt

`func (o *RuntimeRecoveryDispatch) HasClaimExpiresAt() bool`

HasClaimExpiresAt returns a boolean if a field has been set.

### SetClaimExpiresAtNil

`func (o *RuntimeRecoveryDispatch) SetClaimExpiresAtNil(b bool)`

 SetClaimExpiresAtNil sets the value for ClaimExpiresAt to be an explicit nil

### UnsetClaimExpiresAt
`func (o *RuntimeRecoveryDispatch) UnsetClaimExpiresAt()`

UnsetClaimExpiresAt ensures that no value is present for ClaimExpiresAt, not even an explicit nil
### GetAttemptCount

`func (o *RuntimeRecoveryDispatch) GetAttemptCount() int64`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *RuntimeRecoveryDispatch) GetAttemptCountOk() (*int64, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *RuntimeRecoveryDispatch) SetAttemptCount(v int64)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *RuntimeRecoveryDispatch) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetLastError

`func (o *RuntimeRecoveryDispatch) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *RuntimeRecoveryDispatch) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *RuntimeRecoveryDispatch) SetLastError(v string)`

SetLastError sets LastError field to given value.

### HasLastError

`func (o *RuntimeRecoveryDispatch) HasLastError() bool`

HasLastError returns a boolean if a field has been set.

### SetLastErrorNil

`func (o *RuntimeRecoveryDispatch) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *RuntimeRecoveryDispatch) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetCreatedAt

`func (o *RuntimeRecoveryDispatch) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RuntimeRecoveryDispatch) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RuntimeRecoveryDispatch) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RuntimeRecoveryDispatch) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RuntimeRecoveryDispatch) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RuntimeRecoveryDispatch) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


