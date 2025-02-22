[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ImagesSerpElementItem

# Class: ImagesSerpElementItem

## Hierarchy

- [`BaseSerpElementItem`](BaseSerpElementItem.md)
  
  ↳ **`ImagesSerpElementItem`**

## Implements

- [`IImagesSerpElementItem`](../interfaces/IImagesSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ImagesSerpElementItem.md#constructor)

### Properties

- [\_discriminator](ImagesSerpElementItem.md#_discriminator)
- [items](ImagesSerpElementItem.md#items)
- [position](ImagesSerpElementItem.md#position)
- [rank\_absolute](ImagesSerpElementItem.md#rank_absolute)
- [rank\_group](ImagesSerpElementItem.md#rank_group)
- [rectangle](ImagesSerpElementItem.md#rectangle)
- [related\_image\_searches](ImagesSerpElementItem.md#related_image_searches)
- [title](ImagesSerpElementItem.md#title)
- [url](ImagesSerpElementItem.md#url)
- [xpath](ImagesSerpElementItem.md#xpath)

### Methods

- [init](ImagesSerpElementItem.md#init)
- [toJSON](ImagesSerpElementItem.md#tojson)
- [fromJS](ImagesSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new ImagesSerpElementItem**(`data?`): [`ImagesSerpElementItem`](ImagesSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IImagesSerpElementItem`](../interfaces/IImagesSerpElementItem.md) |

#### Returns

[`ImagesSerpElementItem`](ImagesSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[constructor](BaseSerpElementItem.md#constructor)

#### Defined in

[main.ts:28884](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28884)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseSerpElementItem](BaseSerpElementItem.md).[_discriminator](BaseSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19337](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19337)

___


### items

• `Optional` **items**: [`ImagesElement`](ImagesElement.md)[]

contains results featured in the ‘hotels_pack’ element of SERP

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[items](../interfaces/IImagesSerpElementItem.md#items)

#### Defined in

[main.ts:28873](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28873)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[position](../interfaces/IImagesSerpElementItem.md#position)

#### Defined in

[main.ts:28865](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28865)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[rank_absolute](../interfaces/IImagesSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:28861](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28861)

___


### rank\_group

• `Optional` **rank\_group**: `number`

group rank in SERP
position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[rank_group](../interfaces/IImagesSerpElementItem.md#rank_group)

#### Defined in

[main.ts:28858](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28858)

___


### rectangle

• `Optional` **rectangle**: [`Rectangle`](Rectangle.md)

rectangle parameters
contains cartesian coordinates and pixel dimensions of the result’s snippet in SERP
equals null if calculate_rectangles in the POST request is not set to true

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[rectangle](../interfaces/IImagesSerpElementItem.md#rectangle)

#### Defined in

[main.ts:28880](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28880)

___


### related\_image\_searches

• `Optional` **related\_image\_searches**: [`RelatedImageSearchesElement`](RelatedImageSearchesElement.md)[]

contains keywords and images related to the specified search term
if there are none, equals null

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[related_image_searches](../interfaces/IImagesSerpElementItem.md#related_image_searches)

#### Defined in

[main.ts:28876](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28876)

___


### title

• `Optional` **title**: `string`

title of a given link element

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[title](../interfaces/IImagesSerpElementItem.md#title)

#### Defined in

[main.ts:28869](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28869)

___


### url

• `Optional` **url**: `string`

URL

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[url](../interfaces/IImagesSerpElementItem.md#url)

#### Defined in

[main.ts:28871](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28871)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IImagesSerpElementItem](../interfaces/IImagesSerpElementItem.md).[xpath](../interfaces/IImagesSerpElementItem.md#xpath)

#### Defined in

[main.ts:28867](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28867)

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

[main.ts:28889](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28889)

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

[main.ts:28923](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28923)

___


### fromJS

▸ **fromJS**(`data`): [`ImagesSerpElementItem`](ImagesSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ImagesSerpElementItem`](ImagesSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[fromJS](BaseSerpElementItem.md#fromjs)

#### Defined in

[main.ts:28916](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L28916)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")