# FailoverSafetyDecisionTransitionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedRevision** | **int32** |  | 
**Reason** | **string** |  | 

## Methods

### NewFailoverSafetyDecisionTransitionRequest

`func NewFailoverSafetyDecisionTransitionRequest(expectedRevision int32, reason string, ) *FailoverSafetyDecisionTransitionRequest`

NewFailoverSafetyDecisionTransitionRequest instantiates a new FailoverSafetyDecisionTransitionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFailoverSafetyDecisionTransitionRequestWithDefaults

`func NewFailoverSafetyDecisionTransitionRequestWithDefaults() *FailoverSafetyDecisionTransitionRequest`

NewFailoverSafetyDecisionTransitionRequestWithDefaults instantiates a new FailoverSafetyDecisionTransitionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedRevision

`func (o *FailoverSafetyDecisionTransitionRequest) GetExpectedRevision() int32`

GetExpectedRevision returns the ExpectedRevision field if non-nil, zero value otherwise.

### GetExpectedRevisionOk

`func (o *FailoverSafetyDecisionTransitionRequest) GetExpectedRevisionOk() (*int32, bool)`

GetExpectedRevisionOk returns a tuple with the ExpectedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevision

`func (o *FailoverSafetyDecisionTransitionRequest) SetExpectedRevision(v int32)`

SetExpectedRevision sets ExpectedRevision field to given value.


### GetReason

`func (o *FailoverSafetyDecisionTransitionRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *FailoverSafetyDecisionTransitionRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *FailoverSafetyDecisionTransitionRequest) SetReason(v string)`

SetReason sets Reason field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


