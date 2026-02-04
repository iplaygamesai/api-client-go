# CreateAStandaloneFreespinRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GameId** | **int32** | The internal game ID. | 
**PlayerId** | **string** | The player&#39;s ID in your system. | 
**Currency** | **string** | Three-letter currency code (ISO 4217). | 
**FreespinId** | **string** | Your unique identifier for this freespin campaign. | 
**FreespinCount** | **int32** | Number of free spins to award (1-1000). | 
**FreespinBetAmount** | Pointer to [**NullableNumeric**](numeric.md) | optional Bet amount per free spin (0.01-1000). | [optional] 
**ExpireDays** | Pointer to **NullableInt32** | optional Expiration in days, default 7, max 30. | [optional] 
**Provider** | Pointer to **NullableString** | optional Specific provider slug to use. | [optional] 

## Methods

### NewCreateAStandaloneFreespinRequest

`func NewCreateAStandaloneFreespinRequest(gameId int32, playerId string, currency string, freespinId string, freespinCount int32, ) *CreateAStandaloneFreespinRequest`

NewCreateAStandaloneFreespinRequest instantiates a new CreateAStandaloneFreespinRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAStandaloneFreespinRequestWithDefaults

`func NewCreateAStandaloneFreespinRequestWithDefaults() *CreateAStandaloneFreespinRequest`

NewCreateAStandaloneFreespinRequestWithDefaults instantiates a new CreateAStandaloneFreespinRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGameId

`func (o *CreateAStandaloneFreespinRequest) GetGameId() int32`

GetGameId returns the GameId field if non-nil, zero value otherwise.

### GetGameIdOk

`func (o *CreateAStandaloneFreespinRequest) GetGameIdOk() (*int32, bool)`

GetGameIdOk returns a tuple with the GameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameId

`func (o *CreateAStandaloneFreespinRequest) SetGameId(v int32)`

SetGameId sets GameId field to given value.


### GetPlayerId

`func (o *CreateAStandaloneFreespinRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *CreateAStandaloneFreespinRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *CreateAStandaloneFreespinRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetCurrency

`func (o *CreateAStandaloneFreespinRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateAStandaloneFreespinRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateAStandaloneFreespinRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetFreespinId

`func (o *CreateAStandaloneFreespinRequest) GetFreespinId() string`

GetFreespinId returns the FreespinId field if non-nil, zero value otherwise.

### GetFreespinIdOk

`func (o *CreateAStandaloneFreespinRequest) GetFreespinIdOk() (*string, bool)`

GetFreespinIdOk returns a tuple with the FreespinId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreespinId

`func (o *CreateAStandaloneFreespinRequest) SetFreespinId(v string)`

SetFreespinId sets FreespinId field to given value.


### GetFreespinCount

`func (o *CreateAStandaloneFreespinRequest) GetFreespinCount() int32`

GetFreespinCount returns the FreespinCount field if non-nil, zero value otherwise.

### GetFreespinCountOk

`func (o *CreateAStandaloneFreespinRequest) GetFreespinCountOk() (*int32, bool)`

GetFreespinCountOk returns a tuple with the FreespinCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreespinCount

`func (o *CreateAStandaloneFreespinRequest) SetFreespinCount(v int32)`

SetFreespinCount sets FreespinCount field to given value.


### GetFreespinBetAmount

`func (o *CreateAStandaloneFreespinRequest) GetFreespinBetAmount() Numeric`

GetFreespinBetAmount returns the FreespinBetAmount field if non-nil, zero value otherwise.

### GetFreespinBetAmountOk

`func (o *CreateAStandaloneFreespinRequest) GetFreespinBetAmountOk() (*Numeric, bool)`

GetFreespinBetAmountOk returns a tuple with the FreespinBetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreespinBetAmount

`func (o *CreateAStandaloneFreespinRequest) SetFreespinBetAmount(v Numeric)`

SetFreespinBetAmount sets FreespinBetAmount field to given value.

### HasFreespinBetAmount

`func (o *CreateAStandaloneFreespinRequest) HasFreespinBetAmount() bool`

HasFreespinBetAmount returns a boolean if a field has been set.

### SetFreespinBetAmountNil

`func (o *CreateAStandaloneFreespinRequest) SetFreespinBetAmountNil(b bool)`

 SetFreespinBetAmountNil sets the value for FreespinBetAmount to be an explicit nil

### UnsetFreespinBetAmount
`func (o *CreateAStandaloneFreespinRequest) UnsetFreespinBetAmount()`

UnsetFreespinBetAmount ensures that no value is present for FreespinBetAmount, not even an explicit nil
### GetExpireDays

`func (o *CreateAStandaloneFreespinRequest) GetExpireDays() int32`

GetExpireDays returns the ExpireDays field if non-nil, zero value otherwise.

### GetExpireDaysOk

`func (o *CreateAStandaloneFreespinRequest) GetExpireDaysOk() (*int32, bool)`

GetExpireDaysOk returns a tuple with the ExpireDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpireDays

`func (o *CreateAStandaloneFreespinRequest) SetExpireDays(v int32)`

SetExpireDays sets ExpireDays field to given value.

### HasExpireDays

`func (o *CreateAStandaloneFreespinRequest) HasExpireDays() bool`

HasExpireDays returns a boolean if a field has been set.

### SetExpireDaysNil

`func (o *CreateAStandaloneFreespinRequest) SetExpireDaysNil(b bool)`

 SetExpireDaysNil sets the value for ExpireDays to be an explicit nil

### UnsetExpireDays
`func (o *CreateAStandaloneFreespinRequest) UnsetExpireDays()`

UnsetExpireDays ensures that no value is present for ExpireDays, not even an explicit nil
### GetProvider

`func (o *CreateAStandaloneFreespinRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateAStandaloneFreespinRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateAStandaloneFreespinRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *CreateAStandaloneFreespinRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *CreateAStandaloneFreespinRequest) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *CreateAStandaloneFreespinRequest) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


