# Divergence

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**ControllerId** | **string** |  | 
**DivergenceType** | **string** |  | 
**Expected** | Pointer to **interface{}** |  | [optional] 
**Observed** | Pointer to **interface{}** |  | [optional] 
**Resolved** | Pointer to **bool** |  | [optional] 
**ResolvedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**Snapshot** | **string** |  | 
**Observation** | **string** |  | 
**Member** | **string** |  | 

## Methods

### NewDivergence

`func NewDivergence(id string, controllerId string, divergenceType string, createdAt time.Time, snapshot string, observation string, member string, ) *Divergence`

NewDivergence instantiates a new Divergence object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDivergenceWithDefaults

`func NewDivergenceWithDefaults() *Divergence`

NewDivergenceWithDefaults instantiates a new Divergence object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Divergence) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Divergence) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Divergence) SetId(v string)`

SetId sets Id field to given value.


### GetControllerId

`func (o *Divergence) GetControllerId() string`

GetControllerId returns the ControllerId field if non-nil, zero value otherwise.

### GetControllerIdOk

`func (o *Divergence) GetControllerIdOk() (*string, bool)`

GetControllerIdOk returns a tuple with the ControllerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerId

`func (o *Divergence) SetControllerId(v string)`

SetControllerId sets ControllerId field to given value.


### GetDivergenceType

`func (o *Divergence) GetDivergenceType() string`

GetDivergenceType returns the DivergenceType field if non-nil, zero value otherwise.

### GetDivergenceTypeOk

`func (o *Divergence) GetDivergenceTypeOk() (*string, bool)`

GetDivergenceTypeOk returns a tuple with the DivergenceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivergenceType

`func (o *Divergence) SetDivergenceType(v string)`

SetDivergenceType sets DivergenceType field to given value.


### GetExpected

`func (o *Divergence) GetExpected() interface{}`

GetExpected returns the Expected field if non-nil, zero value otherwise.

### GetExpectedOk

`func (o *Divergence) GetExpectedOk() (*interface{}, bool)`

GetExpectedOk returns a tuple with the Expected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpected

`func (o *Divergence) SetExpected(v interface{})`

SetExpected sets Expected field to given value.

### HasExpected

`func (o *Divergence) HasExpected() bool`

HasExpected returns a boolean if a field has been set.

### SetExpectedNil

`func (o *Divergence) SetExpectedNil(b bool)`

 SetExpectedNil sets the value for Expected to be an explicit nil

### UnsetExpected
`func (o *Divergence) UnsetExpected()`

UnsetExpected ensures that no value is present for Expected, not even an explicit nil
### GetObserved

`func (o *Divergence) GetObserved() interface{}`

GetObserved returns the Observed field if non-nil, zero value otherwise.

### GetObservedOk

`func (o *Divergence) GetObservedOk() (*interface{}, bool)`

GetObservedOk returns a tuple with the Observed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObserved

`func (o *Divergence) SetObserved(v interface{})`

SetObserved sets Observed field to given value.

### HasObserved

`func (o *Divergence) HasObserved() bool`

HasObserved returns a boolean if a field has been set.

### SetObservedNil

`func (o *Divergence) SetObservedNil(b bool)`

 SetObservedNil sets the value for Observed to be an explicit nil

### UnsetObserved
`func (o *Divergence) UnsetObserved()`

UnsetObserved ensures that no value is present for Observed, not even an explicit nil
### GetResolved

`func (o *Divergence) GetResolved() bool`

GetResolved returns the Resolved field if non-nil, zero value otherwise.

### GetResolvedOk

`func (o *Divergence) GetResolvedOk() (*bool, bool)`

GetResolvedOk returns a tuple with the Resolved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolved

`func (o *Divergence) SetResolved(v bool)`

SetResolved sets Resolved field to given value.

### HasResolved

`func (o *Divergence) HasResolved() bool`

HasResolved returns a boolean if a field has been set.

### GetResolvedAt

`func (o *Divergence) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *Divergence) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *Divergence) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.

### HasResolvedAt

`func (o *Divergence) HasResolvedAt() bool`

HasResolvedAt returns a boolean if a field has been set.

### SetResolvedAtNil

`func (o *Divergence) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *Divergence) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetCreatedAt

`func (o *Divergence) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Divergence) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Divergence) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetSnapshot

`func (o *Divergence) GetSnapshot() string`

GetSnapshot returns the Snapshot field if non-nil, zero value otherwise.

### GetSnapshotOk

`func (o *Divergence) GetSnapshotOk() (*string, bool)`

GetSnapshotOk returns a tuple with the Snapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshot

`func (o *Divergence) SetSnapshot(v string)`

SetSnapshot sets Snapshot field to given value.


### GetObservation

`func (o *Divergence) GetObservation() string`

GetObservation returns the Observation field if non-nil, zero value otherwise.

### GetObservationOk

`func (o *Divergence) GetObservationOk() (*string, bool)`

GetObservationOk returns a tuple with the Observation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservation

`func (o *Divergence) SetObservation(v string)`

SetObservation sets Observation field to given value.


### GetMember

`func (o *Divergence) GetMember() string`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *Divergence) GetMemberOk() (*string, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *Divergence) SetMember(v string)`

SetMember sets Member field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


