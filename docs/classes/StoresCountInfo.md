[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / StoresCountInfo

# Class: StoresCountInfo

## Implements

- [`IStoresCountInfo`](../interfaces/IStoresCountInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](StoresCountInfo.md#constructor)

### Properties

- [count](StoresCountInfo.md#count)
- [count\_from\_text](StoresCountInfo.md#count_from_text)
- [displayed\_text](StoresCountInfo.md#displayed_text)

### Methods

- [init](StoresCountInfo.md#init)
- [toJSON](StoresCountInfo.md#tojson)
- [fromJS](StoresCountInfo.md#fromjs)

## Constructors

### constructor

• **new StoresCountInfo**(`data?`): [`StoresCountInfo`](StoresCountInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IStoresCountInfo`](../interfaces/IStoresCountInfo.md) |

#### Returns

[`StoresCountInfo`](StoresCountInfo.md)

#### Defined in

[main.ts:164597](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164597)

## Properties

### count

• `Optional` **count**: `string`

number of stores that offer the product

#### Implementation of

[IStoresCountInfo](../interfaces/IStoresCountInfo.md).[count](../interfaces/IStoresCountInfo.md#count)

#### Defined in

[main.ts:164585](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164585)

___


### count\_from\_text

• `Optional` **count\_from\_text**: `boolean`

whether the number of stores is taken from text
indicates whether the number of stores is taken from displayed_text;
if the API finds the exact number of stores in the HTML code of the Google Shopping page, this parameter is false;
if the API cannot find the number of stores in the HTML code of the page, it takes the number from the displayed_text;
in this case, the parameter is true

#### Implementation of

[IStoresCountInfo](../interfaces/IStoresCountInfo.md).[count_from_text](../interfaces/IStoresCountInfo.md#count_from_text)

#### Defined in

[main.ts:164593](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164593)

___


### displayed\_text

• `Optional` **displayed\_text**: `string`

text displayed on the Google Shopping page

#### Implementation of

[IStoresCountInfo](../interfaces/IStoresCountInfo.md).[displayed_text](../interfaces/IStoresCountInfo.md#displayed_text)

#### Defined in

[main.ts:164587](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164587)

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

[main.ts:164606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164606)

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

[main.ts:164625](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164625)

___


### fromJS

▸ **fromJS**(`data`): [`StoresCountInfo`](StoresCountInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`StoresCountInfo`](StoresCountInfo.md)

#### Defined in

[main.ts:164618](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164618)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")