# RegionHealthObservation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**RegionId** | **string** |  | 
**RegionCode** | **string** |  | 
**CheckType** | **string** |  | 
**Status** | **string** |  | 
**ObservedAt** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**LatencyMs** | **NullableInt32** |  | 
**NumericValue** | **NullableFloat64** |  | 
**Message** | **string** |  | 
**Source** | **string** |  | 
**Required** | **bool** |  | 
**Weight** | **int32** |  | 
**Evidence** | **interface{}** |  | 
**Fingerprint** | **string** |  | 

## Methods

### NewRegionHealthObservation

`func NewRegionHealthObservation(id string, organizationId string, regionId string, regionCode string, checkType string, status string, observedAt time.Time, expiresAt time.Time, latencyMs NullableInt32, numericValue NullableFloat64, message string, source string, required bool, weight int32, evidence interface{}, fingerprint string, ) *RegionHealthObservation`

NewRegionHealthObservation instantiates a new RegionHealthObservation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionHealthObservationWithDefaults

`func NewRegionHealthObservationWithDefaults() *RegionHealthObservation`

NewRegionHealthObservationWithDefaults instantiates a new RegionHealthObservation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionHealthObservation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionHealthObservation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionHealthObservation) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *RegionHealthObservation) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *RegionHealthObservation) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *RegionHealthObservation) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRegionId

`func (o *RegionHealthObservation) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *RegionHealthObservation) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *RegionHealthObservation) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.


### GetRegionCode

`func (o *RegionHealthObservation) GetRegionCode() string`

GetRegionCode returns the RegionCode field if non-nil, zero value otherwise.

### GetRegionCodeOk

`func (o *RegionHealthObservation) GetRegionCodeOk() (*string, bool)`

GetRegionCodeOk returns a tuple with the RegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionCode

`func (o *RegionHealthObservation) SetRegionCode(v string)`

SetRegionCode sets RegionCode field to given value.


### GetCheckType

`func (o *RegionHealthObservation) GetCheckType() string`

GetCheckType returns the CheckType field if non-nil, zero value otherwise.

### GetCheckTypeOk

`func (o *RegionHealthObservation) GetCheckTypeOk() (*string, bool)`

GetCheckTypeOk returns a tuple with the CheckType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckType

`func (o *RegionHealthObservation) SetCheckType(v string)`

SetCheckType sets CheckType field to given value.


### GetStatus

`func (o *RegionHealthObservation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RegionHealthObservation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RegionHealthObservation) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetObservedAt

`func (o *RegionHealthObservation) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *RegionHealthObservation) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *RegionHealthObservation) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetExpiresAt

`func (o *RegionHealthObservation) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *RegionHealthObservation) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *RegionHealthObservation) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetLatencyMs

`func (o *RegionHealthObservation) GetLatencyMs() int32`

GetLatencyMs returns the LatencyMs field if non-nil, zero value otherwise.

### GetLatencyMsOk

`func (o *RegionHealthObservation) GetLatencyMsOk() (*int32, bool)`

GetLatencyMsOk returns a tuple with the LatencyMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatencyMs

`func (o *RegionHealthObservation) SetLatencyMs(v int32)`

SetLatencyMs sets LatencyMs field to given value.


### SetLatencyMsNil

`func (o *RegionHealthObservation) SetLatencyMsNil(b bool)`

 SetLatencyMsNil sets the value for LatencyMs to be an explicit nil

### UnsetLatencyMs
`func (o *RegionHealthObservation) UnsetLatencyMs()`

UnsetLatencyMs ensures that no value is present for LatencyMs, not even an explicit nil
### GetNumericValue

`func (o *RegionHealthObservation) GetNumericValue() float64`

GetNumericValue returns the NumericValue field if non-nil, zero value otherwise.

### GetNumericValueOk

`func (o *RegionHealthObservation) GetNumericValueOk() (*float64, bool)`

GetNumericValueOk returns a tuple with the NumericValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumericValue

`func (o *RegionHealthObservation) SetNumericValue(v float64)`

SetNumericValue sets NumericValue field to given value.


### SetNumericValueNil

`func (o *RegionHealthObservation) SetNumericValueNil(b bool)`

 SetNumericValueNil sets the value for NumericValue to be an explicit nil

### UnsetNumericValue
`func (o *RegionHealthObservation) UnsetNumericValue()`

UnsetNumericValue ensures that no value is present for NumericValue, not even an explicit nil
### GetMessage

`func (o *RegionHealthObservation) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionHealthObservation) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionHealthObservation) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetSource

`func (o *RegionHealthObservation) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RegionHealthObservation) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RegionHealthObservation) SetSource(v string)`

SetSource sets Source field to given value.


### GetRequired

`func (o *RegionHealthObservation) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *RegionHealthObservation) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *RegionHealthObservation) SetRequired(v bool)`

SetRequired sets Required field to given value.


### GetWeight

`func (o *RegionHealthObservation) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *RegionHealthObservation) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *RegionHealthObservation) SetWeight(v int32)`

SetWeight sets Weight field to given value.


### GetEvidence

`func (o *RegionHealthObservation) GetEvidence() interface{}`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *RegionHealthObservation) GetEvidenceOk() (*interface{}, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *RegionHealthObservation) SetEvidence(v interface{})`

SetEvidence sets Evidence field to given value.


### SetEvidenceNil

`func (o *RegionHealthObservation) SetEvidenceNil(b bool)`

 SetEvidenceNil sets the value for Evidence to be an explicit nil

### UnsetEvidence
`func (o *RegionHealthObservation) UnsetEvidence()`

UnsetEvidence ensures that no value is present for Evidence, not even an explicit nil
### GetFingerprint

`func (o *RegionHealthObservation) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *RegionHealthObservation) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *RegionHealthObservation) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


