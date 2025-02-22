[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataTripadvisorSearchTaskPostRequestInfo

# Class: BusinessDataTripadvisorSearchTaskPostRequestInfo

## Implements

- [`IBusinessDataTripadvisorSearchTaskPostRequestInfo`](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#constructor)

### Properties

- [depth](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#depth)
- [keyword](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#keyword)
- [location\_code](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#location_code)
- [location\_name](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#location_name)
- [pingback\_url](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#pingback_url)
- [postback\_url](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#postback_url)
- [priority](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#priority)
- [tag](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#tag)

### Methods

- [init](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#init)
- [toJSON](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#tojson)
- [fromJS](BusinessDataTripadvisorSearchTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataTripadvisorSearchTaskPostRequestInfo**(`data?`): [`BusinessDataTripadvisorSearchTaskPostRequestInfo`](BusinessDataTripadvisorSearchTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataTripadvisorSearchTaskPostRequestInfo`](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md) |

#### Returns

[`BusinessDataTripadvisorSearchTaskPostRequestInfo`](BusinessDataTripadvisorSearchTaskPostRequestInfo.md)

#### Defined in

[main.ts:200958](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200958)

## Properties

### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of search results to be returned from the API response
we strongly recommend setting the parsing depth in the multiples of thirty because our systems processes thirty search results in a row;
default value: 30;
maximum value: 210

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[depth](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#depth)

#### Defined in

[main.ts:200928](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200928)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
the keyword you specify should indicate a business category, company name, or a prominent place;
you can specify up to 700 symbols in the keyword filed;
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character);
if you need to use the “%” symbol for your keyword, please specify it as “%25”

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[keyword](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#keyword)

#### Defined in

[main.ts:200901](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200901)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name
you can receive the list of available locations with location_code by making a separate request to the https://api.dataforseo.com/v3/business_data/tripadvisor/locations
example:
1003854

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[location_code](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#location_code)

#### Defined in

[main.ts:200913](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200913)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code
you can receive the list of available locations with location_name by making a separate request to the https://api.dataforseo.com/v3/business_data/tripadvisor/locations
example:
London,England,United Kingdom

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[location_name](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#location_name)

#### Defined in

[main.ts:200907](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200907)

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

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[pingback_url](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:200954](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200954)

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

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[postback_url](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:200944](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200944)

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

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[priority](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#priority)

#### Defined in

[main.ts:200921](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200921)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostRequestInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md).[tag](../interfaces/IBusinessDataTripadvisorSearchTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:200934](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200934)

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

[main.ts:200967](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200967)

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

[main.ts:200991](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200991)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataTripadvisorSearchTaskPostRequestInfo`](BusinessDataTripadvisorSearchTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataTripadvisorSearchTaskPostRequestInfo`](BusinessDataTripadvisorSearchTaskPostRequestInfo.md)

#### Defined in

[main.ts:200984](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200984)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")