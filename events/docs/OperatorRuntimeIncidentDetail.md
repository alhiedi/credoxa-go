# OperatorRuntimeIncidentDetail

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
**Comparator** | Pointer to **string** |  | [optional] 
**Aggregation** | Pointer to **string** |  | [optional] 
**Threshold** | **float64** |  | 
**FirstObservedValue** | **float64** |  | 
**LastObservedValue** | **float64** |  | 
**LastAggregatedValue** | **float64** |  | 
**Title** | **string** |  | 
**Description** | **string** |  | 
**Recommendation** | Pointer to **string** |  | [optional] 
**OccurrenceCount** | Pointer to **int64** |  | [optional] 
**ReopenCount** | Pointer to **int64** |  | [optional] 
**FirstDetectedAt** | **time.Time** |  | 
**LastDetectedAt** | **time.Time** |  | 
**LastObservedAt** | **time.Time** |  | 
**AcknowledgedAt** | Pointer to **NullableTime** |  | [optional] 
**AcknowledgedBy** | Pointer to **string** |  | [optional] 
**AcknowledgementNote** | Pointer to **string** |  | [optional] 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**ResolvedBy** | Pointer to **string** |  | [optional] 
**ResolutionNote** | Pointer to **string** |  | [optional] 
**Context** | Pointer to **interface{}** |  | [optional] 
**Version** | Pointer to **int64** |  | [optional] 
**OccurrenceSummary** | [**OperatorRuntimeIncidentOccurrenceSummary**](OperatorRuntimeIncidentOccurrenceSummary.md) |  | [readonly] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewOperatorRuntimeIncidentDetail

`func NewOperatorRuntimeIncidentDetail(id string, deduplicationKey string, ruleCode string, scope RuntimeIncidentScopeEnum, severity RuntimeIncidentSeverityEnum, active bool, signal string, threshold float64, firstObservedValue float64, lastObservedValue float64, lastAggregatedValue float64, title string, description string, firstDetectedAt time.Time, lastDetectedAt time.Time, lastObservedAt time.Time, occurrenceSummary OperatorRuntimeIncidentOccurrenceSummary, createdAt time.Time, updatedAt time.Time, ) *OperatorRuntimeIncidentDetail`

NewOperatorRuntimeIncidentDetail instantiates a new OperatorRuntimeIncidentDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeIncidentDetailWithDefaults

`func NewOperatorRuntimeIncidentDetailWithDefaults() *OperatorRuntimeIncidentDetail`

NewOperatorRuntimeIncidentDetailWithDefaults instantiates a new OperatorRuntimeIncidentDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperatorRuntimeIncidentDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperatorRuntimeIncidentDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperatorRuntimeIncidentDetail) SetId(v string)`

SetId sets Id field to given value.


### GetDeduplicationKey

`func (o *OperatorRuntimeIncidentDetail) GetDeduplicationKey() string`

GetDeduplicationKey returns the DeduplicationKey field if non-nil, zero value otherwise.

### GetDeduplicationKeyOk

`func (o *OperatorRuntimeIncidentDetail) GetDeduplicationKeyOk() (*string, bool)`

GetDeduplicationKeyOk returns a tuple with the DeduplicationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeduplicationKey

`func (o *OperatorRuntimeIncidentDetail) SetDeduplicationKey(v string)`

SetDeduplicationKey sets DeduplicationKey field to given value.


### GetRuleCode

`func (o *OperatorRuntimeIncidentDetail) GetRuleCode() string`

GetRuleCode returns the RuleCode field if non-nil, zero value otherwise.

### GetRuleCodeOk

`func (o *OperatorRuntimeIncidentDetail) GetRuleCodeOk() (*string, bool)`

GetRuleCodeOk returns a tuple with the RuleCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleCode

`func (o *OperatorRuntimeIncidentDetail) SetRuleCode(v string)`

SetRuleCode sets RuleCode field to given value.


### GetScope

`func (o *OperatorRuntimeIncidentDetail) GetScope() RuntimeIncidentScopeEnum`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *OperatorRuntimeIncidentDetail) GetScopeOk() (*RuntimeIncidentScopeEnum, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *OperatorRuntimeIncidentDetail) SetScope(v RuntimeIncidentScopeEnum)`

