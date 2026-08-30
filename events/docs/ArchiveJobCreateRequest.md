# ArchiveJobCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Source** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**WindowStart** | **time.Time** |  | 
**WindowEnd** | **time.Time** |  | 
**MaxAttempts** | Pointer to **int32** |  | [optional] [default to 5]

## Methods

### NewArchiveJobCreateRequest

`func NewArchiveJobCreateRequest(source string, idempotencyKey string, windowStart time.Time, windowEnd time.Time, ) *ArchiveJobCreateRequest`

NewArchiveJobCreateRequest instantiates a new ArchiveJobCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewArchiveJobCreateRequestWithDefaults

`func NewArchiveJobCreateRequestWithDefaults() *ArchiveJobCreateRequest`

NewArchiveJobCreateRequestWithDefaults instantiates a new ArchiveJobCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSource

`func (o *ArchiveJobCreateRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ArchiveJobCreateRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ArchiveJobCreateRequest) SetSource(v string)`

SetSource sets Source field to given value.


### GetIdempotencyKey

`func (o *ArchiveJobCreateRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *ArchiveJobCreateRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *ArchiveJobCreateRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetWindowStart

`func (o *ArchiveJobCreateRequest) GetWindowStart() time.Time`

GetWindowStart returns the WindowStart field if non-nil, zero value otherwise.

### GetWindowStartOk

`func (o *ArchiveJobCreateRequest) GetWindowStartOk() (*time.Time, bool)`

GetWindowStartOk returns a tuple with the WindowStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowStart

`func (o *ArchiveJobCreateRequest) SetWindowStart(v time.Time)`

SetWindowStart sets WindowStart field to given value.


### GetWindowEnd

`func (o *ArchiveJobCreateRequest) GetWindowEnd() time.Time`

GetWindowEnd returns the WindowEnd field if non-nil, zero value otherwise.

### GetWindowEndOk

`func (o *ArchiveJobCreateRequest) GetWindowEndOk() (*time.Time, bool)`

GetWindowEndOk returns a tuple with the WindowEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowEnd

`func (o *ArchiveJobCreateRequest) SetWindowEnd(v time.Time)`

SetWindowEnd sets WindowEnd field to given value.


### GetMaxAttempts

`func (o *ArchiveJobCreateRequest) GetMaxAttempts() int32`

GetMaxAttempts returns the MaxAttempts field if non-nil, zero value otherwise.

### GetMaxAttemptsOk

`func (o *ArchiveJobCreateRequest) GetMaxAttemptsOk() (*int32, bool)`

GetMaxAttemptsOk returns a tuple with the MaxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAttempts

`func (o *ArchiveJobCreateRequest) SetMaxAttempts(v int32)`

SetMaxAttempts sets MaxAttempts field to given value.

### HasMaxAttempts

`func (o *ArchiveJobCreateRequest) HasMaxAttempts() bool`

HasMaxAttempts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


