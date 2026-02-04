# ListGames200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Producer** | Pointer to **string** |  | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**ImageUrl** | Pointer to **string** |  | [optional] 
**CurrenciesSupported** | Pointer to **[]string** |  | [optional] 
**CountriesSupported** | Pointer to **[]string** |  | [optional] 
**HasDemo** | Pointer to **bool** |  | [optional] 
**HasFreespins** | Pointer to **bool** |  | [optional] 

## Methods

### NewListGames200ResponseDataInner

`func NewListGames200ResponseDataInner() *ListGames200ResponseDataInner`

NewListGames200ResponseDataInner instantiates a new ListGames200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListGames200ResponseDataInnerWithDefaults

`func NewListGames200ResponseDataInnerWithDefaults() *ListGames200ResponseDataInner`

NewListGames200ResponseDataInnerWithDefaults instantiates a new ListGames200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListGames200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListGames200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListGames200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ListGames200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *ListGames200ResponseDataInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ListGames200ResponseDataInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ListGames200ResponseDataInner) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ListGames200ResponseDataInner) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetProducer

`func (o *ListGames200ResponseDataInner) GetProducer() string`

GetProducer returns the Producer field if non-nil, zero value otherwise.

### GetProducerOk

`func (o *ListGames200ResponseDataInner) GetProducerOk() (*string, bool)`

GetProducerOk returns a tuple with the Producer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducer

`func (o *ListGames200ResponseDataInner) SetProducer(v string)`

SetProducer sets Producer field to given value.

### HasProducer

`func (o *ListGames200ResponseDataInner) HasProducer() bool`

HasProducer returns a boolean if a field has been set.

### GetCategory

`func (o *ListGames200ResponseDataInner) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *ListGames200ResponseDataInner) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *ListGames200ResponseDataInner) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *ListGames200ResponseDataInner) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetType

`func (o *ListGames200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListGames200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListGames200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ListGames200ResponseDataInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetImageUrl

`func (o *ListGames200ResponseDataInner) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *ListGames200ResponseDataInner) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *ListGames200ResponseDataInner) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *ListGames200ResponseDataInner) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetCurrenciesSupported

`func (o *ListGames200ResponseDataInner) GetCurrenciesSupported() []string`

GetCurrenciesSupported returns the CurrenciesSupported field if non-nil, zero value otherwise.

### GetCurrenciesSupportedOk

`func (o *ListGames200ResponseDataInner) GetCurrenciesSupportedOk() (*[]string, bool)`

GetCurrenciesSupportedOk returns a tuple with the CurrenciesSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrenciesSupported

`func (o *ListGames200ResponseDataInner) SetCurrenciesSupported(v []string)`

SetCurrenciesSupported sets CurrenciesSupported field to given value.

### HasCurrenciesSupported

`func (o *ListGames200ResponseDataInner) HasCurrenciesSupported() bool`

HasCurrenciesSupported returns a boolean if a field has been set.

### GetCountriesSupported

`func (o *ListGames200ResponseDataInner) GetCountriesSupported() []string`

GetCountriesSupported returns the CountriesSupported field if non-nil, zero value otherwise.

### GetCountriesSupportedOk

`func (o *ListGames200ResponseDataInner) GetCountriesSupportedOk() (*[]string, bool)`

GetCountriesSupportedOk returns a tuple with the CountriesSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesSupported

`func (o *ListGames200ResponseDataInner) SetCountriesSupported(v []string)`

SetCountriesSupported sets CountriesSupported field to given value.

### HasCountriesSupported

`func (o *ListGames200ResponseDataInner) HasCountriesSupported() bool`

HasCountriesSupported returns a boolean if a field has been set.

### GetHasDemo

`func (o *ListGames200ResponseDataInner) GetHasDemo() bool`

GetHasDemo returns the HasDemo field if non-nil, zero value otherwise.

### GetHasDemoOk

`func (o *ListGames200ResponseDataInner) GetHasDemoOk() (*bool, bool)`

GetHasDemoOk returns a tuple with the HasDemo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDemo

`func (o *ListGames200ResponseDataInner) SetHasDemo(v bool)`

SetHasDemo sets HasDemo field to given value.

### HasHasDemo

`func (o *ListGames200ResponseDataInner) HasHasDemo() bool`

HasHasDemo returns a boolean if a field has been set.

### GetHasFreespins

`func (o *ListGames200ResponseDataInner) GetHasFreespins() bool`

GetHasFreespins returns the HasFreespins field if non-nil, zero value otherwise.

### GetHasFreespinsOk

`func (o *ListGames200ResponseDataInner) GetHasFreespinsOk() (*bool, bool)`

GetHasFreespinsOk returns a tuple with the HasFreespins field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasFreespins

`func (o *ListGames200ResponseDataInner) SetHasFreespins(v bool)`

SetHasFreespins sets HasFreespins field to given value.

### HasHasFreespins

`func (o *ListGames200ResponseDataInner) HasHasFreespins() bool`

HasHasFreespins returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


