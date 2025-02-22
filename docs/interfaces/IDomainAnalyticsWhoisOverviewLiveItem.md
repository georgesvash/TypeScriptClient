[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDomainAnalyticsWhoisOverviewLiveItem

# Interface: IDomainAnalyticsWhoisOverviewLiveItem

items array

## Implemented by

- [`DomainAnalyticsWhoisOverviewLiveItem`](../classes/DomainAnalyticsWhoisOverviewLiveItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [backlinks\_info](IDomainAnalyticsWhoisOverviewLiveItem.md#backlinks_info)
- [changed\_datetime](IDomainAnalyticsWhoisOverviewLiveItem.md#changed_datetime)
- [created\_datetime](IDomainAnalyticsWhoisOverviewLiveItem.md#created_datetime)
- [domain](IDomainAnalyticsWhoisOverviewLiveItem.md#domain)
- [epp\_status\_codes](IDomainAnalyticsWhoisOverviewLiveItem.md#epp_status_codes)
- [expiration\_datetime](IDomainAnalyticsWhoisOverviewLiveItem.md#expiration_datetime)
- [first\_seen](IDomainAnalyticsWhoisOverviewLiveItem.md#first_seen)
- [metrics](IDomainAnalyticsWhoisOverviewLiveItem.md#metrics)
- [registered](IDomainAnalyticsWhoisOverviewLiveItem.md#registered)
- [registrar](IDomainAnalyticsWhoisOverviewLiveItem.md#registrar)
- [tld](IDomainAnalyticsWhoisOverviewLiveItem.md#tld)
- [updated\_datetime](IDomainAnalyticsWhoisOverviewLiveItem.md#updated_datetime)

## Properties

### backlinks\_info

• `Optional` **backlinks\_info**: [`BacklinksInfo`](../classes/BacklinksInfo.md)

backlink data for the returned domain

#### Defined in

[main.ts:76237](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76237)

___


### changed\_datetime

• `Optional` **changed\_datetime**: `string`

date and time when the domain entry was changed
date and time (in the ISO 8601 format) when the domain entry was last modified
example:
"2021-01-14 08:36:28 +00:00"

#### Defined in

[main.ts:76203](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76203)

___


### created\_datetime

• `Optional` **created\_datetime**: `string`

date and time of registration
date and time (in the ISO 8601 format) when the domain was first registered
example:
"1997-03-29 03:00:00 +00:00"

#### Defined in

[main.ts:76198](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76198)

___


### domain

• `Optional` **domain**: `string`

domain name

#### Defined in

[main.ts:76193](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76193)

___


### epp\_status\_codes

• `Optional` **epp\_status\_codes**: `string`[]

extensive provisioning protocol status codes
the status of a domain name registration as defined by ICANN

#### Defined in

[main.ts:76221](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76221)

___


### expiration\_datetime

• `Optional` **expiration\_datetime**: `string`

date and time when the domain will expire
date and time (in the ISO 8601 format) when the domain is due to expire
example:
"2022-11-26 17:21:23 +00:00"

#### Defined in

[main.ts:76208](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76208)

___


### first\_seen

• `Optional` **first\_seen**: `string`

date and time when our crawler found the domain for the first time
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
"2019-11-15 12:57:46 +00:00"

#### Defined in

[main.ts:76218](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76218)

___


### metrics

• `Optional` **metrics**: [`MetricsBundleInfo`](../classes/MetricsBundleInfo.md)

ranking data relevant to the specified domain

#### Defined in

[main.ts:76235](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76235)

___


### registered

• `Optional` **registered**: `boolean`

domain registration status
if false, the domain name registration has expired
Note: expired domains will remain in the database for only a short period of time

#### Defined in

[main.ts:76228](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76228)

___


### registrar

• `Optional` **registrar**: `string`

domain registrar
if null, the domain registrar is unknown
example:
NameCheap, Inc.

#### Defined in

[main.ts:76233](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76233)

___


### tld

• `Optional` **tld**: `string`

top-level domain
top-level domain in the DNS root zone

#### Defined in

[main.ts:76224](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76224)

___


### updated\_datetime

• `Optional` **updated\_datetime**: `string`

date and time when the domain was updated
date and time (in the ISO 8601 format) when the domain was last updated
example:
"2021-01-29 13:59:38 +00:00"

#### Defined in

[main.ts:76213](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76213)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")