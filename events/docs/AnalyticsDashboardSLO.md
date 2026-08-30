# AnalyticsDashboardSLO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Target** | **float64** |  | 
**Current** | **float64** |  | 
**Unit** | **string** |  | 
**Status** | **string** |  | 
**Breached** | **bool** |  | 
**ObservedAt** | **time.Time** |  | 
**Fingerprint** | **string** |  | 

## Methods

### NewAnalyticsDashboardSLO

`func NewAnalyticsDashboardSLO(name string, target float64, current float64, unit string, status string, breached bool, observedAt time.Time, fingerprint string, ) *AnalyticsDashboardSLO`

NewAnalyticsDashboardSLO instantiates a new AnalyticsDashboardSLO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsDashboardSLOWithDefaults

`func NewAnalyticsDashboardSLOWithDefaults() *AnalyticsDashboardSLO`

NewAnalyticsDashboardSLOWithDefaults instantiates a new AnalyticsDashboardSLO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *AnalyticsDashboardSLO) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AnalyticsDashboardSLO) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AnalyticsDashboardSLO) SetName(v string)`

SetName sets Name field to given value.


### GetTarget

`func (o *AnalyticsDashboardSLO) GetTarget() float64`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *AnalyticsDashboardSLO) GetTargetOk() (*float64, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *AnalyticsDashboardSLO) SetTarget(v float64)`

SetTarget sets Target field to given value.


### GetCurrent

`func (o *AnalyticsDashboardSLO) GetCurrent() float64`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *AnalyticsDashboardSLO) GetCurrentOk() (*float64, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *AnalyticsDashboardSLO) SetCurrent(v float64)`

SetCurrent sets Current field to given value.


### GetUnit

`func (o *AnalyticsDashboardSLO) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *AnalyticsDashboardSLO) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *AnalyticsDashboardSLO) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetStatus

`func (o *AnalyticsDashboardSLO) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AnalyticsDashboardSLO) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AnalyticsDashboardSLO) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBreached

`func (o *AnalyticsDashboardSLO) GetBreached() bool`

GetBreached returns the Breached field if non-nil, zero value otherwise.

### GetBreachedOk

`func (o *AnalyticsDashboardSLO) GetBreachedOk() (*bool, bool)`

GetBreachedOk returns a tuple with the Breached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreached

`func (o *AnalyticsDashboardSLO) SetBreached(v bool)`

SetBreached sets Breached field to given value.


### GetObservedAt

`func (o *AnalyticsDashboardSLO) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *AnalyticsDashboardSLO) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *AnalyticsDashboardSLO) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetFingerprint

`func (o *AnalyticsDashboardSLO) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *AnalyticsDashboardSLO) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *AnalyticsDashboardSLO) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


