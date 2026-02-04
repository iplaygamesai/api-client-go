# ConfigureJackpotSettingsForTheOperatorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsEnabled** | Pointer to **bool** |  | [optional] 
**PoolTypes** | Pointer to **[]string** |  | [optional] 
**CasinoCutPercentage** | Pointer to **float32** | Must be at least 0. Must not be greater than 0.9. | [optional] 
**WinnerCount** | Pointer to **int32** | Must be at least 1. Must not be greater than 10000. | [optional] 
**DistributionMethod** | Pointer to **string** |  | [optional] 
**WeightCalculation** | Pointer to **string** |  | [optional] 
**PrizeTiers** | Pointer to [**[]ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner**](ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner.md) |  | [optional] 
**GameFilterEnabled** | Pointer to **bool** |  | [optional] 
**WebhookEnabled** | Pointer to **bool** |  | [optional] 
**ReminderHoursBefore** | Pointer to **NullableInt32** | Must be at least 1. Must not be greater than 168. | [optional] 

## Methods

### NewConfigureJackpotSettingsForTheOperatorRequest

`func NewConfigureJackpotSettingsForTheOperatorRequest() *ConfigureJackpotSettingsForTheOperatorRequest`

NewConfigureJackpotSettingsForTheOperatorRequest instantiates a new ConfigureJackpotSettingsForTheOperatorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureJackpotSettingsForTheOperatorRequestWithDefaults

`func NewConfigureJackpotSettingsForTheOperatorRequestWithDefaults() *ConfigureJackpotSettingsForTheOperatorRequest`

NewConfigureJackpotSettingsForTheOperatorRequestWithDefaults instantiates a new ConfigureJackpotSettingsForTheOperatorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetPoolTypes

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetPoolTypes() []string`

GetPoolTypes returns the PoolTypes field if non-nil, zero value otherwise.

### GetPoolTypesOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetPoolTypesOk() (*[]string, bool)`

GetPoolTypesOk returns a tuple with the PoolTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolTypes

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetPoolTypes(v []string)`

SetPoolTypes sets PoolTypes field to given value.

### HasPoolTypes

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasPoolTypes() bool`

HasPoolTypes returns a boolean if a field has been set.

### GetCasinoCutPercentage

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetCasinoCutPercentage() float32`

GetCasinoCutPercentage returns the CasinoCutPercentage field if non-nil, zero value otherwise.

### GetCasinoCutPercentageOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetCasinoCutPercentageOk() (*float32, bool)`

GetCasinoCutPercentageOk returns a tuple with the CasinoCutPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCasinoCutPercentage

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetCasinoCutPercentage(v float32)`

SetCasinoCutPercentage sets CasinoCutPercentage field to given value.

### HasCasinoCutPercentage

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasCasinoCutPercentage() bool`

HasCasinoCutPercentage returns a boolean if a field has been set.

### GetWinnerCount

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetWinnerCount() int32`

GetWinnerCount returns the WinnerCount field if non-nil, zero value otherwise.

### GetWinnerCountOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetWinnerCountOk() (*int32, bool)`

GetWinnerCountOk returns a tuple with the WinnerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinnerCount

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetWinnerCount(v int32)`

SetWinnerCount sets WinnerCount field to given value.

### HasWinnerCount

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasWinnerCount() bool`

HasWinnerCount returns a boolean if a field has been set.

### GetDistributionMethod

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetDistributionMethod() string`

GetDistributionMethod returns the DistributionMethod field if non-nil, zero value otherwise.

### GetDistributionMethodOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetDistributionMethodOk() (*string, bool)`

GetDistributionMethodOk returns a tuple with the DistributionMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistributionMethod

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetDistributionMethod(v string)`

SetDistributionMethod sets DistributionMethod field to given value.

### HasDistributionMethod

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasDistributionMethod() bool`

HasDistributionMethod returns a boolean if a field has been set.

### GetWeightCalculation

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetWeightCalculation() string`

GetWeightCalculation returns the WeightCalculation field if non-nil, zero value otherwise.

### GetWeightCalculationOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetWeightCalculationOk() (*string, bool)`

GetWeightCalculationOk returns a tuple with the WeightCalculation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightCalculation

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetWeightCalculation(v string)`

SetWeightCalculation sets WeightCalculation field to given value.

### HasWeightCalculation

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasWeightCalculation() bool`

HasWeightCalculation returns a boolean if a field has been set.

### GetPrizeTiers

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetPrizeTiers() []ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner`

GetPrizeTiers returns the PrizeTiers field if non-nil, zero value otherwise.

### GetPrizeTiersOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetPrizeTiersOk() (*[]ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner, bool)`

GetPrizeTiersOk returns a tuple with the PrizeTiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrizeTiers

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetPrizeTiers(v []ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner)`

SetPrizeTiers sets PrizeTiers field to given value.

### HasPrizeTiers

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasPrizeTiers() bool`

HasPrizeTiers returns a boolean if a field has been set.

### GetGameFilterEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetGameFilterEnabled() bool`

GetGameFilterEnabled returns the GameFilterEnabled field if non-nil, zero value otherwise.

### GetGameFilterEnabledOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetGameFilterEnabledOk() (*bool, bool)`

GetGameFilterEnabledOk returns a tuple with the GameFilterEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameFilterEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetGameFilterEnabled(v bool)`

SetGameFilterEnabled sets GameFilterEnabled field to given value.

### HasGameFilterEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasGameFilterEnabled() bool`

HasGameFilterEnabled returns a boolean if a field has been set.

### GetWebhookEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetWebhookEnabled() bool`

GetWebhookEnabled returns the WebhookEnabled field if non-nil, zero value otherwise.

### GetWebhookEnabledOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetWebhookEnabledOk() (*bool, bool)`

GetWebhookEnabledOk returns a tuple with the WebhookEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetWebhookEnabled(v bool)`

SetWebhookEnabled sets WebhookEnabled field to given value.

### HasWebhookEnabled

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasWebhookEnabled() bool`

HasWebhookEnabled returns a boolean if a field has been set.

### GetReminderHoursBefore

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetReminderHoursBefore() int32`

GetReminderHoursBefore returns the ReminderHoursBefore field if non-nil, zero value otherwise.

### GetReminderHoursBeforeOk

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) GetReminderHoursBeforeOk() (*int32, bool)`

GetReminderHoursBeforeOk returns a tuple with the ReminderHoursBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReminderHoursBefore

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetReminderHoursBefore(v int32)`

SetReminderHoursBefore sets ReminderHoursBefore field to given value.

### HasReminderHoursBefore

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) HasReminderHoursBefore() bool`

HasReminderHoursBefore returns a boolean if a field has been set.

### SetReminderHoursBeforeNil

`func (o *ConfigureJackpotSettingsForTheOperatorRequest) SetReminderHoursBeforeNil(b bool)`

 SetReminderHoursBeforeNil sets the value for ReminderHoursBefore to be an explicit nil

### UnsetReminderHoursBefore
`func (o *ConfigureJackpotSettingsForTheOperatorRequest) UnsetReminderHoursBefore()`

UnsetReminderHoursBefore ensures that no value is present for ReminderHoursBefore, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


