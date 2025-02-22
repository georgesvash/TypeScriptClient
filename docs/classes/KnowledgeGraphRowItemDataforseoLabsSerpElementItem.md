[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KnowledgeGraphRowItemDataforseoLabsSerpElementItem

# Class: KnowledgeGraphRowItemDataforseoLabsSerpElementItem

## Hierarchy

- [`BaseDataforseoLabsSerpElementItem`](BaseDataforseoLabsSerpElementItem.md)
  
  ↳ **`KnowledgeGraphRowItemDataforseoLabsSerpElementItem`**

## Implements

- [`IKnowledgeGraphRowItemDataforseoLabsSerpElementItem`](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#constructor)

### Properties

- [\_discriminator](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#_discriminator)
- [data\_attrid](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#data_attrid)
- [links](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#links)
- [position](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#position)
- [rank\_absolute](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#rank_absolute)
- [rank\_group](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#rank_group)
- [text](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#text)
- [title](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#title)
- [xpath](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#xpath)

### Methods

- [init](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#init)
- [toJSON](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#tojson)
- [fromJS](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new KnowledgeGraphRowItemDataforseoLabsSerpElementItem**(`data?`): [`KnowledgeGraphRowItemDataforseoLabsSerpElementItem`](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKnowledgeGraphRowItemDataforseoLabsSerpElementItem`](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md) |

#### Returns

[`KnowledgeGraphRowItemDataforseoLabsSerpElementItem`](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md)

#### Overrides

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[constructor](BaseDataforseoLabsSerpElementItem.md#constructor)

#### Defined in

[main.ts:91745](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91745)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[_discriminator](BaseDataforseoLabsSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19715](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19715)

___


### data\_attrid

• `Optional` **data\_attrid**: `string`

google defined data attribute ID
example:
action:listen_artist

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[data_attrid](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#data_attrid)

#### Defined in

[main.ts:91735](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91735)

___


### links

• `Optional` **links**: [`LinkElement`](LinkElement.md)[]

sitelinks
the links shown below some of Google’s search results
if there are none, equals null

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[links](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#links)

#### Defined in

[main.ts:91741](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91741)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[position](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#position)

#### Defined in

[main.ts:91727](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91727)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[rank_absolute](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:91723](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91723)

___


### rank\_group

• `Optional` **rank\_group**: `number`

group rank in SERP
position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[rank_group](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#rank_group)

#### Defined in

[main.ts:91720](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91720)

___


### text

• `Optional` **text**: `string`

row content

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[text](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#text)

#### Defined in

[main.ts:91737](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91737)

___


### title

• `Optional` **title**: `string`

title of the item

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[title](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#title)

#### Defined in

[main.ts:91731](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91731)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IKnowledgeGraphRowItemDataforseoLabsSerpElementItem](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md).[xpath](../interfaces/IKnowledgeGraphRowItemDataforseoLabsSerpElementItem.md#xpath)

#### Defined in

[main.ts:91729](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91729)

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

[main.ts:91750](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91750)

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

[main.ts:91779](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91779)

___


### fromJS

▸ **fromJS**(`data`): [`KnowledgeGraphRowItemDataforseoLabsSerpElementItem`](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KnowledgeGraphRowItemDataforseoLabsSerpElementItem`](KnowledgeGraphRowItemDataforseoLabsSerpElementItem.md)

#### Overrides

[BaseDataforseoLabsSerpElementItem](BaseDataforseoLabsSerpElementItem.md).[fromJS](BaseDataforseoLabsSerpElementItem.md#fromjs)

#### Defined in

[main.ts:91772](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L91772)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")