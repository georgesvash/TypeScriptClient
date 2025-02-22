[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpGoogleImagesLiveAdvancedResultInfo

# Interface: ISerpGoogleImagesLiveAdvancedResultInfo

## Implemented by

- [`SerpGoogleImagesLiveAdvancedResultInfo`](../classes/SerpGoogleImagesLiveAdvancedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [check\_url](ISerpGoogleImagesLiveAdvancedResultInfo.md#check_url)
- [datetime](ISerpGoogleImagesLiveAdvancedResultInfo.md#datetime)
- [item\_types](ISerpGoogleImagesLiveAdvancedResultInfo.md#item_types)
- [items](ISerpGoogleImagesLiveAdvancedResultInfo.md#items)
- [items\_count](ISerpGoogleImagesLiveAdvancedResultInfo.md#items_count)
- [keyword](ISerpGoogleImagesLiveAdvancedResultInfo.md#keyword)
- [language\_code](ISerpGoogleImagesLiveAdvancedResultInfo.md#language_code)
- [location\_code](ISerpGoogleImagesLiveAdvancedResultInfo.md#location_code)
- [se\_domain](ISerpGoogleImagesLiveAdvancedResultInfo.md#se_domain)
- [se\_results\_count](ISerpGoogleImagesLiveAdvancedResultInfo.md#se_results_count)
- [spell](ISerpGoogleImagesLiveAdvancedResultInfo.md#spell)
- [type](ISerpGoogleImagesLiveAdvancedResultInfo.md#type)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided accurate results

#### Defined in

[main.ts:46800](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46800)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:46805](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46805)

___


### item\_types

• `Optional` **item\_types**: `string`[]

types of search results in SERP
contains types of search results (items) found in SERP.
possible item types:
carousel, images_search, related_searches

#### Defined in

[main.ts:46813](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46813)

___


### items

• `Optional` **items**: [`BaseSerpElementItem`](../classes/BaseSerpElementItem.md)[]

contains keywords and images related to the specified search term

#### Defined in

[main.ts:46819](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46819)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Defined in

[main.ts:46817](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46817)

___


### keyword

• `Optional` **keyword**: `string`

keyword received in a POST array
the keyword is returned with decoded %## (plus symbol ‘+’ will be decoded to a space character)

#### Defined in

[main.ts:46789](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46789)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:46797](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46797)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:46795](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46795)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Defined in

[main.ts:46793](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46793)

___


### se\_results\_count

• `Optional` **se\_results\_count**: `number`

total number of results in SERP

#### Defined in

[main.ts:46815](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46815)

___


### spell

• `Optional` **spell**: [`SpellInfo`](../classes/SpellInfo.md)

autocorrection of the search engine
if the search engine provided results for a keyword that was corrected, we will specify the keyword corrected by the search engine and the type of autocorrection

#### Defined in

[main.ts:46808](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46808)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:46791](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46791)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")