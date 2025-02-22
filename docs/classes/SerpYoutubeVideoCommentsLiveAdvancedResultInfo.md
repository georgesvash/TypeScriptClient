[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYoutubeVideoCommentsLiveAdvancedResultInfo

# Class: SerpYoutubeVideoCommentsLiveAdvancedResultInfo

## Implements

- [`ISerpYoutubeVideoCommentsLiveAdvancedResultInfo`](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#constructor)

### Properties

- [check\_url](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#check_url)
- [comments\_count](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#comments_count)
- [datetime](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#datetime)
- [item\_types](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#item_types)
- [items](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#items)
- [items\_count](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#items_count)
- [language\_code](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#language_code)
- [location\_code](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#location_code)
- [se\_domain](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#se_domain)
- [spell](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#spell)
- [title](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#title)
- [video\_id](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#video_id)

### Methods

- [init](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#init)
- [toJSON](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#tojson)
- [fromJS](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYoutubeVideoCommentsLiveAdvancedResultInfo**(`data?`): [`SerpYoutubeVideoCommentsLiveAdvancedResultInfo`](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYoutubeVideoCommentsLiveAdvancedResultInfo`](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md) |

#### Returns

[`SerpYoutubeVideoCommentsLiveAdvancedResultInfo`](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md)

#### Defined in

[main.ts:62410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62410)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided accurate results

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[check_url](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#check_url)

#### Defined in

[main.ts:62385](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62385)

___


### comments\_count

• `Optional` **comments\_count**: `number`

number of comments on the video

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[comments_count](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#comments_count)

#### Defined in

[main.ts:62402](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62402)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[datetime](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#datetime)

#### Defined in

[main.ts:62390](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62390)

___


### item\_types

• `Optional` **item\_types**: `string`[]

types of search results in SERP
contains types of search results (items) found in SERP.
possible item:
youtube_comment

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[item_types](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#item_types)

#### Defined in

[main.ts:62398](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62398)

___


### items

• `Optional` **items**: [`BaseSerpElementItem`](BaseSerpElementItem.md)[]

elements of search results found in SERP

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[items](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#items)

#### Defined in

[main.ts:62406](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62406)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[items_count](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#items_count)

#### Defined in

[main.ts:62404](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62404)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[language_code](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#language_code)

#### Defined in

[main.ts:62382](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62382)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[location_code](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#location_code)

#### Defined in

[main.ts:62380](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62380)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[se_domain](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#se_domain)

#### Defined in

[main.ts:62378](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62378)

___


### spell

• `Optional` **spell**: [`SpellInfo`](SpellInfo.md)

autocorrection of the search engine
if the search engine provided results for a keyword that was corrected, we will specify the keyword corrected by the search engine and the type of autocorrection

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[spell](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#spell)

#### Defined in

[main.ts:62393](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62393)

___


### title

• `Optional` **title**: `string`

title of the video

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[title](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#title)

#### Defined in

[main.ts:62400](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62400)

___


### video\_id

• `Optional` **video\_id**: `string`

ID of the video received in a POST array

#### Implementation of

[ISerpYoutubeVideoCommentsLiveAdvancedResultInfo](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md).[video_id](../interfaces/ISerpYoutubeVideoCommentsLiveAdvancedResultInfo.md#video_id)

#### Defined in

[main.ts:62376](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62376)

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

[main.ts:62419](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62419)

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

[main.ts:62455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62455)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYoutubeVideoCommentsLiveAdvancedResultInfo`](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYoutubeVideoCommentsLiveAdvancedResultInfo`](SerpYoutubeVideoCommentsLiveAdvancedResultInfo.md)

#### Defined in

[main.ts:62448](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62448)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")