[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KnowledgeGraphDescriptionItemSerpElementItem

# Class: KnowledgeGraphDescriptionItemSerpElementItem

## Hierarchy

- [`BaseSerpElementItem`](BaseSerpElementItem.md)
  
  ↳ **`KnowledgeGraphDescriptionItemSerpElementItem`**

## Implements

- [`IKnowledgeGraphDescriptionItemSerpElementItem`](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KnowledgeGraphDescriptionItemSerpElementItem.md#constructor)

### Properties

- [\_discriminator](KnowledgeGraphDescriptionItemSerpElementItem.md#_discriminator)
- [links](KnowledgeGraphDescriptionItemSerpElementItem.md#links)
- [position](KnowledgeGraphDescriptionItemSerpElementItem.md#position)
- [rank\_absolute](KnowledgeGraphDescriptionItemSerpElementItem.md#rank_absolute)
- [rank\_group](KnowledgeGraphDescriptionItemSerpElementItem.md#rank_group)
- [rectangle](KnowledgeGraphDescriptionItemSerpElementItem.md#rectangle)
- [text](KnowledgeGraphDescriptionItemSerpElementItem.md#text)
- [xpath](KnowledgeGraphDescriptionItemSerpElementItem.md#xpath)

### Methods

- [init](KnowledgeGraphDescriptionItemSerpElementItem.md#init)
- [toJSON](KnowledgeGraphDescriptionItemSerpElementItem.md#tojson)
- [fromJS](KnowledgeGraphDescriptionItemSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new KnowledgeGraphDescriptionItemSerpElementItem**(`data?`): [`KnowledgeGraphDescriptionItemSerpElementItem`](KnowledgeGraphDescriptionItemSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKnowledgeGraphDescriptionItemSerpElementItem`](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md) |

#### Returns

[`KnowledgeGraphDescriptionItemSerpElementItem`](KnowledgeGraphDescriptionItemSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[constructor](BaseSerpElementItem.md#constructor)

#### Defined in

[main.ts:26349](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26349)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseSerpElementItem](BaseSerpElementItem.md).[_discriminator](BaseSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19337](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19337)

___


### links

• `Optional` **links**: [`LinkElement`](LinkElement.md)[]

sitelinks
the links shown below some of Google’s search results
if there are none, equals null

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[links](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#links)

#### Defined in

[main.ts:26341](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26341)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[position](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#position)

#### Defined in

[main.ts:26333](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26333)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[rank_absolute](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:26329](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26329)

___


### rank\_group

• `Optional` **rank\_group**: `number`

group rank in SERP
position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[rank_group](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#rank_group)

#### Defined in

[main.ts:26326](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26326)

___


### rectangle

• `Optional` **rectangle**: [`Rectangle`](Rectangle.md)

rectangle parameters
contains cartesian coordinates and pixel dimensions of the result’s snippet in SERP
equals null if calculate_rectangles in the POST request is not set to true

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[rectangle](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#rectangle)

#### Defined in

[main.ts:26345](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26345)

___


### text

• `Optional` **text**: `string`

description content

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[text](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#text)

#### Defined in

[main.ts:26337](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26337)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IKnowledgeGraphDescriptionItemSerpElementItem](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md).[xpath](../interfaces/IKnowledgeGraphDescriptionItemSerpElementItem.md#xpath)

#### Defined in

[main.ts:26335](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26335)

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

[BaseSerpElementItem](BaseSerpElementItem.md).[init](BaseSerpElementItem.md#init)

#### Defined in

[main.ts:26354](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26354)

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

[BaseSerpElementItem](BaseSerpElementItem.md).[toJSON](BaseSerpElementItem.md#tojson)

#### Defined in

[main.ts:26382](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26382)

___


### fromJS

▸ **fromJS**(`data`): [`KnowledgeGraphDescriptionItemSerpElementItem`](KnowledgeGraphDescriptionItemSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KnowledgeGraphDescriptionItemSerpElementItem`](KnowledgeGraphDescriptionItemSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[fromJS](BaseSerpElementItem.md#fromjs)

#### Defined in

[main.ts:26375](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L26375)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")