# OperatorRuntimeMetricsAggregate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **NullableString** |  | 
**CapturedAt** | **time.Time** |  | 
**Consumers** | [**OperatorRuntimeMetricsConsumerSummary**](OperatorRuntimeMetricsConsumerSummary.md) |  | 
**Assignment** | [**OperatorRuntimeMetricsAssignment**](OperatorRuntimeMetricsAssignment.md) |  | 
**Workers** | [**OperatorRuntimeMetricsWorkers**](OperatorRuntimeMetricsWorkers.md) |  | 
**Supervisors** | [**OperatorRuntimeMetricsSupervisors**](OperatorRuntimeMetricsSupervisors.md) |  | 
**Deliveries** | [**OperatorRuntimeMetricsDeliveries**](OperatorRuntimeMetricsDeliveries.md) |  | 
**Collection** | [**OperatorRuntimeMetricsCollectionState**](OperatorRuntimeMetricsCollectionState.md) |  | 
**Points** | Pointer to [**[]OperatorRuntimeMetricPoint**](OperatorRuntimeMetricPoint.md) |  | [optional] 

## Methods

### NewOperatorRuntimeMetricsAggregate

`func NewOperatorRuntimeMetricsAggregate(organizationId NullableString, capturedAt time.Time, consumers OperatorRuntimeMetricsConsumerSummary, assignment OperatorRuntimeMetricsAssignment, workers OperatorRuntimeMetricsWorkers, supervisors OperatorRuntimeMetricsSupervisors, deliveries OperatorRuntimeMetricsDeliveries, collection OperatorRuntimeMetricsCollectionState, ) *OperatorRuntimeMetricsAggregate`

NewOperatorRuntimeMetricsAggregate instantiates a new OperatorRuntimeMetricsAggregate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricsAggregateWithDefaults

`func NewOperatorRuntimeMetricsAggregateWithDefaults() *OperatorRuntimeMetricsAggregate`

NewOperatorRuntimeMetricsAggregateWithDefaults instantiates a new OperatorRuntimeMetricsAggregate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *OperatorRuntimeMetricsAggregate) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeMetricsAggregate) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeMetricsAggregate) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorRuntimeMetricsAggregate) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeMetricsAggregate) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetCapturedAt

`func (o *OperatorRuntimeMetricsAggregate) GetCapturedAt() time.Time`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *OperatorRuntimeMetricsAggregate) GetCapturedAtOk() (*time.Time, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *OperatorRuntimeMetricsAggregate) SetCapturedAt(v time.Time)`

SetCapturedAt sets CapturedAt field to given value.


### GetConsumers

`func (o *OperatorRuntimeMetricsAggregate) GetConsumers() OperatorRuntimeMetricsConsumerSummary`

GetConsumers returns the Consumers field if non-nil, zero value otherwise.

### GetConsumersOk

`func (o *OperatorRuntimeMetricsAggregate) GetConsumersOk() (*OperatorRuntimeMetricsConsumerSummary, bool)`

GetConsumersOk returns a tuple with the Consumers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumers

`func (o *OperatorRuntimeMetricsAggregate) SetConsumers(v OperatorRuntimeMetricsConsumerSummary)`

SetConsumers sets Consumers field to given value.


### GetAssignment

`func (o *OperatorRuntimeMetricsAggregate) GetAssignment() OperatorRuntimeMetricsAssignment`

GetAssignment returns the Assignment field if non-nil, zero value otherwise.

### GetAssignmentOk

`func (o *OperatorRuntimeMetricsAggregate) GetAssignmentOk() (*OperatorRuntimeMetricsAssignment, bool)`

GetAssignmentOk returns a tuple with the Assignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignment

`func (o *OperatorRuntimeMetricsAggregate) SetAssignment(v OperatorRuntimeMetricsAssignment)`

SetAssignment sets Assignment field to given value.


### GetWorkers

`func (o *OperatorRuntimeMetricsAggregate) GetWorkers() OperatorRuntimeMetricsWorkers`

GetWorkers returns the Workers field if non-nil, zero value otherwise.

### GetWorkersOk

`func (o *OperatorRuntimeMetricsAggregate) GetWorkersOk() (*OperatorRuntimeMetricsWorkers, bool)`

GetWorkersOk returns a tuple with the Workers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkers

`func (o *OperatorRuntimeMetricsAggregate) SetWorkers(v OperatorRuntimeMetricsWorkers)`

SetWorkers sets Workers field to given value.


### GetSupervisors

`func (o *OperatorRuntimeMetricsAggregate) GetSupervisors() OperatorRuntimeMetricsSupervisors`

GetSupervisors returns the Supervisors field if non-nil, zero value otherwise.

### GetSupervisorsOk

`func (o *OperatorRuntimeMetricsAggregate) GetSupervisorsOk() (*OperatorRuntimeMetricsSupervisors, bool)`

GetSupervisorsOk returns a tuple with the Supervisors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisors

`func (o *OperatorRuntimeMetricsAggregate) SetSupervisors(v OperatorRuntimeMetricsSupervisors)`

SetSupervisors sets Supervisors field to given value.


### GetDeliveries

`func (o *OperatorRuntimeMetricsAggregate) GetDeliveries() OperatorRuntimeMetricsDeliveries`

GetDeliveries returns the Deliveries field if non-nil, zero value otherwise.

### GetDeliveriesOk

`func (o *OperatorRuntimeMetricsAggregate) GetDeliveriesOk() (*OperatorRuntimeMetricsDeliveries, bool)`

GetDeliveriesOk returns a tuple with the Deliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveries

`func (o *OperatorRuntimeMetricsAggregate) SetDeliveries(v OperatorRuntimeMetricsDeliveries)`

SetDeliveries sets Deliveries field to given value.


### GetCollection

`func (o *OperatorRuntimeMetricsAggregate) GetCollection() OperatorRuntimeMetricsCollectionState`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *OperatorRuntimeMetricsAggregate) GetCollectionOk() (*OperatorRuntimeMetricsCollectionState, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *OperatorRuntimeMetricsAggregate) SetCollection(v OperatorRuntimeMetricsCollectionState)`

SetCollection sets Collection field to given value.


### GetPoints

`func (o *OperatorRuntimeMetricsAggregate) GetPoints() []OperatorRuntimeMetricPoint`

GetPoints returns the Points field if non-nil, zero value otherwise.

### GetPointsOk

`func (o *OperatorRuntimeMetricsAggregate) GetPointsOk() (*[]OperatorRuntimeMetricPoint, bool)`

GetPointsOk returns a tuple with the Points field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoints

`func (o *OperatorRuntimeMetricsAggregate) SetPoints(v []OperatorRuntimeMetricPoint)`

SetPoints sets Points field to given value.

### HasPoints

`func (o *OperatorRuntimeMetricsAggregate) HasPoints() bool`

HasPoints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


