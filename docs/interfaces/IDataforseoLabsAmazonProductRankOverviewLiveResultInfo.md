[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsAmazonProductRankOverviewLiveResultInfo

# Interface: IDataforseoLabsAmazonProductRankOverviewLiveResultInfo

## Implemented by

- [`DataforseoLabsAmazonProductRankOverviewLiveResultInfo`](../classes/DataforseoLabsAmazonProductRankOverviewLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [items](IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#items)
- [items\_count](IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#items_count)
- [language\_code](IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#language_code)
- [location\_code](IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#location_code)
- [se\_type](IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#se_type)
- [total\_count](IDataforseoLabsAmazonProductRankOverviewLiveResultInfo.md#total_count)

## Properties

### items

• `Optional` **items**: [`DataforseoLabsAmazonProductRankOverviewLiveItem`](../classes/DataforseoLabsAmazonProductRankOverviewLiveItem.md)[]

contains detected Amazon product competitors and related data

#### Defined in

[main.ts:100857](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100857)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Defined in

[main.ts:100855](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100855)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array
if there is no data, then the value is null

#### Defined in

[main.ts:100851](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100851)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array
if there is no data, then the value is null

#### Defined in

[main.ts:100848](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100848)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Defined in

[main.ts:100845](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100845)

___


### total\_count

• `Optional` **total\_count**: `number`

total amount of results in our database relevant to your request

#### Defined in

[main.ts:100853](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L100853)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")