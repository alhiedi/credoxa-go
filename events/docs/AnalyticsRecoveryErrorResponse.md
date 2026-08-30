# AnalyticsRecoveryErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Error** | [**AnalyticsRecoveryError**](AnalyticsRecoveryError.md) |  | 

## Methods

### NewAnalyticsRecoveryErrorResponse

`func NewAnalyticsRecoveryErrorResponse(success bool, error_ AnalyticsRecoveryError, ) *AnalyticsRecoveryErrorResponse`

NewAnalyticsRecoveryErrorResponse instantiates a new AnalyticsRecoveryErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsRecoveryErrorResponseWithDefaults

`func NewAnalyticsRecoveryErrorResponseWithDefaults() *AnalyticsRecoveryErrorResponse`

NewAnalyticsRecoveryErrorResponseWithDefaults instantiates a new AnalyticsRecoveryErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AnalyticsRecoveryErrorResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsRecoveryErrorResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsRecoveryErrorResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetError

`func (o *AnalyticsRecoveryErrorResponse) GetError() AnalyticsRecoveryError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AnalyticsRecoveryErrorResponse) GetErrorOk() (*AnalyticsRecoveryError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AnalyticsRecoveryErrorResponse) SetError(v AnalyticsRecoveryError)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


