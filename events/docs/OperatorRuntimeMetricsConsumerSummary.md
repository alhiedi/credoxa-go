# OperatorRuntimeMetricsConsumerSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**Operational** | **int32** |  | 
**OperationalRatio** | **float64** |  | 
**HealthStatuses** | **map[string]int32** |  | 
**DesiredStatuses** | **map[string]int32** |  | 

## Methods

### NewOperatorRuntimeMetricsConsumerSummary

`func NewOperatorRuntimeMetricsConsumerSummary(total int32, operational int32, operationalRatio float64, healthStatuses map[string]int32, desiredStatuses map[string]int32, ) *OperatorRuntimeMetricsConsumerSummary`

NewOperatorRuntimeMetricsConsumerSummary instantiates a new OperatorRuntimeMetricsConsumerSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsConsumerSummaryWithDefaults

`func NewOperatorRuntimeMetricsConsumerSummaryWithDefaults() *OperatorRuntimeMetricsConsumerSummary`

NewOperatorRuntimeMetricsConsumerSummaryWithDefaults instantiates a new OperatorRuntimeMetricsConsumerSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OperatorRuntimeMetricsConsumerSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OperatorRuntimeMetricsConsumerSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OperatorRuntimeMetricsConsumerSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetOperational

`func (o *OperatorRuntimeMetricsConsumerSummary) GetOperational() int32`

GetOperational returns the Operational field if non-nil, zero value otherwise.

### GetOperationalOk

`func (o *OperatorRuntimeMetricsConsumerSummary) GetOperationalOk() (*int32, bool)`

GetOperationalOk returns a tuple with the Operational field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperational

`func (o *OperatorRuntimeMetricsConsumerSummary) SetOperational(v int32)`

SetOperational sets Operational field to given value.


### GetOperationalRatio

`func (o *OperatorRuntimeMetricsConsumerSummary) GetOperationalRatio() float64`

GetOperationalRatio returns the OperationalRatio field if non-nil, zero value otherwise.

### GetOperationalRatioOk

`func (o *OperatorRuntimeMetricsConsumerSummary) GetOperationalRatioOk() (*float64, bool)`

GetOperationalRatioOk returns a tuple with the OperationalRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationalRatio

`func (o *OperatorRuntimeMetricsConsumerSummary) SetOperationalRatio(v float64)`

SetOperationalRatio sets OperationalRatio field to given value.


### GetHealthStatuses

`func (o *OperatorRuntimeMetricsConsumerSummary) GetHealthStatuses() map[string]int32`

GetHealthStatuses returns the HealthStatuses field if non-nil, zero value otherwise.

### GetHealthStatusesOk

`func (o *OperatorRuntimeMetricsConsumerSummary) GetHealthStatusesOk() (*map[string]int32, bool)`

GetHealthStatusesOk returns a tuple with the HealthStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthStatuses

`func (o *OperatorRuntimeMetricsConsumerSummary) SetHealthStatuses(v map[string]int32)`

SetHealthStatuses sets HealthStatuses field to given value.


### GetDesiredStatuses

`func (o *OperatorRuntimeMetricsConsumerSummary) GetDesiredStatuses() map[string]int32`

GetDesiredStatuses returns the DesiredStatuses field if non-nil, zero value otherwise.

### GetDesiredStatusesOk

`func (o *OperatorRuntimeMetricsConsumerSummary) GetDesiredStatusesOk() (*map[string]int32, bool)`

GetDesiredStatusesOk returns a tuple with the DesiredStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredStatuses

`func (o *OperatorRuntimeMetricsConsumerSummary) SetDesiredStatuses(v map[string]int32)`

SetDesiredStatuses sets DesiredStatuses field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


