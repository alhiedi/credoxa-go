# LifecycleReportRequestRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReportType** | [**LifecycleReportRequestReportTypeEnum**](LifecycleReportRequestReportTypeEnum.md) |  | 
**IdempotencyKey** | **string** |  | 
**ExpiresInDays** | Pointer to **int32** |  | [optional] [default to 30]
**GenerateImmediately** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewLifecycleReportRequestRequest

`func NewLifecycleReportRequestRequest(reportType LifecycleReportRequestReportTypeEnum, idempotencyKey string, ) *LifecycleReportRequestRequest`

NewLifecycleReportRequestRequest instantiates a new LifecycleReportRequestRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLifecycleReportRequestRequestWithDefaults

`func NewLifecycleReportRequestRequestWithDefaults() *LifecycleReportRequestRequest`

NewLifecycleReportRequestRequestWithDefaults instantiates a new LifecycleReportRequestRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReportType

`func (o *LifecycleReportRequestRequest) GetReportType() LifecycleReportRequestReportTypeEnum`

GetReportType returns the ReportType field if non-nil, zero value otherwise.

### GetReportTypeOk

`func (o *LifecycleReportRequestRequest) GetReportTypeOk() (*LifecycleReportRequestReportTypeEnum, bool)`

GetReportTypeOk returns a tuple with the ReportType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportType

`func (o *LifecycleReportRequestRequest) SetReportType(v LifecycleReportRequestReportTypeEnum)`

SetReportType sets ReportType field to given value.


### GetIdempotencyKey

`func (o *LifecycleReportRequestRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *LifecycleReportRequestRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *LifecycleReportRequestRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetExpiresInDays

`func (o *LifecycleReportRequestRequest) GetExpiresInDays() int32`

GetExpiresInDays returns the ExpiresInDays field if non-nil, zero value otherwise.

### GetExpiresInDaysOk

`func (o *LifecycleReportRequestRequest) GetExpiresInDaysOk() (*int32, bool)`

GetExpiresInDaysOk returns a tuple with the ExpiresInDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresInDays

`func (o *LifecycleReportRequestRequest) SetExpiresInDays(v int32)`

SetExpiresInDays sets ExpiresInDays field to given value.

### HasExpiresInDays

`func (o *LifecycleReportRequestRequest) HasExpiresInDays() bool`

HasExpiresInDays returns a boolean if a field has been set.

### GetGenerateImmediately

`func (o *LifecycleReportRequestRequest) GetGenerateImmediately() bool`

GetGenerateImmediately returns the GenerateImmediately field if non-nil, zero value otherwise.

### GetGenerateImmediatelyOk

`func (o *LifecycleReportRequestRequest) GetGenerateImmediatelyOk() (*bool, bool)`

GetGenerateImmediatelyOk returns a tuple with the GenerateImmediately field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateImmediately

`func (o *LifecycleReportRequestRequest) SetGenerateImmediately(v bool)`

SetGenerateImmediately sets GenerateImmediately field to given value.

### HasGenerateImmediately

`func (o *LifecycleReportRequestRequest) HasGenerateImmediately() bool`

HasGenerateImmediately returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


