# OperatorRuntimeDashboardDistributions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HealthStatuses** | **map[string]int32** |  | 
**DesiredStatuses** | **map[string]int32** |  | 

## Methods

### NewOperatorRuntimeDashboardDistributions

`func NewOperatorRuntimeDashboardDistributions(healthStatuses map[string]int32, desiredStatuses map[string]int32, ) *OperatorRuntimeDashboardDistributions`

NewOperatorRuntimeDashboardDistributions instantiates a new OperatorRuntimeDashboardDistributions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeDashboardDistributionsWithDefaults

`func NewOperatorRuntimeDashboardDistributionsWithDefaults() *OperatorRuntimeDashboardDistributions`

NewOperatorRuntimeDashboardDistributionsWithDefaults instantiates a new OperatorRuntimeDashboardDistributions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHealthStatuses

`func (o *OperatorRuntimeDashboardDistributions) GetHealthStatuses() map[string]int32`

GetHealthStatuses returns the HealthStatuses field if non-nil, zero value otherwise.

### GetHealthStatusesOk

`func (o *OperatorRuntimeDashboardDistributions) GetHealthStatusesOk() (*map[string]int32, bool)`

GetHealthStatusesOk returns a tuple with the HealthStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthStatuses

`func (o *OperatorRuntimeDashboardDistributions) SetHealthStatuses(v map[string]int32)`

SetHealthStatuses sets HealthStatuses field to given value.


### GetDesiredStatuses

`func (o *OperatorRuntimeDashboardDistributions) GetDesiredStatuses() map[string]int32`

GetDesiredStatuses returns the DesiredStatuses field if non-nil, zero value otherwise.

### GetDesiredStatusesOk

`func (o *OperatorRuntimeDashboardDistributions) GetDesiredStatusesOk() (*map[string]int32, bool)`

GetDesiredStatusesOk returns a tuple with the DesiredStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredStatuses

`func (o *OperatorRuntimeDashboardDistributions) SetDesiredStatuses(v map[string]int32)`

SetDesiredStatuses sets DesiredStatuses field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


