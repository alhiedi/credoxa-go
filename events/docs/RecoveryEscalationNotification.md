# RecoveryEscalationNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | [readonly] 
**Channel** | **string** |  | 
**Recipient** | **string** |  | 
**TemplateCode** | Pointer to **string** |  | [optional] 
**Status** | Pointer to [**RecoveryEscalationNotificationStatusEnum**](RecoveryEscalationNotificationStatusEnum.md) |  | [optional] 
**AvailableAt** | Pointer to **time.Time** |  | [optional] 
**SentAt** | Pointer to **NullableTime** |  | [optional] 
**AttemptCount** | Pointer to **int64** |  | [optional] 
**LastError** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | [readonly] 
**UpdatedAt** | **time.Time** |  | [readonly] 

## Methods

### NewRecoveryEscalationNotification

`func NewRecoveryEscalationNotification(id string, channel string, recipient string, createdAt time.Time, updatedAt time.Time, ) *RecoveryEscalationNotification`

NewRecoveryEscalationNotification instantiates a new RecoveryEscalationNotification object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecoveryEscalationNotificationWithDefaults

`func NewRecoveryEscalationNotificationWithDefaults() *RecoveryEscalationNotification`

NewRecoveryEscalationNotificationWithDefaults instantiates a new RecoveryEscalationNotification object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecoveryEscalationNotification) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecoveryEscalationNotification) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecoveryEscalationNotification) SetId(v string)`

SetId sets Id field to given value.


### GetChannel

`func (o *RecoveryEscalationNotification) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *RecoveryEscalationNotification) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *RecoveryEscalationNotification) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetRecipient

`func (o *RecoveryEscalationNotification) GetRecipient() string`

GetRecipient returns the Recipient field if non-nil, zero value otherwise.

### GetRecipientOk

`func (o *RecoveryEscalationNotification) GetRecipientOk() (*string, bool)`

GetRecipientOk returns a tuple with the Recipient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipient

`func (o *RecoveryEscalationNotification) SetRecipient(v string)`

SetRecipient sets Recipient field to given value.


### GetTemplateCode

`func (o *RecoveryEscalationNotification) GetTemplateCode() string`

GetTemplateCode returns the TemplateCode field if non-nil, zero value otherwise.

### GetTemplateCodeOk

`func (o *RecoveryEscalationNotification) GetTemplateCodeOk() (*string, bool)`

GetTemplateCodeOk returns a tuple with the TemplateCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateCode

`func (o *RecoveryEscalationNotification) SetTemplateCode(v string)`

SetTemplateCode sets TemplateCode field to given value.

### HasTemplateCode

`func (o *RecoveryEscalationNotification) HasTemplateCode() bool`

HasTemplateCode returns a boolean if a field has been set.

### GetStatus

`func (o *RecoveryEscalationNotification) GetStatus() RecoveryEscalationNotificationStatusEnum`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecoveryEscalationNotification) GetStatusOk() (*RecoveryEscalationNotificationStatusEnum, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecoveryEscalationNotification) SetStatus(v RecoveryEscalationNotificationStatusEnum)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RecoveryEscalationNotification) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAvailableAt

`func (o *RecoveryEscalationNotification) GetAvailableAt() time.Time`

GetAvailableAt returns the AvailableAt field if non-nil, zero value otherwise.

### GetAvailableAtOk

`func (o *RecoveryEscalationNotification) GetAvailableAtOk() (*time.Time, bool)`

GetAvailableAtOk returns a tuple with the AvailableAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableAt

`func (o *RecoveryEscalationNotification) SetAvailableAt(v time.Time)`

SetAvailableAt sets AvailableAt field to given value.

### HasAvailableAt

`func (o *RecoveryEscalationNotification) HasAvailableAt() bool`

HasAvailableAt returns a boolean if a field has been set.

### GetSentAt

`func (o *RecoveryEscalationNotification) GetSentAt() time.Time`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *RecoveryEscalationNotification) GetSentAtOk() (*time.Time, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *RecoveryEscalationNotification) SetSentAt(v time.Time)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *RecoveryEscalationNotification) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *RecoveryEscalationNotification) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *RecoveryEscalationNotification) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetAttemptCount

`func (o *RecoveryEscalationNotification) GetAttemptCount() int64`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *RecoveryEscalationNotification) GetAttemptCountOk() (*int64, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *RecoveryEscalationNotification) SetAttemptCount(v int64)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *RecoveryEscalationNotification) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetLastError

`func (o *RecoveryEscalationNotification) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *RecoveryEscalationNotification) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *RecoveryEscalationNotification) SetLastError(v string)`

SetLastError sets LastError field to given value.

### HasLastError

`func (o *RecoveryEscalationNotification) HasLastError() bool`

HasLastError returns a boolean if a field has been set.

### SetLastErrorNil

`func (o *RecoveryEscalationNotification) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *RecoveryEscalationNotification) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetCreatedAt

`func (o *RecoveryEscalationNotification) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecoveryEscalationNotification) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecoveryEscalationNotification) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *RecoveryEscalationNotification) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *RecoveryEscalationNotification) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *RecoveryEscalationNotification) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


