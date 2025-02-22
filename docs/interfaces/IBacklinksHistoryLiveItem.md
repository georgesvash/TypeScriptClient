[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBacklinksHistoryLiveItem

# Interface: IBacklinksHistoryLiveItem

## Implemented by

- [`BacklinksHistoryLiveItem`](../classes/BacklinksHistoryLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [backlinks](IBacklinksHistoryLiveItem.md#backlinks)
- [broken\_backlinks](IBacklinksHistoryLiveItem.md#broken_backlinks)
- [broken\_pages](IBacklinksHistoryLiveItem.md#broken_pages)
- [crawled\_pages](IBacklinksHistoryLiveItem.md#crawled_pages)
- [date](IBacklinksHistoryLiveItem.md#date)
- [external\_links\_count](IBacklinksHistoryLiveItem.md#external_links_count)
- [info](IBacklinksHistoryLiveItem.md#info)
- [internal\_links\_count](IBacklinksHistoryLiveItem.md#internal_links_count)
- [lost\_backlinks](IBacklinksHistoryLiveItem.md#lost_backlinks)
- [lost\_referring\_domains](IBacklinksHistoryLiveItem.md#lost_referring_domains)
- [new\_backlinks](IBacklinksHistoryLiveItem.md#new_backlinks)
- [new\_referring\_domains](IBacklinksHistoryLiveItem.md#new_referring_domains)
- [rank](IBacklinksHistoryLiveItem.md#rank)
- [referring\_domains](IBacklinksHistoryLiveItem.md#referring_domains)
- [referring\_domains\_nofollow](IBacklinksHistoryLiveItem.md#referring_domains_nofollow)
- [referring\_ips](IBacklinksHistoryLiveItem.md#referring_ips)
- [referring\_links\_attributes](IBacklinksHistoryLiveItem.md#referring_links_attributes)
- [referring\_links\_countries](IBacklinksHistoryLiveItem.md#referring_links_countries)
- [referring\_links\_platform\_types](IBacklinksHistoryLiveItem.md#referring_links_platform_types)
- [referring\_links\_semantic\_locations](IBacklinksHistoryLiveItem.md#referring_links_semantic_locations)
- [referring\_links\_tld](IBacklinksHistoryLiveItem.md#referring_links_tld)
- [referring\_links\_types](IBacklinksHistoryLiveItem.md#referring_links_types)
- [referring\_main\_domains](IBacklinksHistoryLiveItem.md#referring_main_domains)
- [referring\_main\_domains\_nofollow](IBacklinksHistoryLiveItem.md#referring_main_domains_nofollow)
- [referring\_pages](IBacklinksHistoryLiveItem.md#referring_pages)
- [referring\_subnets](IBacklinksHistoryLiveItem.md#referring_subnets)
- [type](IBacklinksHistoryLiveItem.md#type)

## Properties

### backlinks

• `Optional` **backlinks**: `number`

number of backlinks

#### Defined in

[main.ts:130269](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130269)

___


### broken\_backlinks

• `Optional` **broken\_backlinks**: `number`

number of broken backlinks
number of broken backlinks pointing to the target

#### Defined in

[main.ts:130302](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130302)

___


### broken\_pages

• `Optional` **broken\_pages**: `number`

number of broken pages
number of pages that receive backlinks but respond with 4xx or 5xx status codes

#### Defined in

[main.ts:130305](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130305)

___


### crawled\_pages

• `Optional` **crawled\_pages**: `number`

number of crawled pages for the target

#### Defined in

[main.ts:130291](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130291)

___


### date

• `Optional` **date**: `string`

date and time when the data for the target was stored
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:130264](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130264)

___


### external\_links\_count

• `Optional` **external\_links\_count**: `number`

number of external links on the page
calculated as the sum of external links on the pages of the specified target

#### Defined in

[main.ts:130299](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130299)

___


### info

• `Optional` **info**: [`TargetInfo`](../classes/TargetInfo.md)

information about the target

#### Defined in

[main.ts:130293](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130293)

___


### internal\_links\_count

• `Optional` **internal\_links\_count**: `number`

number of internal links
calculated as the sum of internal links on the pages of the specified target

#### Defined in

[main.ts:130296](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130296)

___


### lost\_backlinks

• `Optional` **lost\_backlinks**: `number`

number of lost backlinks for the target
data is provided based in a comparison with the previous period
Note: this data is available from May 2021;
if the date range specified in the POST request preceds May 2021, the field will equal 0

#### Defined in

[main.ts:130279](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130279)

___


### lost\_referring\_domains

• `Optional` **lost\_referring\_domains**: `number`

number of lost referring domains for the target
data is provided based in a comparison with the previous period
Note: this data is available from May 2021;
if the date range specified in the POST request preceds May 2021, the field will equal 0

#### Defined in

[main.ts:130289](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130289)

___


### new\_backlinks

• `Optional` **new\_backlinks**: `number`

number of new backlinks for the target
data is provided based in a comparison with the previous period
Note: this data is available from May 2021;
if the date range specified in the POST request preceds May 2021, the field will equal 0

#### Defined in

[main.ts:130274](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130274)

___


### new\_referring\_domains

• `Optional` **new\_referring\_domains**: `number`

number of new referring domains for the target
data is provided based in a comparison with the previous period
Note: this data is available from May 2021;
if the date range specified in the POST request preceds May 2021, the field will equal 0

#### Defined in

[main.ts:130284](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130284)

___


### rank

• `Optional` **rank**: `number`

domain rank on the given date
learn more about the metric and how it is calculated in this help center article

#### Defined in

[main.ts:130267](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130267)

___


### referring\_domains

• `Optional` **referring\_domains**: `number`

number of referring domains
referring domains include subdomains that are counted as separate domains for this metric

#### Defined in

[main.ts:130308](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130308)

___


### referring\_domains\_nofollow

• `Optional` **referring\_domains\_nofollow**: `number`

number of domains pointing at least one nofollow link to the target

#### Defined in

[main.ts:130310](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130310)

___


### referring\_ips

• `Optional` **referring\_ips**: `number`

number of referring IP addresses
number of IP addresses pointing to this page

#### Defined in

[main.ts:130317](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130317)

___


### referring\_links\_attributes

• `Optional` **referring\_links\_attributes**: `Object`

link attributes of the referring links
indicates link attributes of the referring links and link count per each attribute

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:130332](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130332)

___


### referring\_links\_countries

• `Optional` **referring\_links\_countries**: `Object`

ISO country codes of the referring links
indicates ISO country codes of the domains where the referring links are located and the link count per each country

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:130344](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130344)

___


### referring\_links\_platform\_types

• `Optional` **referring\_links\_platform\_types**: `Object`

types of referring platforms
indicates referring platform types and and link count per each platform

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:130335](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130335)

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

[main.ts:130341](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130341)

___


### referring\_links\_tld

• `Optional` **referring\_links\_tld**: `Object`

top-level domains of the referring links
contains top-level domains and referring link count per each

#### Index signature

▪ [key: `string`]: `number`

#### Defined in

[main.ts:130324](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130324)

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

[main.ts:130329](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130329)

___


### referring\_main\_domains

• `Optional` **referring\_main\_domains**: `number`

number of referring main domains

#### Defined in

[main.ts:130312](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130312)

___


### referring\_main\_domains\_nofollow

• `Optional` **referring\_main\_domains\_nofollow**: `number`

number of main domains pointing at least one nofollow link to the target

#### Defined in

[main.ts:130314](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130314)

___


### referring\_pages

• `Optional` **referring\_pages**: `number`

number of pages pointing to the target

#### Defined in

[main.ts:130321](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130321)

___


### referring\_subnets

• `Optional` **referring\_subnets**: `number`

number of referring subnetworks

#### Defined in

[main.ts:130319](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130319)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:130259](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130259)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")