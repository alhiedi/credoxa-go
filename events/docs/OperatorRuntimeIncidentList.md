# OperatorRuntimeIncidentList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**DeduplicationKey** | **string** |  | 
**RuleCode** | **string** |  | 
**Scope** | [**RuntimeIncidentScopeEnum**](RuntimeIncidentScopeEnum.md) |  | 
**OrganizationId** | Pointer to **NullableString** |  | [optional] 
**ConsumerId** | Pointer to **NullableString** |  | [optional] 
**ConsumerCode** | Pointer to **string** |  | [optional] 
**Severity** | [**RuntimeIncidentSeverityEnum**](RuntimeIncidentSeverityEnum.md) |  | 
**Status** | Pointer to [**RuntimeIncidentStatusEnum**](RuntimeIncidentStatusEnum.md) |  | [optional] 
**Active** | **bool** |  | [readonly] 
**Signal** | **string** |  | 
**Threshold** | **float64** |  | 
**OccurrenceCount** | Pointer to **int64** |  | [optional] 
**ReopenCount** | Pointer to **int64** |  | [optional] 
**FirstDetectedAt** | **time.Time** |  | 
**LastDetectedAt** | **time.Time** |  | 
**LastObservedAt** | **time.Time** |  | 
**AcknowledgedAt** | Pointer to **NullableTime** |  | [optional] 
**AcknowledgedBy** | Pointer to **string** |  | [optional] 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**ResolvedBy** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **int64** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewOperatorRuntimeIncidentList

`func NewOperatorRuntimeIncidentList(id string, deduplicationKey string, ruleCode string, scope RuntimeIncidentScopeEnum, severity RuntimeIncidentSeverityEnum, active bool, signal string, threshold float64, firstDetectedAt time.Time, lastDetectedAt time.Time, lastObservedAt time.Time, createdAt time.Time, updatedAt time.Time, ) *OperatorRuntimeIncidentList`

NewOperatorRuntimeIncidentList instantiates a new OperatorRuntimeIncidentList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentListWithDefaults

`func NewOperatorRuntimeIncidentListWithDefaults() *OperatorRuntimeIncidentList`

NewOperatorRuntimeIncidentListWithDefaults instantiates a new OperatorRuntimeIncidentList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorRuntimeIncidentList) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorRuntimeIncidentList) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorRuntimeIncidentList) SetId(v string)`

SetId sets Id field to given value.


### GetDeduplicationKey

`func (o *OperatorRuntimeIncidentList) GetDeduplicationKey() string`

GetDeduplicationKey returns the DeduplicationKey field if non-nil, zero value otherwise.

### GetDeduplicationKeyOk

`func (o *OperatorRuntimeIncidentList) GetDeduplicationKeyOk() (*string, bool)`

GetDeduplicationKeyOk returns a tuple with the DeduplicationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeduplicationKey

`func (o *OperatorRuntimeIncidentList) SetDeduplicationKey(v string)`

SetDeduplicationKey sets DeduplicationKey field to given value.


### GetRuleCode

`func (o *OperatorRuntimeIncidentList) GetRuleCode() string`

GetRuleCode returns the RuleCode field if non-nil, zero value otherwise.

### GetRuleCodeOk

`func (o *OperatorRuntimeIncidentList) GetRuleCodeOk() (*string, bool)`

GetRuleCodeOk returns a tuple with the RuleCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleCode

`func (o *OperatorRuntimeIncidentList) SetRuleCode(v string)`

SetRuleCode sets RuleCode field to given value.


### GetScope

`func (o *OperatorRuntimeIncidentList) GetScope() RuntimeIncidentScopeEnum`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *OperatorRuntimeIncidentList) GetScopeOk() (*RuntimeIncidentScopeEnum, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *OperatorRuntimeIncidentList) SetScope(v RuntimeIncidentScopeEnum)`

SetScope sets Scope field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeIncidentList) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeIncidentList) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeIncidentList) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *OperatorRuntimeIncidentList) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *OperatorRuntimeIncidentList) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeIncidentList) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerId

