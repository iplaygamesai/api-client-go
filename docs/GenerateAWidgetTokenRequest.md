# GenerateAWidgetTokenRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainToken** | **string** | The domain token from domain registration. | 
**PoolTypes** | Pointer to **[]string** | optional Allowed jackpot pool types. Default: [\&quot;daily\&quot;,\&quot;weekly\&quot;,\&quot;monthly\&quot;]. | [optional] 
**PlayerId** | Pointer to **NullableString** | optional Lock token to specific player (anonymous mode if omitted). | [optional] 
**Currency** | Pointer to **NullableString** | optional Player&#39;s currency (required if player_id provided). | [optional] 
**ExpiresAt** | Pointer to [**NullableDatetime**](datetime.md) | optional Token expiration time (null &#x3D; never expires). | [optional] 
**Configuration** | Pointer to **map[string]interface{}** | optional Additional widget configuration. | [optional] 

## Methods

### NewGenerateAWidgetTokenRequest

`func NewGenerateAWidgetTokenRequest(domainToken string, ) *GenerateAWidgetTokenRequest`

NewGenerateAWidgetTokenRequest instantiates a new GenerateAWidgetTokenRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGenerateAWidgetTokenRequestWithDefaults

`func NewGenerateAWidgetTokenRequestWithDefaults() *GenerateAWidgetTokenRequest`

NewGenerateAWidgetTokenRequestWithDefaults instantiates a new GenerateAWidgetTokenRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainToken

`func (o *GenerateAWidgetTokenRequest) GetDomainToken() string`

GetDomainToken returns the DomainToken field if non-nil, zero value otherwise.

### GetDomainTokenOk

`func (o *GenerateAWidgetTokenRequest) GetDomainTokenOk() (*string, bool)`

GetDomainTokenOk returns a tuple with the DomainToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainToken

`func (o *GenerateAWidgetTokenRequest) SetDomainToken(v string)`

SetDomainToken sets DomainToken field to given value.


### GetPoolTypes

`func (o *GenerateAWidgetTokenRequest) GetPoolTypes() []string`

GetPoolTypes returns the PoolTypes field if non-nil, zero value otherwise.

### GetPoolTypesOk

`func (o *GenerateAWidgetTokenRequest) GetPoolTypesOk() (*[]string, bool)`

GetPoolTypesOk returns a tuple with the PoolTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolTypes

`func (o *GenerateAWidgetTokenRequest) SetPoolTypes(v []string)`

SetPoolTypes sets PoolTypes field to given value.

### HasPoolTypes

`func (o *GenerateAWidgetTokenRequest) HasPoolTypes() bool`

HasPoolTypes returns a boolean if a field has been set.

### GetPlayerId

`func (o *GenerateAWidgetTokenRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *GenerateAWidgetTokenRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *GenerateAWidgetTokenRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.

### HasPlayerId

`func (o *GenerateAWidgetTokenRequest) HasPlayerId() bool`

HasPlayerId returns a boolean if a field has been set.

### SetPlayerIdNil

`func (o *GenerateAWidgetTokenRequest) SetPlayerIdNil(b bool)`

 SetPlayerIdNil sets the value for PlayerId to be an explicit nil

### UnsetPlayerId
`func (o *GenerateAWidgetTokenRequest) UnsetPlayerId()`

UnsetPlayerId ensures that no value is present for PlayerId, not even an explicit nil
### GetCurrency

`func (o *GenerateAWidgetTokenRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GenerateAWidgetTokenRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GenerateAWidgetTokenRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *GenerateAWidgetTokenRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *GenerateAWidgetTokenRequest) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *GenerateAWidgetTokenRequest) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetExpiresAt

`func (o *GenerateAWidgetTokenRequest) GetExpiresAt() Datetime`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *GenerateAWidgetTokenRequest) GetExpiresAtOk() (*Datetime, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *GenerateAWidgetTokenRequest) SetExpiresAt(v Datetime)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *GenerateAWidgetTokenRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *GenerateAWidgetTokenRequest) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *GenerateAWidgetTokenRequest) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetConfiguration

`func (o *GenerateAWidgetTokenRequest) GetConfiguration() map[string]interface{}`

GetConfiguration returns the Configuration field if non-nil, zero value otherwise.

### GetConfigurationOk

`func (o *GenerateAWidgetTokenRequest) GetConfigurationOk() (*map[string]interface{}, bool)`

GetConfigurationOk returns a tuple with the Configuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguration

`func (o *GenerateAWidgetTokenRequest) SetConfiguration(v map[string]interface{})`

SetConfiguration sets Configuration field to given value.

### HasConfiguration

`func (o *GenerateAWidgetTokenRequest) HasConfiguration() bool`

HasConfiguration returns a boolean if a field has been set.

### SetConfigurationNil

`func (o *GenerateAWidgetTokenRequest) SetConfigurationNil(b bool)`

 SetConfigurationNil sets the value for Configuration to be an explicit nil

### UnsetConfiguration
`func (o *GenerateAWidgetTokenRequest) UnsetConfiguration()`

UnsetConfiguration ensures that no value is present for Configuration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


