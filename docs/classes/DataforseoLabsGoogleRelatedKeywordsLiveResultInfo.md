[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleRelatedKeywordsLiveResultInfo

# Class: DataforseoLabsGoogleRelatedKeywordsLiveResultInfo

## Implements

- [`IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#constructor)

### Properties

- [items](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#items)
- [items\_count](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#items_count)
- [language\_code](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#language_code)
- [location\_code](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#location_code)
- [se\_type](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#se_type)
- [seed\_keyword](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#seed_keyword)
- [seed\_keyword\_data](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#seed_keyword_data)
- [total\_count](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#total_count)

### Methods

- [init](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#init)
- [toJSON](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleRelatedKeywordsLiveResultInfo**(`data?`): [`DataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md) |

#### Returns

[`DataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md)

#### Defined in

[main.ts:80401](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80401)

## Properties

### items

• `Optional` **items**: [`DataforseoLabsGoogleRelatedKeywordsLiveItem`](DataforseoLabsGoogleRelatedKeywordsLiveItem.md)[]

contains keywords and related data

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[items](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#items)

#### Defined in

[main.ts:80397](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80397)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[items_count](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#items_count)

#### Defined in

[main.ts:80395](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80395)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[language_code](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#language_code)

#### Defined in

[main.ts:80391](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80391)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[location_code](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#location_code)

#### Defined in

[main.ts:80389](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80389)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[se_type](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#se_type)

#### Defined in

[main.ts:80382](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80382)

___


### seed\_keyword

• `Optional` **seed\_keyword**: `string`

keyword in a POST array

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[seed_keyword](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#seed_keyword)

#### Defined in

[main.ts:80384](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80384)

___


### seed\_keyword\_data

• `Optional` **seed\_keyword\_data**: `Object`

keyword data for the seed keyword
fields in the array are identical to that of keyword_data

#### Index signature

▪ [key: `string`]: `string`

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[seed_keyword_data](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#seed_keyword_data)

#### Defined in

[main.ts:80387](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80387)

___


### total\_count

• `Optional` **total\_count**: `number`

total amount of results in our database relevant to your request

#### Implementation of

[IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md).[total_count](../interfaces/IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#total_count)

#### Defined in

[main.ts:80393](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80393)

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

[main.ts:80410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80410)

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

[main.ts:80444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80444)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md)

#### Defined in

[main.ts:80437](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80437)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")