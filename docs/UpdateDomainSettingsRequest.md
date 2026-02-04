# UpdateDomainSettingsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsActive** | Pointer to **NullableBool** | optional Whether the domain is active. | [optional] 
**AllowedWidgets** | Pointer to **[]string** | optional List of allowed widget types. | [optional] 

## Methods

### NewUpdateDomainSettingsRequest

`func NewUpdateDomainSettingsRequest() *UpdateDomainSettingsRequest`

NewUpdateDomainSettingsRequest instantiates a new UpdateDomainSettingsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDomainSettingsRequestWithDefaults

`func NewUpdateDomainSettingsRequestWithDefaults() *UpdateDomainSettingsRequest`

NewUpdateDomainSettingsRequestWithDefaults instantiates a new UpdateDomainSettingsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsActive

`func (o *UpdateDomainSettingsRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateDomainSettingsRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateDomainSettingsRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateDomainSettingsRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *UpdateDomainSettingsRequest) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *UpdateDomainSettingsRequest) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetAllowedWidgets

`func (o *UpdateDomainSettingsRequest) GetAllowedWidgets() []string`

GetAllowedWidgets returns the AllowedWidgets field if non-nil, zero value otherwise.

### GetAllowedWidgetsOk

`func (o *UpdateDomainSettingsRequest) GetAllowedWidgetsOk() (*[]string, bool)`

GetAllowedWidgetsOk returns a tuple with the AllowedWidgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedWidgets

`func (o *UpdateDomainSettingsRequest) SetAllowedWidgets(v []string)`

SetAllowedWidgets sets AllowedWidgets field to given value.

### HasAllowedWidgets

`func (o *UpdateDomainSettingsRequest) HasAllowedWidgets() bool`

HasAllowedWidgets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


