# StartAMultiSessionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlayerId** | **string** | Player&#39;s ID in your system. | 
**Currency** | **string** | Three-letter currency code (ISO 4217). | 
**CountryCode** | **string** | Two-letter country code (ISO 3166-1 alpha-2). | 
**IpAddress** | **string** | Player&#39;s IP address. | 
**GameIds** | Pointer to **[]string** | optional Specific game IDs to include. If not provided, picks random games from each available provider. | [optional] 
**Locale** | Pointer to **NullableString** | optional Player&#39;s language preference (ISO 639-1). | [optional] 
**Device** | Pointer to **NullableString** | optional Device type: desktop, mobile, tablet. | [optional] 

## Methods

### NewStartAMultiSessionRequest

`func NewStartAMultiSessionRequest(playerId string, currency string, countryCode string, ipAddress string, ) *StartAMultiSessionRequest`

NewStartAMultiSessionRequest instantiates a new StartAMultiSessionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStartAMultiSessionRequestWithDefaults

`func NewStartAMultiSessionRequestWithDefaults() *StartAMultiSessionRequest`

NewStartAMultiSessionRequestWithDefaults instantiates a new StartAMultiSessionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlayerId

`func (o *StartAMultiSessionRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *StartAMultiSessionRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *StartAMultiSessionRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetCurrency

`func (o *StartAMultiSessionRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *StartAMultiSessionRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *StartAMultiSessionRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCountryCode

`func (o *StartAMultiSessionRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *StartAMultiSessionRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *StartAMultiSessionRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetIpAddress

`func (o *StartAMultiSessionRequest) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *StartAMultiSessionRequest) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *StartAMultiSessionRequest) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.


### GetGameIds

`func (o *StartAMultiSessionRequest) GetGameIds() []string`

GetGameIds returns the GameIds field if non-nil, zero value otherwise.

### GetGameIdsOk

`func (o *StartAMultiSessionRequest) GetGameIdsOk() (*[]string, bool)`

GetGameIdsOk returns a tuple with the GameIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameIds

`func (o *StartAMultiSessionRequest) SetGameIds(v []string)`

SetGameIds sets GameIds field to given value.

### HasGameIds

`func (o *StartAMultiSessionRequest) HasGameIds() bool`

HasGameIds returns a boolean if a field has been set.

### GetLocale

`func (o *StartAMultiSessionRequest) GetLocale() string`

GetLocale returns the Locale field if non-nil, zero value otherwise.

### GetLocaleOk

`func (o *StartAMultiSessionRequest) GetLocaleOk() (*string, bool)`

GetLocaleOk returns a tuple with the Locale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocale

`func (o *StartAMultiSessionRequest) SetLocale(v string)`

SetLocale sets Locale field to given value.

### HasLocale

`func (o *StartAMultiSessionRequest) HasLocale() bool`

HasLocale returns a boolean if a field has been set.

### SetLocaleNil

`func (o *StartAMultiSessionRequest) SetLocaleNil(b bool)`

 SetLocaleNil sets the value for Locale to be an explicit nil

### UnsetLocale
`func (o *StartAMultiSessionRequest) UnsetLocale()`

UnsetLocale ensures that no value is present for Locale, not even an explicit nil
### GetDevice

`func (o *StartAMultiSessionRequest) GetDevice() string`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *StartAMultiSessionRequest) GetDeviceOk() (*string, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *StartAMultiSessionRequest) SetDevice(v string)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *StartAMultiSessionRequest) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### SetDeviceNil

`func (o *StartAMultiSessionRequest) SetDeviceNil(b bool)`

 SetDeviceNil sets the value for Device to be an explicit nil

### UnsetDevice
`func (o *StartAMultiSessionRequest) UnsetDevice()`

UnsetDevice ensures that no value is present for Device, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