SetScope sets Scope field to given value.


### GetOrganizationId

`func (o *OperatorRuntimeIncidentDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeIncidentDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeIncidentDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *OperatorRuntimeIncidentDetail) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *OperatorRuntimeIncidentDetail) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeIncidentDetail) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetConsumerId

`func (o *OperatorRuntimeIncidentDetail) GetConsumerId() string`

GetConsumerId returns the ConsumerId field if non-nil, zero value otherwise.

### GetConsumerIdOk

`func (o *OperatorRuntimeIncidentDetail) GetConsumerIdOk() (*string, bool)`

GetConsumerIdOk returns a tuple with the ConsumerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerId

`func (o *OperatorRuntimeIncidentDetail) SetConsumerId(v string)`

SetConsumerId sets ConsumerId field to given value.

### HasConsumerId

`func (o *OperatorRuntimeIncidentDetail) HasConsumerId() bool`

HasConsumerId returns a boolean if a field has been set.

### SetConsumerIdNil

`func (o *OperatorRuntimeIncidentDetail) SetConsumerIdNil(b bool)`

 SetConsumerIdNil sets the value for ConsumerId to be an explicit nil

### UnsetConsumerId
`func (o *OperatorRuntimeIncidentDetail) UnsetConsumerId()`

UnsetConsumerId ensures that no value is present for ConsumerId, not even an explicit nil
### GetConsumerCode

`func (o *OperatorRuntimeIncidentDetail) GetConsumerCode() string`

GetConsumerCode returns the ConsumerCode field if non-nil, zero value otherwise.

### GetConsumerCodeOk

`func (o *OperatorRuntimeIncidentDetail) GetConsumerCodeOk() (*string, bool)`

GetConsumerCodeOk returns a tuple with the ConsumerCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumerCode

`func (o *OperatorRuntimeIncidentDetail) SetConsumerCode(v string)`

SetConsumerCode sets ConsumerCode field to given value.

### HasConsumerCode

`func (o *OperatorRuntimeIncidentDetail) HasConsumerCode() bool`

HasConsumerCode returns a boolean if a field has been set.

### GetSeverity

`func (o *OperatorRuntimeIncidentDetail) GetSeverity() RuntimeIncidentSeverityEnum`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *OperatorRuntimeIncidentDetail) GetSeverityOk() (*RuntimeIncidentSeverityEnum, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *OperatorRuntimeIncidentDetail) SetSeverity(v RuntimeIncidentSeverityEnum)`

SetSeverity sets Severity field to given value.


### GetStatus

`func (o *OperatorRuntimeIncidentDetail) GetStatus() RuntimeIncidentStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperatorRuntimeIncidentDetail) GetStatusOk() (*RuntimeIncidentStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperatorRuntimeIncidentDetail) SetStatus(v RuntimeIncidentStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperatorRuntimeIncidentDetail) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetActive

`func (o *OperatorRuntimeIncidentDetail) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *OperatorRuntimeIncidentDetail) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *OperatorRuntimeIncidentDetail) SetActive(v bool)`

SetActive sets Active field to given value.


### GetSignal

`func (o *OperatorRuntimeIncidentDetail) GetSignal() string`

GetSignal returns the Signal field if non-nil, zero value otherwise.

### GetSignalOk

`func (o *OperatorRuntimeIncidentDetail) GetSignalOk() (*string, bool)`

GetSignalOk returns a tuple with the Signal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignal

`func (o *OperatorRuntimeIncidentDetail) SetSignal(v string)`

SetSignal sets Signal field to given value.


### GetComparator

`func (o *OperatorRuntimeIncidentDetail) GetComparator() string`

GetComparator returns the Comparator field if non-nil, zero value otherwise.

### GetComparatorOk

`func (o *OperatorRuntimeIncidentDetail) GetComparatorOk() (*string, bool)`

GetComparatorOk returns a tuple with the Comparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparator

`func (o *OperatorRuntimeIncidentDetail) SetComparator(v string)`

SetComparator sets Comparator field to given value.

### HasComparator

`func (o *OperatorRuntimeIncidentDetail) HasComparator() bool`

HasComparator returns a boolean if a field has been set.

### GetAggregation

`func (o *OperatorRuntimeIncidentDetail) GetAggregation() string`

GetAggregation returns the Aggregation field if non-nil, zero value otherwise.

### GetAggregationOk

`func (o *OperatorRuntimeIncidentDetail) GetAggregationOk() (*string, bool)`

GetAggregationOk returns a tuple with the Aggregation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregation

`func (o *OperatorRuntimeIncidentDetail) SetAggregation(v string)`

SetAggregation sets Aggregation field to given value.

### HasAggregation

`func (o *OperatorRuntimeIncidentDetail) HasAggregation() bool`

HasAggregation returns a boolean if a field has been set.

### GetThreshold

`func (o *OperatorRuntimeIncidentDetail) GetThreshold() float64`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *OperatorRuntimeIncidentDetail) GetThresholdOk() (*float64, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *OperatorRuntimeIncidentDetail) SetThreshold(v float64)`

