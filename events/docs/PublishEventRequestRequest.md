# PublishEventRequestRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventType** | **string** |  | 
**SchemaVersion** | **int32** |  | 
**Source** | **string** |  | 
**Subject** | Pointer to **string** |  | [optional] [default to ""]
**Payload** | **interface{}** |  | 
**Metadata** | Pointer to **interface{}** |  | [optional] 
**CorrelationId** | Pointer to **NullableString** |  | [optional] 
**OccurredAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewPublishEventRequestRequest

`func NewPublishEventRequestRequest(eventType string, schemaVersion int32, source string, payload interface{}, ) *PublishEventRequestRequest`

NewPublishEventRequestRequest instantiates a new PublishEventRequestRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishEventRequestRequestWithDefaults

`func NewPublishEventRequestRequestWithDefaults() *PublishEventRequestRequest`

NewPublishEventRequestRequestWithDefaults instantiates a new PublishEventRequestRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventType

`func (o *PublishEventRequestRequest) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PublishEventRequestRequest) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PublishEventRequestRequest) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetSchemaVersion

`func (o *PublishEventRequestRequest) GetSchemaVersion() int32`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *PublishEventRequestRequest) GetSchemaVersionOk() (*int32, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *PublishEventRequestRequest) SetSchemaVersion(v int32)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetSource

`func (o *PublishEventRequestRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PublishEventRequestRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PublishEventRequestRequest) SetSource(v string)`

SetSource sets Source field to given value.


### GetSubject

`func (o *PublishEventRequestRequest) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *PublishEventRequestRequest) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *PublishEventRequestRequest) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *PublishEventRequestRequest) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetPayload

`func (o *PublishEventRequestRequest) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *PublishEventRequestRequest) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *PublishEventRequestRequest) SetPayload(v interface{})`

SetPayload sets Payload field to given value.


### SetPayloadNil

`func (o *PublishEventRequestRequest) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *PublishEventRequestRequest) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetMetadata

`func (o *PublishEventRequestRequest) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *PublishEventRequestRequest) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *PublishEventRequestRequest) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *PublishEventRequestRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *PublishEventRequestRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *PublishEventRequestRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetCorrelationId

`func (o *PublishEventRequestRequest) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *PublishEventRequestRequest) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *PublishEventRequestRequest) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *PublishEventRequestRequest) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### SetCorrelationIdNil

`func (o *PublishEventRequestRequest) SetCorrelationIdNil(b bool)`

 SetCorrelationIdNil sets the value for CorrelationId to be an explicit nil

### UnsetCorrelationId
`func (o *PublishEventRequestRequest) UnsetCorrelationId()`

UnsetCorrelationId ensures that no value is present for CorrelationId, not even an explicit nil
### GetOccurredAt

`func (o *PublishEventRequestRequest) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *PublishEventRequestRequest) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *PublishEventRequestRequest) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *PublishEventRequestRequest) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### SetOccurredAtNil

`func (o *PublishEventRequestRequest) SetOccurredAtNil(b bool)`

 SetOccurredAtNil sets the value for OccurredAt to be an explicit nil

### UnsetOccurredAt
`func (o *PublishEventRequestRequest) UnsetOccurredAt()`

UnsetOccurredAt ensures that no value is present for OccurredAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


