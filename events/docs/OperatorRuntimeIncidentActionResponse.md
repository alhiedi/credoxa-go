# OperatorRuntimeIncidentActionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IncidentId** | **string** |  | 
**Action** | **string** |  | 
**Status** | **string** |  | 
**OccurrenceId** | **string** |  | 
**Version** | **int32** |  | 
**OccurredAt** | **time.Time** |  | 

## Methods

### NewOperatorRuntimeIncidentActionResponse

`func NewOperatorRuntimeIncidentActionResponse(incidentId string, action string, status string, occurrenceId string, version int32, occurredAt time.Time, ) *OperatorRuntimeIncidentActionResponse`

NewOperatorRuntimeIncidentActionResponse instantiates a new OperatorRuntimeIncidentActionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentActionResponseWithDefaults

`func NewOperatorRuntimeIncidentActionResponseWithDefaults() *OperatorRuntimeIncidentActionResponse`

NewOperatorRuntimeIncidentActionResponseWithDefaults instantiates a new OperatorRuntimeIncidentActionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIncidentId

`func (o *OperatorRuntimeIncidentActionResponse) GetIncidentId() string`

GetIncidentId returns the IncidentId field if non-nil, zero value otherwise.

### GetIncidentIdOk

`func (o *OperatorRuntimeIncidentActionResponse) GetIncidentIdOk() (*string, bool)`

GetIncidentIdOk returns a tuple with the IncidentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentId

`func (o *OperatorRuntimeIncidentActionResponse) SetIncidentId(v string)`

SetIncidentId sets IncidentId field to given value.


### GetAction

`func (o *OperatorRuntimeIncidentActionResponse) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *OperatorRuntimeIncidentActionResponse) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *OperatorRuntimeIncidentActionResponse) SetAction(v string)`

SetAction sets Action field to given value.


### GetStatus

`func (o *OperatorRuntimeIncidentActionResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeIncidentActionResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeIncidentActionResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOccurrenceId

`func (o *OperatorRuntimeIncidentActionResponse) GetOccurrenceId() string`

GetOccurrenceId returns the OccurrenceId field if non-nil, zero value otherwise.

### GetOccurrenceIdOk

`func (o *OperatorRuntimeIncidentActionResponse) GetOccurrenceIdOk() (*string, bool)`

GetOccurrenceIdOk returns a tuple with the OccurrenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceId

`func (o *OperatorRuntimeIncidentActionResponse) SetOccurrenceId(v string)`

SetOccurrenceId sets OccurrenceId field to given value.


### GetVersion

`func (o *OperatorRuntimeIncidentActionResponse) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *OperatorRuntimeIncidentActionResponse) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *OperatorRuntimeIncidentActionResponse) SetVersion(v int32)`

SetVersion sets Version field to given value.


### GetOccurredAt

`func (o *OperatorRuntimeIncidentActionResponse) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *OperatorRuntimeIncidentActionResponse) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *OperatorRuntimeIncidentActionResponse) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