SetThreshold sets Threshold field to given value.


### GetFirstObservedValue

`func (o *OperatorRuntimeIncidentDetail) GetFirstObservedValue() float64`

GetFirstObservedValue returns the FirstObservedValue field if non-nil, zero value otherwise.

### GetFirstObservedValueOk

`func (o *OperatorRuntimeIncidentDetail) GetFirstObservedValueOk() (*float64, bool)`

GetFirstObservedValueOk returns a tuple with the FirstObservedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstObservedValue

`func (o *OperatorRuntimeIncidentDetail) SetFirstObservedValue(v float64)`

SetFirstObservedValue sets FirstObservedValue field to given value.


### GetLastObservedValue

`func (o *OperatorRuntimeIncidentDetail) GetLastObservedValue() float64`

GetLastObservedValue returns the LastObservedValue field if non-nil, zero value otherwise.

### GetLastObservedValueOk

`func (o *OperatorRuntimeIncidentDetail) GetLastObservedValueOk() (*float64, bool)`

GetLastObservedValueOk returns a tuple with the LastObservedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastObservedValue

`func (o *OperatorRuntimeIncidentDetail) SetLastObservedValue(v float64)`

SetLastObservedValue sets LastObservedValue field to given value.


### GetLastAggregatedValue

`func (o *OperatorRuntimeIncidentDetail) GetLastAggregatedValue() float64`

GetLastAggregatedValue returns the LastAggregatedValue field if non-nil, zero value otherwise.

### GetLastAggregatedValueOk

`func (o *OperatorRuntimeIncidentDetail) GetLastAggregatedValueOk() (*float64, bool)`

GetLastAggregatedValueOk returns a tuple with the LastAggregatedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAggregatedValue

`func (o *OperatorRuntimeIncidentDetail) SetLastAggregatedValue(v float64)`

SetLastAggregatedValue sets LastAggregatedValue field to given value.


### GetTitle

`func (o *OperatorRuntimeIncidentDetail) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OperatorRuntimeIncidentDetail) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OperatorRuntimeIncidentDetail) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *OperatorRuntimeIncidentDetail) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OperatorRuntimeIncidentDetail) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OperatorRuntimeIncidentDetail) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetRecommendation

`func (o *OperatorRuntimeIncidentDetail) GetRecommendation() string`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *OperatorRuntimeIncidentDetail) GetRecommendationOk() (*string, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *OperatorRuntimeIncidentDetail) SetRecommendation(v string)`

SetRecommendation sets Recommendation field to given value.

### HasRecommendation

`func (o *OperatorRuntimeIncidentDetail) HasRecommendation() bool`

HasRecommendation returns a boolean if a field has been set.

### GetOccurrenceCount

`func (o *OperatorRuntimeIncidentDetail) GetOccurrenceCount() int64`

GetOccurrenceCount returns the OccurrenceCount field if non-nil, zero value otherwise.

### GetOccurrenceCountOk

`func (o *OperatorRuntimeIncidentDetail) GetOccurrenceCountOk() (*int64, bool)`

GetOccurrenceCountOk returns a tuple with the OccurrenceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceCount

`func (o *OperatorRuntimeIncidentDetail) SetOccurrenceCount(v int64)`

SetOccurrenceCount sets OccurrenceCount field to given value.

### HasOccurrenceCount

`func (o *OperatorRuntimeIncidentDetail) HasOccurrenceCount() bool`

