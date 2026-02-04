# UpdateAPromotionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Must not be greater than 255 characters. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**ImageUrl** | Pointer to **NullableString** | Must be a valid URL. | [optional] 
**TermsAndConditions** | Pointer to **NullableString** |  | [optional] 
**EndsAt** | Pointer to **NullableString** | Must be a valid date. | [optional] 
**PrizeDistribution** | Pointer to **map[string]interface{}** |  | [optional] 
**TotalPrizePool** | Pointer to **NullableFloat32** | Must be at least 0. | [optional] 
**WinnerCount** | Pointer to **NullableInt32** | Must be at least 1. | [optional] 
**EntryConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**GameFilterEnabled** | Pointer to **NullableBool** |  | [optional] 
**ProducerFilterEnabled** | Pointer to **NullableBool** |  | [optional] 
**WebhookEnabled** | Pointer to **NullableBool** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**IsFeatured** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewUpdateAPromotionRequest

`func NewUpdateAPromotionRequest() *UpdateAPromotionRequest`

NewUpdateAPromotionRequest instantiates a new UpdateAPromotionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAPromotionRequestWithDefaults

`func NewUpdateAPromotionRequestWithDefaults() *UpdateAPromotionRequest`

NewUpdateAPromotionRequestWithDefaults instantiates a new UpdateAPromotionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateAPromotionRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateAPromotionRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateAPromotionRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateAPromotionRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateAPromotionRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateAPromotionRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateAPromotionRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateAPromotionRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *UpdateAPromotionRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *UpdateAPromotionRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetImageUrl

`func (o *UpdateAPromotionRequest) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *UpdateAPromotionRequest) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *UpdateAPromotionRequest) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *UpdateAPromotionRequest) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *UpdateAPromotionRequest) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *UpdateAPromotionRequest) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetTermsAndConditions

`func (o *UpdateAPromotionRequest) GetTermsAndConditions() string`

GetTermsAndConditions returns the TermsAndConditions field if non-nil, zero value otherwise.

### GetTermsAndConditionsOk

`func (o *UpdateAPromotionRequest) GetTermsAndConditionsOk() (*string, bool)`

GetTermsAndConditionsOk returns a tuple with the TermsAndConditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsAndConditions

`func (o *UpdateAPromotionRequest) SetTermsAndConditions(v string)`

SetTermsAndConditions sets TermsAndConditions field to given value.

### HasTermsAndConditions

`func (o *UpdateAPromotionRequest) HasTermsAndConditions() bool`

HasTermsAndConditions returns a boolean if a field has been set.

### SetTermsAndConditionsNil

`func (o *UpdateAPromotionRequest) SetTermsAndConditionsNil(b bool)`

 SetTermsAndConditionsNil sets the value for TermsAndConditions to be an explicit nil

### UnsetTermsAndConditions
`func (o *UpdateAPromotionRequest) UnsetTermsAndConditions()`

UnsetTermsAndConditions ensures that no value is present for TermsAndConditions, not even an explicit nil
### GetEndsAt

`func (o *UpdateAPromotionRequest) GetEndsAt() string`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *UpdateAPromotionRequest) GetEndsAtOk() (*string, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *UpdateAPromotionRequest) SetEndsAt(v string)`

SetEndsAt sets EndsAt field to given value.

### HasEndsAt

`func (o *UpdateAPromotionRequest) HasEndsAt() bool`

HasEndsAt returns a boolean if a field has been set.

### SetEndsAtNil

