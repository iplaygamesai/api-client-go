# ListGamesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Search** | Pointer to **NullableString** | Must not be greater than 255 characters. | [optional] 
**ProducerId** | Pointer to **NullableInt32** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the game_producers table. | [optional] 
**Provider** | Pointer to **NullableString** | The &lt;code&gt;slug&lt;/code&gt; of an existing record in the providers table. | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**PerPage** | Pointer to **NullableString** | Must match the regex /^(all. | [optional] 

## Methods

### NewListGamesRequest

`func NewListGamesRequest() *ListGamesRequest`

NewListGamesRequest instantiates a new ListGamesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListGamesRequestWithDefaults

`func NewListGamesRequestWithDefaults() *ListGamesRequest`

NewListGamesRequestWithDefaults instantiates a new ListGamesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSearch

`func (o *ListGamesRequest) GetSearch() string`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *ListGamesRequest) GetSearchOk() (*string, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *ListGamesRequest) SetSearch(v string)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *ListGamesRequest) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### SetSearchNil

`func (o *ListGamesRequest) SetSearchNil(b bool)`

 SetSearchNil sets the value for Search to be an explicit nil

### UnsetSearch
`func (o *ListGamesRequest) UnsetSearch()`

UnsetSearch ensures that no value is present for Search, not even an explicit nil
### GetProducerId

`func (o *ListGamesRequest) GetProducerId() int32`

GetProducerId returns the ProducerId field if non-nil, zero value otherwise.

### GetProducerIdOk

`func (o *ListGamesRequest) GetProducerIdOk() (*int32, bool)`

GetProducerIdOk returns a tuple with the ProducerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerId

`func (o *ListGamesRequest) SetProducerId(v int32)`

SetProducerId sets ProducerId field to given value.

### HasProducerId

`func (o *ListGamesRequest) HasProducerId() bool`

HasProducerId returns a boolean if a field has been set.

### SetProducerIdNil

`func (o *ListGamesRequest) SetProducerIdNil(b bool)`

 SetProducerIdNil sets the value for ProducerId to be an explicit nil

### UnsetProducerId
`func (o *ListGamesRequest) UnsetProducerId()`

UnsetProducerId ensures that no value is present for ProducerId, not even an explicit nil
### GetProvider

`func (o *ListGamesRequest) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ListGamesRequest) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ListGamesRequest) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *ListGamesRequest) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *ListGamesRequest) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *ListGamesRequest) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetType

`func (o *ListGamesRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ListGamesRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ListGamesRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ListGamesRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *ListGamesRequest) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *ListGamesRequest) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetPerPage

`func (o *ListGamesRequest) GetPerPage() string`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ListGamesRequest) GetPerPageOk() (*string, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ListGamesRequest) SetPerPage(v string)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *ListGamesRequest) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### SetPerPageNil

`func (o *ListGamesRequest) SetPerPageNil(b bool)`

 SetPerPageNil sets the value for PerPage to be an explicit nil

### UnsetPerPage
`func (o *ListGamesRequest) UnsetPerPage()`

UnsetPerPage ensures that no value is present for PerPage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


