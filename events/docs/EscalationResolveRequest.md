# EscalationResolveRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedRevision** | **int32** |  | 
**Resolution** | **string** |  | 

## Methods

### NewEscalationResolveRequest

`func NewEscalationResolveRequest(expectedRevision int32, resolution string, ) *EscalationResolveRequest`

NewEscalationResolveRequest instantiates a new EscalationResolveRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEscalationResolveRequestWithDefaults

`func NewEscalationResolveRequestWithDefaults() *EscalationResolveRequest`

NewEscalationResolveRequestWithDefaults instantiates a new EscalationResolveRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedRevision

`func (o *EscalationResolveRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *EscalationResolveRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *EscalationResolveRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetResolution

`func (o *EscalationResolveRequest) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *EscalationResolveRequest) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *EscalationResolveRequest) SetResolution(v string)`

SetResolution sets Resolution field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


