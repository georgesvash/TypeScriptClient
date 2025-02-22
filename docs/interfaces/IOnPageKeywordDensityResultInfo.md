[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IOnPageKeywordDensityResultInfo

# Interface: IOnPageKeywordDensityResultInfo

## Implemented by

- [`OnPageKeywordDensityResultInfo`](../classes/OnPageKeywordDensityResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [crawl\_progress](IOnPageKeywordDensityResultInfo.md#crawl_progress)
- [crawl\_status](IOnPageKeywordDensityResultInfo.md#crawl_status)
- [items](IOnPageKeywordDensityResultInfo.md#items)
- [items\_count](IOnPageKeywordDensityResultInfo.md#items_count)
- [total\_items\_count](IOnPageKeywordDensityResultInfo.md#total_items_count)

## Properties

### crawl\_progress

• `Optional` **crawl\_progress**: `string`

status of the crawling session
possible values: in_progress, finished

#### Defined in

[main.ts:150369](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150369)

___


### crawl\_status

• `Optional` **crawl\_status**: [`CrawlStatusInfo`](../classes/CrawlStatusInfo.md)

details of the crawling session

#### Defined in

[main.ts:150371](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150371)

___


### items

• `Optional` **items**: [`OnPageKeywordDensityItem`](../classes/OnPageKeywordDensityItem.md)[]

items array

#### Defined in

[main.ts:150378](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150378)

___


### items\_count

• `Optional` **items\_count**: `number`

number of items in the results array

#### Defined in

[main.ts:150376](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150376)

___


### total\_items\_count

• `Optional` **total\_items\_count**: `number`

total number of relevant items
total number of keywords on the specified website or web page matching the set keyword_length and filters

#### Defined in

[main.ts:150374](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150374)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")