[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleHotelInfoTaskPostRequestInfo

# Class: BusinessDataGoogleHotelInfoTaskPostRequestInfo

## Hierarchy

- [`BusinessDataTaskRequestInfo`](BusinessDataTaskRequestInfo.md)
  
  ↳ **`BusinessDataGoogleHotelInfoTaskPostRequestInfo`**

## Implements

- [`IBusinessDataGoogleHotelInfoTaskPostRequestInfo`](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#constructor)

### Properties

- [adults](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#adults)
- [check\_in](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#check_in)
- [check\_out](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#check_out)
- [children](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#children)
- [currency](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#currency)
- [hotel\_identifier](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#hotel_identifier)
- [keyword](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#keyword)
- [language\_code](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#language_code)
- [language\_name](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#language_name)
- [location\_code](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#location_code)
- [location\_coordinate](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#location_coordinate)
- [location\_name](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#location_name)
- [pingback\_url](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#pingback_url)
- [postback\_data](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#postback_data)
- [postback\_url](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#postback_url)
- [priority](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#priority)
- [tag](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#tag)

### Methods

- [init](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#init)
- [toJSON](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#tojson)
- [fromJS](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleHotelInfoTaskPostRequestInfo**(`data?`): [`BusinessDataGoogleHotelInfoTaskPostRequestInfo`](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleHotelInfoTaskPostRequestInfo`](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md) |

#### Returns

[`BusinessDataGoogleHotelInfoTaskPostRequestInfo`](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md)

#### Overrides

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[constructor](BusinessDataTaskRequestInfo.md#constructor)

#### Defined in

[main.ts:194870](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194870)

## Properties

### adults

• `Optional` **adults**: `number`

number of adults
optional field
if you don’t specify this field, two adults will be used by default
example:
1

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[adults](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#adults)

#### Defined in

[main.ts:194852](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194852)

___


### check\_in

• `Optional` **check\_in**: `string`

check-in date
optional field
if you don’t specify this field, tomorrow’s date will be used by default;
the value must not be earlier than today’s date
date format: "yyyy-mm-dd"
example:
"2019-01-15"

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[check_in](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#check_in)

#### Defined in

[main.ts:194832](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194832)

___


### check\_out

• `Optional` **check\_out**: `string`

check-out date
optional field
if you don’t specify this field, our system will apply the date of two days from now by default;
Note: the value cannot be less than or equal to check_in;
the range between check_in and check_out values cannot exceed 30 days
date format: "yyyy-mm-dd"
example:
"2019-01-15"

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[check_out](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#check_out)

#### Defined in

[main.ts:194841](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194841)

___


### children

• `Optional` **children**: `string`[]

number and age of children
optional field
if you don’t specify this field, no children will be included in the search;
set the following value if you want to include one 14-years-old child:
[14]
set the following value if you want to include one 13-years-old child and one 8-years-old child:
[13,8]

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[children](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#children)

#### Defined in

[main.ts:194860](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194860)

___


### currency

• `Optional` **currency**: `string`

currency
optional field
example:
"USD"

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[currency](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#currency)

#### Defined in

[main.ts:194846](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194846)

___


### hotel\_identifier

• `Optional` **hotel\_identifier**: `string`

unique hotel identifier
required field if you don’t specify keyword
if you use this field, you don’t need to specify keyword
unique identifier of a hotel entity in Google search;
you can obtain the value by making a request to Advanced Google SERP API (enclosed in the hotels_pack element of the response), or the Hotel Searches endpoint of Business Data API
example:
ChYIq6SB--i6p6cpGgovbS8wN2s5ODZfEAE

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[hotel_identifier](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#hotel_identifier)

#### Defined in

[main.ts:194824](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194824)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
the keyword you specify should indicate the name of the local establishment
you can specify up to 700 symbols in the keyword filed
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character)
if you need to use the “%” symbol for your keyword, please specify it as “%25”;
this field can also be used to pass the following parameters:
cid – a unique, google-defined id of the business entity;
place_id – an identifier of the business entity in Google Maps;
spp – a unique identifier of local services featured in the local_pack element of Google SERP
example:
cid:194604053573767737
place_id:GhIJQWDl0CIeQUARxks3icF8U8A
spp:CgsvZy8xdGN4cWRraBoUChIJPZDrEzLsZIgRoNrpodC5P30
learn more about the cid and place_id identifiers in this help center article

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[keyword](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#keyword)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[keyword](BusinessDataTaskRequestInfo.md#keyword)

#### Defined in

[main.ts:183110](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183110)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
you can receive the list of available languages with their language_code by making a separate request to https://api.dataforseo.com/v3/business_data/google/languages
example:
en

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[language_code](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#language_code)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[language_code](BusinessDataTaskRequestInfo.md#language_code)

#### Defined in

[main.ts:183155](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183155)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available languages with language_name by making a separate request to https://api.dataforseo.com/v3/business_data/google/languages
example:
English

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[language_name](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#language_name)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[language_name](BusinessDataTaskRequestInfo.md#language_name)

#### Defined in

[main.ts:183148](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183148)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available locations with location_code by making a separate request to the https://api.dataforseo.com/v3/business_data/google/locations
example:
2840

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[location_code](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#location_code)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[location_code](BusinessDataTaskRequestInfo.md#location_code)

#### Defined in

[main.ts:183132](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183132)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
required field if you don’t specify location_name or location_code
if you use this field, you don’t need to specify location_name or location_code
location_coordinate parameter should be specified in the “latitude,longitude,radius” format
the maximum number of decimal digits for “latitude” and “longitude”: 7
the minimum value for “radius”: 199.9
example:
53.476225,-2.243572,200

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[location_coordinate](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#location_coordinate)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[location_coordinate](BusinessDataTaskRequestInfo.md#location_coordinate)

#### Defined in

[main.ts:183141](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183141)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available locations with location_name by making a separate request to https://api.dataforseo.com/v3/business_data/google/locations
example:
London,England,United Kingdom

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[location_name](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#location_name)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[location_name](BusinessDataTaskRequestInfo.md#location_name)

#### Defined in

[main.ts:183125](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183125)

___


### pingback\_url

• `Optional` **pingback\_url**: `string`

notification URL of a completed task
optional field
when a task is completed we will notify you by GET request sent to the URL you have specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/pingscript?id=$id
http://your-server.com/pingscript?id=$id&tag=$tag
Note: special symbols in pingback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[pingback_url](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#pingback_url)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[pingback_url](BusinessDataTaskRequestInfo.md#pingback_url)

#### Defined in

[main.ts:183181](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183181)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced, html

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[postback_data](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#postback_data)

#### Defined in

[main.ts:194866](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194866)

___


### postback\_url

• `Optional` **postback\_url**: `string`

return URL for sending task results
optional field
once the task is completed, we will send a POST request with its results compressed in the gzip format to the postback_url you specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/postbackscript?id=$id
http://your-server.com/postbackscript?id=$id&tag=$tag
Note: special symbols in postback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[postback_url](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#postback_url)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[postback_url](BusinessDataTaskRequestInfo.md#postback_url)

#### Defined in

[main.ts:183171](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183171)

___


### priority

• `Optional` **priority**: `number`

task priority
optional field
can take the following values:
1 – normal execution priority (set by default)
2 – high execution priority
You will be additionally charged for the tasks with high execution priority.
The cost can be calculated on the Pricing page.

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[priority](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#priority)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[priority](BusinessDataTaskRequestInfo.md#priority)

#### Defined in

[main.ts:183118](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183118)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IBusinessDataGoogleHotelInfoTaskPostRequestInfo](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md).[tag](../interfaces/IBusinessDataGoogleHotelInfoTaskPostRequestInfo.md#tag)

#### Inherited from

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[tag](BusinessDataTaskRequestInfo.md#tag)

#### Defined in

[main.ts:183161](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183161)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Overrides

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[init](BusinessDataTaskRequestInfo.md#init)

#### Defined in

[main.ts:194874](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194874)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Overrides

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[toJSON](BusinessDataTaskRequestInfo.md#tojson)

#### Defined in

[main.ts:194902](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194902)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleHotelInfoTaskPostRequestInfo`](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleHotelInfoTaskPostRequestInfo`](BusinessDataGoogleHotelInfoTaskPostRequestInfo.md)

#### Overrides

[BusinessDataTaskRequestInfo](BusinessDataTaskRequestInfo.md).[fromJS](BusinessDataTaskRequestInfo.md#fromjs)

#### Defined in

[main.ts:194895](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194895)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")