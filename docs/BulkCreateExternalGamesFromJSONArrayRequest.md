# BulkCreateExternalGamesFromJSONArrayRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Games** | [**[]CreateASingleExternalGameRequest**](CreateASingleExternalGameRequest.md) | Must have at least 1 items. Must not have more than 1000 items. | 

## Methods

### NewBulkCreateExternalGamesFromJSONArrayRequest

`func NewBulkCreateExternalGamesFromJSONArrayRequest(games []CreateASingleExternalGameRequest, ) *BulkCreateExternalGamesFromJSONArrayRequest`

NewBulkCreateExternalGamesFromJSONArrayRequest instantiates a new BulkCreateExternalGamesFromJSONArrayRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkCreateExternalGamesFromJSONArrayRequestWithDefaults

`func NewBulkCreateExternalGamesFromJSONArrayRequestWithDefaults() *BulkCreateExternalGamesFromJSONArrayRequest`

NewBulkCreateExternalGamesFromJSONArrayRequestWithDefaults instantiates a new BulkCreateExternalGamesFromJSONArrayRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGames

`func (o *BulkCreateExternalGamesFromJSONArrayRequest) GetGames() []CreateASingleExternalGameRequest`

GetGames returns the Games field if non-nil, zero value otherwise.

### GetGamesOk

`func (o *BulkCreateExternalGamesFromJSONArrayRequest) GetGamesOk() (*[]CreateASingleExternalGameRequest, bool)`

GetGamesOk returns a tuple with the Games field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGames

`func (o *BulkCreateExternalGamesFromJSONArrayRequest) SetGames(v []CreateASingleExternalGameRequest)`

SetGames sets Games field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


