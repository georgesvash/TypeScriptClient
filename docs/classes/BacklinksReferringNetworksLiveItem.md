[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksReferringNetworksLiveItem

# Class: BacklinksReferringNetworksLiveItem

## Implements

- [`IBacklinksReferringNetworksLiveItem`](../interfaces/IBacklinksReferringNetworksLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksReferringNetworksLiveItem.md#constructor)

### Properties

- [backlinks](BacklinksReferringNetworksLiveItem.md#backlinks)
- [broken\_backlinks](BacklinksReferringNetworksLiveItem.md#broken_backlinks)
- [broken\_pages](BacklinksReferringNetworksLiveItem.md#broken_pages)
- [first\_seen](BacklinksReferringNetworksLiveItem.md#first_seen)
- [lost\_date](BacklinksReferringNetworksLiveItem.md#lost_date)
- [network\_address](BacklinksReferringNetworksLiveItem.md#network_address)
- [rank](BacklinksReferringNetworksLiveItem.md#rank)
- [referring\_domains](BacklinksReferringNetworksLiveItem.md#referring_domains)
- [referring\_domains\_nofollow](BacklinksReferringNetworksLiveItem.md#referring_domains_nofollow)
- [referring\_ips](BacklinksReferringNetworksLiveItem.md#referring_ips)
- [referring\_links\_attributes](BacklinksReferringNetworksLiveItem.md#referring_links_attributes)
- [referring\_links\_countries](BacklinksReferringNetworksLiveItem.md#referring_links_countries)
- [referring\_links\_platform\_types](BacklinksReferringNetworksLiveItem.md#referring_links_platform_types)
- [referring\_links\_semantic\_locations](BacklinksReferringNetworksLiveItem.md#referring_links_semantic_locations)
- [referring\_links\_tld](BacklinksReferringNetworksLiveItem.md#referring_links_tld)
- [referring\_links\_types](BacklinksReferringNetworksLiveItem.md#referring_links_types)
- [referring\_main\_domains](BacklinksReferringNetworksLiveItem.md#referring_main_domains)
- [referring\_main\_domains\_nofollow](BacklinksReferringNetworksLiveItem.md#referring_main_domains_nofollow)
- [referring\_pages](BacklinksReferringNetworksLiveItem.md#referring_pages)
- [referring\_subnets](BacklinksReferringNetworksLiveItem.md#referring_subnets)
- [type](BacklinksReferringNetworksLiveItem.md#type)

### Methods

- [init](BacklinksReferringNetworksLiveItem.md#init)
- [toJSON](BacklinksReferringNetworksLiveItem.md#tojson)
- [fromJS](BacklinksReferringNetworksLiveItem.md#fromjs)

## Constructors

### constructor

• **new BacklinksReferringNetworksLiveItem**(`data?`): [`BacklinksReferringNetworksLiveItem`](BacklinksReferringNetworksLiveItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksReferringNetworksLiveItem`](../interfaces/IBacklinksReferringNetworksLiveItem.md) |

#### Returns

[`BacklinksReferringNetworksLiveItem`](BacklinksReferringNetworksLiveItem.md)

#### Defined in

[main.ts:135518](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135518)

## Properties

### backlinks

• `Optional` **backlinks**: `number`

indicates the number of backlinks pointing to the target

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[backlinks](../interfaces/IBacklinksReferringNetworksLiveItem.md#backlinks)

#### Defined in

[main.ts:135458](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135458)

___


### broken\_backlinks

• `Optional` **broken\_backlinks**: `number`

number of broken backlinks
number of broken backlinks pointing to the domain

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[broken_backlinks](../interfaces/IBacklinksReferringNetworksLiveItem.md#broken_backlinks)

#### Defined in

[main.ts:135472](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135472)

___


### broken\_pages

• `Optional` **broken\_pages**: `number`

number of broken pages
number of pages that respond with 4xx or 5xx status codes where backlinks are pointing to

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[broken_pages](../interfaces/IBacklinksReferringNetworksLiveItem.md#broken_pages)

#### Defined in

[main.ts:135475](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135475)

___


### first\_seen

• `Optional` **first\_seen**: `string`

date and time when our crawler found the backlink for the first time
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[first_seen](../interfaces/IBacklinksReferringNetworksLiveItem.md#first_seen)

#### Defined in

[main.ts:135463](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135463)

___


### lost\_date

• `Optional` **lost\_date**: `string`

date and time when the last backlink from this domain was lost
indicates the date and time when our crawler visited the page and it responded with 4xx or 5xx status code or the last backlink was removed
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2017-01-24 13:20:59 +00:00

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[lost_date](../interfaces/IBacklinksReferringNetworksLiveItem.md#lost_date)

#### Defined in

[main.ts:135469](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135469)

___


### network\_address

• `Optional` **network\_address**: `string`

address of the referring subnetwork or IP

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[network_address](../interfaces/IBacklinksReferringNetworksLiveItem.md#network_address)

#### Defined in

[main.ts:135451](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135451)

___


### rank

• `Optional` **rank**: `number`

network rank
rank volume that a referring network passes to the target
rank is calculated based on the method for node ranking in a linked database – a principle used in the original Google PageRank algorithm
learn more about the metric and how it is calculated in this help center article

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[rank](../interfaces/IBacklinksReferringNetworksLiveItem.md#rank)

#### Defined in

[main.ts:135456](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135456)

___


### referring\_domains

• `Optional` **referring\_domains**: `number`

indicates the number of referring domains
referring domains include subdomains that are counted as separate domains for this metric

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_domains](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_domains)

#### Defined in

[main.ts:135478](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135478)

___


### referring\_domains\_nofollow

• `Optional` **referring\_domains\_nofollow**: `number`

number of domains pointing at least one nofollow link to the target

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_domains_nofollow](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_domains_nofollow)

#### Defined in

[main.ts:135480](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135480)

___


### referring\_ips

• `Optional` **referring\_ips**: `number`

number of referring IP addresses
number of IP addresses pointing to this page

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_ips](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_ips)

#### Defined in

[main.ts:135487](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135487)

___


### referring\_links\_attributes

• `Optional` **referring\_links\_attributes**: `Object`

link attributes of the referring links
indicates link attributes of the referring links and link count per each attribute

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_links_attributes](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_links_attributes)

#### Defined in

[main.ts:135502](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135502)

___


### referring\_links\_countries

• `Optional` **referring\_links\_countries**: `Object`

ISO country codes of the referring links
indicates ISO country codes of the domains where the referring links are located and the link count per each country

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_links_countries](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_links_countries)

#### Defined in

[main.ts:135514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135514)

___


### referring\_links\_platform\_types

• `Optional` **referring\_links\_platform\_types**: `Object`

types of referring platforms
indicates referring platform types and and link count per each platform

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_links_platform_types](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_links_platform_types)

#### Defined in

[main.ts:135505](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135505)

___


### referring\_links\_semantic\_locations

• `Optional` **referring\_links\_semantic\_locations**: `Object`

semantic locations of the referring links
indicates semantic elements in HTML where the referring links are located and the link count per each semantic location
you can get the full list of semantic elements here
examples:
article, section, summary

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_links_semantic_locations](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_links_semantic_locations)

#### Defined in

[main.ts:135511](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135511)

___


### referring\_links\_tld

• `Optional` **referring\_links\_tld**: `Object`

top-level domains of the referring links
contains top level domains and referring link count per each

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_links_tld](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_links_tld)

#### Defined in

[main.ts:135494](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135494)

___


### referring\_links\_types

• `Optional` **referring\_links\_types**: `Object`

types of referring links
indicates the types of the referring links and link count per each type
possible values:
anchor, image, link, meta, canonical, alternate, redirect

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_links_types](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_links_types)

#### Defined in

[main.ts:135499](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135499)

___


### referring\_main\_domains

• `Optional` **referring\_main\_domains**: `number`

indicates the number of referring main domains

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_main_domains](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_main_domains)

#### Defined in

[main.ts:135482](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135482)

___


### referring\_main\_domains\_nofollow

• `Optional` **referring\_main\_domains\_nofollow**: `number`

number of main domains pointing at least one nofollow link to the target

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_main_domains_nofollow](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_main_domains_nofollow)

#### Defined in

[main.ts:135484](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135484)

___


### referring\_pages

• `Optional` **referring\_pages**: `number`

indicates the number of pages pointing to the target specified

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_pages](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_pages)

#### Defined in

[main.ts:135491](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135491)

___


### referring\_subnets

• `Optional` **referring\_subnets**: `number`

number of referring subnetworks

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[referring_subnets](../interfaces/IBacklinksReferringNetworksLiveItem.md#referring_subnets)

#### Defined in

[main.ts:135489](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135489)

___


### type

• `Optional` **type**: `string`

type of element

#### Implementation of

[IBacklinksReferringNetworksLiveItem](../interfaces/IBacklinksReferringNetworksLiveItem.md).[type](../interfaces/IBacklinksReferringNetworksLiveItem.md#type)

#### Defined in

[main.ts:135449](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135449)

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

[main.ts:135527](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135527)

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

[main.ts:135600](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135600)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksReferringNetworksLiveItem`](BacklinksReferringNetworksLiveItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksReferringNetworksLiveItem`](BacklinksReferringNetworksLiveItem.md)

#### Defined in

[main.ts:135593](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135593)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")