HasOccurrenceCount returns a boolean if a field has been set.

### GetReopenCount

`func (o *OperatorRuntimeIncidentDetail) GetReopenCount() int64`

GetReopenCount returns the ReopenCount field if non-nil, zero value otherwise.

### GetReopenCountOk

`func (o *OperatorRuntimeIncidentDetail) GetReopenCountOk() (*int64, bool)`

GetReopenCountOk returns a tuple with the ReopenCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReopenCount

`func (o *OperatorRuntimeIncidentDetail) SetReopenCount(v int64)`

SetReopenCount sets ReopenCount field to given value.

### HasReopenCount

`func (o *OperatorRuntimeIncidentDetail) HasReopenCount() bool`

HasReopenCount returns a boolean if a field has been set.

### GetFirstDetectedAt

`func (o *OperatorRuntimeIncidentDetail) GetFirstDetectedAt() time.Time`

GetFirstDetectedAt returns the FirstDetectedAt field if non-nil, zero value otherwise.

### GetFirstDetectedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetFirstDetectedAtOk() (*time.Time, bool)`

GetFirstDetectedAtOk returns a tuple with the FirstDetectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstDetectedAt

`func (o *OperatorRuntimeIncidentDetail) SetFirstDetectedAt(v time.Time)`

SetFirstDetectedAt sets FirstDetectedAt field to given value.


### GetLastDetectedAt

`func (o *OperatorRuntimeIncidentDetail) GetLastDetectedAt() time.Time`

GetLastDetectedAt returns the LastDetectedAt field if non-nil, zero value otherwise.

### GetLastDetectedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetLastDetectedAtOk() (*time.Time, bool)`

GetLastDetectedAtOk returns a tuple with the LastDetectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDetectedAt

`func (o *OperatorRuntimeIncidentDetail) SetLastDetectedAt(v time.Time)`

SetLastDetectedAt sets LastDetectedAt field to given value.


### GetLastObservedAt

`func (o *OperatorRuntimeIncidentDetail) GetLastObservedAt() time.Time`

GetLastObservedAt returns the LastObservedAt field if non-nil, zero value otherwise.

### GetLastObservedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetLastObservedAtOk() (*time.Time, bool)`

GetLastObservedAtOk returns a tuple with the LastObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastObservedAt

`func (o *OperatorRuntimeIncidentDetail) SetLastObservedAt(v time.Time)`

SetLastObservedAt sets LastObservedAt field to given value.


### GetAcknowledgedAt

`func (o *OperatorRuntimeIncidentDetail) GetAcknowledgedAt() time.Time`

GetAcknowledgedAt returns the AcknowledgedAt field if non-nil, zero value otherwise.

### GetAcknowledgedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetAcknowledgedAtOk() (*time.Time, bool)`

GetAcknowledgedAtOk returns a tuple with the AcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedAt

`func (o *OperatorRuntimeIncidentDetail) SetAcknowledgedAt(v time.Time)`

SetAcknowledgedAt sets AcknowledgedAt field to given value.

### HasAcknowledgedAt

`func (o *OperatorRuntimeIncidentDetail) HasAcknowledgedAt() bool`

HasAcknowledgedAt returns a boolean if a field has been set.

### SetAcknowledgedAtNil

`func (o *OperatorRuntimeIncidentDetail) SetAcknowledgedAtNil(b bool)`

 SetAcknowledgedAtNil sets the value for AcknowledgedAt to be an explicit nil

### UnsetAcknowledgedAt
`func (o *OperatorRuntimeIncidentDetail) UnsetAcknowledgedAt()`

UnsetAcknowledgedAt ensures that no value is present for AcknowledgedAt, not even an explicit nil
### GetAcknowledgedBy

`func (o *OperatorRuntimeIncidentDetail) GetAcknowledgedBy() string`

GetAcknowledgedBy returns the AcknowledgedBy field if non-nil, zero value otherwise.

### GetAcknowledgedByOk

`func (o *OperatorRuntimeIncidentDetail) GetAcknowledgedByOk() (*string, bool)`

GetAcknowledgedByOk returns a tuple with the AcknowledgedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgedBy

`func (o *OperatorRuntimeIncidentDetail) SetAcknowledgedBy(v string)`

