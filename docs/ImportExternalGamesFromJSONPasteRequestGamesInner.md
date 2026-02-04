# ImportExternalGamesFromJSONPasteRequestGamesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalGameId** | **string** | Must not be greater than 100 characters. | 
**Name** | **string** | Must not be greater than 255 characters. | 
**ProducerName** | Pointer to **NullableString** | Must not be greater than 255 characters. | [optional] 
**ImageUrl** | Pointer to **NullableString** | Must be a valid URL. Must not be greater than 500 characters. | [optional] 

## Methods

### NewImportExternalGamesFromJSONPasteRequestGamesInner

`func NewImportExternalGamesFromJSONPasteRequestGamesInner(externalGameId string, name string, ) *ImportExternalGamesFromJSONPasteRequestGamesInner`

NewImportExternalGamesFromJSONPasteRequestGamesInner instantiates a new ImportExternalGamesFromJSONPasteRequestGamesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportExternalGamesFromJSONPasteRequestGamesInnerWithDefaults

`func NewImportExternalGamesFromJSONPasteRequestGamesInnerWithDefaults() *ImportExternalGamesFromJSONPasteRequestGamesInner`

NewImportExternalGamesFromJSONPasteRequestGamesInnerWithDefaults instantiates a new ImportExternalGamesFromJSONPasteRequestGamesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalGameId

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetExternalGameId() string`

GetExternalGameId returns the ExternalGameId field if non-nil, zero value otherwise.

### GetExternalGameIdOk

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetExternalGameIdOk() (*string, bool)`

GetExternalGameIdOk returns a tuple with the ExternalGameId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalGameId

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) SetExternalGameId(v string)`

SetExternalGameId sets ExternalGameId field to given value.


### GetName

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) SetName(v string)`

SetName sets Name field to given value.


### GetProducerName

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetProducerName() string`

GetProducerName returns the ProducerName field if non-nil, zero value otherwise.

### GetProducerNameOk

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetProducerNameOk() (*string, bool)`

GetProducerNameOk returns a tuple with the ProducerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerName

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) SetProducerName(v string)`

SetProducerName sets ProducerName field to given value.

### HasProducerName

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) HasProducerName() bool`

HasProducerName returns a boolean if a field has been set.

### SetProducerNameNil

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) SetProducerNameNil(b bool)`

 SetProducerNameNil sets the value for ProducerName to be an explicit nil

### UnsetProducerName
`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) UnsetProducerName()`

UnsetProducerName ensures that no value is present for ProducerName, not even an explicit nil
### GetImageUrl

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *ImportExternalGamesFromJSONPasteRequestGamesInner) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


