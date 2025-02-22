[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsAmazonProductRankOverviewLiveResultInfo

# Class: DataforseoLabsAmazonProductRankOverviewLiveResultInfo

## Implements

- [`IDataforseoLabsAmazonProductRankOverviewLiveResultInfo`](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#constructor)

### Properties

- [items](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#items)
- [items\_count](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#items_count)
- [language\_code](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#language_code)
- [location\_code](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#location_code)
- [se\_type](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#se_type)
- [total\_count](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#total_count)

### Methods

- [init](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#init)
- [toJSON](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#tojson)
- [fromJS](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsAmazonProductRankOverviewLiveResultInfo**(`data?`): [`DataforseoLabsAmazonProductRankOverviewLiveResultInfo`](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsAmazonProductRankOverviewLiveResultInfo`](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md) |

#### Returns

[`DataforseoLabsAmazonProductRankOverviewLiveResultInfo`](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)

#### Defined in

[main.ts:100788](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100788)

## Properties

### items

• `Optional` **items**: [`DataforseoLabsAmazonProductRankOverviewLiveItem`](DataforseoLabsAmazonProductRankOverviewLiveItem.md)[]

contains detected Amazon product competitors and related data

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveResultInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md).[items](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#items)

#### Defined in

[main.ts:100784](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100784)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveResultInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md).[items_count](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#items_count)

#### Defined in

[main.ts:100782](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100782)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array
if there is no data, then the value is null

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveResultInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md).[language_code](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#language_code)

#### Defined in

[main.ts:100778](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100778)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array
if there is no data, then the value is null

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveResultInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md).[location_code](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#location_code)

#### Defined in

[main.ts:100775](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100775)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveResultInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md).[se_type](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#se_type)

#### Defined in

[main.ts:100772](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100772)

___


### total\_count

• `Optional` **total\_count**: `number`

total amount of results in our database relevant to your request

#### Implementation of

[IDataforseoLabsAmazonProductRankOverviewLiveResultInfo](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md).[total_count](../interfaces/IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#total_count)

#### Defined in

[main.ts:100780](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100780)

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

[main.ts:100797](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100797)

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

[main.ts:100823](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100823)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsAmazonProductRankOverviewLiveResultInfo`](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsAmazonProductRankOverviewLiveResultInfo`](DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)

#### Defined in

[main.ts:100816](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100816)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")