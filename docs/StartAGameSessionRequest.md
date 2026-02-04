# StartAGameSessionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GameId** | **int32** | The ID of the game to start. | 
**PlayerId** | **string** | The player&#39;s ID in your system. | 
**Currency** | **string** | Three-letter currency code (ISO 4217). | 
**IpAddress** | **string** | The player&#39;s IP address. | 
**CountryCode** | **string** | Two-letter country code (ISO 3166-1 alpha-2). | 
**ReturnUrl** | Pointer to **NullableString** | optional URL to redirect the player after game ends. | [optional] 
**Locale** | Pointer to **NullableString** | optional Player&#39;s language preference (ISO 639-1). | [optional] 
**Provider** | Pointer to **NullableString** | optional Provider slug to use for this session. Requires can_override_provider enabled. | [optional] 
**FreespinId** | Pointer to **NullableString** | optional Free spin bonus ID. | [optional] 
**FreespinCount** | Pointer to **NullableInt32** | optional Number of free spins. | [optional] 
**FreespinBetAmount** | Pointer to [**NullableNumeric**](numeric.md) | optional Bet amount per free spin. | [optional] 
**ExpireDays** | Pointer to **NullableInt32** | optional Free spin expiration in days (1-30). | [optional] 
**Device** | Pointer to **NullableString** | optional Device type (desktop, mobile). | [optional] 

## Methods

### NewStartAGameSessionRequest

`func NewStartAGameSessionRequest(gameId int32, playerId string, currency string, ipAddress string, countryCode string, ) *StartAGameSessionRequest`

NewStartAGameSessionRequest instantiates a new StartAGameSessionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStartAGameSessionRequestWithDefaults

`func NewStartAGameSessionRequestWithDefaults() *StartAGameSessionRequest`

NewStartAGameSessionRequestWithDefaults instantiates a new StartAGameSessionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGameId

`func (o *StartAGameSessionRequest) GetGameId() int32`

GetGameId returns the GameId field if non-nil, zero value otherwise.

### GetGameIdOk

`func (o *StartAGameSessionRequest) GetGameIdOk() (*int32, bool)`

GetGameIdOk returns a tuple with the GameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameId

`func (o *StartAGameSessionRequest) SetGameId(v int32)`

SetGameId sets GameId field to given value.


### GetPlayerId

