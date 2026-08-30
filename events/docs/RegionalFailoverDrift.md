# RegionalFailoverDrift

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**DriftType** | **string** |  | 
**Safety** | **string** |  | 
**Message** | Pointer to **string** |  | [optional] 
**Expected** | Pointer to **interface{}** |  | [optional] 
**Observed** | Pointer to **interface{}** |  | [optional] 
**Resolved** | Pointer to **bool** |  | [optional] 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRegionalFailoverDrift

`func NewRegionalFailoverDrift(id string, driftType string, safety string, createdAt time.Time, ) *RegionalFailoverDrift`

NewRegionalFailoverDrift instantiates a new RegionalFailoverDrift object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegionalFailoverDriftWithDefaults

`func NewRegionalFailoverDriftWithDefaults() *RegionalFailoverDrift`

NewRegionalFailoverDriftWithDefaults instantiates a new RegionalFailoverDrift object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RegionalFailoverDrift) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RegionalFailoverDrift) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RegionalFailoverDrift) SetId(v string)`

SetId sets Id field to given value.


### GetDriftType

`func (o *RegionalFailoverDrift) GetDriftType() string`

GetDriftType returns the DriftType field if non-nil, zero value otherwise.

### GetDriftTypeOk

`func (o *RegionalFailoverDrift) GetDriftTypeOk() (*string, bool)`

GetDriftTypeOk returns a tuple with the DriftType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriftType

`func (o *RegionalFailoverDrift) SetDriftType(v string)`

SetDriftType sets DriftType field to given value.


### GetSafety

`func (o *RegionalFailoverDrift) GetSafety() string`

GetSafety returns the Safety field if non-nil, zero value otherwise.

### GetSafetyOk

`func (o *RegionalFailoverDrift) GetSafetyOk() (*string, bool)`

GetSafetyOk returns a tuple with the Safety field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafety

`func (o *RegionalFailoverDrift) SetSafety(v string)`

SetSafety sets Safety field to given value.


### GetMessage

`func (o *RegionalFailoverDrift) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RegionalFailoverDrift) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RegionalFailoverDrift) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RegionalFailoverDrift) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetExpected

`func (o *RegionalFailoverDrift) GetExpected() interface{}`

GetExpected returns the Expected field if non-nil, zero value otherwise.

### GetExpectedOk

`func (o *RegionalFailoverDrift) GetExpectedOk() (*interface{}, bool)`

GetExpectedOk returns a tuple with the Expected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpected

`func (o *RegionalFailoverDrift) SetExpected(v interface{})`

SetExpected sets Expected field to given value.

### HasExpected

`func (o *RegionalFailoverDrift) HasExpected() bool`

HasExpected returns a boolean if a field has been set.

### SetExpectedNil

`func (o *RegionalFailoverDrift) SetExpectedNil(b bool)`

 SetExpectedNil sets the value for Expected to be an explicit nil

### UnsetExpected
`func (o *RegionalFailoverDrift) UnsetExpected()`

UnsetExpected ensures that no value is present for Expected, not even an explicit nil
### GetObserved

`func (o *RegionalFailoverDrift) GetObserved() interface{}`

GetObserved returns the Observed field if non-nil, zero value otherwise.

### GetObservedOk

`func (o *RegionalFailoverDrift) GetObservedOk() (*interface{}, bool)`

GetObservedOk returns a tuple with the Observed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObserved

`func (o *RegionalFailoverDrift) SetObserved(v interface{})`

SetObserved sets Observed field to given value.

### HasObserved

`func (o *RegionalFailoverDrift) HasObserved() bool`

HasObserved returns a boolean if a field has been set.

### SetObservedNil

`func (o *RegionalFailoverDrift) SetObservedNil(b bool)`

 SetObservedNil sets the value for Observed to be an explicit nil

### UnsetObserved
`func (o *RegionalFailoverDrift) UnsetObserved()`

UnsetObserved ensures that no value is present for Observed, not even an explicit nil
### GetResolved

`func (o *RegionalFailoverDrift) GetResolved() bool`

GetResolved returns the Resolved field if non-nil, zero value otherwise.

### GetResolvedOk

`func (o *RegionalFailoverDrift) GetResolvedOk() (*bool, bool)`

GetResolvedOk returns a tuple with the Resolved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolved

`func (o *RegionalFailoverDrift) SetResolved(v bool)`

SetResolved sets Resolved field to given value.

### HasResolved

`func (o *RegionalFailoverDrift) HasResolved() bool`

HasResolved returns a boolean if a field has been set.

### GetResolvedAt

`func (o *RegionalFailoverDrift) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *RegionalFailoverDrift) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *RegionalFailoverDrift) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *RegionalFailoverDrift) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *RegionalFailoverDrift) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *RegionalFailoverDrift) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetCreatedAt

`func (o *RegionalFailoverDrift) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RegionalFailoverDrift) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RegionalFailoverDrift) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


