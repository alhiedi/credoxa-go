# AnalyticsDashboardMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Section** | **string** |  | 
**OrganizationId** | **NullableString** |  | 
**ActorId** | **string** |  | 
**RequestId** | **string** |  | 
**CorrelationId** | **string** |  | 
**Success** | **bool** |  | 
**ObservedAt** | **time.Time** |  | 
**EvidenceFingerprint** | **string** |  | 
**DashboardFingerprint** | Pointer to **string** |  | [optional] 
**GeneratedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewAnalyticsDashboardMeta

`func NewAnalyticsDashboardMeta(section string, organizationId NullableString, actorId string, requestId string, correlationId string, success bool, observedAt time.Time, evidenceFingerprint string, ) *AnalyticsDashboardMeta`

NewAnalyticsDashboardMeta instantiates a new AnalyticsDashboardMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDashboardMetaWithDefaults

`func NewAnalyticsDashboardMetaWithDefaults() *AnalyticsDashboardMeta`

NewAnalyticsDashboardMetaWithDefaults instantiates a new AnalyticsDashboardMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSection

`func (o *AnalyticsDashboardMeta) GetSection() string`

GetSection returns the Section field if non-nil, zero value otherwise.

### GetSectionOk

`func (o *AnalyticsDashboardMeta) GetSectionOk() (*string, bool)`

GetSectionOk returns a tuple with the Section field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSection

`func (o *AnalyticsDashboardMeta) SetSection(v string)`

SetSection sets Section field to given value.


### GetOrganizationId

`func (o *AnalyticsDashboardMeta) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AnalyticsDashboardMeta) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AnalyticsDashboardMeta) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *AnalyticsDashboardMeta) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *AnalyticsDashboardMeta) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetActorId

`func (o *AnalyticsDashboardMeta) GetActorId() string`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *AnalyticsDashboardMeta) GetActorIdOk() (*string, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *AnalyticsDashboardMeta) SetActorId(v string)`

SetActorId sets ActorId field to given value.


### GetRequestId

`func (o *AnalyticsDashboardMeta) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AnalyticsDashboardMeta) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AnalyticsDashboardMeta) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetCorrelationId

`func (o *AnalyticsDashboardMeta) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AnalyticsDashboardMeta) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AnalyticsDashboardMeta) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetSuccess

`func (o *AnalyticsDashboardMeta) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AnalyticsDashboardMeta) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AnalyticsDashboardMeta) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetObservedAt

`func (o *AnalyticsDashboardMeta) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *AnalyticsDashboardMeta) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *AnalyticsDashboardMeta) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetEvidenceFingerprint

`func (o *AnalyticsDashboardMeta) GetEvidenceFingerprint() string`

GetEvidenceFingerprint returns the EvidenceFingerprint field if non-nil, zero value otherwise.

### GetEvidenceFingerprintOk

`func (o *AnalyticsDashboardMeta) GetEvidenceFingerprintOk() (*string, bool)`

GetEvidenceFingerprintOk returns a tuple with the EvidenceFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceFingerprint

`func (o *AnalyticsDashboardMeta) SetEvidenceFingerprint(v string)`

SetEvidenceFingerprint sets EvidenceFingerprint field to given value.


### GetDashboardFingerprint

`func (o *AnalyticsDashboardMeta) GetDashboardFingerprint() string`

GetDashboardFingerprint returns the DashboardFingerprint field if non-nil, zero value otherwise.

### GetDashboardFingerprintOk

`func (o *AnalyticsDashboardMeta) GetDashboardFingerprintOk() (*string, bool)`

GetDashboardFingerprintOk returns a tuple with the DashboardFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDashboardFingerprint

`func (o *AnalyticsDashboardMeta) SetDashboardFingerprint(v string)`

SetDashboardFingerprint sets DashboardFingerprint field to given value.

### HasDashboardFingerprint

`func (o *AnalyticsDashboardMeta) HasDashboardFingerprint() bool`

HasDashboardFingerprint returns a boolean if a field has been set.

### GetGeneratedAt

`func (o *AnalyticsDashboardMeta) GetGeneratedAt() time.Time`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *AnalyticsDashboardMeta) GetGeneratedAtOk() (*time.Time, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *AnalyticsDashboardMeta) SetGeneratedAt(v time.Time)`

SetGeneratedAt sets GeneratedAt field to given value.

### HasGeneratedAt

`func (o *AnalyticsDashboardMeta) HasGeneratedAt() bool`

HasGeneratedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


