# GetMultiSessionStatus200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**TotalGames** | Pointer to **int32** |  | [optional] 
**ActiveSessions** | Pointer to **int32** |  | [optional] 
**CurrentIndex** | Pointer to **int32** |  | [optional] 
**Games** | Pointer to [**[]GetMultiSessionStatus200ResponseDataGamesInner**](GetMultiSessionStatus200ResponseDataGamesInner.md) |  | [optional] 
**ExpiresAt** | Pointer to **string** |  | [optional] 

## Methods

### NewGetMultiSessionStatus200ResponseData

`func NewGetMultiSessionStatus200ResponseData() *GetMultiSessionStatus200ResponseData`

NewGetMultiSessionStatus200ResponseData instantiates a new GetMultiSessionStatus200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetMultiSessionStatus200ResponseDataWithDefaults

`func NewGetMultiSessionStatus200ResponseDataWithDefaults() *GetMultiSessionStatus200ResponseData`

NewGetMultiSessionStatus200ResponseDataWithDefaults instantiates a new GetMultiSessionStatus200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *GetMultiSessionStatus200ResponseData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetMultiSessionStatus200ResponseData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetMultiSessionStatus200ResponseData) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GetMultiSessionStatus200ResponseData) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotalGames

`func (o *GetMultiSessionStatus200ResponseData) GetTotalGames() int32`

GetTotalGames returns the TotalGames field if non-nil, zero value otherwise.

### GetTotalGamesOk

`func (o *GetMultiSessionStatus200ResponseData) GetTotalGamesOk() (*int32, bool)`

GetTotalGamesOk returns a tuple with the TotalGames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGames

`func (o *GetMultiSessionStatus200ResponseData) SetTotalGames(v int32)`

SetTotalGames sets TotalGames field to given value.

### HasTotalGames

`func (o *GetMultiSessionStatus200ResponseData) HasTotalGames() bool`

HasTotalGames returns a boolean if a field has been set.

### GetActiveSessions

`func (o *GetMultiSessionStatus200ResponseData) GetActiveSessions() int32`

GetActiveSessions returns the ActiveSessions field if non-nil, zero value otherwise.

### GetActiveSessionsOk

`func (o *GetMultiSessionStatus200ResponseData) GetActiveSessionsOk() (*int32, bool)`

GetActiveSessionsOk returns a tuple with the ActiveSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveSessions

`func (o *GetMultiSessionStatus200ResponseData) SetActiveSessions(v int32)`

SetActiveSessions sets ActiveSessions field to given value.

### HasActiveSessions

`func (o *GetMultiSessionStatus200ResponseData) HasActiveSessions() bool`

HasActiveSessions returns a boolean if a field has been set.

### GetCurrentIndex

`func (o *GetMultiSessionStatus200ResponseData) GetCurrentIndex() int32`

GetCurrentIndex returns the CurrentIndex field if non-nil, zero value otherwise.

### GetCurrentIndexOk

`func (o *GetMultiSessionStatus200ResponseData) GetCurrentIndexOk() (*int32, bool)`

GetCurrentIndexOk returns a tuple with the CurrentIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentIndex

`func (o *GetMultiSessionStatus200ResponseData) SetCurrentIndex(v int32)`

SetCurrentIndex sets CurrentIndex field to given value.

### HasCurrentIndex

`func (o *GetMultiSessionStatus200ResponseData) HasCurrentIndex() bool`

HasCurrentIndex returns a boolean if a field has been set.

### GetGames

`func (o *GetMultiSessionStatus200ResponseData) GetGames() []GetMultiSessionStatus200ResponseDataGamesInner`

GetGames returns the Games field if non-nil, zero value otherwise.

### GetGamesOk

`func (o *GetMultiSessionStatus200ResponseData) GetGamesOk() (*[]GetMultiSessionStatus200ResponseDataGamesInner, bool)`

GetGamesOk returns a tuple with the Games field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGames

`func (o *GetMultiSessionStatus200ResponseData) SetGames(v []GetMultiSessionStatus200ResponseDataGamesInner)`

SetGames sets Games field to given value.

### HasGames

`func (o *GetMultiSessionStatus200ResponseData) HasGames() bool`

HasGames returns a boolean if a field has been set.

### GetExpiresAt

`func (o *GetMultiSessionStatus200ResponseData) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *GetMultiSessionStatus200ResponseData) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *GetMultiSessionStatus200ResponseData) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *GetMultiSessionStatus200ResponseData) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


