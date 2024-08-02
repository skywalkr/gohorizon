# SmartCardAuthTokens

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | Pointer to **string** | Access Token to be used in API calls. | [optional] 
**Domain** | Pointer to **string** | Domain | [optional] 
**RefreshToken** | Pointer to **string** | Refresh Token to be used to get a new Access token. | [optional] 
**UserName** | Pointer to **string** | User Name | [optional] 

## Methods

### NewSmartCardAuthTokens

`func NewSmartCardAuthTokens() *SmartCardAuthTokens`

NewSmartCardAuthTokens instantiates a new SmartCardAuthTokens object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmartCardAuthTokensWithDefaults

`func NewSmartCardAuthTokensWithDefaults() *SmartCardAuthTokens`

NewSmartCardAuthTokensWithDefaults instantiates a new SmartCardAuthTokens object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *SmartCardAuthTokens) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *SmartCardAuthTokens) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *SmartCardAuthTokens) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.

### HasAccessToken

`func (o *SmartCardAuthTokens) HasAccessToken() bool`

HasAccessToken returns a boolean if a field has been set.

### GetDomain

`func (o *SmartCardAuthTokens) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *SmartCardAuthTokens) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *SmartCardAuthTokens) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *SmartCardAuthTokens) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetRefreshToken

`func (o *SmartCardAuthTokens) GetRefreshToken() string`

GetRefreshToken returns the RefreshToken field if non-nil, zero value otherwise.

### GetRefreshTokenOk

`func (o *SmartCardAuthTokens) GetRefreshTokenOk() (*string, bool)`

GetRefreshTokenOk returns a tuple with the RefreshToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshToken

`func (o *SmartCardAuthTokens) SetRefreshToken(v string)`

SetRefreshToken sets RefreshToken field to given value.

### HasRefreshToken

`func (o *SmartCardAuthTokens) HasRefreshToken() bool`

HasRefreshToken returns a boolean if a field has been set.

### GetUserName

`func (o *SmartCardAuthTokens) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *SmartCardAuthTokens) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *SmartCardAuthTokens) SetUserName(v string)`

SetUserName sets UserName field to given value.

### HasUserName

`func (o *SmartCardAuthTokens) HasUserName() bool`

HasUserName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