`func (o *StartAGameSessionRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *StartAGameSessionRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *StartAGameSessionRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetCurrency

`func (o *StartAGameSessionRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *StartAGameSessionRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *StartAGameSessionRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetIpAddress

`func (o *StartAGameSessionRequest) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *StartAGameSessionRequest) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *StartAGameSessionRequest) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.


### GetCountryCode

`func (o *StartAGameSessionRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *StartAGameSessionRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *StartAGameSessionRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetReturnUrl

`func (o *StartAGameSessionRequest) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *StartAGameSessionRequest) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *StartAGameSessionRequest) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *StartAGameSessionRequest) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.

### SetReturnUrlNil

`func (o *StartAGameSessionRequest) SetReturnUrlNil(b bool)`

 SetReturnUrlNil sets the value for ReturnUrl to be an explicit nil

### UnsetReturnUrl
`func (o *StartAGameSessionRequest) UnsetReturnUrl()`

UnsetReturnUrl ensures that no value is present for ReturnUrl, not even an explicit nil
### GetLocale

`func (o *StartAGameSessionRequest) GetLocale() string`

GetLocale returns the Locale field if non-nil, zero value otherwise.

### GetLocaleOk

`func (o *StartAGameSessionRequest) GetLocaleOk() (*string, bool)`

GetLocaleOk returns a tuple with the Locale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocale

`func (o *StartAGameSessionRequest) SetLocale(v string)`

SetLocale sets Locale field to given value.

### HasLocale

`func (o *StartAGameSessionRequest) HasLocale() bool`

HasLocale returns a boolean if a field has been set.

### SetLocaleNil

`func (o *StartAGameSessionRequest) SetLocaleNil(b bool)`

 SetLocaleNil sets the value for Locale to be an explicit nil

### UnsetLocale
`func (o *StartAGameSessionRequest) UnsetLocale()`

UnsetLocale ensures that no value is present for Locale, not even an explicit nil
### GetProvider

`func (o *StartAGameSessionRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *StartAGameSessionRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *StartAGameSessionRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *StartAGameSessionRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *StartAGameSessionRequest) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *StartAGameSessionRequest) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetFreespinId

`func (o *StartAGameSessionRequest) GetFreespinId() string`

GetFreespinId returns the FreespinId field if non-nil, zero value otherwise.

### GetFreespinIdOk

`func (o *StartAGameSessionRequest) GetFreespinIdOk() (*string, bool)`

GetFreespinIdOk returns a tuple with the FreespinId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreespinId

`func (o *StartAGameSessionRequest) SetFreespinId(v string)`

SetFreespinId sets FreespinId field to given value.

### HasFreespinId

`func (o *StartAGameSessionRequest) HasFreespinId() bool`

HasFreespinId returns a boolean if a field has been set.

### SetFreespinIdNil

`func (o *StartAGameSessionRequest) SetFreespinIdNil(b bool)`

 SetFreespinIdNil sets the value for FreespinId to be an explicit nil

### UnsetFreespinId
`func (o *StartAGameSessionRequest) UnsetFreespinId()`

UnsetFreespinId ensures that no value is present for FreespinId, not even an explicit nil
### GetFreespinCount

`func (o *StartAGameSessionRequest) GetFreespinCount() int32`

GetFreespinCount returns the FreespinCount field if non-nil, zero value otherwise.

### GetFreespinCountOk

`func (o *StartAGameSessionRequest) GetFreespinCountOk() (*int32, bool)`

GetFreespinCountOk returns a tuple with the FreespinCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreespinCount

`func (o *StartAGameSessionRequest) SetFreespinCount(v int32)`

SetFreespinCount sets FreespinCount field to given value.

### HasFreespinCount

`func (o *StartAGameSessionRequest) HasFreespinCount() bool`

HasFreespinCount returns a boolean if a field has been set.

### SetFreespinCountNil

`func (o *StartAGameSessionRequest) SetFreespinCountNil(b bool)`

 SetFreespinCountNil sets the value for FreespinCount to be an explicit nil

### UnsetFreespinCount
`func (o *StartAGameSessionRequest) UnsetFreespinCount()`

UnsetFreespinCount ensures that no value is present for FreespinCount, not even an explicit nil
### GetFreespinBetAmount

`func (o *StartAGameSessionRequest) GetFreespinBetAmount() Numeric`

GetFreespinBetAmount returns the FreespinBetAmount field if non-nil, zero value otherwise.

### GetFreespinBetAmountOk

`func (o *StartAGameSessionRequest) GetFreespinBetAmountOk() (*Numeric, bool)`

GetFreespinBetAmountOk returns a tuple with the FreespinBetAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreespinBetAmount

`func (o *StartAGameSessionRequest) SetFreespinBetAmount(v Numeric)`

SetFreespinBetAmount sets FreespinBetAmount field to given value.

### HasFreespinBetAmount

`func (o *StartAGameSessionRequest) HasFreespinBetAmount() bool`

HasFreespinBetAmount returns a boolean if a field has been set.

### SetFreespinBetAmountNil

`func (o *StartAGameSessionRequest) SetFreespinBetAmountNil(b bool)`

 SetFreespinBetAmountNil sets the value for FreespinBetAmount to be an explicit nil

### UnsetFreespinBetAmount
`func (o *StartAGameSessionRequest) UnsetFreespinBetAmount()`

UnsetFreespinBetAmount ensures that no value is present for FreespinBetAmount, not even an explicit nil
### GetExpireDays

`func (o *StartAGameSessionRequest) GetExpireDays() int32`

GetExpireDays returns the ExpireDays field if non-nil, zero value otherwise.

### GetExpireDaysOk

`func (o *StartAGameSessionRequest) GetExpireDaysOk() (*int32, bool)`

GetExpireDaysOk returns a tuple with the ExpireDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpireDays

`func (o *StartAGameSessionRequest) SetExpireDays(v int32)`

SetExpireDays sets ExpireDays field to given value.

### HasExpireDays

`func (o *StartAGameSessionRequest) HasExpireDays() bool`

HasExpireDays returns a boolean if a field has been set.

### SetExpireDaysNil

`func (o *StartAGameSessionRequest) SetExpireDaysNil(b bool)`

 SetExpireDaysNil sets the value for ExpireDays to be an explicit nil

### UnsetExpireDays
`func (o *StartAGameSessionRequest) UnsetExpireDays()`

UnsetExpireDays ensures that no value is present for ExpireDays, not even an explicit nil
### GetDevice

`func (o *StartAGameSessionRequest) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *StartAGameSessionRequest) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *StartAGameSessionRequest) SetDevice(v string)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *StartAGameSessionRequest) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### SetDeviceNil

`func (o *StartAGameSessionRequest) SetDeviceNil(b bool)`

 SetDeviceNil sets the value for Device to be an explicit nil

### UnsetDevice
`func (o *StartAGameSessionRequest) UnsetDevice()`

UnsetDevice ensures that no value is present for Device, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


