# OperatorConsumerRuntimeSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**ConsumerCode** | **string** |  | 
**ConsumerName** | **string** |  | 
**DesiredStatus** | **string** |  | 
**CapturedAt** | **time.Time** |  | 
**Assignment** | [**OperatorRuntimeAssignment**](OperatorRuntimeAssignment.md) |  | 
**Workers** | [**OperatorRuntimeWorkers**](OperatorRuntimeWorkers.md) |  | 
**Supervisor** | [**NullableOperatorRuntimeSupervisor**](OperatorRuntimeSupervisor.md) |  | 
**Deliveries** | [**OperatorRuntimeDeliveries**](OperatorRuntimeDeliveries.md) |  | 
**SourceErrors** | **map[string]string** |  | 

## Methods

### NewOperatorConsumerRuntimeSnapshot

`func NewOperatorConsumerRuntimeSnapshot(consumerId string, organizationId NullableString, consumerCode string, consumerName string, desiredStatus string, capturedAt time.Time, assignment OperatorRuntimeAssignment, workers OperatorRuntimeWorkers, supervisor NullableOperatorRuntimeSupervisor, deliveries OperatorRuntimeDeliveries, sourceErrors map[string]string, ) *OperatorConsumerRuntimeSnapshot`

NewOperatorConsumerRuntimeSnapshot instantiates a new OperatorConsumerRuntimeSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerRuntimeSnapshotWithDefaults

`func NewOperatorConsumerRuntimeSnapshotWithDefaults() *OperatorConsumerRuntimeSnapshot`

NewOperatorConsumerRuntimeSnapshotWithDefaults instantiates a new OperatorConsumerRuntimeSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *OperatorConsumerRuntimeSnapshot) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorConsumerRuntimeSnapshot) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorConsumerRuntimeSnapshot) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetOrganizationId

`func (o *OperatorConsumerRuntimeSnapshot) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorConsumerRuntimeSnapshot) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorConsumerRuntimeSnapshot) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorConsumerRuntimeSnapshot) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorConsumerRuntimeSnapshot) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorConsumerRuntimeSnapshot) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorConsumerRuntimeSnapshot) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorConsumerRuntimeSnapshot) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.


### GetConsumerName

`func (o *OperatorConsumerRuntimeSnapshot) GetConsumerName() string`

GetConsumerName returns the ConsumerName field if non-nil, zero value otherwise.

### GetConsumerNameOk

`func (o *OperatorConsumerRuntimeSnapshot) GetConsumerNameOk() (*string, bool)`

GetConsumerNameOk returns a tuple with the ConsumerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerName

`func (o *OperatorConsumerRuntimeSnapshot) SetConsumerName(v string)`

SetConsumerName sets ConsumerName field to given value.


### GetDesiredStatus

`func (o *OperatorConsumerRuntimeSnapshot) GetDesiredStatus() string`

GetDesiredStatus returns the DesiredStatus field if non-nil, zero value otherwise.

### GetDesiredStatusOk

`func (o *OperatorConsumerRuntimeSnapshot) GetDesiredStatusOk() (*string, bool)`

GetDesiredStatusOk returns a tuple with the DesiredStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredStatus

`func (o *OperatorConsumerRuntimeSnapshot) SetDesiredStatus(v string)`

SetDesiredStatus sets DesiredStatus field to given value.


### GetCapturedAt

`func (o *OperatorConsumerRuntimeSnapshot) GetCapturedAt() time.Time`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *OperatorConsumerRuntimeSnapshot) GetCapturedAtOk() (*time.Time, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *OperatorConsumerRuntimeSnapshot) SetCapturedAt(v time.Time)`

SetCapturedAt sets CapturedAt field to given value.


### GetAssignment

`func (o *OperatorConsumerRuntimeSnapshot) GetAssignment() OperatorRuntimeAssignment`

GetAssignment returns the Assignment field if non-nil, zero value otherwise.

### GetAssignmentOk

`func (o *OperatorConsumerRuntimeSnapshot) GetAssignmentOk() (*OperatorRuntimeAssignment, bool)`

GetAssignmentOk returns a tuple with the Assignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignment

`func (o *OperatorConsumerRuntimeSnapshot) SetAssignment(v OperatorRuntimeAssignment)`

SetAssignment sets Assignment field to given value.


### GetWorkers

`func (o *OperatorConsumerRuntimeSnapshot) GetWorkers() OperatorRuntimeWorkers`

GetWorkers returns the Workers field if non-nil, zero value otherwise.

### GetWorkersOk

`func (o *OperatorConsumerRuntimeSnapshot) GetWorkersOk() (*OperatorRuntimeWorkers, bool)`

GetWorkersOk returns a tuple with the Workers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkers

`func (o *OperatorConsumerRuntimeSnapshot) SetWorkers(v OperatorRuntimeWorkers)`

SetWorkers sets Workers field to given value.


### GetSupervisor

`func (o *OperatorConsumerRuntimeSnapshot) GetSupervisor() OperatorRuntimeSupervisor`

GetSupervisor returns the Supervisor field if non-nil, zero value otherwise.

### GetSupervisorOk

`func (o *OperatorConsumerRuntimeSnapshot) GetSupervisorOk() (*OperatorRuntimeSupervisor, bool)`

GetSupervisorOk returns a tuple with the Supervisor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisor

`func (o *OperatorConsumerRuntimeSnapshot) SetSupervisor(v OperatorRuntimeSupervisor)`

SetSupervisor sets Supervisor field to given value.


### SetSupervisorNil

`func (o *OperatorConsumerRuntimeSnapshot) SetSupervisorNil(b bool)`

 SetSupervisorNil sets the value for Supervisor to be an explicit nil

### UnsetSupervisor
`func (o *OperatorConsumerRuntimeSnapshot) UnsetSupervisor()`

UnsetSupervisor ensures that no value is present for Supervisor, not even an explicit nil
### GetDeliveries

`func (o *OperatorConsumerRuntimeSnapshot) GetDeliveries() OperatorRuntimeDeliveries`

GetDeliveries returns the Deliveries field if non-nil, zero value otherwise.

### GetDeliveriesOk

`func (o *OperatorConsumerRuntimeSnapshot) GetDeliveriesOk() (*OperatorRuntimeDeliveries, bool)`

GetDeliveriesOk returns a tuple with the Deliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveries

`func (o *OperatorConsumerRuntimeSnapshot) SetDeliveries(v OperatorRuntimeDeliveries)`

SetDeliveries sets Deliveries field to given value.


### GetSourceErrors

`func (o *OperatorConsumerRuntimeSnapshot) GetSourceErrors() map[string]string`

GetSourceErrors returns the SourceErrors field if non-nil, zero value otherwise.

### GetSourceErrorsOk

`func (o *OperatorConsumerRuntimeSnapshot) GetSourceErrorsOk() (*map[string]string, bool)`

GetSourceErrorsOk returns a tuple with the SourceErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceErrors

`func (o *OperatorConsumerRuntimeSnapshot) SetSourceErrors(v map[string]string)`

SetSourceErrors sets SourceErrors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


