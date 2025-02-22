[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / VisualStoriesDataforseoLabsSerpElementItem

# Class: VisualStoriesDataforseoLabsSerpElementItem

## Hierarchy

- [`BaseDataforseoLabsSerpElementItem`](BaseDataforseoLabsSerpElementItem.md)
  
  ↳ **`VisualStoriesDataforseoLabsSerpElementItem`**

## Implements

- [`IVisualStoriesDataforseoLabsSerpElementItem`](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](VisualStoriesDataforseoLabsSerpElementItem.md#constructor)

### Properties

- [\_discriminator](VisualStoriesDataforseoLabsSerpElementItem.md#_discriminator)
- [items](VisualStoriesDataforseoLabsSerpElementItem.md#items)
- [position](VisualStoriesDataforseoLabsSerpElementItem.md#position)
- [rank\_absolute](VisualStoriesDataforseoLabsSerpElementItem.md#rank_absolute)
- [rank\_group](VisualStoriesDataforseoLabsSerpElementItem.md#rank_group)
- [xpath](VisualStoriesDataforseoLabsSerpElementItem.md#xpath)

### Methods

- [init](VisualStoriesDataforseoLabsSerpElementItem.md#init)
- [toJSON](VisualStoriesDataforseoLabsSerpElementItem.md#tojson)
- [fromJS](VisualStoriesDataforseoLabsSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new VisualStoriesDataforseoLabsSerpElementItem**(`data?`): [`VisualStoriesDataforseoLabsSerpElementItem`](VisualStoriesDataforseoLabsSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IVisualStoriesDataforseoLabsSerpElementItem`](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md) |

#### Returns

[`VisualStoriesDataforseoLabsSerpElementItem`](VisualStoriesDataforseoLabsSerpElementItem.md)

#### Overrides

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[constructor](BaseDataforseoLabsSerpElementItem.md#constructor)

#### Defined in

[main.ts:95833](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95833)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[_discriminator](BaseDataforseoLabsSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19715](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19715)

___


### items

• `Optional` **items**: [`LicensesElement`](LicensesElement.md)[]

elements of search results found in SERP

#### Implementation of

[IVisualStoriesDataforseoLabsSerpElementItem](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md).[items](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md#items)

#### Defined in

[main.ts:95829](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95829)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Implementation of

[IVisualStoriesDataforseoLabsSerpElementItem](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md).[position](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md#position)

#### Defined in

[main.ts:95825](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95825)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Implementation of

[IVisualStoriesDataforseoLabsSerpElementItem](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md).[rank_absolute](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:95821](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95821)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IVisualStoriesDataforseoLabsSerpElementItem](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md).[rank_group](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md#rank_group)

#### Defined in

[main.ts:95818](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95818)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IVisualStoriesDataforseoLabsSerpElementItem](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md).[xpath](../interfaces/IVisualStoriesDataforseoLabsSerpElementItem.md#xpath)

#### Defined in

[main.ts:95827](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95827)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Overrides

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[init](BaseDataforseoLabsSerpElementItem.md#init)

#### Defined in

[main.ts:95838](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95838)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Overrides

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[toJSON](BaseDataforseoLabsSerpElementItem.md#tojson)

#### Defined in

[main.ts:95864](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95864)

___


### fromJS

▸ **fromJS**(`data`): [`VisualStoriesDataforseoLabsSerpElementItem`](VisualStoriesDataforseoLabsSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`VisualStoriesDataforseoLabsSerpElementItem`](VisualStoriesDataforseoLabsSerpElementItem.md)

#### Overrides

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[fromJS](BaseDataforseoLabsSerpElementItem.md#fromjs)

#### Defined in

[main.ts:95857](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L95857)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")