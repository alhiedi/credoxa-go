# OperatorRuntimeDashboardResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Scope** | [**OperatorRuntimeDashboardScope**](OperatorRuntimeDashboardScope.md) |  | 
**GeneratedAt** | **time.Time** |  | 
**PlatformStatus** | [**PlatformStatusEnum**](PlatformStatusEnum.md) |  | 
**Kpis** | [**OperatorRuntimeDashboardKPI**](OperatorRuntimeDashboardKPI.md) |  | 
**Distributions** | [**OperatorRuntimeDashboardDistributions**](OperatorRuntimeDashboardDistributions.md) |  | 
**Collection** | [**OperatorRuntimeDashboardCollection**](OperatorRuntimeDashboardCollection.md) |  | 
**Alerts** | [**[]OperatorRuntimeDashboardAlert**](OperatorRuntimeDashboardAlert.md) |  | 
**TopConsumers** | [**[]OperatorRuntimeDashboardConsumerItem**](OperatorRuntimeDashboardConsumerItem.md) |  | 

## Methods

### NewOperatorRuntimeDashboardResponse

`func NewOperatorRuntimeDashboardResponse(scope OperatorRuntimeDashboardScope, generatedAt time.Time, platformStatus PlatformStatusEnum, kpis OperatorRuntimeDashboardKPI, distributions OperatorRuntimeDashboardDistributions, collection OperatorRuntimeDashboardCollection, alerts []OperatorRuntimeDashboardAlert, topConsumers []OperatorRuntimeDashboardConsumerItem, ) *OperatorRuntimeDashboardResponse`

NewOperatorRuntimeDashboardResponse instantiates a new OperatorRuntimeDashboardResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeDashboardResponseWithDefaults

`func NewOperatorRuntimeDashboardResponseWithDefaults() *OperatorRuntimeDashboardResponse`

NewOperatorRuntimeDashboardResponseWithDefaults instantiates a new OperatorRuntimeDashboardResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScope

`func (o *OperatorRuntimeDashboardResponse) GetScope() OperatorRuntimeDashboardScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *OperatorRuntimeDashboardResponse) GetScopeOk() (*OperatorRuntimeDashboardScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *OperatorRuntimeDashboardResponse) SetScope(v OperatorRuntimeDashboardScope)`

SetScope sets Scope field to given value.


### GetGeneratedAt

`func (o *OperatorRuntimeDashboardResponse) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *OperatorRuntimeDashboardResponse) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *OperatorRuntimeDashboardResponse) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPlatformStatus

`func (o *OperatorRuntimeDashboardResponse) GetPlatformStatus() PlatformStatusEnum`

GetPlatformStatus returns the PlatformStatus field if non-nil, zero value otherwise.

### GetPlatformStatusOk

`func (o *OperatorRuntimeDashboardResponse) GetPlatformStatusOk() (*PlatformStatusEnum, bool)`

GetPlatformStatusOk returns a tuple with the PlatformStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformStatus

`func (o *OperatorRuntimeDashboardResponse) SetPlatformStatus(v PlatformStatusEnum)`

SetPlatformStatus sets PlatformStatus field to given value.


### GetKpis

`func (o *OperatorRuntimeDashboardResponse) GetKpis() OperatorRuntimeDashboardKPI`

GetKpis returns the Kpis field if non-nil, zero value otherwise.

### GetKpisOk

`func (o *OperatorRuntimeDashboardResponse) GetKpisOk() (*OperatorRuntimeDashboardKPI, bool)`

GetKpisOk returns a tuple with the Kpis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKpis

`func (o *OperatorRuntimeDashboardResponse) SetKpis(v OperatorRuntimeDashboardKPI)`

SetKpis sets Kpis field to given value.


### GetDistributions

`func (o *OperatorRuntimeDashboardResponse) GetDistributions() OperatorRuntimeDashboardDistributions`

GetDistributions returns the Distributions field if non-nil, zero value otherwise.

### GetDistributionsOk

`func (o *OperatorRuntimeDashboardResponse) GetDistributionsOk() (*OperatorRuntimeDashboardDistributions, bool)`

GetDistributionsOk returns a tuple with the Distributions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistributions

`func (o *OperatorRuntimeDashboardResponse) SetDistributions(v OperatorRuntimeDashboardDistributions)`

SetDistributions sets Distributions field to given value.


### GetCollection

`func (o *OperatorRuntimeDashboardResponse) GetCollection() OperatorRuntimeDashboardCollection`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *OperatorRuntimeDashboardResponse) GetCollectionOk() (*OperatorRuntimeDashboardCollection, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *OperatorRuntimeDashboardResponse) SetCollection(v OperatorRuntimeDashboardCollection)`

SetCollection sets Collection field to given value.


### GetAlerts

`func (o *OperatorRuntimeDashboardResponse) GetAlerts() []OperatorRuntimeDashboardAlert`

GetAlerts returns the Alerts field if non-nil, zero value otherwise.

### GetAlertsOk

`func (o *OperatorRuntimeDashboardResponse) GetAlertsOk() (*[]OperatorRuntimeDashboardAlert, bool)`

GetAlertsOk returns a tuple with the Alerts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlerts

`func (o *OperatorRuntimeDashboardResponse) SetAlerts(v []OperatorRuntimeDashboardAlert)`

SetAlerts sets Alerts field to given value.


### GetTopConsumers

`func (o *OperatorRuntimeDashboardResponse) GetTopConsumers() []OperatorRuntimeDashboardConsumerItem`

GetTopConsumers returns the TopConsumers field if non-nil, zero value otherwise.

### GetTopConsumersOk

`func (o *OperatorRuntimeDashboardResponse) GetTopConsumersOk() (*[]OperatorRuntimeDashboardConsumerItem, bool)`

GetTopConsumersOk returns a tuple with the TopConsumers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopConsumers

`func (o *OperatorRuntimeDashboardResponse) SetTopConsumers(v []OperatorRuntimeDashboardConsumerItem)`

SetTopConsumers sets TopConsumers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


