[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / RatingElement

# Class: RatingElement

## Implements

- [`IRatingElement`](../interfaces/IRatingElement.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](RatingElement.md#constructor)

### Properties

- [position](RatingElement.md#position)
- [rating\_max](RatingElement.md#rating_max)
- [rating\_type](RatingElement.md#rating_type)
- [type](RatingElement.md#type)
- [value](RatingElement.md#value)
- [votes\_count](RatingElement.md#votes_count)

### Methods

- [init](RatingElement.md#init)
- [toJSON](RatingElement.md#tojson)
- [fromJS](RatingElement.md#fromjs)

## Constructors

### constructor

• **new RatingElement**(`data?`): [`RatingElement`](RatingElement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IRatingElement`](../interfaces/IRatingElement.md) |

#### Returns

[`RatingElement`](RatingElement.md)

#### Defined in

[main.ts:164446](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164446)

## Properties

### position

• `Optional` **position**: `string`

the alignment of the element in Google Shopping SERP
possible values:
left, right

#### Implementation of

[IRatingElement](../interfaces/IRatingElement.md).[position](../interfaces/IRatingElement.md#position)

#### Defined in

[main.ts:164433](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164433)

___


### rating\_max

• `Optional` **rating\_max**: `number`

the maximum value for a rating_type

#### Implementation of

[IRatingElement](../interfaces/IRatingElement.md).[rating_max](../interfaces/IRatingElement.md#rating_max)

#### Defined in

[main.ts:164442](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164442)

___


### rating\_type

• `Optional` **rating\_type**: `string`

the type of rating
here you can find the following elements: Max5, Percents, CustomMax

#### Implementation of

[IRatingElement](../interfaces/IRatingElement.md).[rating_type](../interfaces/IRatingElement.md#rating_type)

#### Defined in

[main.ts:164436](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164436)

___


### type

• `Optional` **type**: `string`

type of element

#### Implementation of

[IRatingElement](../interfaces/IRatingElement.md).[type](../interfaces/IRatingElement.md#type)

#### Defined in

[main.ts:164429](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164429)

___


### value

• `Optional` **value**: `string`

value of the rating

#### Implementation of

[IRatingElement](../interfaces/IRatingElement.md).[value](../interfaces/IRatingElement.md#value)

#### Defined in

[main.ts:164438](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164438)

___


### votes\_count

• `Optional` **votes\_count**: `number`

the amount of feedback

#### Implementation of

[IRatingElement](../interfaces/IRatingElement.md).[votes_count](../interfaces/IRatingElement.md#votes_count)

#### Defined in

[main.ts:164440](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164440)

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

[main.ts:164455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164455)

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

[main.ts:164477](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164477)

___


### fromJS

▸ **fromJS**(`data`): [`RatingElement`](RatingElement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`RatingElement`](RatingElement.md)

#### Defined in

[main.ts:164470](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164470)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")