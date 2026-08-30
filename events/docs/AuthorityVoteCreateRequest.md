# AuthorityVoteCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControllerId** | **string** |  | 
**Decision** | [**DecisionEnum**](DecisionEnum.md) |  | 
**Reason** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewAuthorityVoteCreateRequest

`func NewAuthorityVoteCreateRequest(controllerId string, decision DecisionEnum, ) *AuthorityVoteCreateRequest`

NewAuthorityVoteCreateRequest instantiates a new AuthorityVoteCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorityVoteCreateRequestWithDefaults

`func NewAuthorityVoteCreateRequestWithDefaults() *AuthorityVoteCreateRequest`

NewAuthorityVoteCreateRequestWithDefaults instantiates a new AuthorityVoteCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControllerId

`func (o *AuthorityVoteCreateRequest) GetControllerId() string`

GetControllerId returns the ControllerId field if non-nil, zero value otherwise.

### GetControllerIdOk

`func (o *AuthorityVoteCreateRequest) GetControllerIdOk() (*string, bool)`

GetControllerIdOk returns a tuple with the ControllerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerId

`func (o *AuthorityVoteCreateRequest) SetControllerId(v string)`

SetControllerId sets ControllerId field to given value.


### GetDecision

`func (o *AuthorityVoteCreateRequest) GetDecision() DecisionEnum`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *AuthorityVoteCreateRequest) GetDecisionOk() (*DecisionEnum, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *AuthorityVoteCreateRequest) SetDecision(v DecisionEnum)`

SetDecision sets Decision field to given value.


### GetReason

`func (o *AuthorityVoteCreateRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuthorityVoteCreateRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuthorityVoteCreateRequest) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AuthorityVoteCreateRequest) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


