# SaaSOperatorReservationRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReservationId** | **string** |  | 
**OrganizationId** | **string** |  | 
**QuotaCode** | **string** |  | 
**Status** | **string** |  | 
**RequestedQuantity** | **string** |  | 
**CommittedQuantity** | **string** |  | 
**ReleasedQuantity** | **string** |  | 
**RemainingQuantity** | **string** |  | 
**LeaseExpiresAt** | **time.Time** |  | 
**ReservedAt** | **time.Time** |  | 
**Revision** | **int32** |  | 

## Methods

### NewSaaSOperatorReservationRecord

`func NewSaaSOperatorReservationRecord(reservationId string, organizationId string, quotaCode string, status string, requestedQuantity string, committedQuantity string, releasedQuantity string, remainingQuantity string, leaseExpiresAt time.Time, reservedAt time.Time, revision int32, ) *SaaSOperatorReservationRecord`

NewSaaSOperatorReservationRecord instantiates a new SaaSOperatorReservationRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaaSOperatorReservationRecordWithDefaults

`func NewSaaSOperatorReservationRecordWithDefaults() *SaaSOperatorReservationRecord`

NewSaaSOperatorReservationRecordWithDefaults instantiates a new SaaSOperatorReservationRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReservationId

`func (o *SaaSOperatorReservationRecord) GetReservationId() string`

GetReservationId returns the ReservationId field if non-nil, zero value otherwise.

### GetReservationIdOk

`func (o *SaaSOperatorReservationRecord) GetReservationIdOk() (*string, bool)`

GetReservationIdOk returns a tuple with the ReservationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservationId

`func (o *SaaSOperatorReservationRecord) SetReservationId(v string)`

SetReservationId sets ReservationId field to given value.


### GetOrganizationId

`func (o *SaaSOperatorReservationRecord) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *SaaSOperatorReservationRecord) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *SaaSOperatorReservationRecord) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetQuotaCode

`func (o *SaaSOperatorReservationRecord) GetQuotaCode() string`

GetQuotaCode returns the QuotaCode field if non-nil, zero value otherwise.

### GetQuotaCodeOk

`func (o *SaaSOperatorReservationRecord) GetQuotaCodeOk() (*string, bool)`

GetQuotaCodeOk returns a tuple with the QuotaCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaCode

`func (o *SaaSOperatorReservationRecord) SetQuotaCode(v string)`

SetQuotaCode sets QuotaCode field to given value.


### GetStatus

`func (o *SaaSOperatorReservationRecord) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SaaSOperatorReservationRecord) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SaaSOperatorReservationRecord) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetRequestedQuantity

`func (o *SaaSOperatorReservationRecord) GetRequestedQuantity() string`

GetRequestedQuantity returns the RequestedQuantity field if non-nil, zero value otherwise.

### GetRequestedQuantityOk

`func (o *SaaSOperatorReservationRecord) GetRequestedQuantityOk() (*string, bool)`

GetRequestedQuantityOk returns a tuple with the RequestedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedQuantity

`func (o *SaaSOperatorReservationRecord) SetRequestedQuantity(v string)`

SetRequestedQuantity sets RequestedQuantity field to given value.


### GetCommittedQuantity

`func (o *SaaSOperatorReservationRecord) GetCommittedQuantity() string`

GetCommittedQuantity returns the CommittedQuantity field if non-nil, zero value otherwise.

### GetCommittedQuantityOk

`func (o *SaaSOperatorReservationRecord) GetCommittedQuantityOk() (*string, bool)`

GetCommittedQuantityOk returns a tuple with the CommittedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommittedQuantity

`func (o *SaaSOperatorReservationRecord) SetCommittedQuantity(v string)`

SetCommittedQuantity sets CommittedQuantity field to given value.


### GetReleasedQuantity

`func (o *SaaSOperatorReservationRecord) GetReleasedQuantity() string`

GetReleasedQuantity returns the ReleasedQuantity field if non-nil, zero value otherwise.

### GetReleasedQuantityOk

`func (o *SaaSOperatorReservationRecord) GetReleasedQuantityOk() (*string, bool)`

GetReleasedQuantityOk returns a tuple with the ReleasedQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleasedQuantity

`func (o *SaaSOperatorReservationRecord) SetReleasedQuantity(v string)`

SetReleasedQuantity sets ReleasedQuantity field to given value.


### GetRemainingQuantity

`func (o *SaaSOperatorReservationRecord) GetRemainingQuantity() string`

GetRemainingQuantity returns the RemainingQuantity field if non-nil, zero value otherwise.

### GetRemainingQuantityOk

`func (o *SaaSOperatorReservationRecord) GetRemainingQuantityOk() (*string, bool)`

GetRemainingQuantityOk returns a tuple with the RemainingQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemainingQuantity

`func (o *SaaSOperatorReservationRecord) SetRemainingQuantity(v string)`

SetRemainingQuantity sets RemainingQuantity field to given value.


### GetLeaseExpiresAt

`func (o *SaaSOperatorReservationRecord) GetLeaseExpiresAt() time.Time`

GetLeaseExpiresAt returns the LeaseExpiresAt field if non-nil, zero value otherwise.

### GetLeaseExpiresAtOk

`func (o *SaaSOperatorReservationRecord) GetLeaseExpiresAtOk() (*time.Time, bool)`

GetLeaseExpiresAtOk returns a tuple with the LeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseExpiresAt

`func (o *SaaSOperatorReservationRecord) SetLeaseExpiresAt(v time.Time)`

SetLeaseExpiresAt sets LeaseExpiresAt field to given value.


### GetReservedAt

`func (o *SaaSOperatorReservationRecord) GetReservedAt() time.Time`

GetReservedAt returns the ReservedAt field if non-nil, zero value otherwise.

### GetReservedAtOk

`func (o *SaaSOperatorReservationRecord) GetReservedAtOk() (*time.Time, bool)`

GetReservedAtOk returns a tuple with the ReservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedAt

`func (o *SaaSOperatorReservationRecord) SetReservedAt(v time.Time)`

SetReservedAt sets ReservedAt field to given value.


### GetRevision

`func (o *SaaSOperatorReservationRecord) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *SaaSOperatorReservationRecord) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *SaaSOperatorReservationRecord) SetRevision(v int32)`

SetRevision sets Revision field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


