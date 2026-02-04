# ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tier** | Pointer to **int32** | This field is required when &lt;code&gt;prize_tiers&lt;/code&gt; is present. Must be at least 1. | [optional] 
**WinnerCount** | Pointer to **int32** | This field is required when &lt;code&gt;prize_tiers&lt;/code&gt; is present. Must be at least 1. | [optional] 
**Percentage** | Pointer to **float32** | This field is required when &lt;code&gt;prize_tiers&lt;/code&gt; is present. Must be at least 0.01. Must not be greater than 100. | [optional] 

## Methods

### NewConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner

`func NewConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner() *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner`

NewConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner instantiates a new ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInnerWithDefaults

`func NewConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInnerWithDefaults() *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner`

NewConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInnerWithDefaults instantiates a new ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTier

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) GetTier() int32`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) GetTierOk() (*int32, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) SetTier(v int32)`

SetTier sets Tier field to given value.

### HasTier

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) HasTier() bool`

HasTier returns a boolean if a field has been set.

### GetWinnerCount

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) GetWinnerCount() int32`

GetWinnerCount returns the WinnerCount field if non-nil, zero value otherwise.

### GetWinnerCountOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) GetWinnerCountOk() (*int32, bool)`

GetWinnerCountOk returns a tuple with the WinnerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinnerCount

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) SetWinnerCount(v int32)`

SetWinnerCount sets WinnerCount field to given value.

### HasWinnerCount

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) HasWinnerCount() bool`

HasWinnerCount returns a boolean if a field has been set.

### GetPercentage

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) GetPercentage() float32`

GetPercentage returns the Percentage field if non-nil, zero value otherwise.

### GetPercentageOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) GetPercentageOk() (*float32, bool)`

GetPercentageOk returns a tuple with the Percentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentage

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) SetPercentage(v float32)`

SetPercentage sets Percentage field to given value.

### HasPercentage

`func (o *ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner) HasPercentage() bool`

HasPercentage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


