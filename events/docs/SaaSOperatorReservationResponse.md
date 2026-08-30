# SaaSOperatorReservationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Results** | [**[]SaaSOperatorReservationRecord**](SaaSOperatorReservationRecord.md) |  | 

## Methods

### NewSaaSOperatorReservationResponse

`func NewSaaSOperatorReservationResponse(count int32, results []SaaSOperatorReservationRecord, ) *SaaSOperatorReservationResponse`

NewSaaSOperatorReservationResponse instantiates a new SaaSOperatorReservationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaaSOperatorReservationResponseWithDefaults

`func NewSaaSOperatorReservationResponseWithDefaults() *SaaSOperatorReservationResponse`

NewSaaSOperatorReservationResponseWithDefaults instantiates a new SaaSOperatorReservationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *SaaSOperatorReservationResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *SaaSOperatorReservationResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *SaaSOperatorReservationResponse) SetCount(v int32)`

SetCount sets Count field to given value.


### GetResults

`func (o *SaaSOperatorReservationResponse) GetResults() []SaaSOperatorReservationRecord`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *SaaSOperatorReservationResponse) GetResultsOk() (*[]SaaSOperatorReservationRecord, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *SaaSOperatorReservationResponse) SetResults(v []SaaSOperatorReservationRecord)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


