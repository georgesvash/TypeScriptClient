[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBacklinksAnchorsLiveItem

# Interface: IBacklinksAnchorsLiveItem

## Implemented by

- [`BacklinksAnchorsLiveItem`](../classes/BacklinksAnchorsLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [anchor](IBacklinksAnchorsLiveItem.md#anchor)
- [backlinks](IBacklinksAnchorsLiveItem.md#backlinks)
- [backlinks\_spam\_score](IBacklinksAnchorsLiveItem.md#backlinks_spam_score)
- [broken\_backlinks](IBacklinksAnchorsLiveItem.md#broken_backlinks)
- [broken\_pages](IBacklinksAnchorsLiveItem.md#broken_pages)
- [first\_seen](IBacklinksAnchorsLiveItem.md#first_seen)
- [lost\_date](IBacklinksAnchorsLiveItem.md#lost_date)
- [rank](IBacklinksAnchorsLiveItem.md#rank)
- [referring\_domains](IBacklinksAnchorsLiveItem.md#referring_domains)
- [referring\_domains\_nofollow](IBacklinksAnchorsLiveItem.md#referring_domains_nofollow)
- [referring\_ips](IBacklinksAnchorsLiveItem.md#referring_ips)
- [referring\_links\_attributes](IBacklinksAnchorsLiveItem.md#referring_links_attributes)
- [referring\_links\_countries](IBacklinksAnchorsLiveItem.md#referring_links_countries)
- [referring\_links\_platform\_types](IBacklinksAnchorsLiveItem.md#referring_links_platform_types)
- [referring\_links\_semantic\_locations](IBacklinksAnchorsLiveItem.md#referring_links_semantic_locations)
- [referring\_links\_tld](IBacklinksAnchorsLiveItem.md#referring_links_tld)
- [referring\_links\_types](IBacklinksAnchorsLiveItem.md#referring_links_types)
- [referring\_main\_domains](IBacklinksAnchorsLiveItem.md#referring_main_domains)
- [referring\_main\_domains\_nofollow](IBacklinksAnchorsLiveItem.md#referring_main_domains_nofollow)
- [referring\_pages](IBacklinksAnchorsLiveItem.md#referring_pages)
- [referring\_subnets](IBacklinksAnchorsLiveItem.md#referring_subnets)
- [type](IBacklinksAnchorsLiveItem.md#type)

## Properties

### anchor

• `Optional` **anchor**: `string`

anchor of the backlink

#### Defined in

[main.ts:132197](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132197)

___


### backlinks

• `Optional` **backlinks**: `number`

indicates the number of backlinks

#### Defined in

[main.ts:132204](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132204)

___


### backlinks\_spam\_score

• `Optional` **backlinks\_spam\_score**: `number`

average spam score of all backlinks with this anchor
learn more about how the metric is calculated on this help center page

#### Defined in

[main.ts:132218](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132218)

___


### broken\_backlinks

• `Optional` **broken\_backlinks**: `number`

number of broken backlinks
number of broken backlinks pointing to the target

#### Defined in

[main.ts:132221](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132221)

___


### broken\_pages

• `Optional` **broken\_pages**: `number`

number of broken pages
number of pages that respond with 4xx or 5xx status codes where backlinks are pointing to

#### Defined in

[main.ts:132224](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132224)

___


### first\_seen

• `Optional` **first\_seen**: `string`

date and time when our crawler found the backlink for the first time
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:132209](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132209)

___


### lost\_date

• `Optional` **lost\_date**: `string`

date and time when the last backlink with this anchor was lost
indicates the date and time when our crawler visited the page and it responded with 4xx or 5xx status code or the last backlink was removed
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2017-01-24 13:20:59 +00:00

#### Defined in

[main.ts:132215](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132215)

___


### rank

• `Optional` **rank**: `number`

rank of the anchor links
rank volume that referring websites pass to the target through links with a particular anchor
rank is calculated based on the method for node ranking in a linked database – a principle used in the original Google PageRank algorithm
learn more about the metric and how it is calculated in this help center article

#### Defined in

[main.ts:132202](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132202)

___


### referring\_domains

• `Optional` **referring\_domains**: `number`

indicates the number of referring domains

#### Defined in

[main.ts:132226](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132226)

___


### referring\_domains\_nofollow

• `Optional` **referring\_domains\_nofollow**: `number`

number of domains pointing at least one nofollow link to the target

#### Defined in

[main.ts:132228](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132228)

___


### referring\_ips

• `Optional` **referring\_ips**: `number`

number of referring IP addresses
number of IP addresses pointing to this page

#### Defined in

[main.ts:132235](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132235)

___


### referring\_links\_attributes

• `Optional` **referring\_links\_attributes**: `Object`

link attributes of the referring links
indicates link attributes of the referring links and link count per each attribute

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:132250](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132250)

___


### referring\_links\_countries

• `Optional` **referring\_links\_countries**: `Object`

ISO country codes of the referring links
indicates ISO country codes of the domains where the referring links are located and the link count per each country

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:132262](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132262)

___


### referring\_links\_platform\_types

• `Optional` **referring\_links\_platform\_types**: `Object`

types of referring platforms
indicates referring platform types and and link count per each platform

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:132253](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132253)

___


### referring\_links\_semantic\_locations

• `Optional` **referring\_links\_semantic\_locations**: `Object`

semantic locations of the referring links
indicates semantic elements in HTML where the referring links are located and link count per each semantic location
you can get the full list of semantic elements here
examples:
article, section, summary

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:132259](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132259)

___


### referring\_links\_tld

• `Optional` **referring\_links\_tld**: `Object`

top-level domains of the referring links
contains top level domains and referring link count per each

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:132242](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132242)

___


### referring\_links\_types

• `Optional` **referring\_links\_types**: `Object`

types of referring links
indicates the types of the referring links and link count per each type
possible values:
anchor, image, link, meta, canonical, alternate, redirect

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:132247](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132247)

___


### referring\_main\_domains

• `Optional` **referring\_main\_domains**: `number`

indicates the number of referring main domains

#### Defined in

[main.ts:132230](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132230)

___


### referring\_main\_domains\_nofollow

• `Optional` **referring\_main\_domains\_nofollow**: `number`

number of main domains pointing at least one nofollow link to the target

#### Defined in

[main.ts:132232](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132232)

___


### referring\_pages

• `Optional` **referring\_pages**: `number`

indicates the number of pages pointing to target with this anchor

#### Defined in

[main.ts:132239](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132239)

___


### referring\_subnets

• `Optional` **referring\_subnets**: `number`

number of referring subnetworks

#### Defined in

[main.ts:132237](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132237)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:132195](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L132195)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")