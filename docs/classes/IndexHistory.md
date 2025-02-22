[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IndexHistory

# Class: IndexHistory

## Implements

- [`IIndexHistory`](../interfaces/IIndexHistory.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](IndexHistory.md#constructor)

### Properties

- [date](IndexHistory.md#date)
- [total\_backlinks](IndexHistory.md#total_backlinks)
- [total\_domains](IndexHistory.md#total_domains)
- [total\_pages](IndexHistory.md#total_pages)

### Methods

- [init](IndexHistory.md#init)
- [toJSON](IndexHistory.md#tojson)
- [fromJS](IndexHistory.md#fromjs)

## Constructors

### constructor

• **new IndexHistory**(`data?`): [`IndexHistory`](IndexHistory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IIndexHistory`](../interfaces/IIndexHistory.md) |

#### Returns

[`IndexHistory`](IndexHistory.md)

#### Defined in

[main.ts:128952](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128952)

## Properties

### date

• `Optional` **date**: `string`

date for which index volume data is provided
in the UTC format: “yyyy-mm-dd”
example:
2021-10-01

#### Implementation of

[IIndexHistory](../interfaces/IIndexHistory.md).[date](../interfaces/IIndexHistory.md#date)

#### Defined in

[main.ts:128942](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128942)

___


### total\_backlinks

• `Optional` **total\_backlinks**: `number`

total number of backlinks our database contained on the given date

#### Implementation of

[IIndexHistory](../interfaces/IIndexHistory.md).[total_backlinks](../interfaces/IIndexHistory.md#total_backlinks)

#### Defined in

[main.ts:128944](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128944)

___


### total\_domains

• `Optional` **total\_domains**: `number`

total number of domains our database contained on the given date

#### Implementation of

[IIndexHistory](../interfaces/IIndexHistory.md).[total_domains](../interfaces/IIndexHistory.md#total_domains)

#### Defined in

[main.ts:128948](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128948)

___


### total\_pages

• `Optional` **total\_pages**: `number`

total number of pages our database contained on the given date

#### Implementation of

[IIndexHistory](../interfaces/IIndexHistory.md).[total_pages](../interfaces/IIndexHistory.md#total_pages)

#### Defined in

[main.ts:128946](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128946)

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

[main.ts:128961](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128961)

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

[main.ts:128981](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128981)

___


### fromJS

▸ **fromJS**(`data`): [`IndexHistory`](IndexHistory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`IndexHistory`](IndexHistory.md)

#### Defined in

[main.ts:128974](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128974)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")