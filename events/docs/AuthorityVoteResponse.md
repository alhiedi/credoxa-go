# AuthorityVoteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Vote** | [**AuthorityVote**](AuthorityVote.md) |  | 
**Proposal** | [**AuthorityProposal**](AuthorityProposal.md) |  | 

## Methods

### NewAuthorityVoteResponse

`func NewAuthorityVoteResponse(vote AuthorityVote, proposal AuthorityProposal, ) *AuthorityVoteResponse`

NewAuthorityVoteResponse instantiates a new AuthorityVoteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorityVoteResponseWithDefaults

`func NewAuthorityVoteResponseWithDefaults() *AuthorityVoteResponse`

NewAuthorityVoteResponseWithDefaults instantiates a new AuthorityVoteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVote

`func (o *AuthorityVoteResponse) GetVote() AuthorityVote`

GetVote returns the Vote field if non-nil, zero value otherwise.

### GetVoteOk

`func (o *AuthorityVoteResponse) GetVoteOk() (*AuthorityVote, bool)`

GetVoteOk returns a tuple with the Vote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVote

`func (o *AuthorityVoteResponse) SetVote(v AuthorityVote)`

SetVote sets Vote field to given value.


### GetProposal

`func (o *AuthorityVoteResponse) GetProposal() AuthorityProposal`

GetProposal returns the Proposal field if non-nil, zero value otherwise.

### GetProposalOk

`func (o *AuthorityVoteResponse) GetProposalOk() (*AuthorityProposal, bool)`

GetProposalOk returns a tuple with the Proposal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposal

`func (o *AuthorityVoteResponse) SetProposal(v AuthorityProposal)`

SetProposal sets Proposal field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


