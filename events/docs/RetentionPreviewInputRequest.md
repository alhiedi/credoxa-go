# RetentionPreviewInputRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventTypeId** | **string** |  | 
**Source** | **string** |  | 
**ReceivedAt** | **time.Time** |  | 
**OccurredAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewRetentionPreviewInputRequest

`func NewRetentionPreviewInputRequest(eventTypeId string, source string, receivedAt time.Time, ) *RetentionPreviewInputRequest`

NewRetentionPreviewInputRequest instantiates a new RetentionPreviewInputRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetentionPreviewInputRequestWithDefaults

`func NewRetentionPreviewInputRequestWithDefaults() *RetentionPreviewInputRequest`

NewRetentionPreviewInputRequestWithDefaults instantiates a new RetentionPreviewInputRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventTypeId

`func (o *RetentionPreviewInputRequest) GetEventTypeId() string`

GetEventTypeId returns the EventTypeId field if non-nil, zero value otherwise.

### GetEventTypeIdOk

`func (o *RetentionPreviewInputRequest) GetEventTypeIdOk() (*string, bool)`

GetEventTypeIdOk returns a tuple with the EventTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypeId

`func (o *RetentionPreviewInputRequest) SetEventTypeId(v string)`

SetEventTypeId sets EventTypeId field to given value.


### GetSource

`func (o *RetentionPreviewInputRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RetentionPreviewInputRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RetentionPreviewInputRequest) SetSource(v string)`

SetSource sets Source field to given value.


### GetReceivedAt

`func (o *RetentionPreviewInputRequest) GetReceivedAt() time.Time`

GetReceivedAt returns the ReceivedAt field if non-nil, zero value otherwise.

### GetReceivedAtOk

`func (o *RetentionPreviewInputRequest) GetReceivedAtOk() (*time.Time, bool)`

GetReceivedAtOk returns a tuple with the ReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedAt

`func (o *RetentionPreviewInputRequest) SetReceivedAt(v time.Time)`

SetReceivedAt sets ReceivedAt field to given value.


### GetOccurredAt

`func (o *RetentionPreviewInputRequest) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *RetentionPreviewInputRequest) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *RetentionPreviewInputRequest) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *RetentionPreviewInputRequest) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### SetOccurredAtNil

`func (o *RetentionPreviewInputRequest) SetOccurredAtNil(b bool)`

 SetOccurredAtNil sets the value for OccurredAt to be an explicit nil

### UnsetOccurredAt
`func (o *RetentionPreviewInputRequest) UnsetOccurredAt()`

UnsetOccurredAt ensures that no value is present for OccurredAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