`func (o *OperatorRuntimeIncidentList) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorRuntimeIncidentList) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorRuntimeIncidentList) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *OperatorRuntimeIncidentList) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *OperatorRuntimeIncidentList) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *OperatorRuntimeIncidentList) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorRuntimeIncidentList) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeIncidentList) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeIncidentList) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.

### HasConsumerCode

`func (o *OperatorRuntimeIncidentList) HasConsumerCode() bool`

HasConsumerCode returns a boolean if a field has been set.

### GetSeverity

`func (o *OperatorRuntimeIncidentList) GetSeverity() RuntimeIncidentSeverityEnum`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeIncidentList) GetSeverityOk() (*RuntimeIncidentSeverityEnum, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeIncidentList) SetSeverity(v RuntimeIncidentSeverityEnum)`

SetSeverity sets Severity field to given value.


### GetStatus

`func (o *OperatorRuntimeIncidentList) GetStatus() RuntimeIncidentStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeIncidentList) GetStatusOk() (*RuntimeIncidentStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeIncidentList) SetStatus(v RuntimeIncidentStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperatorRuntimeIncidentList) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetActive

`func (o *OperatorRuntimeIncidentList) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *OperatorRuntimeIncidentList) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *OperatorRuntimeIncidentList) SetActive(v bool)`

SetActive sets Active field to given value.


### GetSignal

`func (o *OperatorRuntimeIncidentList) GetSignal() string`

GetSignal returns the Signal field if non-nil, zero value otherwise.

### GetSignalOk

`func (o *OperatorRuntimeIncidentList) GetSignalOk() (*string, bool)`

GetSignalOk returns a tuple with the Signal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignal

`func (o *OperatorRuntimeIncidentList) SetSignal(v string)`

SetSignal sets Signal field to given value.


### GetThreshold

`func (o *OperatorRuntimeIncidentList) GetThreshold() float64`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *OperatorRuntimeIncidentList) GetThresholdOk() (*float64, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *OperatorRuntimeIncidentList) SetThreshold(v float64)`

SetThreshold sets Threshold field to given value.


### GetOccurrenceCount

`func (o *OperatorRuntimeIncidentList) GetOccurrenceCount() int64`

GetOccurrenceCount returns the OccurrenceCount field if non-nil, zero value otherwise.

### GetOccurrenceCountOk

`func (o *OperatorRuntimeIncidentList) GetOccurrenceCountOk() (*int64, bool)`

GetOccurrenceCountOk returns a tuple with the OccurrenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceCount

`func (o *OperatorRuntimeIncidentList) SetOccurrenceCount(v int64)`

SetOccurrenceCount sets OccurrenceCount field to given value.

### HasOccurrenceCount

`func (o *OperatorRuntimeIncidentList) HasOccurrenceCount() bool`

HasOccurrenceCount returns a boolean if a field has been set.

### GetReopenCount

`func (o *OperatorRuntimeIncidentList) GetReopenCount() int64`

GetReopenCount returns the ReopenCount field if non-nil, zero value otherwise.

### GetReopenCountOk

`func (o *OperatorRuntimeIncidentList) GetReopenCountOk() (*int64, bool)`

GetReopenCountOk returns a tuple with the ReopenCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReopenCount

`func (o *OperatorRuntimeIncidentList) SetReopenCount(v int64)`

SetReopenCount sets ReopenCount field to given value.

### HasReopenCount

`func (o *OperatorRuntimeIncidentList) HasReopenCount() bool`

HasReopenCount returns a boolean if a field has been set.

### GetFirstDetectedAt

`func (o *OperatorRuntimeIncidentList) GetFirstDetectedAt() time.Time`

GetFirstDetectedAt returns the FirstDetectedAt field if non-nil, zero value otherwise.

### GetFirstDetectedAtOk

`func (o *OperatorRuntimeIncidentList) GetFirstDetectedAtOk() (*time.Time, bool)`

GetFirstDetectedAtOk returns a tuple with the FirstDetectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstDetectedAt

`func (o *OperatorRuntimeIncidentList) SetFirstDetectedAt(v time.Time)`

SetFirstDetectedAt sets FirstDetectedAt field to given value.


### GetLastDetectedAt

`func (o *OperatorRuntimeIncidentList) GetLastDetectedAt() time.Time`

