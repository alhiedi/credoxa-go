# AnalyticsProjectionSelectorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **int32** |  | [optional] 
**ProjectionId** | Pointer to **string** |  | [optional] 
**RequireActive** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewAnalyticsProjectionSelectorRequest

`func NewAnalyticsProjectionSelectorRequest() *AnalyticsProjectionSelectorRequest`

NewAnalyticsProjectionSelectorRequest instantiates a new AnalyticsProjectionSelectorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsProjectionSelectorRequestWithDefaults

`func NewAnalyticsProjectionSelectorRequestWithDefaults() *AnalyticsProjectionSelectorRequest`

NewAnalyticsProjectionSelectorRequestWithDefaults instantiates a new AnalyticsProjectionSelectorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *AnalyticsProjectionSelectorRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AnalyticsProjectionSelectorRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AnalyticsProjectionSelectorRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AnalyticsProjectionSelectorRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetVersion

`func (o *AnalyticsProjectionSelectorRequest) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *AnalyticsProjectionSelectorRequest) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *AnalyticsProjectionSelectorRequest) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *AnalyticsProjectionSelectorRequest) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetProjectionId

`func (o *AnalyticsProjectionSelectorRequest) GetProjectionId() string`

GetProjectionId returns the ProjectionId field if non-nil, zero value otherwise.

### GetProjectionIdOk

`func (o *AnalyticsProjectionSelectorRequest) GetProjectionIdOk() (*string, bool)`

GetProjectionIdOk returns a tuple with the ProjectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionId

`func (o *AnalyticsProjectionSelectorRequest) SetProjectionId(v string)`

SetProjectionId sets ProjectionId field to given value.

### HasProjectionId

`func (o *AnalyticsProjectionSelectorRequest) HasProjectionId() bool`

HasProjectionId returns a boolean if a field has been set.

### GetRequireActive

`func (o *AnalyticsProjectionSelectorRequest) GetRequireActive() bool`

GetRequireActive returns the RequireActive field if non-nil, zero value otherwise.

### GetRequireActiveOk

`func (o *AnalyticsProjectionSelectorRequest) GetRequireActiveOk() (*bool, bool)`

GetRequireActiveOk returns a tuple with the RequireActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireActive

`func (o *AnalyticsProjectionSelectorRequest) SetRequireActive(v bool)`

SetRequireActive sets RequireActive field to given value.

### HasRequireActive

`func (o *AnalyticsProjectionSelectorRequest) HasRequireActive() bool`

HasRequireActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


