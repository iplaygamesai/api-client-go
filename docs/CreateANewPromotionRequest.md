# CreateANewPromotionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Must not be greater than 255 characters. | 
**Description** | Pointer to **NullableString** |  | [optional] 
**ImageUrl** | Pointer to **NullableString** | Must be a valid URL. | [optional] 
**TermsAndConditions** | Pointer to **NullableString** |  | [optional] 
**PromotionType** | **string** |  | 
**CycleType** | **string** |  | 
**StartsAt** | Pointer to **NullableString** | Must be a valid date. | [optional] 
**EndsAt** | Pointer to **NullableString** | Must be a valid date. Must be a date after &lt;code&gt;starts_at&lt;/code&gt;. | [optional] 
**Timezone** | Pointer to **NullableString** |  | [optional] 
**PrizeDistribution** | Pointer to **map[string]interface{}** |  | [optional] 
**TotalPrizePool** | Pointer to **NullableFloat32** | Must be at least 0. | [optional] 
**PrizeCurrency** | Pointer to **NullableString** | Must be 3 characters. | [optional] 
**WinnerCount** | Pointer to **NullableInt32** | Must be at least 1. | [optional] 
**EntryConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**GameFilterEnabled** | Pointer to **NullableBool** |  | [optional] 
**ProducerFilterEnabled** | Pointer to **NullableBool** |  | [optional] 
**WebhookEnabled** | Pointer to **NullableBool** |  | [optional] 
**IsFeatured** | Pointer to **NullableBool** |  | [optional] 
**GameIds** | Pointer to **[]int32** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the games table. | [optional] 
**ProducerIds** | Pointer to **[]int32** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the producers table. | [optional] 

## Methods

### NewCreateANewPromotionRequest

`func NewCreateANewPromotionRequest(name string, promotionType string, cycleType string, ) *CreateANewPromotionRequest`

NewCreateANewPromotionRequest instantiates a new CreateANewPromotionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateANewPromotionRequestWithDefaults

`func NewCreateANewPromotionRequestWithDefaults() *CreateANewPromotionRequest`

NewCreateANewPromotionRequestWithDefaults instantiates a new CreateANewPromotionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateANewPromotionRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateANewPromotionRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateANewPromotionRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *CreateANewPromotionRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateANewPromotionRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateANewPromotionRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateANewPromotionRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateANewPromotionRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateANewPromotionRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetImageUrl

`func (o *CreateANewPromotionRequest) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CreateANewPromotionRequest) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CreateANewPromotionRequest) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *CreateANewPromotionRequest) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *CreateANewPromotionRequest) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *CreateANewPromotionRequest) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetTermsAndConditions

`func (o *CreateANewPromotionRequest) GetTermsAndConditions() string`

GetTermsAndConditions returns the TermsAndConditions field if non-nil, zero value otherwise.

### GetTermsAndConditionsOk

`func (o *CreateANewPromotionRequest) GetTermsAndConditionsOk() (*string, bool)`

GetTermsAndConditionsOk returns a tuple with the TermsAndConditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsAndConditions

`func (o *CreateANewPromotionRequest) SetTermsAndConditions(v string)`

SetTermsAndConditions sets TermsAndConditions field to given value.

### HasTermsAndConditions

`func (o *CreateANewPromotionRequest) HasTermsAndConditions() bool`

HasTermsAndConditions returns a boolean if a field has been set.

### SetTermsAndConditionsNil

`func (o *CreateANewPromotionRequest) SetTermsAndConditionsNil(b bool)`

 SetTermsAndConditionsNil sets the value for TermsAndConditions to be an explicit nil

### UnsetTermsAndConditions
`func (o *CreateANewPromotionRequest) UnsetTermsAndConditions()`

UnsetTermsAndConditions ensures that no value is present for TermsAndConditions, not even an explicit nil
### GetPromotionType

`func (o *CreateANewPromotionRequest) GetPromotionType() string`

GetPromotionType returns the PromotionType field if non-nil, zero value otherwise.

### GetPromotionTypeOk

`func (o *CreateANewPromotionRequest) GetPromotionTypeOk() (*string, bool)`

GetPromotionTypeOk returns a tuple with the PromotionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromotionType

`func (o *CreateANewPromotionRequest) SetPromotionType(v string)`

SetPromotionType sets PromotionType field to given value.


### GetCycleType

`func (o *CreateANewPromotionRequest) GetCycleType() string`

GetCycleType returns the CycleType field if non-nil, zero value otherwise.

### GetCycleTypeOk

`func (o *CreateANewPromotionRequest) GetCycleTypeOk() (*string, bool)`

GetCycleTypeOk returns a tuple with the CycleType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleType

`func (o *CreateANewPromotionRequest) SetCycleType(v string)`

SetCycleType sets CycleType field to given value.


### GetStartsAt

`func (o *CreateANewPromotionRequest) GetStartsAt() string`

GetStartsAt returns the StartsAt field if non-nil, zero value otherwise.

### GetStartsAtOk

`func (o *CreateANewPromotionRequest) GetStartsAtOk() (*string, bool)`

GetStartsAtOk returns a tuple with the StartsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsAt

`func (o *CreateANewPromotionRequest) SetStartsAt(v string)`

SetStartsAt sets StartsAt field to given value.

### HasStartsAt

`func (o *CreateANewPromotionRequest) HasStartsAt() bool`

HasStartsAt returns a boolean if a field has been set.

### SetStartsAtNil

`func (o *CreateANewPromotionRequest) SetStartsAtNil(b bool)`

 SetStartsAtNil sets the value for StartsAt to be an explicit nil

### UnsetStartsAt
`func (o *CreateANewPromotionRequest) UnsetStartsAt()`

UnsetStartsAt ensures that no value is present for StartsAt, not even an explicit nil
### GetEndsAt

`func (o *CreateANewPromotionRequest) GetEndsAt() string`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *CreateANewPromotionRequest) GetEndsAtOk() (*string, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *CreateANewPromotionRequest) SetEndsAt(v string)`

