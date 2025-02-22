[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IOnPageDuplicateContentResultInfo

# Interface: IOnPageDuplicateContentResultInfo

## Implemented by

- [`OnPageDuplicateContentResultInfo`](../classes/OnPageDuplicateContentResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [crawl\_progress](IOnPageDuplicateContentResultInfo.md#crawl_progress)
- [crawl\_status](IOnPageDuplicateContentResultInfo.md#crawl_status)
- [items](IOnPageDuplicateContentResultInfo.md#items)
- [items\_count](IOnPageDuplicateContentResultInfo.md#items_count)

## Properties

### crawl\_progress

• `Optional` **crawl\_progress**: `string`

status of the crawling session
possible values: in_progress, finished

#### Defined in

[main.ts:147750](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147750)

___


### crawl\_status

• `Optional` **crawl\_status**: [`CrawlStatusInfo`](../classes/CrawlStatusInfo.md)

details of the crawling session

#### Defined in

[main.ts:147752](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147752)

___


### items

• `Optional` **items**: [`OnPageDuplicateContentItem`](../classes/OnPageDuplicateContentItem.md)[]

items array

#### Defined in

[main.ts:147756](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147756)

___


### items\_count

• `Optional` **items\_count**: `number`

number of items in the results array

#### Defined in

[main.ts:147754](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L147754)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")