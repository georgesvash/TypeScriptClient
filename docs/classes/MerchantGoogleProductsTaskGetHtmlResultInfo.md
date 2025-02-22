[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantGoogleProductsTaskGetHtmlResultInfo

# Class: MerchantGoogleProductsTaskGetHtmlResultInfo

## Implements

- [`IMerchantGoogleProductsTaskGetHtmlResultInfo`](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantGoogleProductsTaskGetHtmlResultInfo.md#constructor)

### Properties

- [datetime](MerchantGoogleProductsTaskGetHtmlResultInfo.md#datetime)
- [items](MerchantGoogleProductsTaskGetHtmlResultInfo.md#items)
- [items\_count](MerchantGoogleProductsTaskGetHtmlResultInfo.md#items_count)
- [keyword](MerchantGoogleProductsTaskGetHtmlResultInfo.md#keyword)
- [language\_code](MerchantGoogleProductsTaskGetHtmlResultInfo.md#language_code)
- [location\_code](MerchantGoogleProductsTaskGetHtmlResultInfo.md#location_code)
- [se\_domain](MerchantGoogleProductsTaskGetHtmlResultInfo.md#se_domain)
- [type](MerchantGoogleProductsTaskGetHtmlResultInfo.md#type)

### Methods

- [init](MerchantGoogleProductsTaskGetHtmlResultInfo.md#init)
- [toJSON](MerchantGoogleProductsTaskGetHtmlResultInfo.md#tojson)
- [fromJS](MerchantGoogleProductsTaskGetHtmlResultInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantGoogleProductsTaskGetHtmlResultInfo**(`data?`): [`MerchantGoogleProductsTaskGetHtmlResultInfo`](MerchantGoogleProductsTaskGetHtmlResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantGoogleProductsTaskGetHtmlResultInfo`](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md) |

#### Returns

[`MerchantGoogleProductsTaskGetHtmlResultInfo`](MerchantGoogleProductsTaskGetHtmlResultInfo.md)

#### Defined in

[main.ts:165651](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165651)

## Properties

### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[datetime](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#datetime)

#### Defined in

[main.ts:165643](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165643)

___


### items

• `Optional` **items**: [`HtmlItem`](HtmlItem.md)[]

elements of search results found on Google Shopping

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[items](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#items)

#### Defined in

[main.ts:165647](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165647)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of results returned in the items array

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[items_count](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#items_count)

#### Defined in

[main.ts:165645](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165645)

___


### keyword

• `Optional` **keyword**: `string`

keyword received in a POST array
keyword is returned with decoded %## (plus symbol ‘+’ will be decoded to a space character)

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[keyword](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#keyword)

#### Defined in

[main.ts:165630](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165630)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[language_code](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#language_code)

#### Defined in

[main.ts:165638](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165638)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[location_code](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#location_code)

#### Defined in

[main.ts:165636](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165636)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[se_domain](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#se_domain)

#### Defined in

[main.ts:165634](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165634)

___


### type

• `Optional` **type**: `string`

type of element

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlResultInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md).[type](../interfaces/IMerchantGoogleProductsTaskGetHtmlResultInfo.md#type)

#### Defined in

[main.ts:165632](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165632)

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

[main.ts:165660](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165660)

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

[main.ts:165688](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165688)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantGoogleProductsTaskGetHtmlResultInfo`](MerchantGoogleProductsTaskGetHtmlResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantGoogleProductsTaskGetHtmlResultInfo`](MerchantGoogleProductsTaskGetHtmlResultInfo.md)

#### Defined in

[main.ts:165681](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165681)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")