SetAcknowledgedBy sets AcknowledgedBy field to given value.

### HasAcknowledgedBy

`func (o *OperatorRuntimeIncidentDetail) HasAcknowledgedBy() bool`

HasAcknowledgedBy returns a boolean if a field has been set.

### GetAcknowledgementNote

`func (o *OperatorRuntimeIncidentDetail) GetAcknowledgementNote() string`

GetAcknowledgementNote returns the AcknowledgementNote field if non-nil, zero value otherwise.

### GetAcknowledgementNoteOk

`func (o *OperatorRuntimeIncidentDetail) GetAcknowledgementNoteOk() (*string, bool)`

GetAcknowledgementNoteOk returns a tuple with the AcknowledgementNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcknowledgementNote

`func (o *OperatorRuntimeIncidentDetail) SetAcknowledgementNote(v string)`

SetAcknowledgementNote sets AcknowledgementNote field to given value.

### HasAcknowledgementNote

`func (o *OperatorRuntimeIncidentDetail) HasAcknowledgementNote() bool`

HasAcknowledgementNote returns a boolean if a field has been set.

### GetResolvedAt

`func (o *OperatorRuntimeIncidentDetail) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *OperatorRuntimeIncidentDetail) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *OperatorRuntimeIncidentDetail) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *OperatorRuntimeIncidentDetail) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *OperatorRuntimeIncidentDetail) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *OperatorRuntimeIncidentDetail) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *OperatorRuntimeIncidentDetail) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *OperatorRuntimeIncidentDetail) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.

### HasResolvedBy

`func (o *OperatorRuntimeIncidentDetail) HasResolvedBy() bool`

HasResolvedBy returns a boolean if a field has been set.

### GetResolutionNote

`func (o *OperatorRuntimeIncidentDetail) GetResolutionNote() string`

GetResolutionNote returns the ResolutionNote field if non-nil, zero value otherwise.

### GetResolutionNoteOk

`func (o *OperatorRuntimeIncidentDetail) GetResolutionNoteOk() (*string, bool)`

GetResolutionNoteOk returns a tuple with the ResolutionNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolutionNote

`func (o *OperatorRuntimeIncidentDetail) SetResolutionNote(v string)`

SetResolutionNote sets ResolutionNote field to given value.

### HasResolutionNote

`func (o *OperatorRuntimeIncidentDetail) HasResolutionNote() bool`

HasResolutionNote returns a boolean if a field has been set.

### GetContext

`func (o *OperatorRuntimeIncidentDetail) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *OperatorRuntimeIncidentDetail) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *OperatorRuntimeIncidentDetail) SetContext(v interface{})`

SetContext sets Context field to given value.

### HasContext

`func (o *OperatorRuntimeIncidentDetail) HasContext() bool`

HasContext returns a boolean if a field has been set.

### SetContextNil

`func (o *OperatorRuntimeIncidentDetail) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *OperatorRuntimeIncidentDetail) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetVersion

`func (o *OperatorRuntimeIncidentDetail) GetVersion() int64`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *OperatorRuntimeIncidentDetail) GetVersionOk() (*int64, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *OperatorRuntimeIncidentDetail) SetVersion(v int64)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *OperatorRuntimeIncidentDetail) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetOccurrenceSummary

`func (o *OperatorRuntimeIncidentDetail) GetOccurrenceSummary() OperatorRuntimeIncidentOccurrenceSummary`

GetOccurrenceSummary returns the OccurrenceSummary field if non-nil, zero value otherwise.

### GetOccurrenceSummaryOk

`func (o *OperatorRuntimeIncidentDetail) GetOccurrenceSummaryOk() (*OperatorRuntimeIncidentOccurrenceSummary, bool)`

GetOccurrenceSummaryOk returns a tuple with the OccurrenceSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurrenceSummary

`func (o *OperatorRuntimeIncidentDetail) SetOccurrenceSummary(v OperatorRuntimeIncidentOccurrenceSummary)`

SetOccurrenceSummary sets OccurrenceSummary field to given value.


### GetCreatedAt

`func (o *OperatorRuntimeIncidentDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperatorRuntimeIncidentDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OperatorRuntimeIncidentDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperatorRuntimeIncidentDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperatorRuntimeIncidentDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


