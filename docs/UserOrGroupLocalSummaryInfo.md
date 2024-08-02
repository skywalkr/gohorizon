# UserOrGroupLocalSummaryInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationEntitlements** | Pointer to **[]string** | Local application entitlements for this user or group. | [optional] 
**ApplicationLocalSessionIds** | Pointer to **[]string** | Ids for local application sessions for this user. | [optional] 
**ApplicationPoolIds** | Pointer to **[]string** | Local application IDs for which this user has an entitlement. | [optional] 
**Container** | Pointer to **string** | AD container for this user or group. | [optional] 
**Description** | Pointer to **string** | Description number of this user or group. Supported Filters : &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;Contains&#39;. | [optional] 
**DesktopEntitlements** | Pointer to **[]string** | Local desktop entitlements for this user or group. | [optional] 
**DesktopLocalSessionIds** | Pointer to **[]string** | Ids for local desktop sessions for this user. | [optional] 
**DesktopPoolIds** | Pointer to **[]string** | Local desktop IDs for which this user has an entitlement. | [optional] 
**DisplayName** | Pointer to **string** | Login name with domain of this user or group. | [optional] 
**DistinguishedName** | Pointer to **string** | Active Directory distinguished name for this user or group. | [optional] 
**Domain** | Pointer to **string** | DNS name of the domain in which this user or group belongs. Supported Filters : &#39;Equals&#39;.  Also, if &#39;Or&#39; filter is used anywhere in filter string for this model class, then that &#39;Or&#39; filter should nest only &#39;Equals&#39; filter on &#39;domain&#39; or &#39;id&#39; field. | [optional] 
**Email** | Pointer to **string** | Email address of this user or group. Supported Filters : &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;Contains&#39;. | [optional] 
**FirstName** | Pointer to **string** | First name of this user or group. | [optional] 
**Group** | Pointer to **bool** | Indicates if this object represents a group. This field is NOT supported in filter string. To use any filter on &#39;group&#39;, use &#39;group_only&#39; query param directly. | [optional] 
**HeldUser** | Pointer to **bool** | Indicates if this user is a \&quot;held user\&quot;. Supported Filters : &#39;Equals&#39;. | [optional] 
**Id** | Pointer to **string** | Unique SID representing this AD User or Group. Supported Filters : &#39;Equals&#39;.&#39;Or&#39; filter chain of &#39;Equals&#39; filter can be used to query for more than one id. For this model, if &#39;Or&#39; filter is used, then it should nest only &#39;Equals&#39; filter on &#39;domain&#39; or &#39;id&#39; field. | [optional] 
**KioskUser** | Pointer to **bool** | Indicates if this user or group is a \&quot;kiosk user\&quot; that supports client authentication. Client authentication is the process of supporting client devices directly logging into resources. | [optional] 
**LastName** | Pointer to **string** | Last name of this user or group. | [optional] 
**LoginName** | Pointer to **string** | Login name of this user or group.  Supported Filters : &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;Contains&#39;. | [optional] 
**LongDisplayName** | Pointer to **string** | Login name, domain and name for this user or group, else display name | [optional] 
**MachineIds** | Pointer to **[]string** | Machines this user or group is assigned to. | [optional] 
**Name** | Pointer to **string** | Name of this user or group.  Supported Filters : &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;Contains&#39;. | [optional] 
**Phone** | Pointer to **string** | Phone number of this user. Supported Filters : &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;Contains&#39;. | [optional] 
**UnauthenticatedAccessUser** | Pointer to **bool** | Whether or not this is unauthenticated access user. | [optional] 
**UserDisplayName** | Pointer to **string** | User or group&#39;s display name. This corresponds with displayName attribute in AD. | [optional] 
**UserPrincipalName** | Pointer to **string** | User Principal name(UPN) of this user. Supported Filters : &#39;Equals&#39;, &#39;StartsWith&#39;, &#39;Contains&#39;. | [optional] 

## Methods

### NewUserOrGroupLocalSummaryInfo

`func NewUserOrGroupLocalSummaryInfo() *UserOrGroupLocalSummaryInfo`

NewUserOrGroupLocalSummaryInfo instantiates a new UserOrGroupLocalSummaryInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserOrGroupLocalSummaryInfoWithDefaults

`func NewUserOrGroupLocalSummaryInfoWithDefaults() *UserOrGroupLocalSummaryInfo`

NewUserOrGroupLocalSummaryInfoWithDefaults instantiates a new UserOrGroupLocalSummaryInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationEntitlements

`func (o *UserOrGroupLocalSummaryInfo) GetApplicationEntitlements() []string`

GetApplicationEntitlements returns the ApplicationEntitlements field if non-nil, zero value otherwise.

### GetApplicationEntitlementsOk

