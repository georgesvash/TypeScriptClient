[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpGoogleMapsLiveAdvancedResultInfo

# Interface: ISerpGoogleMapsLiveAdvancedResultInfo

## Implemented by

- [`SerpGoogleMapsLiveAdvancedResultInfo`](../classes/SerpGoogleMapsLiveAdvancedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [check\_url](ISerpGoogleMapsLiveAdvancedResultInfo.md#check_url)
- [datetime](ISerpGoogleMapsLiveAdvancedResultInfo.md#datetime)
- [item\_types](ISerpGoogleMapsLiveAdvancedResultInfo.md#item_types)
- [items](ISerpGoogleMapsLiveAdvancedResultInfo.md#items)
- [items\_count](ISerpGoogleMapsLiveAdvancedResultInfo.md#items_count)
- [keyword](ISerpGoogleMapsLiveAdvancedResultInfo.md#keyword)
- [language\_code](ISerpGoogleMapsLiveAdvancedResultInfo.md#language_code)
- [location\_code](ISerpGoogleMapsLiveAdvancedResultInfo.md#location_code)
- [se\_domain](ISerpGoogleMapsLiveAdvancedResultInfo.md#se_domain)
- [se\_results\_count](ISerpGoogleMapsLiveAdvancedResultInfo.md#se_results_count)
- [spell](ISerpGoogleMapsLiveAdvancedResultInfo.md#spell)
- [type](ISerpGoogleMapsLiveAdvancedResultInfo.md#type)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided exact results
Note: to check location-specific results, follow the provided check url, scroll up and down, then click the “Search this area” button

#### Defined in

[main.ts:39500](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39500)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:39505](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39505)

___


### item\_types

• `Optional` **item\_types**: `string`[]

types of search results in SERP
contains types of search results (items) found in SERP.
possible item types:
maps_search, maps_paid_item

#### Defined in

[main.ts:39513](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39513)

___


### items

• `Optional` **items**: [`BaseSerpElementItem`](../classes/BaseSerpElementItem.md)[]

elements of search results found in SERP

#### Defined in

[main.ts:39519](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39519)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Defined in

[main.ts:39517](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39517)

___


### keyword

• `Optional` **keyword**: `string`

keyword received in a POST array
the keyword is returned with decoded %## (plus symbol ‘+’ will be decoded to a space character)

#### Defined in

[main.ts:39488](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39488)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:39496](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39496)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:39494](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39494)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Defined in

[main.ts:39492](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39492)

___


### se\_results\_count

• `Optional` **se\_results\_count**: `number`

total number of results in SERP

#### Defined in

[main.ts:39515](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39515)

___


### spell

• `Optional` **spell**: [`SpellInfo`](../classes/SpellInfo.md)

autocorrection of the search engine
if the search engine provided results for a keyword that was corrected, we will specify the keyword corrected by the search engine and the type of autocorrection

#### Defined in

[main.ts:39508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39508)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:39490](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L39490)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")