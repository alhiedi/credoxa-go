# OperatorConsumerSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** |  | 
**Counts** | **map[string]int32** |  | 
**EnabledBindings** | **int32** |  | 
**Deliveries** | [**OperatorConsumerDeliverySummary**](OperatorConsumerDeliverySummary.md) |  | 
**RecentFailures** | [**[]OperatorConsumerDeliveryFailure**](OperatorConsumerDeliveryFailure.md) |  | 

## Methods

### NewOperatorConsumerSummary

`func NewOperatorConsumerSummary(total int32, counts map[string]int32, enabledBindings int32, deliveries OperatorConsumerDeliverySummary, recentFailures []OperatorConsumerDeliveryFailure, ) *OperatorConsumerSummary`

NewOperatorConsumerSummary instantiates a new OperatorConsumerSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerSummaryWithDefaults

`func NewOperatorConsumerSummaryWithDefaults() *OperatorConsumerSummary`

NewOperatorConsumerSummaryWithDefaults instantiates a new OperatorConsumerSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *OperatorConsumerSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OperatorConsumerSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OperatorConsumerSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetCounts

`func (o *OperatorConsumerSummary) GetCounts() map[string]int32`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *OperatorConsumerSummary) GetCountsOk() (*map[string]int32, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *OperatorConsumerSummary) SetCounts(v map[string]int32)`

SetCounts sets Counts field to given value.


### GetEnabledBindings

`func (o *OperatorConsumerSummary) GetEnabledBindings() int32`

GetEnabledBindings returns the EnabledBindings field if non-nil, zero value otherwise.

### GetEnabledBindingsOk

`func (o *OperatorConsumerSummary) GetEnabledBindingsOk() (*int32, bool)`

GetEnabledBindingsOk returns a tuple with the EnabledBindings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabledBindings

`func (o *OperatorConsumerSummary) SetEnabledBindings(v int32)`

SetEnabledBindings sets EnabledBindings field to given value.


### GetDeliveries

`func (o *OperatorConsumerSummary) GetDeliveries() OperatorConsumerDeliverySummary`

GetDeliveries returns the Deliveries field if non-nil, zero value otherwise.

### GetDeliveriesOk

`func (o *OperatorConsumerSummary) GetDeliveriesOk() (*OperatorConsumerDeliverySummary, bool)`

GetDeliveriesOk returns a tuple with the Deliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveries

`func (o *OperatorConsumerSummary) SetDeliveries(v OperatorConsumerDeliverySummary)`

SetDeliveries sets Deliveries field to given value.


### GetRecentFailures

`func (o *OperatorConsumerSummary) GetRecentFailures() []OperatorConsumerDeliveryFailure`

GetRecentFailures returns the RecentFailures field if non-nil, zero value otherwise.

### GetRecentFailuresOk

`func (o *OperatorConsumerSummary) GetRecentFailuresOk() (*[]OperatorConsumerDeliveryFailure, bool)`

GetRecentFailuresOk returns a tuple with the RecentFailures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentFailures

`func (o *OperatorConsumerSummary) SetRecentFailures(v []OperatorConsumerDeliveryFailure)`

SetRecentFailures sets RecentFailures field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


