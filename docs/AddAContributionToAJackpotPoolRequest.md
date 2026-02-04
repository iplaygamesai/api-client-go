# AddAContributionToAJackpotPoolRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlayerId** | **string** | Must not be greater than 100 characters. | 
**Currency** | **string** | Must be 3 characters. | 
**Amount** | **float32** | Must be at least 0.01. Must not be greater than 10000000. | 
**Type** | **string** | Max 10 million per contribution. | 
**TransactionId** | **string** | Must not be greater than 255 characters. | 
**GameId** | Pointer to **NullableInt32** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the games table. | [optional] 
**ExternalGameId** | Pointer to **NullableString** | Must not be greater than 100 characters. | [optional] 
**GameSessionId** | Pointer to **NullableInt32** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the game_sessions table. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAddAContributionToAJackpotPoolRequest

`func NewAddAContributionToAJackpotPoolRequest(playerId string, currency string, amount float32, type_ string, transactionId string, ) *AddAContributionToAJackpotPoolRequest`

NewAddAContributionToAJackpotPoolRequest instantiates a new AddAContributionToAJackpotPoolRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddAContributionToAJackpotPoolRequestWithDefaults

`func NewAddAContributionToAJackpotPoolRequestWithDefaults() *AddAContributionToAJackpotPoolRequest`

NewAddAContributionToAJackpotPoolRequestWithDefaults instantiates a new AddAContributionToAJackpotPoolRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlayerId

`func (o *AddAContributionToAJackpotPoolRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *AddAContributionToAJackpotPoolRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *AddAContributionToAJackpotPoolRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetCurrency

`func (o *AddAContributionToAJackpotPoolRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *AddAContributionToAJackpotPoolRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *AddAContributionToAJackpotPoolRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetAmount

`func (o *AddAContributionToAJackpotPoolRequest) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AddAContributionToAJackpotPoolRequest) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AddAContributionToAJackpotPoolRequest) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetType

`func (o *AddAContributionToAJackpotPoolRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AddAContributionToAJackpotPoolRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AddAContributionToAJackpotPoolRequest) SetType(v string)`

SetType sets Type field to given value.


### GetTransactionId

`func (o *AddAContributionToAJackpotPoolRequest) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *AddAContributionToAJackpotPoolRequest) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *AddAContributionToAJackpotPoolRequest) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetGameId

`func (o *AddAContributionToAJackpotPoolRequest) GetGameId() int32`

GetGameId returns the GameId field if non-nil, zero value otherwise.

### GetGameIdOk

`func (o *AddAContributionToAJackpotPoolRequest) GetGameIdOk() (*int32, bool)`

GetGameIdOk returns a tuple with the GameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameId

`func (o *AddAContributionToAJackpotPoolRequest) SetGameId(v int32)`

SetGameId sets GameId field to given value.

### HasGameId

`func (o *AddAContributionToAJackpotPoolRequest) HasGameId() bool`

HasGameId returns a boolean if a field has been set.

### SetGameIdNil

`func (o *AddAContributionToAJackpotPoolRequest) SetGameIdNil(b bool)`

 SetGameIdNil sets the value for GameId to be an explicit nil

### UnsetGameId
`func (o *AddAContributionToAJackpotPoolRequest) UnsetGameId()`

UnsetGameId ensures that no value is present for GameId, not even an explicit nil
### GetExternalGameId

`func (o *AddAContributionToAJackpotPoolRequest) GetExternalGameId() string`

GetExternalGameId returns the ExternalGameId field if non-nil, zero value otherwise.

### GetExternalGameIdOk

`func (o *AddAContributionToAJackpotPoolRequest) GetExternalGameIdOk() (*string, bool)`

GetExternalGameIdOk returns a tuple with the ExternalGameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalGameId

`func (o *AddAContributionToAJackpotPoolRequest) SetExternalGameId(v string)`

SetExternalGameId sets ExternalGameId field to given value.

### HasExternalGameId

`func (o *AddAContributionToAJackpotPoolRequest) HasExternalGameId() bool`

HasExternalGameId returns a boolean if a field has been set.

### SetExternalGameIdNil

`func (o *AddAContributionToAJackpotPoolRequest) SetExternalGameIdNil(b bool)`

 SetExternalGameIdNil sets the value for ExternalGameId to be an explicit nil

### UnsetExternalGameId
`func (o *AddAContributionToAJackpotPoolRequest) UnsetExternalGameId()`

UnsetExternalGameId ensures that no value is present for ExternalGameId, not even an explicit nil
### GetGameSessionId

`func (o *AddAContributionToAJackpotPoolRequest) GetGameSessionId() int32`

GetGameSessionId returns the GameSessionId field if non-nil, zero value otherwise.

### GetGameSessionIdOk

`func (o *AddAContributionToAJackpotPoolRequest) GetGameSessionIdOk() (*int32, bool)`

GetGameSessionIdOk returns a tuple with the GameSessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameSessionId

`func (o *AddAContributionToAJackpotPoolRequest) SetGameSessionId(v int32)`

SetGameSessionId sets GameSessionId field to given value.

### HasGameSessionId

`func (o *AddAContributionToAJackpotPoolRequest) HasGameSessionId() bool`

HasGameSessionId returns a boolean if a field has been set.

### SetGameSessionIdNil

`func (o *AddAContributionToAJackpotPoolRequest) SetGameSessionIdNil(b bool)`

 SetGameSessionIdNil sets the value for GameSessionId to be an explicit nil

### UnsetGameSessionId
`func (o *AddAContributionToAJackpotPoolRequest) UnsetGameSessionId()`

UnsetGameSessionId ensures that no value is present for GameSessionId, not even an explicit nil
### GetMetadata

`func (o *AddAContributionToAJackpotPoolRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AddAContributionToAJackpotPoolRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AddAContributionToAJackpotPoolRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AddAContributionToAJackpotPoolRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AddAContributionToAJackpotPoolRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AddAContributionToAJackpotPoolRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


