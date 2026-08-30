# RegionReadinessSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**RegionId** | **string** |  | 
**RegionCode** | **string** |  | 
**RegionName** | **string** |  | 
**Status** | **string** |  | 
**Score** | **float64** |  | 
**EvaluatedAt** | **time.Time** |  | 
**ReplicationLagMs** | **NullableInt32** |  | 
**ReasonCodes** | **interface{}** |  | 
**Checks** | **interface{}** |  | 
**PolicyFingerprint** | **string** |  | 

## Methods

### NewRegionReadinessSnapshot

`func NewRegionReadinessSnapshot(id string, organizationId string, regionId string, regionCode string, regionName string, status string, score float64, evaluatedAt time.Time, replicationLagMs NullableInt32, reasonCodes interface{}, checks interface{}, policyFingerprint string, ) *RegionReadinessSnapshot`

NewRegionReadinessSnapshot instantiates a new RegionReadinessSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionReadinessSnapshotWithDefaults

`func NewRegionReadinessSnapshotWithDefaults() *RegionReadinessSnapshot`

NewRegionReadinessSnapshotWithDefaults instantiates a new RegionReadinessSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionReadinessSnapshot) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionReadinessSnapshot) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionReadinessSnapshot) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RegionReadinessSnapshot) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RegionReadinessSnapshot) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RegionReadinessSnapshot) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRegionId

`func (o *RegionReadinessSnapshot) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *RegionReadinessSnapshot) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *RegionReadinessSnapshot) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.


### GetRegionCode

`func (o *RegionReadinessSnapshot) GetRegionCode() string`

GetRegionCode returns the RegionCode field if non-nil, zero value otherwise.

### GetRegionCodeOk

`func (o *RegionReadinessSnapshot) GetRegionCodeOk() (*string, bool)`

GetRegionCodeOk returns a tuple with the RegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionCode

`func (o *RegionReadinessSnapshot) SetRegionCode(v string)`

SetRegionCode sets RegionCode field to given value.


### GetRegionName

`func (o *RegionReadinessSnapshot) GetRegionName() string`

GetRegionName returns the RegionName field if non-nil, zero value otherwise.

### GetRegionNameOk

`func (o *RegionReadinessSnapshot) GetRegionNameOk() (*string, bool)`

GetRegionNameOk returns a tuple with the RegionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionName

`func (o *RegionReadinessSnapshot) SetRegionName(v string)`

SetRegionName sets RegionName field to given value.


### GetStatus

`func (o *RegionReadinessSnapshot) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionReadinessSnapshot) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionReadinessSnapshot) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetScore

`func (o *RegionReadinessSnapshot) GetScore() float64`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *RegionReadinessSnapshot) GetScoreOk() (*float64, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *RegionReadinessSnapshot) SetScore(v float64)`

SetScore sets Score field to given value.


### GetEvaluatedAt

`func (o *RegionReadinessSnapshot) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *RegionReadinessSnapshot) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *RegionReadinessSnapshot) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.


### GetReplicationLagMs

`func (o *RegionReadinessSnapshot) GetReplicationLagMs() int32`

GetReplicationLagMs returns the ReplicationLagMs field if non-nil, zero value otherwise.

### GetReplicationLagMsOk

`func (o *RegionReadinessSnapshot) GetReplicationLagMsOk() (*int32, bool)`

GetReplicationLagMsOk returns a tuple with the ReplicationLagMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplicationLagMs

`func (o *RegionReadinessSnapshot) SetReplicationLagMs(v int32)`

SetReplicationLagMs sets ReplicationLagMs field to given value.


### SetReplicationLagMsNil

`func (o *RegionReadinessSnapshot) SetReplicationLagMsNil(b bool)`

 SetReplicationLagMsNil sets the value for ReplicationLagMs to be an explicit nil

### UnsetReplicationLagMs
`func (o *RegionReadinessSnapshot) UnsetReplicationLagMs()`

UnsetReplicationLagMs ensures that no value is present for ReplicationLagMs, not even an explicit nil
### GetReasonCodes

`func (o *RegionReadinessSnapshot) GetReasonCodes() interface{}`

GetReasonCodes returns the ReasonCodes field if non-nil, zero value otherwise.

### GetReasonCodesOk

`func (o *RegionReadinessSnapshot) GetReasonCodesOk() (*interface{}, bool)`

GetReasonCodesOk returns a tuple with the ReasonCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCodes

`func (o *RegionReadinessSnapshot) SetReasonCodes(v interface{})`

SetReasonCodes sets ReasonCodes field to given value.


### SetReasonCodesNil

`func (o *RegionReadinessSnapshot) SetReasonCodesNil(b bool)`

 SetReasonCodesNil sets the value for ReasonCodes to be an explicit nil

### UnsetReasonCodes
`func (o *RegionReadinessSnapshot) UnsetReasonCodes()`

UnsetReasonCodes ensures that no value is present for ReasonCodes, not even an explicit nil
### GetChecks

`func (o *RegionReadinessSnapshot) GetChecks() interface{}`

GetChecks returns the Checks field if non-nil, zero value otherwise.

### GetChecksOk

`func (o *RegionReadinessSnapshot) GetChecksOk() (*interface{}, bool)`

GetChecksOk returns a tuple with the Checks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecks

`func (o *RegionReadinessSnapshot) SetChecks(v interface{})`

SetChecks sets Checks field to given value.


### SetChecksNil

`func (o *RegionReadinessSnapshot) SetChecksNil(b bool)`

 SetChecksNil sets the value for Checks to be an explicit nil

### UnsetChecks
`func (o *RegionReadinessSnapshot) UnsetChecks()`

UnsetChecks ensures that no value is present for Checks, not even an explicit nil
### GetPolicyFingerprint

`func (o *RegionReadinessSnapshot) GetPolicyFingerprint() string`

GetPolicyFingerprint returns the PolicyFingerprint field if non-nil, zero value otherwise.

### GetPolicyFingerprintOk

`func (o *RegionReadinessSnapshot) GetPolicyFingerprintOk() (*string, bool)`

GetPolicyFingerprintOk returns a tuple with the PolicyFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyFingerprint

`func (o *RegionReadinessSnapshot) SetPolicyFingerprint(v string)`

SetPolicyFingerprint sets PolicyFingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