`func (o *UserOrGroupLocalSummaryInfo) GetApplicationEntitlementsOk() (*[]string, bool)`

GetApplicationEntitlementsOk returns a tuple with the ApplicationEntitlements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationEntitlements

`func (o *UserOrGroupLocalSummaryInfo) SetApplicationEntitlements(v []string)`

SetApplicationEntitlements sets ApplicationEntitlements field to given value.

### HasApplicationEntitlements

`func (o *UserOrGroupLocalSummaryInfo) HasApplicationEntitlements() bool`

HasApplicationEntitlements returns a boolean if a field has been set.

### GetApplicationLocalSessionIds

`func (o *UserOrGroupLocalSummaryInfo) GetApplicationLocalSessionIds() []string`

GetApplicationLocalSessionIds returns the ApplicationLocalSessionIds field if non-nil, zero value otherwise.

### GetApplicationLocalSessionIdsOk

`func (o *UserOrGroupLocalSummaryInfo) GetApplicationLocalSessionIdsOk() (*[]string, bool)`

GetApplicationLocalSessionIdsOk returns a tuple with the ApplicationLocalSessionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationLocalSessionIds

`func (o *UserOrGroupLocalSummaryInfo) SetApplicationLocalSessionIds(v []string)`

SetApplicationLocalSessionIds sets ApplicationLocalSessionIds field to given value.

### HasApplicationLocalSessionIds

`func (o *UserOrGroupLocalSummaryInfo) HasApplicationLocalSessionIds() bool`

HasApplicationLocalSessionIds returns a boolean if a field has been set.

### GetApplicationPoolIds

`func (o *UserOrGroupLocalSummaryInfo) GetApplicationPoolIds() []string`

GetApplicationPoolIds returns the ApplicationPoolIds field if non-nil, zero value otherwise.

### GetApplicationPoolIdsOk

`func (o *UserOrGroupLocalSummaryInfo) GetApplicationPoolIdsOk() (*[]string, bool)`

GetApplicationPoolIdsOk returns a tuple with the ApplicationPoolIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationPoolIds

`func (o *UserOrGroupLocalSummaryInfo) SetApplicationPoolIds(v []string)`

SetApplicationPoolIds sets ApplicationPoolIds field to given value.

### HasApplicationPoolIds

`func (o *UserOrGroupLocalSummaryInfo) HasApplicationPoolIds() bool`

HasApplicationPoolIds returns a boolean if a field has been set.

### GetContainer

`func (o *UserOrGroupLocalSummaryInfo) GetContainer() string`

GetContainer returns the Container field if non-nil, zero value otherwise.

### GetContainerOk

`func (o *UserOrGroupLocalSummaryInfo) GetContainerOk() (*string, bool)`

GetContainerOk returns a tuple with the Container field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainer

`func (o *UserOrGroupLocalSummaryInfo) SetContainer(v string)`

SetContainer sets Container field to given value.

### HasContainer

`func (o *UserOrGroupLocalSummaryInfo) HasContainer() bool`

HasContainer returns a boolean if a field has been set.

### GetDescription

`func (o *UserOrGroupLocalSummaryInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UserOrGroupLocalSummaryInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UserOrGroupLocalSummaryInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UserOrGroupLocalSummaryInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDesktopEntitlements

`func (o *UserOrGroupLocalSummaryInfo) GetDesktopEntitlements() []string`

GetDesktopEntitlements returns the DesktopEntitlements field if non-nil, zero value otherwise.

### GetDesktopEntitlementsOk

`func (o *UserOrGroupLocalSummaryInfo) GetDesktopEntitlementsOk() (*[]string, bool)`

GetDesktopEntitlementsOk returns a tuple with the DesktopEntitlements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopEntitlements

`func (o *UserOrGroupLocalSummaryInfo) SetDesktopEntitlements(v []string)`

SetDesktopEntitlements sets DesktopEntitlements field to given value.

### HasDesktopEntitlements

`func (o *UserOrGroupLocalSummaryInfo) HasDesktopEntitlements() bool`

HasDesktopEntitlements returns a boolean if a field has been set.

### GetDesktopLocalSessionIds

`func (o *UserOrGroupLocalSummaryInfo) GetDesktopLocalSessionIds() []string`

GetDesktopLocalSessionIds returns the DesktopLocalSessionIds field if non-nil, zero value otherwise.

### GetDesktopLocalSessionIdsOk

`func (o *UserOrGroupLocalSummaryInfo) GetDesktopLocalSessionIdsOk() (*[]string, bool)`

GetDesktopLocalSessionIdsOk returns a tuple with the DesktopLocalSessionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopLocalSessionIds

`func (o *UserOrGroupLocalSummaryInfo) SetDesktopLocalSessionIds(v []string)`

SetDesktopLocalSessionIds sets DesktopLocalSessionIds field to given value.

### HasDesktopLocalSessionIds

`func (o *UserOrGroupLocalSummaryInfo) HasDesktopLocalSessionIds() bool`

HasDesktopLocalSessionIds returns a boolean if a field has been set.

### GetDesktopPoolIds

`func (o *UserOrGroupLocalSummaryInfo) GetDesktopPoolIds() []string`

GetDesktopPoolIds returns the DesktopPoolIds field if non-nil, zero value otherwise.

### GetDesktopPoolIdsOk

`func (o *UserOrGroupLocalSummaryInfo) GetDesktopPoolIdsOk() (*[]string, bool)`

GetDesktopPoolIdsOk returns a tuple with the DesktopPoolIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopPoolIds

`func (o *UserOrGroupLocalSummaryInfo) SetDesktopPoolIds(v []string)`

SetDesktopPoolIds sets DesktopPoolIds field to given value.

### HasDesktopPoolIds

`func (o *UserOrGroupLocalSummaryInfo) HasDesktopPoolIds() bool`

HasDesktopPoolIds returns a boolean if a field has been set.

### GetDisplayName

`func (o *UserOrGroupLocalSummaryInfo) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *UserOrGroupLocalSummaryInfo) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *UserOrGroupLocalSummaryInfo) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetDistinguishedName

`func (o *UserOrGroupLocalSummaryInfo) GetDistinguishedName() string`

GetDistinguishedName returns the DistinguishedName field if non-nil, zero value otherwise.

### GetDistinguishedNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetDistinguishedNameOk() (*string, bool)`

GetDistinguishedNameOk returns a tuple with the DistinguishedName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistinguishedName

`func (o *UserOrGroupLocalSummaryInfo) SetDistinguishedName(v string)`

SetDistinguishedName sets DistinguishedName field to given value.

### HasDistinguishedName

`func (o *UserOrGroupLocalSummaryInfo) HasDistinguishedName() bool`

HasDistinguishedName returns a boolean if a field has been set.

### GetDomain

`func (o *UserOrGroupLocalSummaryInfo) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *UserOrGroupLocalSummaryInfo) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *UserOrGroupLocalSummaryInfo) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *UserOrGroupLocalSummaryInfo) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetEmail

`func (o *UserOrGroupLocalSummaryInfo) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserOrGroupLocalSummaryInfo) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserOrGroupLocalSummaryInfo) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *UserOrGroupLocalSummaryInfo) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *UserOrGroupLocalSummaryInfo) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *UserOrGroupLocalSummaryInfo) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *UserOrGroupLocalSummaryInfo) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetGroup

`func (o *UserOrGroupLocalSummaryInfo) GetGroup() bool`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *UserOrGroupLocalSummaryInfo) GetGroupOk() (*bool, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *UserOrGroupLocalSummaryInfo) SetGroup(v bool)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *UserOrGroupLocalSummaryInfo) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetHeldUser

`func (o *UserOrGroupLocalSummaryInfo) GetHeldUser() bool`

GetHeldUser returns the HeldUser field if non-nil, zero value otherwise.

### GetHeldUserOk

`func (o *UserOrGroupLocalSummaryInfo) GetHeldUserOk() (*bool, bool)`

GetHeldUserOk returns a tuple with the HeldUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeldUser

`func (o *UserOrGroupLocalSummaryInfo) SetHeldUser(v bool)`

SetHeldUser sets HeldUser field to given value.

### HasHeldUser

`func (o *UserOrGroupLocalSummaryInfo) HasHeldUser() bool`

HasHeldUser returns a boolean if a field has been set.

### GetId

`func (o *UserOrGroupLocalSummaryInfo) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserOrGroupLocalSummaryInfo) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserOrGroupLocalSummaryInfo) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *UserOrGroupLocalSummaryInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetKioskUser

`func (o *UserOrGroupLocalSummaryInfo) GetKioskUser() bool`

GetKioskUser returns the KioskUser field if non-nil, zero value otherwise.

### GetKioskUserOk

`func (o *UserOrGroupLocalSummaryInfo) GetKioskUserOk() (*bool, bool)`

GetKioskUserOk returns a tuple with the KioskUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKioskUser

`func (o *UserOrGroupLocalSummaryInfo) SetKioskUser(v bool)`

SetKioskUser sets KioskUser field to given value.

### HasKioskUser

`func (o *UserOrGroupLocalSummaryInfo) HasKioskUser() bool`

HasKioskUser returns a boolean if a field has been set.

### GetLastName

`func (o *UserOrGroupLocalSummaryInfo) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *UserOrGroupLocalSummaryInfo) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *UserOrGroupLocalSummaryInfo) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetLoginName

`func (o *UserOrGroupLocalSummaryInfo) GetLoginName() string`

