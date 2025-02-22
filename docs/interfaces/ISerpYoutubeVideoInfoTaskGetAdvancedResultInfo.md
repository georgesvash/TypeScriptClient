[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo

# Interface: ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo

## Implemented by

- [`SerpYoutubeVideoInfoTaskGetAdvancedResultInfo`](../classes/SerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [check\_url](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#check_url)
- [datetime](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#datetime)
- [item\_types](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#item_types)
- [items](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#items)
- [items\_count](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#items_count)
- [language\_code](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#language_code)
- [location\_code](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#location_code)
- [se\_domain](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#se_domain)
- [spell](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#spell)
- [video\_id](ISerpYoutubeVideoInfoTaskGetAdvancedResultInfo.md#video_id)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided accurate results

#### Defined in

[main.ts:58902](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58902)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:58907](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58907)

___


### item\_types

• `Optional` **item\_types**: `string`[]

types of search results in SERP
contains types of search results (items) found in SERP.
possible item:
youtube_video_info

#### Defined in

[main.ts:58915](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58915)

___


### items

• `Optional` **items**: [`BaseSerpElementItem`](../classes/BaseSerpElementItem.md)[]

elements of search results found in SERP

#### Defined in

[main.ts:58919](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58919)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Defined in

[main.ts:58917](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58917)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:58899](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58899)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:58897](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58897)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Defined in

[main.ts:58895](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58895)

___


### spell

• `Optional` **spell**: [`SpellInfo`](../classes/SpellInfo.md)

autocorrection of the search engine
if the search engine provided results for a keyword that was corrected, we will specify the keyword corrected by the search engine and the type of autocorrection

#### Defined in

[main.ts:58910](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58910)

___


### video\_id

• `Optional` **video\_id**: `string`

ID of the video received in a POST array

#### Defined in

[main.ts:58893](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58893)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")