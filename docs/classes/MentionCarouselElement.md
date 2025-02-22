[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MentionCarouselElement

# Class: MentionCarouselElement

## Implements

- [`IMentionCarouselElement`](../interfaces/IMentionCarouselElement.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MentionCarouselElement.md#constructor)

### Properties

- [mentioned\_in](MentionCarouselElement.md#mentioned_in)
- [price](MentionCarouselElement.md#price)
- [rating](MentionCarouselElement.md#rating)
- [title](MentionCarouselElement.md#title)
- [type](MentionCarouselElement.md#type)

### Methods

- [init](MentionCarouselElement.md#init)
- [toJSON](MentionCarouselElement.md#tojson)
- [fromJS](MentionCarouselElement.md#fromjs)

## Constructors

### constructor

• **new MentionCarouselElement**(`data?`): [`MentionCarouselElement`](MentionCarouselElement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMentionCarouselElement`](../interfaces/IMentionCarouselElement.md) |

#### Returns

[`MentionCarouselElement`](MentionCarouselElement.md)

#### Defined in

[main.ts:30791](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30791)

## Properties

### mentioned\_in

• `Optional` **mentioned\_in**: [`LinkElement`](LinkElement.md)[]

additional elements in the mention_carousel item

#### Implementation of

[IMentionCarouselElement](../interfaces/IMentionCarouselElement.md).[mentioned_in](../interfaces/IMentionCarouselElement.md#mentioned_in)

#### Defined in

[main.ts:30787](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30787)

___


### price

• `Optional` **price**: [`PriceInfo`](PriceInfo.md)

price of booking a place for the specified dates of stay

#### Implementation of

[IMentionCarouselElement](../interfaces/IMentionCarouselElement.md).[price](../interfaces/IMentionCarouselElement.md#price)

#### Defined in

[main.ts:30782](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30782)

___


### rating

• `Optional` **rating**: [`RatingInfo`](RatingInfo.md)

the item’s rating
the popularity rate based on reviews and displayed in SERP

#### Implementation of

[IMentionCarouselElement](../interfaces/IMentionCarouselElement.md).[rating](../interfaces/IMentionCarouselElement.md#rating)

#### Defined in

[main.ts:30785](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30785)

___


### title

• `Optional` **title**: `string`

title of the row

#### Implementation of

[IMentionCarouselElement](../interfaces/IMentionCarouselElement.md).[title](../interfaces/IMentionCarouselElement.md#title)

#### Defined in

[main.ts:30780](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30780)

___


### type

• `Optional` **type**: `string`

type of element

#### Implementation of

[IMentionCarouselElement](../interfaces/IMentionCarouselElement.md).[type](../interfaces/IMentionCarouselElement.md#type)

#### Defined in

[main.ts:30778](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30778)

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

[main.ts:30800](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30800)

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

[main.ts:30825](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30825)

___


### fromJS

▸ **fromJS**(`data`): [`MentionCarouselElement`](MentionCarouselElement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MentionCarouselElement`](MentionCarouselElement.md)

#### Defined in

[main.ts:30818](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L30818)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")