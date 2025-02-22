[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo

# Class: DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo

## Implements

- [`IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo`](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#constructor)

### Properties

- [items](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#items)
- [items\_count](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#items_count)
- [language\_code](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#language_code)
- [location\_code](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#location_code)
- [se\_type](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#se_type)
- [total\_count](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#total_count)

### Methods

- [init](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#init)
- [toJSON](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo**(`data?`): [`DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo`](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo`](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md) |

#### Returns

[`DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo`](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md)

#### Defined in

[main.ts:82446](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82446)

## Properties

### items

• `Optional` **items**: [`DataforseoLabsBBulkKeywordDifficultyLiveItem`](DataforseoLabsBBulkKeywordDifficultyLiveItem.md)[]

contains keywords and related keyword difficulty scores

#### Implementation of

[IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md).[items](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#items)

#### Defined in

[main.ts:82442](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82442)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Implementation of

[IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md).[items_count](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#items_count)

#### Defined in

[main.ts:82440](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82440)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array
if there is no data, then the value is null

#### Implementation of

[IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md).[language_code](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#language_code)

#### Defined in

[main.ts:82436](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82436)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array
if there is no data, then the value is null

#### Implementation of

[IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md).[location_code](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#location_code)

#### Defined in

[main.ts:82433](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82433)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Implementation of

[IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md).[se_type](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#se_type)

#### Defined in

[main.ts:82430](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82430)

___


### total\_count

• `Optional` **total\_count**: `number`

total amount of results in our database relevant to your request

#### Implementation of

[IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md).[total_count](../interfaces/IDataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md#total_count)

#### Defined in

[main.ts:82438](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82438)

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

[main.ts:82455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82455)

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

[main.ts:82481](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82481)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo`](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo`](DataforseoLabsGoogleBulkKeywordDifficultyLiveResultInfo.md)

#### Defined in

[main.ts:82474](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L82474)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")