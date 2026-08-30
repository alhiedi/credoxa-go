# OperatorRuntimeMetricHealth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**Severity** | **int32** |  | 
**Operational** | **bool** |  | 

## Methods

### NewOperatorRuntimeMetricHealth

`func NewOperatorRuntimeMetricHealth(status string, severity int32, operational bool, ) *OperatorRuntimeMetricHealth`

NewOperatorRuntimeMetricHealth instantiates a new OperatorRuntimeMetricHealth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricHealthWithDefaults

`func NewOperatorRuntimeMetricHealthWithDefaults() *OperatorRuntimeMetricHealth`

NewOperatorRuntimeMetricHealthWithDefaults instantiates a new OperatorRuntimeMetricHealth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *OperatorRuntimeMetricHealth) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeMetricHealth) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeMetricHealth) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSeverity

`func (o *OperatorRuntimeMetricHealth) GetSeverity() int32`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeMetricHealth) GetSeverityOk() (*int32, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeMetricHealth) SetSeverity(v int32)`

SetSeverity sets Severity field to given value.


### GetOperational

`func (o *OperatorRuntimeMetricHealth) GetOperational() bool`

GetOperational returns the Operational field if non-nil, zero value otherwise.

### GetOperationalOk

`func (o *OperatorRuntimeMetricHealth) GetOperationalOk() (*bool, bool)`

GetOperationalOk returns a tuple with the Operational field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperational

`func (o *OperatorRuntimeMetricHealth) SetOperational(v bool)`

SetOperational sets Operational field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


