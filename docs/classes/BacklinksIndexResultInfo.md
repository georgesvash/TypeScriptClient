[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksIndexResultInfo

# Class: BacklinksIndexResultInfo

## Implements

- [`IBacklinksIndexResultInfo`](../interfaces/IBacklinksIndexResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksIndexResultInfo.md#constructor)

### Properties

- [index\_history](BacklinksIndexResultInfo.md#index_history)
- [total\_backlinks](BacklinksIndexResultInfo.md#total_backlinks)
- [total\_domains](BacklinksIndexResultInfo.md#total_domains)
- [total\_pages](BacklinksIndexResultInfo.md#total_pages)

### Methods

- [init](BacklinksIndexResultInfo.md#init)
- [toJSON](BacklinksIndexResultInfo.md#tojson)
- [fromJS](BacklinksIndexResultInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksIndexResultInfo**(`data?`): [`BacklinksIndexResultInfo`](BacklinksIndexResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksIndexResultInfo`](../interfaces/IBacklinksIndexResultInfo.md) |

#### Returns

[`BacklinksIndexResultInfo`](BacklinksIndexResultInfo.md)

#### Defined in

[main.ts:129023](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129023)

## Properties

### index\_history

• `Optional` **index\_history**: [`IndexHistory`](IndexHistory.md)[]

index volume data for the past 12 months

#### Implementation of

[IBacklinksIndexResultInfo](../interfaces/IBacklinksIndexResultInfo.md).[index_history](../interfaces/IBacklinksIndexResultInfo.md#index_history)

#### Defined in

[main.ts:129019](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129019)

___


### total\_backlinks

• `Optional` **total\_backlinks**: `number`

total number of backlinks our database contains for the moment of checking

#### Implementation of

[IBacklinksIndexResultInfo](../interfaces/IBacklinksIndexResultInfo.md).[total_backlinks](../interfaces/IBacklinksIndexResultInfo.md#total_backlinks)

#### Defined in

[main.ts:129013](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129013)

___


### total\_domains

• `Optional` **total\_domains**: `number`

total number of domains our database contains for the moment of checking

#### Implementation of

[IBacklinksIndexResultInfo](../interfaces/IBacklinksIndexResultInfo.md).[total_domains](../interfaces/IBacklinksIndexResultInfo.md#total_domains)

#### Defined in

[main.ts:129017](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129017)

___


### total\_pages

• `Optional` **total\_pages**: `number`

total number of pages our database contains for the moment of checking

#### Implementation of

[IBacklinksIndexResultInfo](../interfaces/IBacklinksIndexResultInfo.md).[total_pages](../interfaces/IBacklinksIndexResultInfo.md#total_pages)

#### Defined in

[main.ts:129015](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129015)

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

[main.ts:129032](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129032)

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

[main.ts:129056](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129056)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksIndexResultInfo`](BacklinksIndexResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksIndexResultInfo`](BacklinksIndexResultInfo.md)

#### Defined in

[main.ts:129049](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129049)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")