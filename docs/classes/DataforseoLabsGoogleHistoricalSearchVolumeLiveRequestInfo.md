[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo

# Class: DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo

## Implements

- [`IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo`](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#constructor)

### Properties

- [include\_serp\_info](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#include_serp_info)
- [keywords](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#keywords)
- [language\_code](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#language_code)
- [language\_name](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#language_name)
- [location\_code](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#location_code)
- [location\_name](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#location_name)
- [tag](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#tag)

### Methods

- [init](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#init)
- [toJSON](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo**(`data?`): [`DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo`](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo`](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md) |

#### Returns

[`DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo`](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md)

#### Defined in

[main.ts:81792](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81792)

## Properties

### include\_serp\_info

• `Optional` **include\_serp\_info**: `boolean`

include data from SERP for each keyword
optional field
if set to true, we will return a serp_info array containing SERP data (number of search results, relevant URL, and SERP features) for every keyword in the response
default value: false

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[include_serp_info](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#include_serp_info)

#### Defined in

[main.ts:81782](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81782)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords
required field
The maximum number of keywords you can specify: 700
The maximum number of characters for each keyword: 80
The maximum number of words for each keyword phrase: 10
the specified keywords will be converted to lowercase format, data will be provided in a separate array
note that if some of the keywords specified in this array are omitted in the results you receive, then our database doesn’t contain such keywords and cannot return data on them
you will not be charged for the keywords omitted in the results

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[keywords](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#keywords)

#### Defined in

[main.ts:81745](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81745)

___


### language\_code

• `Optional` **language\_code**: `string`

language code
required field if you don’t specify language_name
Note: it is required to specify either language_name or language_code
you can receive the list of available locations with their language_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
en

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[language_code](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#language_code)

#### Defined in

[main.ts:81777](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81777)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
required field if you don’t specify language_code
Note: it is required to specify either language_name or language_code
you can receive the list of available locations with their language_name by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
English

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[language_name](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#language_name)

#### Defined in

[main.ts:81769](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81769)

___


### location\_code

• `Optional` **location\_code**: `number`

location code
required field if you don’t specify location_name
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
2840

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[location_code](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#location_code)

#### Defined in

[main.ts:81761](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81761)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_name by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
United Kingdom

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[location_name](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#location_name)

#### Defined in

[main.ts:81753](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81753)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md).[tag](../interfaces/IDataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md#tag)

#### Defined in

[main.ts:81788](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81788)

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

[main.ts:81801](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81801)

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

[main.ts:81828](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81828)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo`](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo`](DataforseoLabsGoogleHistoricalSearchVolumeLiveRequestInfo.md)

#### Defined in

[main.ts:81821](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81821)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")