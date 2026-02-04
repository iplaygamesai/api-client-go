# ListExternalGamesForOperatorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Search** | Pointer to **string** | Must not be greater than 255 characters. | [optional] 
**ProducerName** | Pointer to **string** | Must not be greater than 255 characters. | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**PerPage** | Pointer to **int32** | Must be at least 1. Must not be greater than 100. | [optional] 

## Methods

### NewListExternalGamesForOperatorRequest

`func NewListExternalGamesForOperatorRequest() *ListExternalGamesForOperatorRequest`

NewListExternalGamesForOperatorRequest instantiates a new ListExternalGamesForOperatorRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListExternalGamesForOperatorRequestWithDefaults

`func NewListExternalGamesForOperatorRequestWithDefaults() *ListExternalGamesForOperatorRequest`

NewListExternalGamesForOperatorRequestWithDefaults instantiates a new ListExternalGamesForOperatorRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSearch

`func (o *ListExternalGamesForOperatorRequest) GetSearch() string`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *ListExternalGamesForOperatorRequest) GetSearchOk() (*string, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *ListExternalGamesForOperatorRequest) SetSearch(v string)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *ListExternalGamesForOperatorRequest) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### GetProducerName

`func (o *ListExternalGamesForOperatorRequest) GetProducerName() string`

GetProducerName returns the ProducerName field if non-nil, zero value otherwise.

### GetProducerNameOk

`func (o *ListExternalGamesForOperatorRequest) GetProducerNameOk() (*string, bool)`

GetProducerNameOk returns a tuple with the ProducerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducerName

`func (o *ListExternalGamesForOperatorRequest) SetProducerName(v string)`

SetProducerName sets ProducerName field to given value.

### HasProducerName

`func (o *ListExternalGamesForOperatorRequest) HasProducerName() bool`

HasProducerName returns a boolean if a field has been set.

### GetIsActive

`func (o *ListExternalGamesForOperatorRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ListExternalGamesForOperatorRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ListExternalGamesForOperatorRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ListExternalGamesForOperatorRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetPerPage

`func (o *ListExternalGamesForOperatorRequest) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *ListExternalGamesForOperatorRequest) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *ListExternalGamesForOperatorRequest) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *ListExternalGamesForOperatorRequest) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


