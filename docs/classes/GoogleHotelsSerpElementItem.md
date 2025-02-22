[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / GoogleHotelsSerpElementItem

# Class: GoogleHotelsSerpElementItem

## Hierarchy

- [`BaseSerpElementItem`](BaseSerpElementItem.md)
  
  ↳ **`GoogleHotelsSerpElementItem`**

## Implements

- [`IGoogleHotelsSerpElementItem`](../interfaces/IGoogleHotelsSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](GoogleHotelsSerpElementItem.md#constructor)

### Properties

- [\_discriminator](GoogleHotelsSerpElementItem.md#_discriminator)
- [cid](GoogleHotelsSerpElementItem.md#cid)
- [hotel\_identifier](GoogleHotelsSerpElementItem.md#hotel_identifier)
- [position](GoogleHotelsSerpElementItem.md#position)
- [rank\_absolute](GoogleHotelsSerpElementItem.md#rank_absolute)
- [rank\_group](GoogleHotelsSerpElementItem.md#rank_group)
- [rectangle](GoogleHotelsSerpElementItem.md#rectangle)
- [url](GoogleHotelsSerpElementItem.md#url)
- [xpath](GoogleHotelsSerpElementItem.md#xpath)

### Methods

- [init](GoogleHotelsSerpElementItem.md#init)
- [toJSON](GoogleHotelsSerpElementItem.md#tojson)
- [fromJS](GoogleHotelsSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new GoogleHotelsSerpElementItem**(`data?`): [`GoogleHotelsSerpElementItem`](GoogleHotelsSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IGoogleHotelsSerpElementItem`](../interfaces/IGoogleHotelsSerpElementItem.md) |

#### Returns

[`GoogleHotelsSerpElementItem`](GoogleHotelsSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[constructor](BaseSerpElementItem.md#constructor)

#### Defined in

[main.ts:33815](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33815)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseSerpElementItem](BaseSerpElementItem.md).[_discriminator](BaseSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19337](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19337)

___


### cid

• `Optional` **cid**: `string`

google-defined client id

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[cid](../interfaces/IGoogleHotelsSerpElementItem.md#cid)

#### Defined in

[main.ts:33807](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33807)

___


### hotel\_identifier

• `Optional` **hotel\_identifier**: `string`

unique hotel identifier
unique hotel identifier assigned by Google;
example: "CgoIjaeSlI6CnNpVEAE"

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[hotel_identifier](../interfaces/IGoogleHotelsSerpElementItem.md#hotel_identifier)

#### Defined in

[main.ts:33803](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33803)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[position](../interfaces/IGoogleHotelsSerpElementItem.md#position)

#### Defined in

[main.ts:33797](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33797)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[rank_absolute](../interfaces/IGoogleHotelsSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:33793](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33793)

___


### rank\_group

• `Optional` **rank\_group**: `number`

group rank in SERP
position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[rank_group](../interfaces/IGoogleHotelsSerpElementItem.md#rank_group)

#### Defined in

[main.ts:33790](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33790)

___


### rectangle

• `Optional` **rectangle**: [`Rectangle`](Rectangle.md)

rectangle parameters
contains cartesian coordinates and pixel dimensions of the result’s snippet in SERP
equals null if calculate_rectangles in the POST request is not set to true

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[rectangle](../interfaces/IGoogleHotelsSerpElementItem.md#rectangle)

#### Defined in

[main.ts:33811](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33811)

___


### url

• `Optional` **url**: `string`

URL

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[url](../interfaces/IGoogleHotelsSerpElementItem.md#url)

#### Defined in

[main.ts:33805](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33805)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IGoogleHotelsSerpElementItem](../interfaces/IGoogleHotelsSerpElementItem.md).[xpath](../interfaces/IGoogleHotelsSerpElementItem.md#xpath)

#### Defined in

[main.ts:33799](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33799)

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

[main.ts:33820](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33820)

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

[main.ts:33845](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33845)

___


### fromJS

▸ **fromJS**(`data`): [`GoogleHotelsSerpElementItem`](GoogleHotelsSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`GoogleHotelsSerpElementItem`](GoogleHotelsSerpElementItem.md)

#### Overrides

[BaseSerpElementItem](BaseSerpElementItem.md).[fromJS](BaseSerpElementItem.md#fromjs)

#### Defined in

[main.ts:33838](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L33838)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")