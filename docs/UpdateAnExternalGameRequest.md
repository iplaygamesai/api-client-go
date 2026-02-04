# UpdateAnExternalGameRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalGameId** | Pointer to **string** | Must not be greater than 100 characters. | [optional] 
**Name** | Pointer to **string** | Must not be greater than 255 characters. | [optional] 
**ProducerName** | Pointer to **NullableString** | Must not be greater than 255 characters. | [optional] 
**ImageUrl** | Pointer to **NullableString** | Must be a valid URL. Must not be greater than 500 characters. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdateAnExternalGameRequest

`func NewUpdateAnExternalGameRequest() *UpdateAnExternalGameRequest`

NewUpdateAnExternalGameRequest instantiates a new UpdateAnExternalGameRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAnExternalGameRequestWithDefaults

`func NewUpdateAnExternalGameRequestWithDefaults() *UpdateAnExternalGameRequest`

NewUpdateAnExternalGameRequestWithDefaults instantiates a new UpdateAnExternalGameRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalGameId

`func (o *UpdateAnExternalGameRequest) GetExternalGameId() string`

GetExternalGameId returns the ExternalGameId field if non-nil, zero value otherwise.

### GetExternalGameIdOk

`func (o *UpdateAnExternalGameRequest) GetExternalGameIdOk() (*string, bool)`

GetExternalGameIdOk returns a tuple with the ExternalGameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalGameId

`func (o *UpdateAnExternalGameRequest) SetExternalGameId(v string)`

SetExternalGameId sets ExternalGameId field to given value.

### HasExternalGameId

`func (o *UpdateAnExternalGameRequest) HasExternalGameId() bool`

HasExternalGameId returns a boolean if a field has been set.

### GetName

`func (o *UpdateAnExternalGameRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateAnExternalGameRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateAnExternalGameRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateAnExternalGameRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetProducerName

`func (o *UpdateAnExternalGameRequest) GetProducerName() string`

GetProducerName returns the ProducerName field if non-nil, zero value otherwise.

### GetProducerNameOk

`func (o *UpdateAnExternalGameRequest) GetProducerNameOk() (*string, bool)`

GetProducerNameOk returns a tuple with the ProducerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerName

`func (o *UpdateAnExternalGameRequest) SetProducerName(v string)`

SetProducerName sets ProducerName field to given value.

### HasProducerName

`func (o *UpdateAnExternalGameRequest) HasProducerName() bool`

HasProducerName returns a boolean if a field has been set.

### SetProducerNameNil

`func (o *UpdateAnExternalGameRequest) SetProducerNameNil(b bool)`

 SetProducerNameNil sets the value for ProducerName to be an explicit nil

### UnsetProducerName
`func (o *UpdateAnExternalGameRequest) UnsetProducerName()`

UnsetProducerName ensures that no value is present for ProducerName, not even an explicit nil
### GetImageUrl

`func (o *UpdateAnExternalGameRequest) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *UpdateAnExternalGameRequest) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *UpdateAnExternalGameRequest) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *UpdateAnExternalGameRequest) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *UpdateAnExternalGameRequest) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *UpdateAnExternalGameRequest) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetMetadata

`func (o *UpdateAnExternalGameRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *UpdateAnExternalGameRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *UpdateAnExternalGameRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *UpdateAnExternalGameRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *UpdateAnExternalGameRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *UpdateAnExternalGameRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetIsActive

`func (o *UpdateAnExternalGameRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateAnExternalGameRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateAnExternalGameRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateAnExternalGameRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


