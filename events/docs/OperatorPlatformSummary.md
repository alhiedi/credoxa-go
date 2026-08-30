# OperatorPlatformSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archives** | [**OperatorArchiveSummary**](OperatorArchiveSummary.md) |  | 
**Replays** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewOperatorPlatformSummary

`func NewOperatorPlatformSummary(archives OperatorArchiveSummary, ) *OperatorPlatformSummary`

NewOperatorPlatformSummary instantiates a new OperatorPlatformSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperatorPlatformSummaryWithDefaults

`func NewOperatorPlatformSummaryWithDefaults() *OperatorPlatformSummary`

NewOperatorPlatformSummaryWithDefaults instantiates a new OperatorPlatformSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchives

`func (o *OperatorPlatformSummary) GetArchives() OperatorArchiveSummary`

GetArchives returns the Archives field if non-nil, zero value otherwise.

### GetArchivesOk

`func (o *OperatorPlatformSummary) GetArchivesOk() (*OperatorArchiveSummary, bool)`

GetArchivesOk returns a tuple with the Archives field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchives

`func (o *OperatorPlatformSummary) SetArchives(v OperatorArchiveSummary)`

SetArchives sets Archives field to given value.


### GetReplays

`func (o *OperatorPlatformSummary) GetReplays() map[string]interface{}`

GetReplays returns the Replays field if non-nil, zero value otherwise.

### GetReplaysOk

`func (o *OperatorPlatformSummary) GetReplaysOk() (*map[string]interface{}, bool)`

GetReplaysOk returns a tuple with the Replays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplays

`func (o *OperatorPlatformSummary) SetReplays(v map[string]interface{})`

SetReplays sets Replays field to given value.

### HasReplays

`func (o *OperatorPlatformSummary) HasReplays() bool`

HasReplays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


