[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonSellersTaskPostRequestInfo

# Class: MerchantAmazonSellersTaskPostRequestInfo

## Implements

- [`IMerchantAmazonSellersTaskPostRequestInfo`](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonSellersTaskPostRequestInfo.md#constructor)

### Properties

- [asin](MerchantAmazonSellersTaskPostRequestInfo.md#asin)
- [language\_code](MerchantAmazonSellersTaskPostRequestInfo.md#language_code)
- [language\_name](MerchantAmazonSellersTaskPostRequestInfo.md#language_name)
- [location\_code](MerchantAmazonSellersTaskPostRequestInfo.md#location_code)
- [location\_coordinate](MerchantAmazonSellersTaskPostRequestInfo.md#location_coordinate)
- [location\_name](MerchantAmazonSellersTaskPostRequestInfo.md#location_name)
- [pingback\_url](MerchantAmazonSellersTaskPostRequestInfo.md#pingback_url)
- [postback\_data](MerchantAmazonSellersTaskPostRequestInfo.md#postback_data)
- [postback\_url](MerchantAmazonSellersTaskPostRequestInfo.md#postback_url)
- [priority](MerchantAmazonSellersTaskPostRequestInfo.md#priority)
- [se\_domain](MerchantAmazonSellersTaskPostRequestInfo.md#se_domain)
- [tag](MerchantAmazonSellersTaskPostRequestInfo.md#tag)

### Methods

- [init](MerchantAmazonSellersTaskPostRequestInfo.md#init)
- [toJSON](MerchantAmazonSellersTaskPostRequestInfo.md#tojson)
- [fromJS](MerchantAmazonSellersTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonSellersTaskPostRequestInfo**(`data?`): [`MerchantAmazonSellersTaskPostRequestInfo`](MerchantAmazonSellersTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonSellersTaskPostRequestInfo`](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md) |

#### Returns

[`MerchantAmazonSellersTaskPostRequestInfo`](MerchantAmazonSellersTaskPostRequestInfo.md)

#### Defined in

[main.ts:173652](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173652)

## Properties

### asin

• `Optional` **asin**: `string`

unique product identifier on Amazon
required field
you can get this value making a separate request to the Amazon Products endpoint
note that there is no full list of possible values as the asin values is a dynamic value assigned by Amazon
example:
B085RFFC9Q
learn more about the identifier in this help center guide

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[asin](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#asin)

#### Defined in

[main.ts:173564](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173564)

___


### language\_code

• `Optional` **language\_code**: `string`

language code
required field if you don’t specify language_name
if you use this field, you don’t need to specify language_name
you can receive the list of available Amazon languages with their language_code by making a separate request to the https://api.dataforseo.com/v3/merchant/amazon/languages
example:
en

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[language_code](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#language_code)

#### Defined in

[main.ts:173609](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173609)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available Amazon languages with their language_name by making a separate request to the https://api.dataforseo.com/v3/merchant/amazon/languages
example:
English

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[language_name](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#language_name)

#### Defined in

[main.ts:173602](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173602)

___


### location\_code

• `Optional` **location\_code**: `number`

location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available Amazon locations with their location_code by making a separate request to the https://api.dataforseo.com/v3/merchant/amazon/locations
example:
2840

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[location_code](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#location_code)

#### Defined in

[main.ts:173586](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173586)

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

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[location_coordinate](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#location_coordinate)

#### Defined in

[main.ts:173595](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173595)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available Amazon locations with their location_name by making a separate request to the https://api.dataforseo.com/v3/merchant/amazon/locations
example:
London,England,United Kingdom

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[location_name](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#location_name)

#### Defined in

[main.ts:173579](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173579)

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

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[pingback_url](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:173648](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173648)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced, html

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[postback_data](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#postback_data)

#### Defined in

[main.ts:173638](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173638)

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

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[postback_url](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:173632](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173632)

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

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[priority](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#priority)

#### Defined in

[main.ts:173572](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173572)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain
optional field
we choose the relevant search engine domain automatically according to the location and language you specify
however, you can set a custom search engine domain in this field
example:
amazon.co.uk, amazon.com.au, amazon.de, etc.

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[se_domain](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#se_domain)

#### Defined in

[main.ts:173616](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173616)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IMerchantAmazonSellersTaskPostRequestInfo](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md).[tag](../interfaces/IMerchantAmazonSellersTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:173622](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173622)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Defined in

[main.ts:173661](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173661)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Defined in

[main.ts:173689](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173689)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonSellersTaskPostRequestInfo`](MerchantAmazonSellersTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonSellersTaskPostRequestInfo`](MerchantAmazonSellersTaskPostRequestInfo.md)

#### Defined in

[main.ts:173682](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173682)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")