SetEndsAt sets EndsAt field to given value.

### HasEndsAt

`func (o *CreateANewPromotionRequest) HasEndsAt() bool`

HasEndsAt returns a boolean if a field has been set.

### SetEndsAtNil

`func (o *CreateANewPromotionRequest) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *CreateANewPromotionRequest) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil
### GetTimezone

`func (o *CreateANewPromotionRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *CreateANewPromotionRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *CreateANewPromotionRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *CreateANewPromotionRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### SetTimezoneNil

`func (o *CreateANewPromotionRequest) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *CreateANewPromotionRequest) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil
### GetPrizeDistribution

`func (o *CreateANewPromotionRequest) GetPrizeDistribution() map[string]interface{}`

GetPrizeDistribution returns the PrizeDistribution field if non-nil, zero value otherwise.

### GetPrizeDistributionOk

`func (o *CreateANewPromotionRequest) GetPrizeDistributionOk() (*map[string]interface{}, bool)`

GetPrizeDistributionOk returns a tuple with the PrizeDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrizeDistribution

`func (o *CreateANewPromotionRequest) SetPrizeDistribution(v map[string]interface{})`

SetPrizeDistribution sets PrizeDistribution field to given value.

### HasPrizeDistribution

`func (o *CreateANewPromotionRequest) HasPrizeDistribution() bool`

HasPrizeDistribution returns a boolean if a field has been set.

### SetPrizeDistributionNil

`func (o *CreateANewPromotionRequest) SetPrizeDistributionNil(b bool)`

 SetPrizeDistributionNil sets the value for PrizeDistribution to be an explicit nil

### UnsetPrizeDistribution
`func (o *CreateANewPromotionRequest) UnsetPrizeDistribution()`

UnsetPrizeDistribution ensures that no value is present for PrizeDistribution, not even an explicit nil
### GetTotalPrizePool

`func (o *CreateANewPromotionRequest) GetTotalPrizePool() float32`

GetTotalPrizePool returns the TotalPrizePool field if non-nil, zero value otherwise.

### GetTotalPrizePoolOk

`func (o *CreateANewPromotionRequest) GetTotalPrizePoolOk() (*float32, bool)`

GetTotalPrizePoolOk returns a tuple with the TotalPrizePool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrizePool

`func (o *CreateANewPromotionRequest) SetTotalPrizePool(v float32)`

SetTotalPrizePool sets TotalPrizePool field to given value.

### HasTotalPrizePool

`func (o *CreateANewPromotionRequest) HasTotalPrizePool() bool`

HasTotalPrizePool returns a boolean if a field has been set.

### SetTotalPrizePoolNil

`func (o *CreateANewPromotionRequest) SetTotalPrizePoolNil(b bool)`

 SetTotalPrizePoolNil sets the value for TotalPrizePool to be an explicit nil

### UnsetTotalPrizePool
`func (o *CreateANewPromotionRequest) UnsetTotalPrizePool()`

UnsetTotalPrizePool ensures that no value is present for TotalPrizePool, not even an explicit nil
### GetPrizeCurrency

`func (o *CreateANewPromotionRequest) GetPrizeCurrency() string`

GetPrizeCurrency returns the PrizeCurrency field if non-nil, zero value otherwise.

### GetPrizeCurrencyOk

`func (o *CreateANewPromotionRequest) GetPrizeCurrencyOk() (*string, bool)`

GetPrizeCurrencyOk returns a tuple with the PrizeCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrizeCurrency

`func (o *CreateANewPromotionRequest) SetPrizeCurrency(v string)`

SetPrizeCurrency sets PrizeCurrency field to given value.

### HasPrizeCurrency

`func (o *CreateANewPromotionRequest) HasPrizeCurrency() bool`

HasPrizeCurrency returns a boolean if a field has been set.

### SetPrizeCurrencyNil

`func (o *CreateANewPromotionRequest) SetPrizeCurrencyNil(b bool)`

 SetPrizeCurrencyNil sets the value for PrizeCurrency to be an explicit nil

### UnsetPrizeCurrency
`func (o *CreateANewPromotionRequest) UnsetPrizeCurrency()`

UnsetPrizeCurrency ensures that no value is present for PrizeCurrency, not even an explicit nil
### GetWinnerCount

`func (o *CreateANewPromotionRequest) GetWinnerCount() int32`

GetWinnerCount returns the WinnerCount field if non-nil, zero value otherwise.

### GetWinnerCountOk

`func (o *CreateANewPromotionRequest) GetWinnerCountOk() (*int32, bool)`

GetWinnerCountOk returns a tuple with the WinnerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinnerCount

`func (o *CreateANewPromotionRequest) SetWinnerCount(v int32)`

SetWinnerCount sets WinnerCount field to given value.

### HasWinnerCount

`func (o *CreateANewPromotionRequest) HasWinnerCount() bool`

HasWinnerCount returns a boolean if a field has been set.

### SetWinnerCountNil

`func (o *CreateANewPromotionRequest) SetWinnerCountNil(b bool)`

 SetWinnerCountNil sets the value for WinnerCount to be an explicit nil

### UnsetWinnerCount
`func (o *CreateANewPromotionRequest) UnsetWinnerCount()`

UnsetWinnerCount ensures that no value is present for WinnerCount, not even an explicit nil
### GetEntryConfig

`func (o *CreateANewPromotionRequest) GetEntryConfig() map[string]interface{}`

GetEntryConfig returns the EntryConfig field if non-nil, zero value otherwise.

### GetEntryConfigOk

`func (o *CreateANewPromotionRequest) GetEntryConfigOk() (*map[string]interface{}, bool)`

GetEntryConfigOk returns a tuple with the EntryConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryConfig

`func (o *CreateANewPromotionRequest) SetEntryConfig(v map[string]interface{})`

SetEntryConfig sets EntryConfig field to given value.

### HasEntryConfig

`func (o *CreateANewPromotionRequest) HasEntryConfig() bool`

HasEntryConfig returns a boolean if a field has been set.

### SetEntryConfigNil

`func (o *CreateANewPromotionRequest) SetEntryConfigNil(b bool)`

 SetEntryConfigNil sets the value for EntryConfig to be an explicit nil

### UnsetEntryConfig
`func (o *CreateANewPromotionRequest) UnsetEntryConfig()`

UnsetEntryConfig ensures that no value is present for EntryConfig, not even an explicit nil
### GetGameFilterEnabled

`func (o *CreateANewPromotionRequest) GetGameFilterEnabled() bool`

GetGameFilterEnabled returns the GameFilterEnabled field if non-nil, zero value otherwise.

### GetGameFilterEnabledOk

`func (o *CreateANewPromotionRequest) GetGameFilterEnabledOk() (*bool, bool)`

GetGameFilterEnabledOk returns a tuple with the GameFilterEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameFilterEnabled

`func (o *CreateANewPromotionRequest) SetGameFilterEnabled(v bool)`

SetGameFilterEnabled sets GameFilterEnabled field to given value.

### HasGameFilterEnabled

`func (o *CreateANewPromotionRequest) HasGameFilterEnabled() bool`

HasGameFilterEnabled returns a boolean if a field has been set.

### SetGameFilterEnabledNil

`func (o *CreateANewPromotionRequest) SetGameFilterEnabledNil(b bool)`

 SetGameFilterEnabledNil sets the value for GameFilterEnabled to be an explicit nil

### UnsetGameFilterEnabled
`func (o *CreateANewPromotionRequest) UnsetGameFilterEnabled()`

UnsetGameFilterEnabled ensures that no value is present for GameFilterEnabled, not even an explicit nil
### GetProducerFilterEnabled

`func (o *CreateANewPromotionRequest) GetProducerFilterEnabled() bool`

GetProducerFilterEnabled returns the ProducerFilterEnabled field if non-nil, zero value otherwise.

### GetProducerFilterEnabledOk

`func (o *CreateANewPromotionRequest) GetProducerFilterEnabledOk() (*bool, bool)`

GetProducerFilterEnabledOk returns a tuple with the ProducerFilterEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerFilterEnabled

`func (o *CreateANewPromotionRequest) SetProducerFilterEnabled(v bool)`

SetProducerFilterEnabled sets ProducerFilterEnabled field to given value.

### HasProducerFilterEnabled

`func (o *CreateANewPromotionRequest) HasProducerFilterEnabled() bool`

HasProducerFilterEnabled returns a boolean if a field has been set.

### SetProducerFilterEnabledNil

`func (o *CreateANewPromotionRequest) SetProducerFilterEnabledNil(b bool)`

 SetProducerFilterEnabledNil sets the value for ProducerFilterEnabled to be an explicit nil

### UnsetProducerFilterEnabled
`func (o *CreateANewPromotionRequest) UnsetProducerFilterEnabled()`

UnsetProducerFilterEnabled ensures that no value is present for ProducerFilterEnabled, not even an explicit nil
### GetWebhookEnabled

`func (o *CreateANewPromotionRequest) GetWebhookEnabled() bool`

GetWebhookEnabled returns the WebhookEnabled field if non-nil, zero value otherwise.

### GetWebhookEnabledOk

`func (o *CreateANewPromotionRequest) GetWebhookEnabledOk() (*bool, bool)`

GetWebhookEnabledOk returns a tuple with the WebhookEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEnabled

`func (o *CreateANewPromotionRequest) SetWebhookEnabled(v bool)`

SetWebhookEnabled sets WebhookEnabled field to given value.

### HasWebhookEnabled

`func (o *CreateANewPromotionRequest) HasWebhookEnabled() bool`

HasWebhookEnabled returns a boolean if a field has been set.

### SetWebhookEnabledNil

`func (o *CreateANewPromotionRequest) SetWebhookEnabledNil(b bool)`

 SetWebhookEnabledNil sets the value for WebhookEnabled to be an explicit nil

### UnsetWebhookEnabled
`func (o *CreateANewPromotionRequest) UnsetWebhookEnabled()`

UnsetWebhookEnabled ensures that no value is present for WebhookEnabled, not even an explicit nil
### GetIsFeatured

`func (o *CreateANewPromotionRequest) GetIsFeatured() bool`

GetIsFeatured returns the IsFeatured field if non-nil, zero value otherwise.

### GetIsFeaturedOk

`func (o *CreateANewPromotionRequest) GetIsFeaturedOk() (*bool, bool)`

GetIsFeaturedOk returns a tuple with the IsFeatured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFeatured

`func (o *CreateANewPromotionRequest) SetIsFeatured(v bool)`

SetIsFeatured sets IsFeatured field to given value.

### HasIsFeatured

`func (o *CreateANewPromotionRequest) HasIsFeatured() bool`

HasIsFeatured returns a boolean if a field has been set.

### SetIsFeaturedNil

`func (o *CreateANewPromotionRequest) SetIsFeaturedNil(b bool)`

 SetIsFeaturedNil sets the value for IsFeatured to be an explicit nil

### UnsetIsFeatured
`func (o *CreateANewPromotionRequest) UnsetIsFeatured()`

UnsetIsFeatured ensures that no value is present for IsFeatured, not even an explicit nil
### GetGameIds

`func (o *CreateANewPromotionRequest) GetGameIds() []int32`

GetGameIds returns the GameIds field if non-nil, zero value otherwise.

### GetGameIdsOk

`func (o *CreateANewPromotionRequest) GetGameIdsOk() (*[]int32, bool)`

GetGameIdsOk returns a tuple with the GameIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameIds

`func (o *CreateANewPromotionRequest) SetGameIds(v []int32)`

SetGameIds sets GameIds field to given value.

### HasGameIds

`func (o *CreateANewPromotionRequest) HasGameIds() bool`

HasGameIds returns a boolean if a field has been set.

### GetProducerIds

`func (o *CreateANewPromotionRequest) GetProducerIds() []int32`

GetProducerIds returns the ProducerIds field if non-nil, zero value otherwise.

### GetProducerIdsOk

`func (o *CreateANewPromotionRequest) GetProducerIdsOk() (*[]int32, bool)`

GetProducerIdsOk returns a tuple with the ProducerIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerIds

`func (o *CreateANewPromotionRequest) SetProducerIds(v []int32)`

SetProducerIds sets ProducerIds field to given value.

### HasProducerIds

`func (o *CreateANewPromotionRequest) HasProducerIds() bool`

HasProducerIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


