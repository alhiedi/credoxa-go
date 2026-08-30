# SaaSOperatorSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **time.Time** |  | 
**Subscriptions** | **map[string]int32** |  | 
**Reservations** | **map[string]int32** |  | 
**Outbox** | **map[string]int32** |  | 
**OutboxAttempts** | **map[string]int32** |  | 
**UsageEvents** | **int32** |  | 

## Methods

### NewSaaSOperatorSummary

`func NewSaaSOperatorSummary(generatedAt time.Time, subscriptions map[string]int32, reservations map[string]int32, outbox map[string]int32, outboxAttempts map[string]int32, usageEvents int32, ) *SaaSOperatorSummary`

NewSaaSOperatorSummary instantiates a new SaaSOperatorSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaaSOperatorSummaryWithDefaults

`func NewSaaSOperatorSummaryWithDefaults() *SaaSOperatorSummary`

NewSaaSOperatorSummaryWithDefaults instantiates a new SaaSOperatorSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *SaaSOperatorSummary) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *SaaSOperatorSummary) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *SaaSOperatorSummary) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetSubscriptions

`func (o *SaaSOperatorSummary) GetSubscriptions() map[string]int32`

GetSubscriptions returns the Subscriptions field if non-nil, zero value otherwise.

### GetSubscriptionsOk

`func (o *SaaSOperatorSummary) GetSubscriptionsOk() (*map[string]int32, bool)`

GetSubscriptionsOk returns a tuple with the Subscriptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptions

`func (o *SaaSOperatorSummary) SetSubscriptions(v map[string]int32)`

SetSubscriptions sets Subscriptions field to given value.


### GetReservations

`func (o *SaaSOperatorSummary) GetReservations() map[string]int32`

GetReservations returns the Reservations field if non-nil, zero value otherwise.

### GetReservationsOk

`func (o *SaaSOperatorSummary) GetReservationsOk() (*map[string]int32, bool)`

GetReservationsOk returns a tuple with the Reservations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservations

`func (o *SaaSOperatorSummary) SetReservations(v map[string]int32)`

SetReservations sets Reservations field to given value.


### GetOutbox

`func (o *SaaSOperatorSummary) GetOutbox() map[string]int32`

GetOutbox returns the Outbox field if non-nil, zero value otherwise.

### GetOutboxOk

`func (o *SaaSOperatorSummary) GetOutboxOk() (*map[string]int32, bool)`

GetOutboxOk returns a tuple with the Outbox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutbox

`func (o *SaaSOperatorSummary) SetOutbox(v map[string]int32)`

SetOutbox sets Outbox field to given value.


### GetOutboxAttempts

`func (o *SaaSOperatorSummary) GetOutboxAttempts() map[string]int32`

GetOutboxAttempts returns the OutboxAttempts field if non-nil, zero value otherwise.

### GetOutboxAttemptsOk

`func (o *SaaSOperatorSummary) GetOutboxAttemptsOk() (*map[string]int32, bool)`

GetOutboxAttemptsOk returns a tuple with the OutboxAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboxAttempts

`func (o *SaaSOperatorSummary) SetOutboxAttempts(v map[string]int32)`

SetOutboxAttempts sets OutboxAttempts field to given value.


### GetUsageEvents

`func (o *SaaSOperatorSummary) GetUsageEvents() int32`

GetUsageEvents returns the UsageEvents field if non-nil, zero value otherwise.

### GetUsageEventsOk

`func (o *SaaSOperatorSummary) GetUsageEventsOk() (*int32, bool)`

GetUsageEventsOk returns a tuple with the UsageEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageEvents

`func (o *SaaSOperatorSummary) SetUsageEvents(v int32)`

SetUsageEvents sets UsageEvents field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


