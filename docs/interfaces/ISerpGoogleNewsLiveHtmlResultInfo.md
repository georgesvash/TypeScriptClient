[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpGoogleNewsLiveHtmlResultInfo

# Interface: ISerpGoogleNewsLiveHtmlResultInfo

## Implemented by

- [`SerpGoogleNewsLiveHtmlResultInfo`](../classes/SerpGoogleNewsLiveHtmlResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [datetime](ISerpGoogleNewsLiveHtmlResultInfo.md#datetime)
- [items](ISerpGoogleNewsLiveHtmlResultInfo.md#items)
- [items\_count](ISerpGoogleNewsLiveHtmlResultInfo.md#items_count)
- [keyword](ISerpGoogleNewsLiveHtmlResultInfo.md#keyword)
- [language\_code](ISerpGoogleNewsLiveHtmlResultInfo.md#language_code)
- [location\_code](ISerpGoogleNewsLiveHtmlResultInfo.md#location_code)
- [se\_domain](ISerpGoogleNewsLiveHtmlResultInfo.md#se_domain)
- [type](ISerpGoogleNewsLiveHtmlResultInfo.md#type)

## Properties

### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:43453](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43453)

___


### items

• `Optional` **items**: [`HtmlItem`](../classes/HtmlItem.md)[]

elements of search results found in SERP

#### Defined in

[main.ts:43457](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43457)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Defined in

[main.ts:43455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43455)

___


### keyword

• `Optional` **keyword**: `string`

keyword received in a POST array
keyword is returned with decoded %## (plus symbol ‘+’ will be decoded to a space character)

#### Defined in

[main.ts:43440](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43440)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:43448](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43448)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:43446](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43446)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Defined in

[main.ts:43444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43444)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:43442](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43442)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")