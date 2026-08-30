# PaginatedOperatorRuntimeIncidentListList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Next** | Pointer to **NullableString** |  | [optional] 
**Previous** | Pointer to **NullableString** |  | [optional] 
**Results** | [**[]OperatorRuntimeIncidentList**](OperatorRuntimeIncidentList.md) |  | 

## Methods

### NewPaginatedOperatorRuntimeIncidentListList

`func NewPaginatedOperatorRuntimeIncidentListList(count int32, results []OperatorRuntimeIncidentList, ) *PaginatedOperatorRuntimeIncidentListList`

NewPaginatedOperatorRuntimeIncidentListList instantiates a new PaginatedOperatorRuntimeIncidentListList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedOperatorRuntimeIncidentListListWithDefaults

`func NewPaginatedOperatorRuntimeIncidentListListWithDefaults() *PaginatedOperatorRuntimeIncidentListList`

NewPaginatedOperatorRuntimeIncidentListListWithDefaults instantiates a new PaginatedOperatorRuntimeIncidentListList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *PaginatedOperatorRuntimeIncidentListList) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedOperatorRuntimeIncidentListList) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedOperatorRuntimeIncidentListList) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNext

`func (o *PaginatedOperatorRuntimeIncidentListList) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *PaginatedOperatorRuntimeIncidentListList) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *PaginatedOperatorRuntimeIncidentListList) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *PaginatedOperatorRuntimeIncidentListList) HasNext() bool`

HasNext returns a boolean if a field has been set.

### SetNextNil

`func (o *PaginatedOperatorRuntimeIncidentListList) SetNextNil(b bool)`

 SetNextNil sets the value for Next to be an explicit nil

### UnsetNext
`func (o *PaginatedOperatorRuntimeIncidentListList) UnsetNext()`

UnsetNext ensures that no value is present for Next, not even an explicit nil
### GetPrevious

`func (o *PaginatedOperatorRuntimeIncidentListList) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *PaginatedOperatorRuntimeIncidentListList) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *PaginatedOperatorRuntimeIncidentListList) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *PaginatedOperatorRuntimeIncidentListList) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.

### SetPreviousNil

`func (o *PaginatedOperatorRuntimeIncidentListList) SetPreviousNil(b bool)`

 SetPreviousNil sets the value for Previous to be an explicit nil

### UnsetPrevious
`func (o *PaginatedOperatorRuntimeIncidentListList) UnsetPrevious()`

UnsetPrevious ensures that no value is present for Previous, not even an explicit nil
### GetResults

`func (o *PaginatedOperatorRuntimeIncidentListList) GetResults() []OperatorRuntimeIncidentList`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PaginatedOperatorRuntimeIncidentListList) GetResultsOk() (*[]OperatorRuntimeIncidentList, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PaginatedOperatorRuntimeIncidentListList) SetResults(v []OperatorRuntimeIncidentList)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


