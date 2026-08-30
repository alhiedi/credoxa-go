# OperatorRuntimeDashboardScope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **NullableString** |  | 
**Kind** | [**OperatorRuntimeDashboardScopeKindEnum**](OperatorRuntimeDashboardScopeKindEnum.md) |  | 

## Methods

### NewOperatorRuntimeDashboardScope

`func NewOperatorRuntimeDashboardScope(organizationId NullableString, kind OperatorRuntimeDashboardScopeKindEnum, ) *OperatorRuntimeDashboardScope`

NewOperatorRuntimeDashboardScope instantiates a new OperatorRuntimeDashboardScope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorRuntimeDashboardScopeWithDefaults

`func NewOperatorRuntimeDashboardScopeWithDefaults() *OperatorRuntimeDashboardScope`

NewOperatorRuntimeDashboardScopeWithDefaults instantiates a new OperatorRuntimeDashboardScope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *OperatorRuntimeDashboardScope) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OperatorRuntimeDashboardScope) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OperatorRuntimeDashboardScope) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *OperatorRuntimeDashboardScope) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *OperatorRuntimeDashboardScope) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetKind

`func (o *OperatorRuntimeDashboardScope) GetKind() OperatorRuntimeDashboardScopeKindEnum`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *OperatorRuntimeDashboardScope) GetKindOk() (*OperatorRuntimeDashboardScopeKindEnum, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *OperatorRuntimeDashboardScope) SetKind(v OperatorRuntimeDashboardScopeKindEnum)`

SetKind sets Kind field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


