# OperatorConsumerRuntimeHealth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConsumerId** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**ConsumerCode** | **string** |  | 
**DesiredStatus** | **string** |  | 
**Status** | [**OperatorConsumerRuntimeHealthStatusEnum**](OperatorConsumerRuntimeHealthStatusEnum.md) |  | 
**Severity** | **int32** |  | 
**IsOperational** | **bool** |  | 
**Reasons** | **[]string** |  | 
**Recommendations** | **[]string** |  | 
**Capacity** | [**OperatorRuntimeCapacity**](OperatorRuntimeCapacity.md) |  | 
**Deliveries** | [**OperatorRuntimeDelivery**](OperatorRuntimeDelivery.md) |  | 
**Findings** | [**[]OperatorRuntimeHealthFinding**](OperatorRuntimeHealthFinding.md) |  | 
**EvaluatedAt** | **time.Time** |  | 

## Methods

### NewOperatorConsumerRuntimeHealth

`func NewOperatorConsumerRuntimeHealth(consumerId string, organizationId NullableString, consumerCode string, desiredStatus string, status OperatorConsumerRuntimeHealthStatusEnum, severity int32, isOperational bool, reasons []string, recommendations []string, capacity OperatorRuntimeCapacity, deliveries OperatorRuntimeDelivery, findings []OperatorRuntimeHealthFinding, evaluatedAt time.Time, ) *OperatorConsumerRuntimeHealth`

NewOperatorConsumerRuntimeHealth instantiates a new OperatorConsumerRuntimeHealth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorConsumerRuntimeHealthWithDefaults

`func NewOperatorConsumerRuntimeHealthWithDefaults() *OperatorConsumerRuntimeHealth`

NewOperatorConsumerRuntimeHealthWithDefaults instantiates a new OperatorConsumerRuntimeHealth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsumerId

`func (o *OperatorConsumerRuntimeHealth) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorConsumerRuntimeHealth) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorConsumerRuntimeHealth) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.


### GetOrganizationId

`func (o *OperatorConsumerRuntimeHealth) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorConsumerRuntimeHealth) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorConsumerRuntimeHealth) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorConsumerRuntimeHealth) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorConsumerRuntimeHealth) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorConsumerRuntimeHealth) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorConsumerRuntimeHealth) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorConsumerRuntimeHealth) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.


### GetDesiredStatus

`func (o *OperatorConsumerRuntimeHealth) GetDesiredStatus() string`

GetDesiredStatus returns the DesiredStatus field if non-nil, zero value otherwise.

### GetDesiredStatusOk

`func (o *OperatorConsumerRuntimeHealth) GetDesiredStatusOk() (*string, bool)`

GetDesiredStatusOk returns a tuple with the DesiredStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesiredStatus

`func (o *OperatorConsumerRuntimeHealth) SetDesiredStatus(v string)`

SetDesiredStatus sets DesiredStatus field to given value.


### GetStatus

`func (o *OperatorConsumerRuntimeHealth) GetStatus() OperatorConsumerRuntimeHealthStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorConsumerRuntimeHealth) GetStatusOk() (*OperatorConsumerRuntimeHealthStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorConsumerRuntimeHealth) SetStatus(v OperatorConsumerRuntimeHealthStatusEnum)`

SetStatus sets Status field to given value.


### GetSeverity

`func (o *OperatorConsumerRuntimeHealth) GetSeverity() int32`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorConsumerRuntimeHealth) GetSeverityOk() (*int32, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorConsumerRuntimeHealth) SetSeverity(v int32)`

SetSeverity sets Severity field to given value.


### GetIsOperational

`func (o *OperatorConsumerRuntimeHealth) GetIsOperational() bool`

GetIsOperational returns the IsOperational field if non-nil, zero value otherwise.

### GetIsOperationalOk

`func (o *OperatorConsumerRuntimeHealth) GetIsOperationalOk() (*bool, bool)`

GetIsOperationalOk returns a tuple with the IsOperational field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOperational

`func (o *OperatorConsumerRuntimeHealth) SetIsOperational(v bool)`

SetIsOperational sets IsOperational field to given value.


### GetReasons

`func (o *OperatorConsumerRuntimeHealth) GetReasons() []string`

GetReasons returns the Reasons field if non-nil, zero value otherwise.

### GetReasonsOk

`func (o *OperatorConsumerRuntimeHealth) GetReasonsOk() (*[]string, bool)`

GetReasonsOk returns a tuple with the Reasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasons

`func (o *OperatorConsumerRuntimeHealth) SetReasons(v []string)`

SetReasons sets Reasons field to given value.


### GetRecommendations

`func (o *OperatorConsumerRuntimeHealth) GetRecommendations() []string`

GetRecommendations returns the Recommendations field if non-nil, zero value otherwise.

### GetRecommendationsOk

`func (o *OperatorConsumerRuntimeHealth) GetRecommendationsOk() (*[]string, bool)`

GetRecommendationsOk returns a tuple with the Recommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendations

`func (o *OperatorConsumerRuntimeHealth) SetRecommendations(v []string)`

SetRecommendations sets Recommendations field to given value.


### GetCapacity

`func (o *OperatorConsumerRuntimeHealth) GetCapacity() OperatorRuntimeCapacity`

GetCapacity returns the Capacity field if non-nil, zero value otherwise.

### GetCapacityOk

`func (o *OperatorConsumerRuntimeHealth) GetCapacityOk() (*OperatorRuntimeCapacity, bool)`

GetCapacityOk returns a tuple with the Capacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacity

`func (o *OperatorConsumerRuntimeHealth) SetCapacity(v OperatorRuntimeCapacity)`

SetCapacity sets Capacity field to given value.


### GetDeliveries

`func (o *OperatorConsumerRuntimeHealth) GetDeliveries() OperatorRuntimeDelivery`

GetDeliveries returns the Deliveries field if non-nil, zero value otherwise.

### GetDeliveriesOk

`func (o *OperatorConsumerRuntimeHealth) GetDeliveriesOk() (*OperatorRuntimeDelivery, bool)`

GetDeliveriesOk returns a tuple with the Deliveries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveries

`func (o *OperatorConsumerRuntimeHealth) SetDeliveries(v OperatorRuntimeDelivery)`

SetDeliveries sets Deliveries field to given value.


### GetFindings

`func (o *OperatorConsumerRuntimeHealth) GetFindings() []OperatorRuntimeHealthFinding`

GetFindings returns the Findings field if non-nil, zero value otherwise.

### GetFindingsOk

`func (o *OperatorConsumerRuntimeHealth) GetFindingsOk() (*[]OperatorRuntimeHealthFinding, bool)`

GetFindingsOk returns a tuple with the Findings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFindings

`func (o *OperatorConsumerRuntimeHealth) SetFindings(v []OperatorRuntimeHealthFinding)`

SetFindings sets Findings field to given value.


### GetEvaluatedAt

`func (o *OperatorConsumerRuntimeHealth) GetEvaluatedAt() time.Time`

GetEvaluatedAt returns the EvaluatedAt field if non-nil, zero value otherwise.

### GetEvaluatedAtOk

`func (o *OperatorConsumerRuntimeHealth) GetEvaluatedAtOk() (*time.Time, bool)`

GetEvaluatedAtOk returns a tuple with the EvaluatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluatedAt

`func (o *OperatorConsumerRuntimeHealth) SetEvaluatedAt(v time.Time)`

SetEvaluatedAt sets EvaluatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