GetLoginName returns the LoginName field if non-nil, zero value otherwise.

### GetLoginNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetLoginNameOk() (*string, bool)`

GetLoginNameOk returns a tuple with the LoginName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginName

`func (o *UserOrGroupLocalSummaryInfo) SetLoginName(v string)`

SetLoginName sets LoginName field to given value.

### HasLoginName

`func (o *UserOrGroupLocalSummaryInfo) HasLoginName() bool`

HasLoginName returns a boolean if a field has been set.

### GetLongDisplayName

`func (o *UserOrGroupLocalSummaryInfo) GetLongDisplayName() string`

GetLongDisplayName returns the LongDisplayName field if non-nil, zero value otherwise.

### GetLongDisplayNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetLongDisplayNameOk() (*string, bool)`

GetLongDisplayNameOk returns a tuple with the LongDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongDisplayName

`func (o *UserOrGroupLocalSummaryInfo) SetLongDisplayName(v string)`

SetLongDisplayName sets LongDisplayName field to given value.

### HasLongDisplayName

`func (o *UserOrGroupLocalSummaryInfo) HasLongDisplayName() bool`

HasLongDisplayName returns a boolean if a field has been set.

### GetMachineIds

`func (o *UserOrGroupLocalSummaryInfo) GetMachineIds() []string`

GetMachineIds returns the MachineIds field if non-nil, zero value otherwise.

### GetMachineIdsOk

`func (o *UserOrGroupLocalSummaryInfo) GetMachineIdsOk() (*[]string, bool)`

GetMachineIdsOk returns a tuple with the MachineIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineIds

`func (o *UserOrGroupLocalSummaryInfo) SetMachineIds(v []string)`

SetMachineIds sets MachineIds field to given value.

### HasMachineIds

`func (o *UserOrGroupLocalSummaryInfo) HasMachineIds() bool`

HasMachineIds returns a boolean if a field has been set.

### GetName

`func (o *UserOrGroupLocalSummaryInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserOrGroupLocalSummaryInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UserOrGroupLocalSummaryInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPhone

`func (o *UserOrGroupLocalSummaryInfo) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *UserOrGroupLocalSummaryInfo) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *UserOrGroupLocalSummaryInfo) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *UserOrGroupLocalSummaryInfo) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetUnauthenticatedAccessUser

`func (o *UserOrGroupLocalSummaryInfo) GetUnauthenticatedAccessUser() bool`

GetUnauthenticatedAccessUser returns the UnauthenticatedAccessUser field if non-nil, zero value otherwise.

### GetUnauthenticatedAccessUserOk

`func (o *UserOrGroupLocalSummaryInfo) GetUnauthenticatedAccessUserOk() (*bool, bool)`

GetUnauthenticatedAccessUserOk returns a tuple with the UnauthenticatedAccessUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnauthenticatedAccessUser

`func (o *UserOrGroupLocalSummaryInfo) SetUnauthenticatedAccessUser(v bool)`

SetUnauthenticatedAccessUser sets UnauthenticatedAccessUser field to given value.

### HasUnauthenticatedAccessUser

`func (o *UserOrGroupLocalSummaryInfo) HasUnauthenticatedAccessUser() bool`

HasUnauthenticatedAccessUser returns a boolean if a field has been set.

### GetUserDisplayName

`func (o *UserOrGroupLocalSummaryInfo) GetUserDisplayName() string`

GetUserDisplayName returns the UserDisplayName field if non-nil, zero value otherwise.

### GetUserDisplayNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetUserDisplayNameOk() (*string, bool)`

GetUserDisplayNameOk returns a tuple with the UserDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserDisplayName

`func (o *UserOrGroupLocalSummaryInfo) SetUserDisplayName(v string)`

SetUserDisplayName sets UserDisplayName field to given value.

### HasUserDisplayName

`func (o *UserOrGroupLocalSummaryInfo) HasUserDisplayName() bool`

HasUserDisplayName returns a boolean if a field has been set.

### GetUserPrincipalName

`func (o *UserOrGroupLocalSummaryInfo) GetUserPrincipalName() string`

GetUserPrincipalName returns the UserPrincipalName field if non-nil, zero value otherwise.

### GetUserPrincipalNameOk

`func (o *UserOrGroupLocalSummaryInfo) GetUserPrincipalNameOk() (*string, bool)`

GetUserPrincipalNameOk returns a tuple with the UserPrincipalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserPrincipalName

`func (o *UserOrGroupLocalSummaryInfo) SetUserPrincipalName(v string)`

SetUserPrincipalName sets UserPrincipalName field to given value.

### HasUserPrincipalName

`func (o *UserOrGroupLocalSummaryInfo) HasUserPrincipalName() bool`

HasUserPrincipalName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


