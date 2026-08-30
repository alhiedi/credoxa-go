# ControlPlaneElectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MembershipRevision** | [**MembershipRevision**](MembershipRevision.md) |  | 
**LeadershipTerm** | [**LeadershipTerm**](LeadershipTerm.md) |  | 

## Methods

### NewControlPlaneElectionResponse

`func NewControlPlaneElectionResponse(membershipRevision MembershipRevision, leadershipTerm LeadershipTerm, ) *ControlPlaneElectionResponse`

NewControlPlaneElectionResponse instantiates a new ControlPlaneElectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewControlPlaneElectionResponseWithDefaults

`func NewControlPlaneElectionResponseWithDefaults() *ControlPlaneElectionResponse`

NewControlPlaneElectionResponseWithDefaults instantiates a new ControlPlaneElectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMembershipRevision

`func (o *ControlPlaneElectionResponse) GetMembershipRevision() MembershipRevision`

GetMembershipRevision returns the MembershipRevision field if non-nil, zero value otherwise.

### GetMembershipRevisionOk

`func (o *ControlPlaneElectionResponse) GetMembershipRevisionOk() (*MembershipRevision, bool)`

GetMembershipRevisionOk returns a tuple with the MembershipRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipRevision

`func (o *ControlPlaneElectionResponse) SetMembershipRevision(v MembershipRevision)`

SetMembershipRevision sets MembershipRevision field to given value.


### GetLeadershipTerm

`func (o *ControlPlaneElectionResponse) GetLeadershipTerm() LeadershipTerm`

GetLeadershipTerm returns the LeadershipTerm field if non-nil, zero value otherwise.

### GetLeadershipTermOk

`func (o *ControlPlaneElectionResponse) GetLeadershipTermOk() (*LeadershipTerm, bool)`

GetLeadershipTermOk returns a tuple with the LeadershipTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadershipTerm

`func (o *ControlPlaneElectionResponse) SetLeadershipTerm(v LeadershipTerm)`

SetLeadershipTerm sets LeadershipTerm field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


