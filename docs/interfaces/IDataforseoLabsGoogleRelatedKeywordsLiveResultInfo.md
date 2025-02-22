[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo

# Interface: IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo

## Implemented by

- [`DataforseoLabsGoogleRelatedKeywordsLiveResultInfo`](../classes/DataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [items](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#items)
- [items\_count](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#items_count)
- [language\_code](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#language_code)
- [location\_code](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#location_code)
- [se\_type](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#se_type)
- [seed\_keyword](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#seed_keyword)
- [seed\_keyword\_data](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#seed_keyword_data)
- [total\_count](IDataforseoLabsGoogleRelatedKeywordsLiveResultInfo.md#total_count)

## Properties

### items

• `Optional` **items**: [`DataforseoLabsGoogleRelatedKeywordsLiveItem`](../classes/DataforseoLabsGoogleRelatedKeywordsLiveItem.md)[]

contains keywords and related data

#### Defined in

[main.ts:80489](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80489)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Defined in

[main.ts:80487](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80487)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:80483](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80483)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:80481](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80481)

___


### se\_type

• `Optional` **se\_type**: `string`

search engine type

#### Defined in

[main.ts:80474](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80474)

___


### seed\_keyword

• `Optional` **seed\_keyword**: `string`

keyword in a POST array

#### Defined in

[main.ts:80476](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80476)

___


### seed\_keyword\_data

• `Optional` **seed\_keyword\_data**: `Object`

keyword data for the seed keyword
fields in the array are identical to that of keyword_data

#### Index signature

▪ [key: `string`]: `string`

#### Defined in

[main.ts:80479](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80479)

___


### total\_count

• `Optional` **total\_count**: `number`

total amount of results in our database relevant to your request

#### Defined in

[main.ts:80485](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80485)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")