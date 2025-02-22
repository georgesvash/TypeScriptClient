[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AmazonRelatedSearchesSerpElementItem

# Class: AmazonRelatedSearchesSerpElementItem

## Hierarchy

- [`BaseAmazonSerpElementItem`](BaseAmazonSerpElementItem.md)
  
  ↳ **`AmazonRelatedSearchesSerpElementItem`**

## Implements

- [`IAmazonRelatedSearchesSerpElementItem`](../interfaces/IAmazonRelatedSearchesSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AmazonRelatedSearchesSerpElementItem.md#constructor)

### Properties

- [\_discriminator](AmazonRelatedSearchesSerpElementItem.md#_discriminator)
- [items](AmazonRelatedSearchesSerpElementItem.md#items)
- [position](AmazonRelatedSearchesSerpElementItem.md#position)
- [rank\_absolute](AmazonRelatedSearchesSerpElementItem.md#rank_absolute)
- [rank\_group](AmazonRelatedSearchesSerpElementItem.md#rank_group)
- [xpath](AmazonRelatedSearchesSerpElementItem.md#xpath)

### Methods

- [init](AmazonRelatedSearchesSerpElementItem.md#init)
- [toJSON](AmazonRelatedSearchesSerpElementItem.md#tojson)
- [fromJS](AmazonRelatedSearchesSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new AmazonRelatedSearchesSerpElementItem**(`data?`): [`AmazonRelatedSearchesSerpElementItem`](AmazonRelatedSearchesSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAmazonRelatedSearchesSerpElementItem`](../interfaces/IAmazonRelatedSearchesSerpElementItem.md) |

#### Returns

[`AmazonRelatedSearchesSerpElementItem`](AmazonRelatedSearchesSerpElementItem.md)

#### Overrides

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[constructor](BaseAmazonSerpElementItem.md#constructor)

#### Defined in

[main.ts:171116](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171116)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[_discriminator](BaseAmazonSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:20756](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L20756)

___


### items

• `Optional` **items**: [`RelatedSearchesElement`](RelatedSearchesElement.md)[]

Amazon product items

#### Implementation of

[IAmazonRelatedSearchesSerpElementItem](../interfaces/IAmazonRelatedSearchesSerpElementItem.md).[items](../interfaces/IAmazonRelatedSearchesSerpElementItem.md#items)

#### Defined in

[main.ts:171112](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171112)

___


### position

• `Optional` **position**: `string`

the alignment of the element in Amazon SERP
possible values:
left, right

#### Implementation of

[IAmazonRelatedSearchesSerpElementItem](../interfaces/IAmazonRelatedSearchesSerpElementItem.md).[position](../interfaces/IAmazonRelatedSearchesSerpElementItem.md#position)

#### Defined in

[main.ts:171108](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171108)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements found in Amazon SERP

#### Implementation of

[IAmazonRelatedSearchesSerpElementItem](../interfaces/IAmazonRelatedSearchesSerpElementItem.md).[rank_absolute](../interfaces/IAmazonRelatedSearchesSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:171104](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171104)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IAmazonRelatedSearchesSerpElementItem](../interfaces/IAmazonRelatedSearchesSerpElementItem.md).[rank_group](../interfaces/IAmazonRelatedSearchesSerpElementItem.md#rank_group)

#### Defined in

[main.ts:171101](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171101)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IAmazonRelatedSearchesSerpElementItem](../interfaces/IAmazonRelatedSearchesSerpElementItem.md).[xpath](../interfaces/IAmazonRelatedSearchesSerpElementItem.md#xpath)

#### Defined in

[main.ts:171110](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171110)

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

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[init](BaseAmazonSerpElementItem.md#init)

#### Defined in

[main.ts:171121](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171121)

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

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[toJSON](BaseAmazonSerpElementItem.md#tojson)

#### Defined in

[main.ts:171147](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171147)

___


### fromJS

▸ **fromJS**(`data`): [`AmazonRelatedSearchesSerpElementItem`](AmazonRelatedSearchesSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AmazonRelatedSearchesSerpElementItem`](AmazonRelatedSearchesSerpElementItem.md)

#### Overrides

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[fromJS](BaseAmazonSerpElementItem.md#fromjs)

#### Defined in

[main.ts:171140](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171140)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")