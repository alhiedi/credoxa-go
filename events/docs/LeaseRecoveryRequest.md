# LeaseRecoveryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | Pointer to **string** |  | [optional] 
**ProjectionId** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Reason** | **string** |  | 
**ExpectedLeaseToken** | **string** |  | 
**ExpectedFencingGeneration** | **int32** |  | 
**Force** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewLeaseRecoveryRequest

`func NewLeaseRecoveryRequest(projectionId string, idempotencyKey string, reason string, expectedLeaseToken string, expectedFencingGeneration int32, ) *LeaseRecoveryRequest`

NewLeaseRecoveryRequest instantiates a new LeaseRecoveryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLeaseRecoveryRequestWithDefaults

`func NewLeaseRecoveryRequestWithDefaults() *LeaseRecoveryRequest`

NewLeaseRecoveryRequestWithDefaults instantiates a new LeaseRecoveryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *LeaseRecoveryRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LeaseRecoveryRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LeaseRecoveryRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *LeaseRecoveryRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetProjectionId

`func (o *LeaseRecoveryRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *LeaseRecoveryRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *LeaseRecoveryRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.


### GetIdempotencyKey

`func (o *LeaseRecoveryRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *LeaseRecoveryRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *LeaseRecoveryRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetReason

`func (o *LeaseRecoveryRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *LeaseRecoveryRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *LeaseRecoveryRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetExpectedLeaseToken

`func (o *LeaseRecoveryRequest) GetExpectedLeaseToken() string`

GetExpectedLeaseToken returns the ExpectedLeaseToken field if non-nil, zero value otherwise.

### GetExpectedLeaseTokenOk

`func (o *LeaseRecoveryRequest) GetExpectedLeaseTokenOk() (*string, bool)`

GetExpectedLeaseTokenOk returns a tuple with the ExpectedLeaseToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedLeaseToken

`func (o *LeaseRecoveryRequest) SetExpectedLeaseToken(v string)`

SetExpectedLeaseToken sets ExpectedLeaseToken field to given value.


### GetExpectedFencingGeneration

`func (o *LeaseRecoveryRequest) GetExpectedFencingGeneration() int32`

GetExpectedFencingGeneration returns the ExpectedFencingGeneration field if non-nil, zero value otherwise.

### GetExpectedFencingGenerationOk

`func (o *LeaseRecoveryRequest) GetExpectedFencingGenerationOk() (*int32, bool)`

GetExpectedFencingGenerationOk returns a tuple with the ExpectedFencingGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedFencingGeneration

`func (o *LeaseRecoveryRequest) SetExpectedFencingGeneration(v int32)`

SetExpectedFencingGeneration sets ExpectedFencingGeneration field to given value.


### GetForce

`func (o *LeaseRecoveryRequest) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *LeaseRecoveryRequest) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *LeaseRecoveryRequest) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *LeaseRecoveryRequest) HasForce() bool`

HasForce returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


