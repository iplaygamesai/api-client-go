# CreateASingleExternalGameRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalGameId** | **string** | Must not be greater than 100 characters. | 
**Name** | **string** | Must not be greater than 255 characters. | 
**ProducerName** | Pointer to **NullableString** | Must not be greater than 255 characters. | [optional] 
**ImageUrl** | Pointer to **NullableString** | Must be a valid URL. Must not be greater than 500 characters. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCreateASingleExternalGameRequest

`func NewCreateASingleExternalGameRequest(externalGameId string, name string, ) *CreateASingleExternalGameRequest`

NewCreateASingleExternalGameRequest instantiates a new CreateASingleExternalGameRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateASingleExternalGameRequestWithDefaults

`func NewCreateASingleExternalGameRequestWithDefaults() *CreateASingleExternalGameRequest`

NewCreateASingleExternalGameRequestWithDefaults instantiates a new CreateASingleExternalGameRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalGameId

`func (o *CreateASingleExternalGameRequest) GetExternalGameId() string`

GetExternalGameId returns the ExternalGameId field if non-nil, zero value otherwise.

### GetExternalGameIdOk

`func (o *CreateASingleExternalGameRequest) GetExternalGameIdOk() (*string, bool)`

GetExternalGameIdOk returns a tuple with the ExternalGameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalGameId

`func (o *CreateASingleExternalGameRequest) SetExternalGameId(v string)`

SetExternalGameId sets ExternalGameId field to given value.


### GetName

`func (o *CreateASingleExternalGameRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateASingleExternalGameRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateASingleExternalGameRequest) SetName(v string)`

SetName sets Name field to given value.


### GetProducerName

`func (o *CreateASingleExternalGameRequest) GetProducerName() string`

GetProducerName returns the ProducerName field if non-nil, zero value otherwise.

### GetProducerNameOk

`func (o *CreateASingleExternalGameRequest) GetProducerNameOk() (*string, bool)`

GetProducerNameOk returns a tuple with the ProducerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerName

`func (o *CreateASingleExternalGameRequest) SetProducerName(v string)`

SetProducerName sets ProducerName field to given value.

### HasProducerName

`func (o *CreateASingleExternalGameRequest) HasProducerName() bool`

HasProducerName returns a boolean if a field has been set.

### SetProducerNameNil

`func (o *CreateASingleExternalGameRequest) SetProducerNameNil(b bool)`

 SetProducerNameNil sets the value for ProducerName to be an explicit nil

### UnsetProducerName
`func (o *CreateASingleExternalGameRequest) UnsetProducerName()`

UnsetProducerName ensures that no value is present for ProducerName, not even an explicit nil
### GetImageUrl

`func (o *CreateASingleExternalGameRequest) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *CreateASingleExternalGameRequest) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *CreateASingleExternalGameRequest) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *CreateASingleExternalGameRequest) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *CreateASingleExternalGameRequest) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *CreateASingleExternalGameRequest) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetMetadata

`func (o *CreateASingleExternalGameRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateASingleExternalGameRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateASingleExternalGameRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateASingleExternalGameRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *CreateASingleExternalGameRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *CreateASingleExternalGameRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


