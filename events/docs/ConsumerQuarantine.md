# ConsumerQuarantine

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**OrganizationId** | **string** |  | 
**ConsumerId** | **string** |  | 
**Active** | Pointer to **bool** |  | [optional] 
**ReasonCode** | Pointer to **NullableString** |  | [optional] 
**Reason** | Pointer to **NullableString** |  | [optional] 
**Source** | Pointer to [**SourceEnum**](SourceEnum.md) |  | [optional] 
**Evidence** | Pointer to **interface{}** |  | [optional] 
**FailureCount** | Pointer to **int64** |  | [optional] 
**FailureThreshold** | Pointer to **int64** |  | [optional] 
**FailureWindowSeconds** | Pointer to **int64** |  | [optional] 
**QuarantinedAt** | Pointer to **NullableTime** |  | [optional] 
**MinimumReleaseAt** | Pointer to **NullableTime** |  | [optional] 
**CooldownUntil** | Pointer to **NullableTime** |  | [optional] 
**ReleasedAt** | Pointer to **NullableTime** |  | [optional] 
**ReleasedBy** | Pointer to **NullableString** |  | [optional] 
**ReleaseReason** | Pointer to **NullableString** |  | [optional] 
**Revision** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 
**Events** | [**[]ConsumerQuarantineEvent**](ConsumerQuarantineEvent.md) |  | [readonly] 

## Methods

### NewConsumerQuarantine

`func NewConsumerQuarantine(id string, organizationId string, consumerId string, createdAt time.Time, updatedAt time.Time, events []ConsumerQuarantineEvent, ) *ConsumerQuarantine`

NewConsumerQuarantine instantiates a new ConsumerQuarantine object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConsumerQuarantineWithDefaults

`func NewConsumerQuarantineWithDefaults() *ConsumerQuarantine`

NewConsumerQuarantineWithDefaults instantiates a new ConsumerQuarantine object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ConsumerQuarantine) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConsumerQuarantine) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConsumerQuarantine) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *ConsumerQuarantine) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ConsumerQuarantine) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ConsumerQuarantine) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetConsumerId

`func (o *ConsumerQuarantine) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *ConsumerQuarantine) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *ConsumerQuarantine) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetActive

`func (o *ConsumerQuarantine) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ConsumerQuarantine) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ConsumerQuarantine) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ConsumerQuarantine) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetReasonCode

`func (o *ConsumerQuarantine) GetReasonCode() string`

GetReasonCode returns the ReasonCode field if non-nil, zero value otherwise.

### GetReasonCodeOk

`func (o *ConsumerQuarantine) GetReasonCodeOk() (*string, bool)`

GetReasonCodeOk returns a tuple with the ReasonCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasonCode

`func (o *ConsumerQuarantine) SetReasonCode(v string)`

SetReasonCode sets ReasonCode field to given value.

### HasReasonCode

`func (o *ConsumerQuarantine) HasReasonCode() bool`

HasReasonCode returns a boolean if a field has been set.

### SetReasonCodeNil

`func (o *ConsumerQuarantine) SetReasonCodeNil(b bool)`

 SetReasonCodeNil sets the value for ReasonCode to be an explicit nil

### UnsetReasonCode
`func (o *ConsumerQuarantine) UnsetReasonCode()`

UnsetReasonCode ensures that no value is present for ReasonCode, not even an explicit nil
### GetReason

`func (o *ConsumerQuarantine) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ConsumerQuarantine) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ConsumerQuarantine) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *ConsumerQuarantine) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *ConsumerQuarantine) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *ConsumerQuarantine) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetSource

`func (o *ConsumerQuarantine) GetSource() SourceEnum`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ConsumerQuarantine) GetSourceOk() (*SourceEnum, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ConsumerQuarantine) SetSource(v SourceEnum)`

SetSource sets Source field to given value.

### HasSource

`func (o *ConsumerQuarantine) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetEvidence

`func (o *ConsumerQuarantine) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *ConsumerQuarantine) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *ConsumerQuarantine) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *ConsumerQuarantine) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### SetEvidenceNil