`func (o *UpdateAPromotionRequest) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *UpdateAPromotionRequest) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil
### GetPrizeDistribution

`func (o *UpdateAPromotionRequest) GetPrizeDistribution() map[string]interface{}`

GetPrizeDistribution returns the PrizeDistribution field if non-nil, zero value otherwise.

### GetPrizeDistributionOk

`func (o *UpdateAPromotionRequest) GetPrizeDistributionOk() (*map[string]interface{}, bool)`

GetPrizeDistributionOk returns a tuple with the PrizeDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrizeDistribution

`func (o *UpdateAPromotionRequest) SetPrizeDistribution(v map[string]interface{})`

SetPrizeDistribution sets PrizeDistribution field to given value.

### HasPrizeDistribution

`func (o *UpdateAPromotionRequest) HasPrizeDistribution() bool`

HasPrizeDistribution returns a boolean if a field has been set.

### SetPrizeDistributionNil

`func (o *UpdateAPromotionRequest) SetPrizeDistributionNil(b bool)`

 SetPrizeDistributionNil sets the value for PrizeDistribution to be an explicit nil

### UnsetPrizeDistribution
`func (o *UpdateAPromotionRequest) UnsetPrizeDistribution()`

UnsetPrizeDistribution ensures that no value is present for PrizeDistribution, not even an explicit nil
### GetTotalPrizePool

`func (o *UpdateAPromotionRequest) GetTotalPrizePool() float32`

GetTotalPrizePool returns the TotalPrizePool field if non-nil, zero value otherwise.

### GetTotalPrizePoolOk

`func (o *UpdateAPromotionRequest) GetTotalPrizePoolOk() (*float32, bool)`

GetTotalPrizePoolOk returns a tuple with the TotalPrizePool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrizePool

`func (o *UpdateAPromotionRequest) SetTotalPrizePool(v float32)`

SetTotalPrizePool sets TotalPrizePool field to given value.

### HasTotalPrizePool

`func (o *UpdateAPromotionRequest) HasTotalPrizePool() bool`

HasTotalPrizePool returns a boolean if a field has been set.

### SetTotalPrizePoolNil

`func (o *UpdateAPromotionRequest) SetTotalPrizePoolNil(b bool)`

 SetTotalPrizePoolNil sets the value for TotalPrizePool to be an explicit nil

### UnsetTotalPrizePool
`func (o *UpdateAPromotionRequest) UnsetTotalPrizePool()`

UnsetTotalPrizePool ensures that no value is present for TotalPrizePool, not even an explicit nil
### GetWinnerCount

`func (o *UpdateAPromotionRequest) GetWinnerCount() int32`

GetWinnerCount returns the WinnerCount field if non-nil, zero value otherwise.

### GetWinnerCountOk

`func (o *UpdateAPromotionRequest) GetWinnerCountOk() (*int32, bool)`

GetWinnerCountOk returns a tuple with the WinnerCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinnerCount

`func (o *UpdateAPromotionRequest) SetWinnerCount(v int32)`

SetWinnerCount sets WinnerCount field to given value.

### HasWinnerCount

`func (o *UpdateAPromotionRequest) HasWinnerCount() bool`

HasWinnerCount returns a boolean if a field has been set.

### SetWinnerCountNil

`func (o *UpdateAPromotionRequest) SetWinnerCountNil(b bool)`

 SetWinnerCountNil sets the value for WinnerCount to be an explicit nil

### UnsetWinnerCount
`func (o *UpdateAPromotionRequest) UnsetWinnerCount()`

UnsetWinnerCount ensures that no value is present for WinnerCount, not even an explicit nil
### GetEntryConfig

`func (o *UpdateAPromotionRequest) GetEntryConfig() map[string]interface{}`

GetEntryConfig returns the EntryConfig field if non-nil, zero value otherwise.

### GetEntryConfigOk

`func (o *UpdateAPromotionRequest) GetEntryConfigOk() (*map[string]interface{}, bool)`

GetEntryConfigOk returns a tuple with the EntryConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryConfig

`func (o *UpdateAPromotionRequest) SetEntryConfig(v map[string]interface{})`

SetEntryConfig sets EntryConfig field to given value.

### HasEntryConfig

`func (o *UpdateAPromotionRequest) HasEntryConfig() bool`

HasEntryConfig returns a boolean if a field has been set.

### SetEntryConfigNil

`func (o *UpdateAPromotionRequest) SetEntryConfigNil(b bool)`

 SetEntryConfigNil sets the value for EntryConfig to be an explicit nil

### UnsetEntryConfig
`func (o *UpdateAPromotionRequest) UnsetEntryConfig()`

UnsetEntryConfig ensures that no value is present for EntryConfig, not even an explicit nil
### GetGameFilterEnabled

`func (o *UpdateAPromotionRequest) GetGameFilterEnabled() bool`

GetGameFilterEnabled returns the GameFilterEnabled field if non-nil, zero value otherwise.

### GetGameFilterEnabledOk

`func (o *UpdateAPromotionRequest) GetGameFilterEnabledOk() (*bool, bool)`

GetGameFilterEnabledOk returns a tuple with the GameFilterEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameFilterEnabled

`func (o *UpdateAPromotionRequest) SetGameFilterEnabled(v bool)`

SetGameFilterEnabled sets GameFilterEnabled field to given value.

### HasGameFilterEnabled

`func (o *UpdateAPromotionRequest) HasGameFilterEnabled() bool`

HasGameFilterEnabled returns a boolean if a field has been set.

### SetGameFilterEnabledNil

`func (o *UpdateAPromotionRequest) SetGameFilterEnabledNil(b bool)`

 SetGameFilterEnabledNil sets the value for GameFilterEnabled to be an explicit nil

### UnsetGameFilterEnabled
`func (o *UpdateAPromotionRequest) UnsetGameFilterEnabled()`

UnsetGameFilterEnabled ensures that no value is present for GameFilterEnabled, not even an explicit nil
### GetProducerFilterEnabled

`func (o *UpdateAPromotionRequest) GetProducerFilterEnabled() bool`

GetProducerFilterEnabled returns the ProducerFilterEnabled field if non-nil, zero value otherwise.

### GetProducerFilterEnabledOk

`func (o *UpdateAPromotionRequest) GetProducerFilterEnabledOk() (*bool, bool)`

GetProducerFilterEnabledOk returns a tuple with the ProducerFilterEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerFilterEnabled

`func (o *UpdateAPromotionRequest) SetProducerFilterEnabled(v bool)`

SetProducerFilterEnabled sets ProducerFilterEnabled field to given value.

### HasProducerFilterEnabled

`func (o *UpdateAPromotionRequest) HasProducerFilterEnabled() bool`

HasProducerFilterEnabled returns a boolean if a field has been set.

### SetProducerFilterEnabledNil

`func (o *UpdateAPromotionRequest) SetProducerFilterEnabledNil(b bool)`

 SetProducerFilterEnabledNil sets the value for ProducerFilterEnabled to be an explicit nil

### UnsetProducerFilterEnabled
`func (o *UpdateAPromotionRequest) UnsetProducerFilterEnabled()`

UnsetProducerFilterEnabled ensures that no value is present for ProducerFilterEnabled, not even an explicit nil
### GetWebhookEnabled

`func (o *UpdateAPromotionRequest) GetWebhookEnabled() bool`

GetWebhookEnabled returns the WebhookEnabled field if non-nil, zero value otherwise.

### GetWebhookEnabledOk

`func (o *UpdateAPromotionRequest) GetWebhookEnabledOk() (*bool, bool)`

GetWebhookEnabledOk returns a tuple with the WebhookEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEnabled

`func (o *UpdateAPromotionRequest) SetWebhookEnabled(v bool)`

SetWebhookEnabled sets WebhookEnabled field to given value.

### HasWebhookEnabled

`func (o *UpdateAPromotionRequest) HasWebhookEnabled() bool`

HasWebhookEnabled returns a boolean if a field has been set.

### SetWebhookEnabledNil

`func (o *UpdateAPromotionRequest) SetWebhookEnabledNil(b bool)`

 SetWebhookEnabledNil sets the value for WebhookEnabled to be an explicit nil

### UnsetWebhookEnabled
`func (o *UpdateAPromotionRequest) UnsetWebhookEnabled()`

UnsetWebhookEnabled ensures that no value is present for WebhookEnabled, not even an explicit nil
### GetIsActive

`func (o *UpdateAPromotionRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateAPromotionRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateAPromotionRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateAPromotionRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *UpdateAPromotionRequest) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *UpdateAPromotionRequest) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetIsFeatured

`func (o *UpdateAPromotionRequest) GetIsFeatured() bool`

GetIsFeatured returns the IsFeatured field if non-nil, zero value otherwise.

### GetIsFeaturedOk

`func (o *UpdateAPromotionRequest) GetIsFeaturedOk() (*bool, bool)`

GetIsFeaturedOk returns a tuple with the IsFeatured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFeatured

`func (o *UpdateAPromotionRequest) SetIsFeatured(v bool)`

SetIsFeatured sets IsFeatured field to given value.

### HasIsFeatured

`func (o *UpdateAPromotionRequest) HasIsFeatured() bool`

HasIsFeatured returns a boolean if a field has been set.

### SetIsFeaturedNil

`func (o *UpdateAPromotionRequest) SetIsFeaturedNil(b bool)`

 SetIsFeaturedNil sets the value for IsFeatured to be an explicit nil

### UnsetIsFeatured
`func (o *UpdateAPromotionRequest) UnsetIsFeatured()`

UnsetIsFeatured ensures that no value is present for IsFeatured, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


