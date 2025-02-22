[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleTrendsExploreLiveResultInfo

# Class: KeywordsDataGoogleTrendsExploreLiveResultInfo

## Implements

- [`IKeywordsDataGoogleTrendsExploreLiveResultInfo`](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#constructor)

### Properties

- [check\_url](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#check_url)
- [datetime](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#datetime)
- [items](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#items)
- [items\_count](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#items_count)
- [keywords](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#keywords)
- [language\_code](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#language_code)
- [location\_code](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#location_code)
- [type](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#type)

### Methods

- [init](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#init)
- [toJSON](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#tojson)
- [fromJS](KeywordsDataGoogleTrendsExploreLiveResultInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleTrendsExploreLiveResultInfo**(`data?`): [`KeywordsDataGoogleTrendsExploreLiveResultInfo`](KeywordsDataGoogleTrendsExploreLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleTrendsExploreLiveResultInfo`](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md) |

#### Returns

[`KeywordsDataGoogleTrendsExploreLiveResultInfo`](KeywordsDataGoogleTrendsExploreLiveResultInfo.md)

#### Defined in

[main.ts:121719](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121719)

## Properties

### check\_url

• `Optional` **check\_url**: `string`

direct URL to the Google Trends results
you can use it to make sure that we provided accurate results

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[check_url](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#check_url)

#### Defined in

[main.ts:121706](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121706)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[datetime](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#datetime)

#### Defined in

[main.ts:121711](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121711)

___


### items

• `Optional` **items**: [`BaseGoogleTrendsItem`](BaseGoogleTrendsItem.md)[]

items on the Google Trends page

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[items](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#items)

#### Defined in

[main.ts:121715](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121715)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[items_count](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#items_count)

#### Defined in

[main.ts:121713](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121713)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords in a POST array

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[keywords](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#keywords)

#### Defined in

[main.ts:121695](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121695)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[language_code](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#language_code)

#### Defined in

[main.ts:121703](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121703)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array
if there is no data, then the value is null

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[location_code](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#location_code)

#### Defined in

[main.ts:121700](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121700)

___


### type

• `Optional` **type**: `string`

type of element

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveResultInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md).[type](../interfaces/IKeywordsDataGoogleTrendsExploreLiveResultInfo.md#type)

#### Defined in

[main.ts:121697](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121697)

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

[main.ts:121728](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121728)

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

[main.ts:121760](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121760)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleTrendsExploreLiveResultInfo`](KeywordsDataGoogleTrendsExploreLiveResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleTrendsExploreLiveResultInfo`](KeywordsDataGoogleTrendsExploreLiveResultInfo.md)

#### Defined in

[main.ts:121753](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121753)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")