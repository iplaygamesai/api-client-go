# ConfigureLiveModeSettingsForAPoolRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsLiveMode** | **bool** |  | 
**LiveModeWindowSeconds** | Pointer to **int32** | Must be at least 10. Must not be greater than 300. | [optional] 

## Methods

### NewConfigureLiveModeSettingsForAPoolRequest

`func NewConfigureLiveModeSettingsForAPoolRequest(isLiveMode bool, ) *ConfigureLiveModeSettingsForAPoolRequest`

NewConfigureLiveModeSettingsForAPoolRequest instantiates a new ConfigureLiveModeSettingsForAPoolRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureLiveModeSettingsForAPoolRequestWithDefaults

`func NewConfigureLiveModeSettingsForAPoolRequestWithDefaults() *ConfigureLiveModeSettingsForAPoolRequest`

NewConfigureLiveModeSettingsForAPoolRequestWithDefaults instantiates a new ConfigureLiveModeSettingsForAPoolRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsLiveMode

`func (o *ConfigureLiveModeSettingsForAPoolRequest) GetIsLiveMode() bool`

GetIsLiveMode returns the IsLiveMode field if non-nil, zero value otherwise.

### GetIsLiveModeOk

`func (o *ConfigureLiveModeSettingsForAPoolRequest) GetIsLiveModeOk() (*bool, bool)`

GetIsLiveModeOk returns a tuple with the IsLiveMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLiveMode

`func (o *ConfigureLiveModeSettingsForAPoolRequest) SetIsLiveMode(v bool)`

SetIsLiveMode sets IsLiveMode field to given value.


### GetLiveModeWindowSeconds

`func (o *ConfigureLiveModeSettingsForAPoolRequest) GetLiveModeWindowSeconds() int32`

GetLiveModeWindowSeconds returns the LiveModeWindowSeconds field if non-nil, zero value otherwise.

### GetLiveModeWindowSecondsOk

`func (o *ConfigureLiveModeSettingsForAPoolRequest) GetLiveModeWindowSecondsOk() (*int32, bool)`

GetLiveModeWindowSecondsOk returns a tuple with the LiveModeWindowSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiveModeWindowSeconds

`func (o *ConfigureLiveModeSettingsForAPoolRequest) SetLiveModeWindowSeconds(v int32)`

SetLiveModeWindowSeconds sets LiveModeWindowSeconds field to given value.

### HasLiveModeWindowSeconds

`func (o *ConfigureLiveModeSettingsForAPoolRequest) HasLiveModeWindowSeconds() bool`

HasLiveModeWindowSeconds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


