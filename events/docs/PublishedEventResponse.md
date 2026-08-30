# PublishedEventResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventId** | **string** |  | 
**EventType** | **string** |  | 
**SchemaVersion** | **int32** |  | 
**Source** | **string** |  | 
**Subject** | **string** |  | 
**Status** | **string** |  | 
**Created** | **bool** |  | 
**ReceivedAt** | **time.Time** |  | 

## Methods

### NewPublishedEventResponse

`func NewPublishedEventResponse(eventId string, eventType string, schemaVersion int32, source string, subject string, status string, created bool, receivedAt time.Time, ) *PublishedEventResponse`

NewPublishedEventResponse instantiates a new PublishedEventResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishedEventResponseWithDefaults

`func NewPublishedEventResponseWithDefaults() *PublishedEventResponse`

NewPublishedEventResponseWithDefaults instantiates a new PublishedEventResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventId

`func (o *PublishedEventResponse) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *PublishedEventResponse) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *PublishedEventResponse) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetEventType

`func (o *PublishedEventResponse) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PublishedEventResponse) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PublishedEventResponse) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetSchemaVersion

`func (o *PublishedEventResponse) GetSchemaVersion() int32`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *PublishedEventResponse) GetSchemaVersionOk() (*int32, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *PublishedEventResponse) SetSchemaVersion(v int32)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetSource

`func (o *PublishedEventResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PublishedEventResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PublishedEventResponse) SetSource(v string)`

SetSource sets Source field to given value.


### GetSubject

`func (o *PublishedEventResponse) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *PublishedEventResponse) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *PublishedEventResponse) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetStatus

`func (o *PublishedEventResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PublishedEventResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PublishedEventResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreated

`func (o *PublishedEventResponse) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *PublishedEventResponse) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *PublishedEventResponse) SetCreated(v bool)`

SetCreated sets Created field to given value.


### GetReceivedAt

`func (o *PublishedEventResponse) GetReceivedAt() time.Time`

GetReceivedAt returns the ReceivedAt field if non-nil, zero value otherwise.

### GetReceivedAtOk

`func (o *PublishedEventResponse) GetReceivedAtOk() (*time.Time, bool)`

GetReceivedAtOk returns a tuple with the ReceivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceivedAt

`func (o *PublishedEventResponse) SetReceivedAt(v time.Time)`

SetReceivedAt sets ReceivedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


