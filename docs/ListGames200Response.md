# ListGames200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ListGames200ResponseDataInner**](ListGames200ResponseDataInner.md) |  | [optional] 
**Meta** | Pointer to [**ListGames200ResponseMeta**](ListGames200ResponseMeta.md) |  | [optional] 

## Methods

### NewListGames200Response

`func NewListGames200Response() *ListGames200Response`

NewListGames200Response instantiates a new ListGames200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListGames200ResponseWithDefaults

`func NewListGames200ResponseWithDefaults() *ListGames200Response`

NewListGames200ResponseWithDefaults instantiates a new ListGames200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListGames200Response) GetData() []ListGames200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListGames200Response) GetDataOk() (*[]ListGames200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListGames200Response) SetData(v []ListGames200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *ListGames200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMeta

`func (o *ListGames200Response) GetMeta() ListGames200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListGames200Response) GetMetaOk() (*ListGames200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListGames200Response) SetMeta(v ListGames200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListGames200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