`func (o *ConsumerQuarantine) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *ConsumerQuarantine) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetFailureCount

`func (o *ConsumerQuarantine) GetFailureCount() int64`

GetFailureCount returns the FailureCount field if non-nil, zero value otherwise.

### GetFailureCountOk

`func (o *ConsumerQuarantine) GetFailureCountOk() (*int64, bool)`

GetFailureCountOk returns a tuple with the FailureCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCount

`func (o *ConsumerQuarantine) SetFailureCount(v int64)`

SetFailureCount sets FailureCount field to given value.

### HasFailureCount

`func (o *ConsumerQuarantine) HasFailureCount() bool`

HasFailureCount returns a boolean if a field has been set.

### GetFailureThreshold

`func (o *ConsumerQuarantine) GetFailureThreshold() int64`

GetFailureThreshold returns the FailureThreshold field if non-nil, zero value otherwise.

### GetFailureThresholdOk

`func (o *ConsumerQuarantine) GetFailureThresholdOk() (*int64, bool)`

GetFailureThresholdOk returns a tuple with the FailureThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureThreshold

`func (o *ConsumerQuarantine) SetFailureThreshold(v int64)`

SetFailureThreshold sets FailureThreshold field to given value.

### HasFailureThreshold

`func (o *ConsumerQuarantine) HasFailureThreshold() bool`

HasFailureThreshold returns a boolean if a field has been set.

### GetFailureWindowSeconds

`func (o *ConsumerQuarantine) GetFailureWindowSeconds() int64`

GetFailureWindowSeconds returns the FailureWindowSeconds field if non-nil, zero value otherwise.

### GetFailureWindowSecondsOk

`func (o *ConsumerQuarantine) GetFailureWindowSecondsOk() (*int64, bool)`

GetFailureWindowSecondsOk returns a tuple with the FailureWindowSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureWindowSeconds

`func (o *ConsumerQuarantine) SetFailureWindowSeconds(v int64)`

SetFailureWindowSeconds sets FailureWindowSeconds field to given value.

### HasFailureWindowSeconds

`func (o *ConsumerQuarantine) HasFailureWindowSeconds() bool`

HasFailureWindowSeconds returns a boolean if a field has been set.

### GetQuarantinedAt

`func (o *ConsumerQuarantine) GetQuarantinedAt() time.Time`

GetQuarantinedAt returns the QuarantinedAt field if non-nil, zero value otherwise.

### GetQuarantinedAtOk

`func (o *ConsumerQuarantine) GetQuarantinedAtOk() (*time.Time, bool)`

GetQuarantinedAtOk returns a tuple with the QuarantinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuarantinedAt

`func (o *ConsumerQuarantine) SetQuarantinedAt(v time.Time)`

SetQuarantinedAt sets QuarantinedAt field to given value.

### HasQuarantinedAt

`func (o *ConsumerQuarantine) HasQuarantinedAt() bool`

HasQuarantinedAt returns a boolean if a field has been set.

### SetQuarantinedAtNil

`func (o *ConsumerQuarantine) SetQuarantinedAtNil(b bool)`

 SetQuarantinedAtNil sets the value for QuarantinedAt to be an explicit nil

### UnsetQuarantinedAt
`func (o *ConsumerQuarantine) UnsetQuarantinedAt()`

UnsetQuarantinedAt ensures that no value is present for QuarantinedAt, not even an explicit nil
### GetMinimumReleaseAt

`func (o *ConsumerQuarantine) GetMinimumReleaseAt() time.Time`

GetMinimumReleaseAt returns the MinimumReleaseAt field if non-nil, zero value otherwise.

### GetMinimumReleaseAtOk

`func (o *ConsumerQuarantine) GetMinimumReleaseAtOk() (*time.Time, bool)`

GetMinimumReleaseAtOk returns a tuple with the MinimumReleaseAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumReleaseAt

`func (o *ConsumerQuarantine) SetMinimumReleaseAt(v time.Time)`

SetMinimumReleaseAt sets MinimumReleaseAt field to given value.

### HasMinimumReleaseAt

`func (o *ConsumerQuarantine) HasMinimumReleaseAt() bool`

HasMinimumReleaseAt returns a boolean if a field has been set.

### SetMinimumReleaseAtNil

`func (o *ConsumerQuarantine) SetMinimumReleaseAtNil(b bool)`

 SetMinimumReleaseAtNil sets the value for MinimumReleaseAt to be an explicit nil

### UnsetMinimumReleaseAt
`func (o *ConsumerQuarantine) UnsetMinimumReleaseAt()`

UnsetMinimumReleaseAt ensures that no value is present for MinimumReleaseAt, not even an explicit nil
### GetCooldownUntil

`func (o *ConsumerQuarantine) GetCooldownUntil() time.Time`

GetCooldownUntil returns the CooldownUntil field if non-nil, zero value otherwise.

### GetCooldownUntilOk

`func (o *ConsumerQuarantine) GetCooldownUntilOk() (*time.Time, bool)`

GetCooldownUntilOk returns a tuple with the CooldownUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCooldownUntil

`func (o *ConsumerQuarantine) SetCooldownUntil(v time.Time)`

SetCooldownUntil sets CooldownUntil field to given value.

### HasCooldownUntil

`func (o *ConsumerQuarantine) HasCooldownUntil() bool`

HasCooldownUntil returns a boolean if a field has been set.

### SetCooldownUntilNil

`func (o *ConsumerQuarantine) SetCooldownUntilNil(b bool)`

 SetCooldownUntilNil sets the value for CooldownUntil to be an explicit nil

### UnsetCooldownUntil
`func (o *ConsumerQuarantine) UnsetCooldownUntil()`

UnsetCooldownUntil ensures that no value is present for CooldownUntil, not even an explicit nil
### GetReleasedAt

`func (o *ConsumerQuarantine) GetReleasedAt() time.Time`

GetReleasedAt returns the ReleasedAt field if non-nil, zero value otherwise.

### GetReleasedAtOk

`func (o *ConsumerQuarantine) GetReleasedAtOk() (*time.Time, bool)`

GetReleasedAtOk returns a tuple with the ReleasedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedAt

`func (o *ConsumerQuarantine) SetReleasedAt(v time.Time)`

SetReleasedAt sets ReleasedAt field to given value.

### HasReleasedAt

`func (o *ConsumerQuarantine) HasReleasedAt() bool`

HasReleasedAt returns a boolean if a field has been set.

### SetReleasedAtNil

`func (o *ConsumerQuarantine) SetReleasedAtNil(b bool)`

 SetReleasedAtNil sets the value for ReleasedAt to be an explicit nil

### UnsetReleasedAt
`func (o *ConsumerQuarantine) UnsetReleasedAt()`

UnsetReleasedAt ensures that no value is present for ReleasedAt, not even an explicit nil
### GetReleasedBy

`func (o *ConsumerQuarantine) GetReleasedBy() string`

GetReleasedBy returns the ReleasedBy field if non-nil, zero value otherwise.

### GetReleasedByOk

`func (o *ConsumerQuarantine) GetReleasedByOk() (*string, bool)`

GetReleasedByOk returns a tuple with the ReleasedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedBy

`func (o *ConsumerQuarantine) SetReleasedBy(v string)`

SetReleasedBy sets ReleasedBy field to given value.

### HasReleasedBy

`func (o *ConsumerQuarantine) HasReleasedBy() bool`

HasReleasedBy returns a boolean if a field has been set.

### SetReleasedByNil

`func (o *ConsumerQuarantine) SetReleasedByNil(b bool)`

 SetReleasedByNil sets the value for ReleasedBy to be an explicit nil

### UnsetReleasedBy
`func (o *ConsumerQuarantine) UnsetReleasedBy()`

UnsetReleasedBy ensures that no value is present for ReleasedBy, not even an explicit nil
### GetReleaseReason

`func (o *ConsumerQuarantine) GetReleaseReason() string`

GetReleaseReason returns the ReleaseReason field if non-nil, zero value otherwise.

### GetReleaseReasonOk

`func (o *ConsumerQuarantine) GetReleaseReasonOk() (*string, bool)`

GetReleaseReasonOk returns a tuple with the ReleaseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseReason

`func (o *ConsumerQuarantine) SetReleaseReason(v string)`

SetReleaseReason sets ReleaseReason field to given value.

### HasReleaseReason

`func (o *ConsumerQuarantine) HasReleaseReason() bool`

HasReleaseReason returns a boolean if a field has been set.

### SetReleaseReasonNil

`func (o *ConsumerQuarantine) SetReleaseReasonNil(b bool)`

 SetReleaseReasonNil sets the value for ReleaseReason to be an explicit nil

### UnsetReleaseReason
`func (o *ConsumerQuarantine) UnsetReleaseReason()`

UnsetReleaseReason ensures that no value is present for ReleaseReason, not even an explicit nil
### GetRevision

`func (o *ConsumerQuarantine) GetRevision() int64`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ConsumerQuarantine) GetRevisionOk() (*int64, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ConsumerQuarantine) SetRevision(v int64)`

SetRevision sets Revision field to given value.

### HasRevision

`func (o *ConsumerQuarantine) HasRevision() bool`

HasRevision returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ConsumerQuarantine) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ConsumerQuarantine) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ConsumerQuarantine) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ConsumerQuarantine) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ConsumerQuarantine) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ConsumerQuarantine) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetEvents

`func (o *ConsumerQuarantine) GetEvents() []ConsumerQuarantineEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *ConsumerQuarantine) GetEventsOk() (*[]ConsumerQuarantineEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *ConsumerQuarantine) SetEvents(v []ConsumerQuarantineEvent)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


