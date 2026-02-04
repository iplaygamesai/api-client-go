# ImportExternalGamesFromJSONPasteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Games** | [**[]ImportExternalGamesFromJSONPasteRequestGamesInner**](ImportExternalGamesFromJSONPasteRequestGamesInner.md) | Must have at least 1 items. Must not have more than 1000 items. | 

## Methods

### NewImportExternalGamesFromJSONPasteRequest

`func NewImportExternalGamesFromJSONPasteRequest(games []ImportExternalGamesFromJSONPasteRequestGamesInner, ) *ImportExternalGamesFromJSONPasteRequest`

NewImportExternalGamesFromJSONPasteRequest instantiates a new ImportExternalGamesFromJSONPasteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportExternalGamesFromJSONPasteRequestWithDefaults

`func NewImportExternalGamesFromJSONPasteRequestWithDefaults() *ImportExternalGamesFromJSONPasteRequest`

NewImportExternalGamesFromJSONPasteRequestWithDefaults instantiates a new ImportExternalGamesFromJSONPasteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGames

`func (o *ImportExternalGamesFromJSONPasteRequest) GetGames() []ImportExternalGamesFromJSONPasteRequestGamesInner`

GetGames returns the Games field if non-nil, zero value otherwise.

### GetGamesOk

`func (o *ImportExternalGamesFromJSONPasteRequest) GetGamesOk() (*[]ImportExternalGamesFromJSONPasteRequestGamesInner, bool)`

GetGamesOk returns a tuple with the Games field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGames

`func (o *ImportExternalGamesFromJSONPasteRequest) SetGames(v []ImportExternalGamesFromJSONPasteRequestGamesInner)`

SetGames sets Games field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