GetLastDetectedAt returns the LastDetectedAt field if non-nil, zero value otherwise.

### GetLastDetectedAtOk

`func (o *OperatorRuntimeIncidentList) GetLastDetectedAtOk() (*time.Time, bool)`

GetLastDetectedAtOk returns a tuple with the LastDetectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDetectedAt

`func (o *OperatorRuntimeIncidentList) SetLastDetectedAt(v time.Time)`

SetLastDetectedAt sets LastDetectedAt field to given value.


### GetLastObservedAt

`func (o *OperatorRuntimeIncidentList) GetLastObservedAt() time.Time`

GetLastObservedAt returns the LastObservedAt field if non-nil, zero value otherwise.

### GetLastObservedAtOk

`func (o *OperatorRuntimeIncidentList) GetLastObservedAtOk() (*time.Time, bool)`

GetLastObservedAtOk returns a tuple with the LastObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastObservedAt

`func (o *OperatorRuntimeIncidentList) SetLastObservedAt(v time.Time)`

SetLastObservedAt sets LastObservedAt field to given value.


### GetAcknowledgedAt

`func (o *OperatorRuntimeIncidentList) GetAcknowledgedAt() time.Time`

GetAcknowledgedAt returns the AcknowledgedAt field if non-nil, zero value otherwise.

### GetAcknowledgedAtOk

`func (o *OperatorRuntimeIncidentList) GetAcknowledgedAtOk() (*time.Time, bool)`

GetAcknowledgedAtOk returns a tuple with the AcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedAt

`func (o *OperatorRuntimeIncidentList) SetAcknowledgedAt(v time.Time)`

SetAcknowledgedAt sets AcknowledgedAt field to given value.

### HasAcknowledgedAt

`func (o *OperatorRuntimeIncidentList) HasAcknowledgedAt() bool`

HasAcknowledgedAt returns a boolean if a field has been set.

### SetAcknowledgedAtNil

`func (o *OperatorRuntimeIncidentList) SetAcknowledgedAtNil(b bool)`

 SetAcknowledgedAtNil sets the value for AcknowledgedAt to be an explicit nil

### UnsetAcknowledgedAt
`func (o *OperatorRuntimeIncidentList) UnsetAcknowledgedAt()`

UnsetAcknowledgedAt ensures that no value is present for AcknowledgedAt, not even an explicit nil
### GetAcknowledgedBy

`func (o *OperatorRuntimeIncidentList) GetAcknowledgedBy() string`

GetAcknowledgedBy returns the AcknowledgedBy field if non-nil, zero value otherwise.

### GetAcknowledgedByOk

`func (o *OperatorRuntimeIncidentList) GetAcknowledgedByOk() (*string, bool)`

GetAcknowledgedByOk returns a tuple with the AcknowledgedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedBy

`func (o *OperatorRuntimeIncidentList) SetAcknowledgedBy(v string)`

SetAcknowledgedBy sets AcknowledgedBy field to given value.

### HasAcknowledgedBy

`func (o *OperatorRuntimeIncidentList) HasAcknowledgedBy() bool`

HasAcknowledgedBy returns a boolean if a field has been set.

### GetResolvedAt

`func (o *OperatorRuntimeIncidentList) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *OperatorRuntimeIncidentList) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *OperatorRuntimeIncidentList) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *OperatorRuntimeIncidentList) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *OperatorRuntimeIncidentList) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *OperatorRuntimeIncidentList) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *OperatorRuntimeIncidentList) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *OperatorRuntimeIncidentList) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *OperatorRuntimeIncidentList) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.

### HasResolvedBy

`func (o *OperatorRuntimeIncidentList) HasResolvedBy() bool`

HasResolvedBy returns a boolean if a field has been set.

### GetVersion

`func (o *OperatorRuntimeIncidentList) GetVersion() int64`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *OperatorRuntimeIncidentList) GetVersionOk() (*int64, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *OperatorRuntimeIncidentList) SetVersion(v int64)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *OperatorRuntimeIncidentList) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OperatorRuntimeIncidentList) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorRuntimeIncidentList) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorRuntimeIncidentList) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorRuntimeIncidentList) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorRuntimeIncidentList) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorRuntimeIncidentList) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


