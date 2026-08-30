# RegionalFailoverExecutionCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SafetyDecisionId** | **string** |  | 
**Reason** | **string** |  | 
**Metadata** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewRegionalFailoverExecutionCreateRequest

`func NewRegionalFailoverExecutionCreateRequest(safetyDecisionId string, reason string, ) *RegionalFailoverExecutionCreateRequest`

NewRegionalFailoverExecutionCreateRequest instantiates a new RegionalFailoverExecutionCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverExecutionCreateRequestWithDefaults

`func NewRegionalFailoverExecutionCreateRequestWithDefaults() *RegionalFailoverExecutionCreateRequest`

NewRegionalFailoverExecutionCreateRequestWithDefaults instantiates a new RegionalFailoverExecutionCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSafetyDecisionId

`func (o *RegionalFailoverExecutionCreateRequest) GetSafetyDecisionId() string`

GetSafetyDecisionId returns the SafetyDecisionId field if non-nil, zero value otherwise.

### GetSafetyDecisionIdOk

`func (o *RegionalFailoverExecutionCreateRequest) GetSafetyDecisionIdOk() (*string, bool)`

GetSafetyDecisionIdOk returns a tuple with the SafetyDecisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafetyDecisionId

`func (o *RegionalFailoverExecutionCreateRequest) SetSafetyDecisionId(v string)`

SetSafetyDecisionId sets SafetyDecisionId field to given value.


### GetReason

`func (o *RegionalFailoverExecutionCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RegionalFailoverExecutionCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RegionalFailoverExecutionCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### GetMetadata

`func (o *RegionalFailoverExecutionCreateRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RegionalFailoverExecutionCreateRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RegionalFailoverExecutionCreateRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RegionalFailoverExecutionCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *RegionalFailoverExecutionCreateRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *RegionalFailoverExecutionCreateRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


