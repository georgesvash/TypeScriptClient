[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBacklinksDomainPagesSummaryLiveItem

# Interface: IBacklinksDomainPagesSummaryLiveItem

## Implemented by

- [`BacklinksDomainPagesSummaryLiveItem`](../classes/BacklinksDomainPagesSummaryLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [backlinks](IBacklinksDomainPagesSummaryLiveItem.md#backlinks)
- [backlinks\_spam\_score](IBacklinksDomainPagesSummaryLiveItem.md#backlinks_spam_score)
- [broken\_backlinks](IBacklinksDomainPagesSummaryLiveItem.md#broken_backlinks)
- [broken\_pages](IBacklinksDomainPagesSummaryLiveItem.md#broken_pages)
- [first\_seen](IBacklinksDomainPagesSummaryLiveItem.md#first_seen)
- [lost\_date](IBacklinksDomainPagesSummaryLiveItem.md#lost_date)
- [rank](IBacklinksDomainPagesSummaryLiveItem.md#rank)
- [referring\_domains](IBacklinksDomainPagesSummaryLiveItem.md#referring_domains)
- [referring\_domains\_nofollow](IBacklinksDomainPagesSummaryLiveItem.md#referring_domains_nofollow)
- [referring\_ips](IBacklinksDomainPagesSummaryLiveItem.md#referring_ips)
- [referring\_links\_attributes](IBacklinksDomainPagesSummaryLiveItem.md#referring_links_attributes)
- [referring\_links\_countries](IBacklinksDomainPagesSummaryLiveItem.md#referring_links_countries)
- [referring\_links\_platform\_types](IBacklinksDomainPagesSummaryLiveItem.md#referring_links_platform_types)
- [referring\_links\_semantic\_locations](IBacklinksDomainPagesSummaryLiveItem.md#referring_links_semantic_locations)
- [referring\_links\_tld](IBacklinksDomainPagesSummaryLiveItem.md#referring_links_tld)
- [referring\_links\_types](IBacklinksDomainPagesSummaryLiveItem.md#referring_links_types)
- [referring\_main\_domains](IBacklinksDomainPagesSummaryLiveItem.md#referring_main_domains)
- [referring\_main\_domains\_nofollow](IBacklinksDomainPagesSummaryLiveItem.md#referring_main_domains_nofollow)
- [referring\_pages](IBacklinksDomainPagesSummaryLiveItem.md#referring_pages)
- [referring\_subnets](IBacklinksDomainPagesSummaryLiveItem.md#referring_subnets)
- [type](IBacklinksDomainPagesSummaryLiveItem.md#type)
- [url](IBacklinksDomainPagesSummaryLiveItem.md#url)

## Properties

### backlinks

• `Optional` **backlinks**: `number`

number of backlinks

#### Defined in

[main.ts:134126](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134126)

___


### backlinks\_spam\_score

• `Optional` **backlinks\_spam\_score**: `number`

average spam score of the backlinks pointing to the page
learn more about how the metric is calculated on this help center page

#### Defined in

[main.ts:134140](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134140)

___


### broken\_backlinks

• `Optional` **broken\_backlinks**: `number`

number of broken backlinks
number of broken backlinks pointing to the page

#### Defined in

[main.ts:134143](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134143)

___


### broken\_pages

• `Optional` **broken\_pages**: `number`

number of broken pages
number of pages that respond with 4xx or 5xx status codes where backlinks are pointing to

#### Defined in

[main.ts:134146](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134146)

___


### first\_seen

• `Optional` **first\_seen**: `string`

date and time when our crawler found a backlink to this page for the first time
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:134131](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134131)

___


### lost\_date

• `Optional` **lost\_date**: `string`

date and time when the last backlink to this page was lost
indicates the date and time when our crawler visited the page and it responded with 4xx or 5xx status code or the last backlink was removed
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2017-01-24 13:20:59 +00:00

#### Defined in

[main.ts:134137](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134137)

___


### rank

• `Optional` **rank**: `number`

page rank
rank of the page on the target website
rank is calculated based on the method for node ranking in a linked database – a principle used in the original Google PageRank algorithm
learn more about the metric and how it is calculated in this help center article

#### Defined in

[main.ts:134124](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134124)

___


### referring\_domains

• `Optional` **referring\_domains**: `number`

indicates the number domains referring to the page

#### Defined in

[main.ts:134148](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134148)

___


### referring\_domains\_nofollow

• `Optional` **referring\_domains\_nofollow**: `number`

number of domains pointing at least one nofollow link to the target

#### Defined in

[main.ts:134150](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134150)

___


### referring\_ips

• `Optional` **referring\_ips**: `number`

number of referring IP addresses
number of IP addresses pointing to this page

#### Defined in

[main.ts:134157](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134157)

___


### referring\_links\_attributes

• `Optional` **referring\_links\_attributes**: `Object`

link attributes of the referring links
indicates link attributes of the referring links and link count per each attribute

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:134172](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134172)

___


### referring\_links\_countries

• `Optional` **referring\_links\_countries**: `Object`

ISO country codes of the referring links
indicates ISO country codes of the domains where the referring links are located and the link count per each country

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:134184](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134184)

___


### referring\_links\_platform\_types

• `Optional` **referring\_links\_platform\_types**: `Object`

types of referring platforms
indicates referring platform types and and link count per each platform

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:134175](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134175)

___


### referring\_links\_semantic\_locations

• `Optional` **referring\_links\_semantic\_locations**: `Object`

semantic locations of the referring links
indicates semantic elements in HTML where the referring links are located and link count per each semantic location
you can get the full list of semantic elements here
examples:
article, section, footer

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:134181](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134181)

___


### referring\_links\_tld

• `Optional` **referring\_links\_tld**: `Object`

top-level domains of the referring links
contains top level domains and referring link count per each

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:134164](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134164)

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

[main.ts:134169](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134169)

___


### referring\_main\_domains

• `Optional` **referring\_main\_domains**: `number`

indicates the number of referring main domains

#### Defined in

[main.ts:134152](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134152)

___


### referring\_main\_domains\_nofollow

• `Optional` **referring\_main\_domains\_nofollow**: `number`

number of main domains pointing at least one nofollow link to the target

#### Defined in

[main.ts:134154](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134154)

___


### referring\_pages

• `Optional` **referring\_pages**: `number`

indicates the number of pages pointing to the relevant url

#### Defined in

[main.ts:134161](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134161)

___


### referring\_subnets

• `Optional` **referring\_subnets**: `number`

number of referring subnetworks

#### Defined in

[main.ts:134159](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134159)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:134117](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134117)

___


### url

• `Optional` **url**: `string`

page URL

#### Defined in

[main.ts:134119](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L134119)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")