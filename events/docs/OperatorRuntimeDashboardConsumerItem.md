# OperatorRuntimeDashboardConsumerItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**ConsumerCode** | **string** |  | 
**DesiredStatus** | **string** |  | 
**Health** | [**OperatorRuntimeDashboardConsumerHealth**](OperatorRuntimeDashboardConsumerHealth.md) |  | 
**Assignment** | [**OperatorRuntimeDashboardConsumerAssignment**](OperatorRuntimeDashboardConsumerAssignment.md) |  | 
**Workers** | [**OperatorRuntimeDashboardConsumerWorkers**](OperatorRuntimeDashboardConsumerWorkers.md) |  | 
**Deliveries** | [**OperatorRuntimeDashboardConsumerDeliveries**](OperatorRuntimeDashboardConsumerDeliveries.md) |  | 
**Supervisor** | [**OperatorRuntimeDashboardConsumerSupervisor**](OperatorRuntimeDashboardConsumerSupervisor.md) |  | 
**Collection** | [**OperatorRuntimeDashboardConsumerCollection**](OperatorRuntimeDashboardConsumerCollection.md) |  | 
**IssueScore** | **int32** |  | 
**CapturedAt** | **time.Time** |  | 

## Methods

### NewOperatorRuntimeDashboardConsumerItem

`func NewOperatorRuntimeDashboardConsumerItem(consumerId string, organizationId NullableString, consumerCode string, desiredStatus string, health OperatorRuntimeDashboardConsumerHealth, assignment OperatorRuntimeDashboardConsumerAssignment, workers OperatorRuntimeDashboardConsumerWorkers, deliveries OperatorRuntimeDashboardConsumerDeliveries, supervisor OperatorRuntimeDashboardConsumerSupervisor, collection OperatorRuntimeDashboardConsumerCollection, issueScore int32, capturedAt time.Time, ) *OperatorRuntimeDashboardConsumerItem`

NewOperatorRuntimeDashboardConsumerItem instantiates a new OperatorRuntimeDashboardConsumerItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeDashboardConsumerItemWithDefaults

`func NewOperatorRuntimeDashboardConsumerItemWithDefaults() *OperatorRuntimeDashboardConsumerItem`

NewOperatorRuntimeDashboardConsumerItemWithDefaults instantiates a new OperatorRuntimeDashboardConsumerItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *OperatorRuntimeDashboardConsumerItem) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorRuntimeDashboardConsumerItem) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeDashboardConsumerItem) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeDashboardConsumerItem) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorRuntimeDashboardConsumerItem) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeDashboardConsumerItem) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorRuntimeDashboardConsumerItem) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeDashboardConsumerItem) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.


### GetDesiredStatus

`func (o *OperatorRuntimeDashboardConsumerItem) GetDesiredStatus() string`

GetDesiredStatus returns the DesiredStatus field if non-nil, zero value otherwise.

### GetDesiredStatusOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetDesiredStatusOk() (*string, bool)`

GetDesiredStatusOk returns a tuple with the DesiredStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredStatus

`func (o *OperatorRuntimeDashboardConsumerItem) SetDesiredStatus(v string)`

SetDesiredStatus sets DesiredStatus field to given value.


### GetHealth

`func (o *OperatorRuntimeDashboardConsumerItem) GetHealth() OperatorRuntimeDashboardConsumerHealth`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetHealthOk() (*OperatorRuntimeDashboardConsumerHealth, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *OperatorRuntimeDashboardConsumerItem) SetHealth(v OperatorRuntimeDashboardConsumerHealth)`

SetHealth sets Health field to given value.


### GetAssignment

`func (o *OperatorRuntimeDashboardConsumerItem) GetAssignment() OperatorRuntimeDashboardConsumerAssignment`

GetAssignment returns the Assignment field if non-nil, zero value otherwise.

### GetAssignmentOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetAssignmentOk() (*OperatorRuntimeDashboardConsumerAssignment, bool)`

GetAssignmentOk returns a tuple with the Assignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignment

`func (o *OperatorRuntimeDashboardConsumerItem) SetAssignment(v OperatorRuntimeDashboardConsumerAssignment)`

SetAssignment sets Assignment field to given value.


### GetWorkers

`func (o *OperatorRuntimeDashboardConsumerItem) GetWorkers() OperatorRuntimeDashboardConsumerWorkers`

GetWorkers returns the Workers field if non-nil, zero value otherwise.

### GetWorkersOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetWorkersOk() (*OperatorRuntimeDashboardConsumerWorkers, bool)`

GetWorkersOk returns a tuple with the Workers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkers

`func (o *OperatorRuntimeDashboardConsumerItem) SetWorkers(v OperatorRuntimeDashboardConsumerWorkers)`

SetWorkers sets Workers field to given value.


### GetDeliveries

`func (o *OperatorRuntimeDashboardConsumerItem) GetDeliveries() OperatorRuntimeDashboardConsumerDeliveries`

GetDeliveries returns the Deliveries field if non-nil, zero value otherwise.

### GetDeliveriesOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetDeliveriesOk() (*OperatorRuntimeDashboardConsumerDeliveries, bool)`

GetDeliveriesOk returns a tuple with the Deliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveries

`func (o *OperatorRuntimeDashboardConsumerItem) SetDeliveries(v OperatorRuntimeDashboardConsumerDeliveries)`

SetDeliveries sets Deliveries field to given value.


### GetSupervisor

`func (o *OperatorRuntimeDashboardConsumerItem) GetSupervisor() OperatorRuntimeDashboardConsumerSupervisor`

GetSupervisor returns the Supervisor field if non-nil, zero value otherwise.

### GetSupervisorOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetSupervisorOk() (*OperatorRuntimeDashboardConsumerSupervisor, bool)`

GetSupervisorOk returns a tuple with the Supervisor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisor

`func (o *OperatorRuntimeDashboardConsumerItem) SetSupervisor(v OperatorRuntimeDashboardConsumerSupervisor)`

SetSupervisor sets Supervisor field to given value.


### GetCollection

`func (o *OperatorRuntimeDashboardConsumerItem) GetCollection() OperatorRuntimeDashboardConsumerCollection`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetCollectionOk() (*OperatorRuntimeDashboardConsumerCollection, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *OperatorRuntimeDashboardConsumerItem) SetCollection(v OperatorRuntimeDashboardConsumerCollection)`

SetCollection sets Collection field to given value.


### GetIssueScore

`func (o *OperatorRuntimeDashboardConsumerItem) GetIssueScore() int32`

GetIssueScore returns the IssueScore field if non-nil, zero value otherwise.

### GetIssueScoreOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetIssueScoreOk() (*int32, bool)`

GetIssueScoreOk returns a tuple with the IssueScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueScore

`func (o *OperatorRuntimeDashboardConsumerItem) SetIssueScore(v int32)`

SetIssueScore sets IssueScore field to given value.


### GetCapturedAt

`func (o *OperatorRuntimeDashboardConsumerItem) GetCapturedAt() time.Time`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *OperatorRuntimeDashboardConsumerItem) GetCapturedAtOk() (*time.Time, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *OperatorRuntimeDashboardConsumerItem) SetCapturedAt(v time.Time)`

SetCapturedAt sets CapturedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


