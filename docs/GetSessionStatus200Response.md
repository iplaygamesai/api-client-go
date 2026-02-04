# GetSessionStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**GetSessionStatus200ResponseData**](GetSessionStatus200ResponseData.md) |  | [optional] 

## Methods

### NewGetSessionStatus200Response

`func NewGetSessionStatus200Response() *GetSessionStatus200Response`

NewGetSessionStatus200Response instantiates a new GetSessionStatus200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetSessionStatus200ResponseWithDefaults

`func NewGetSessionStatus200ResponseWithDefaults() *GetSessionStatus200Response`

NewGetSessionStatus200ResponseWithDefaults instantiates a new GetSessionStatus200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetSessionStatus200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetSessionStatus200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetSessionStatus200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetSessionStatus200Response) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *GetSessionStatus200Response) GetData() GetSessionStatus200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetSessionStatus200Response) GetDataOk() (*GetSessionStatus200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetSessionStatus200Response) SetData(v GetSessionStatus200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *GetSessionStatus200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


