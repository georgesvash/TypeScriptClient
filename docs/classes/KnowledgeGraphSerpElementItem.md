[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KnowledgeGraphSerpElementItem

# Class: KnowledgeGraphSerpElementItem

## Hierarchy

- [`BaseSerpElementItem`](BaseSerpElementItem.md)
  
  ↳ **`KnowledgeGraphSerpElementItem`**

## Implements

- [`IKnowledgeGraphSerpElementItem`](../interfaces/IKnowledgeGraphSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KnowledgeGraphSerpElementItem.md#constructor)

### Properties

- [\_discriminator](KnowledgeGraphSerpElementItem.md#_discriminator)
- [card\_id](KnowledgeGraphSerpElementItem.md#card_id)
- [cid](KnowledgeGraphSerpElementItem.md#cid)
- [description](KnowledgeGraphSerpElementItem.md#description)
- [image\_url](KnowledgeGraphSerpElementItem.md#image_url)
- [items](KnowledgeGraphSerpElementItem.md#items)
- [logo\_url](KnowledgeGraphSerpElementItem.md#logo_url)
- [position](KnowledgeGraphSerpElementItem.md#position)
- [rank\_absolute](KnowledgeGraphSerpElementItem.md#rank_absolute)
- [rank\_group](KnowledgeGraphSerpElementItem.md#rank_group)
- [rectangle](KnowledgeGraphSerpElementItem.md#rectangle)
- [subtitle](KnowledgeGraphSerpElementItem.md#subtitle)
- [title](KnowledgeGraphSerpElementItem.md#title)
- [url](KnowledgeGraphSerpElementItem.md#url)
- [xpath](KnowledgeGraphSerpElementItem.md#xpath)

### Methods

- [init](KnowledgeGraphSerpElementItem.md#init)
- [toJSON](KnowledgeGraphSerpElementItem.md#tojson)
- [fromJS](KnowledgeGraphSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new KnowledgeGraphSerpElementItem**(`data?`): [`KnowledgeGraphSerpElementItem`](KnowledgeGraphSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKnowledgeGraphSerpElementItem`](../interfaces/IKnowledgeGraphSerpElementItem.md) |

#### Returns

[`KnowledgeGraphSerpElementItem`](KnowledgeGraphSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[constructor](BaseSerpElementItem.md#constructor)

#### Defined in

[main.ts:27559](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27559)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseSerpElementItem](BaseSerpElementItem.md).[_discriminator](BaseSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19337](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19337)

___


### card\_id

• `Optional` **card\_id**: `string`

card id

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[card_id](../interfaces/IKnowledgeGraphSerpElementItem.md#card_id)

#### Defined in

[main.ts:27537](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27537)

___


### cid

• `Optional` **cid**: `string`

google-defined client id
unique id of a local establishment;
can be used with Google Reviews API to get a full list of reviews

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[cid](../interfaces/IKnowledgeGraphSerpElementItem.md#cid)

#### Defined in

[main.ts:27548](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27548)

___


### description

• `Optional` **description**: `string`

description of the results element in SERP

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[description](../interfaces/IKnowledgeGraphSerpElementItem.md#description)

#### Defined in

[main.ts:27535](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27535)

___


### image\_url

• `Optional` **image\_url**: `string`

URL of the image
the URL leading to the image on the original resource or DataForSEO storage (in case the original source is not available)

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[image_url](../interfaces/IKnowledgeGraphSerpElementItem.md#image_url)

#### Defined in

[main.ts:27542](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27542)

___


### items

• `Optional` **items**: [`BaseSerpElementItem`](BaseSerpElementItem.md)[]

additional items present in the element
if there are none, equals null

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[items](../interfaces/IKnowledgeGraphSerpElementItem.md#items)

#### Defined in

[main.ts:27551](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27551)

___


### logo\_url

• `Optional` **logo\_url**: `string`

URL of the logo from knowledge graph

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[logo_url](../interfaces/IKnowledgeGraphSerpElementItem.md#logo_url)

#### Defined in

[main.ts:27544](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27544)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[position](../interfaces/IKnowledgeGraphSerpElementItem.md#position)

#### Defined in

[main.ts:27527](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27527)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[rank_absolute](../interfaces/IKnowledgeGraphSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:27523](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27523)

___


### rank\_group

• `Optional` **rank\_group**: `number`

group rank in SERP
position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[rank_group](../interfaces/IKnowledgeGraphSerpElementItem.md#rank_group)

#### Defined in

[main.ts:27520](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27520)

___


### rectangle

• `Optional` **rectangle**: [`Rectangle`](Rectangle.md)

rectangle parameters
contains cartesian coordinates and pixel dimensions of the result’s snippet in SERP
equals null if calculate_rectangles in the POST request is not set to true

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[rectangle](../interfaces/IKnowledgeGraphSerpElementItem.md#rectangle)

#### Defined in

[main.ts:27555](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27555)

___


### subtitle

• `Optional` **subtitle**: `string`

subtitle of the item

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[subtitle](../interfaces/IKnowledgeGraphSerpElementItem.md#subtitle)

#### Defined in

[main.ts:27533](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27533)

___


### title

• `Optional` **title**: `string`

title of the result in SERP

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[title](../interfaces/IKnowledgeGraphSerpElementItem.md#title)

#### Defined in

[main.ts:27531](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27531)

___


### url

• `Optional` **url**: `string`

relevant URL in SERP

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[url](../interfaces/IKnowledgeGraphSerpElementItem.md#url)

#### Defined in

[main.ts:27539](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27539)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IKnowledgeGraphSerpElementItem](../interfaces/IKnowledgeGraphSerpElementItem.md).[xpath](../interfaces/IKnowledgeGraphSerpElementItem.md#xpath)

#### Defined in

[main.ts:27529](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27529)

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

[main.ts:27564](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27564)

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

[main.ts:27599](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27599)

___


### fromJS

▸ **fromJS**(`data`): [`KnowledgeGraphSerpElementItem`](KnowledgeGraphSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KnowledgeGraphSerpElementItem`](KnowledgeGraphSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[fromJS](BaseSerpElementItem.md#fromjs)

#### Defined in

[main.ts:27592](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L27592)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")