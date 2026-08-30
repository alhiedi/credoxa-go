# OperatorRuntimeMetricPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**ConsumerCode** | **string** |  | 
**DesiredStatus** | **string** |  | 
**Health** | [**OperatorRuntimeMetricHealth**](OperatorRuntimeMetricHealth.md) |  | 
**Assignment** | [**OperatorRuntimeMetricAssignment**](OperatorRuntimeMetricAssignment.md) |  | 
**Workers** | [**OperatorRuntimeMetricWorkers**](OperatorRuntimeMetricWorkers.md) |  | 
**Supervisor** | [**OperatorRuntimeMetricSupervisor**](OperatorRuntimeMetricSupervisor.md) |  | 
**Deliveries** | [**OperatorRuntimeMetricDeliveries**](OperatorRuntimeMetricDeliveries.md) |  | 
**Collection** | [**OperatorRuntimeMetricCollection**](OperatorRuntimeMetricCollection.md) |  | 
**CapturedAt** | **time.Time** |  | 

## Methods

### NewOperatorRuntimeMetricPoint

`func NewOperatorRuntimeMetricPoint(consumerId string, organizationId NullableString, consumerCode string, desiredStatus string, health OperatorRuntimeMetricHealth, assignment OperatorRuntimeMetricAssignment, workers OperatorRuntimeMetricWorkers, supervisor OperatorRuntimeMetricSupervisor, deliveries OperatorRuntimeMetricDeliveries, collection OperatorRuntimeMetricCollection, capturedAt time.Time, ) *OperatorRuntimeMetricPoint`

NewOperatorRuntimeMetricPoint instantiates a new OperatorRuntimeMetricPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeMetricPointWithDefaults

`func NewOperatorRuntimeMetricPointWithDefaults() *OperatorRuntimeMetricPoint`

NewOperatorRuntimeMetricPointWithDefaults instantiates a new OperatorRuntimeMetricPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *OperatorRuntimeMetricPoint) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorRuntimeMetricPoint) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorRuntimeMetricPoint) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeMetricPoint) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeMetricPoint) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeMetricPoint) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorRuntimeMetricPoint) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeMetricPoint) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorRuntimeMetricPoint) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeMetricPoint) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeMetricPoint) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.


### GetDesiredStatus

`func (o *OperatorRuntimeMetricPoint) GetDesiredStatus() string`

GetDesiredStatus returns the DesiredStatus field if non-nil, zero value otherwise.

### GetDesiredStatusOk

`func (o *OperatorRuntimeMetricPoint) GetDesiredStatusOk() (*string, bool)`

GetDesiredStatusOk returns a tuple with the DesiredStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredStatus

`func (o *OperatorRuntimeMetricPoint) SetDesiredStatus(v string)`

SetDesiredStatus sets DesiredStatus field to given value.


### GetHealth

`func (o *OperatorRuntimeMetricPoint) GetHealth() OperatorRuntimeMetricHealth`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *OperatorRuntimeMetricPoint) GetHealthOk() (*OperatorRuntimeMetricHealth, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *OperatorRuntimeMetricPoint) SetHealth(v OperatorRuntimeMetricHealth)`

SetHealth sets Health field to given value.


### GetAssignment

`func (o *OperatorRuntimeMetricPoint) GetAssignment() OperatorRuntimeMetricAssignment`

GetAssignment returns the Assignment field if non-nil, zero value otherwise.

### GetAssignmentOk

`func (o *OperatorRuntimeMetricPoint) GetAssignmentOk() (*OperatorRuntimeMetricAssignment, bool)`

GetAssignmentOk returns a tuple with the Assignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignment

`func (o *OperatorRuntimeMetricPoint) SetAssignment(v OperatorRuntimeMetricAssignment)`

SetAssignment sets Assignment field to given value.


### GetWorkers

`func (o *OperatorRuntimeMetricPoint) GetWorkers() OperatorRuntimeMetricWorkers`

GetWorkers returns the Workers field if non-nil, zero value otherwise.

### GetWorkersOk

`func (o *OperatorRuntimeMetricPoint) GetWorkersOk() (*OperatorRuntimeMetricWorkers, bool)`

GetWorkersOk returns a tuple with the Workers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkers

`func (o *OperatorRuntimeMetricPoint) SetWorkers(v OperatorRuntimeMetricWorkers)`

SetWorkers sets Workers field to given value.


### GetSupervisor

`func (o *OperatorRuntimeMetricPoint) GetSupervisor() OperatorRuntimeMetricSupervisor`

GetSupervisor returns the Supervisor field if non-nil, zero value otherwise.

### GetSupervisorOk

`func (o *OperatorRuntimeMetricPoint) GetSupervisorOk() (*OperatorRuntimeMetricSupervisor, bool)`

GetSupervisorOk returns a tuple with the Supervisor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisor

`func (o *OperatorRuntimeMetricPoint) SetSupervisor(v OperatorRuntimeMetricSupervisor)`

SetSupervisor sets Supervisor field to given value.


### GetDeliveries

`func (o *OperatorRuntimeMetricPoint) GetDeliveries() OperatorRuntimeMetricDeliveries`

GetDeliveries returns the Deliveries field if non-nil, zero value otherwise.

### GetDeliveriesOk

`func (o *OperatorRuntimeMetricPoint) GetDeliveriesOk() (*OperatorRuntimeMetricDeliveries, bool)`

GetDeliveriesOk returns a tuple with the Deliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveries

`func (o *OperatorRuntimeMetricPoint) SetDeliveries(v OperatorRuntimeMetricDeliveries)`

SetDeliveries sets Deliveries field to given value.


### GetCollection

`func (o *OperatorRuntimeMetricPoint) GetCollection() OperatorRuntimeMetricCollection`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *OperatorRuntimeMetricPoint) GetCollectionOk() (*OperatorRuntimeMetricCollection, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *OperatorRuntimeMetricPoint) SetCollection(v OperatorRuntimeMetricCollection)`

SetCollection sets Collection field to given value.


### GetCapturedAt

`func (o *OperatorRuntimeMetricPoint) GetCapturedAt() time.Time`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *OperatorRuntimeMetricPoint) GetCapturedAtOk() (*time.Time, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *OperatorRuntimeMetricPoint) SetCapturedAt(v time.Time)`

SetCapturedAt sets CapturedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


