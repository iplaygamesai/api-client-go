# CreateATargetedPlayerConfigurationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlayerId** | **string** | Must not be greater than 100 characters. | 
**PoolType** | **string** |  | 
**Currency** | **string** | Must be 3 characters. | 
**ThresholdAmount** | **float32** | Must be at least 1. | 
**ThresholdVariance** | Pointer to **float32** | Must be at least 0. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCreateATargetedPlayerConfigurationRequest

`func NewCreateATargetedPlayerConfigurationRequest(playerId string, poolType string, currency string, thresholdAmount float32, ) *CreateATargetedPlayerConfigurationRequest`

NewCreateATargetedPlayerConfigurationRequest instantiates a new CreateATargetedPlayerConfigurationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateATargetedPlayerConfigurationRequestWithDefaults

`func NewCreateATargetedPlayerConfigurationRequestWithDefaults() *CreateATargetedPlayerConfigurationRequest`

NewCreateATargetedPlayerConfigurationRequestWithDefaults instantiates a new CreateATargetedPlayerConfigurationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlayerId

`func (o *CreateATargetedPlayerConfigurationRequest) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *CreateATargetedPlayerConfigurationRequest) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *CreateATargetedPlayerConfigurationRequest) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetPoolType

`func (o *CreateATargetedPlayerConfigurationRequest) GetPoolType() string`

GetPoolType returns the PoolType field if non-nil, zero value otherwise.

### GetPoolTypeOk

`func (o *CreateATargetedPlayerConfigurationRequest) GetPoolTypeOk() (*string, bool)`

GetPoolTypeOk returns a tuple with the PoolType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoolType

`func (o *CreateATargetedPlayerConfigurationRequest) SetPoolType(v string)`

SetPoolType sets PoolType field to given value.


### GetCurrency

`func (o *CreateATargetedPlayerConfigurationRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateATargetedPlayerConfigurationRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateATargetedPlayerConfigurationRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetThresholdAmount

`func (o *CreateATargetedPlayerConfigurationRequest) GetThresholdAmount() float32`

GetThresholdAmount returns the ThresholdAmount field if non-nil, zero value otherwise.

### GetThresholdAmountOk

`func (o *CreateATargetedPlayerConfigurationRequest) GetThresholdAmountOk() (*float32, bool)`

GetThresholdAmountOk returns a tuple with the ThresholdAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThresholdAmount

`func (o *CreateATargetedPlayerConfigurationRequest) SetThresholdAmount(v float32)`

SetThresholdAmount sets ThresholdAmount field to given value.


### GetThresholdVariance

`func (o *CreateATargetedPlayerConfigurationRequest) GetThresholdVariance() float32`

GetThresholdVariance returns the ThresholdVariance field if non-nil, zero value otherwise.

### GetThresholdVarianceOk

`func (o *CreateATargetedPlayerConfigurationRequest) GetThresholdVarianceOk() (*float32, bool)`

GetThresholdVarianceOk returns a tuple with the ThresholdVariance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThresholdVariance

`func (o *CreateATargetedPlayerConfigurationRequest) SetThresholdVariance(v float32)`

SetThresholdVariance sets ThresholdVariance field to given value.

### HasThresholdVariance

`func (o *CreateATargetedPlayerConfigurationRequest) HasThresholdVariance() bool`

HasThresholdVariance returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateATargetedPlayerConfigurationRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateATargetedPlayerConfigurationRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateATargetedPlayerConfigurationRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateATargetedPlayerConfigurationRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


