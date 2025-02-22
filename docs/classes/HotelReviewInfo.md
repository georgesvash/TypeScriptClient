[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / HotelReviewInfo

# Class: HotelReviewInfo

## Implements

- [`IHotelReviewInfo`](../interfaces/IHotelReviewInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](HotelReviewInfo.md#constructor)

### Properties

- [mentions](HotelReviewInfo.md#mentions)
- [other\_sites\_reviews](HotelReviewInfo.md#other_sites_reviews)
- [rating\_distribution](HotelReviewInfo.md#rating_distribution)
- [value](HotelReviewInfo.md#value)
- [votes\_count](HotelReviewInfo.md#votes_count)

### Methods

- [init](HotelReviewInfo.md#init)
- [toJSON](HotelReviewInfo.md#tojson)
- [fromJS](HotelReviewInfo.md#fromjs)

## Constructors

### constructor

• **new HotelReviewInfo**(`data?`): [`HotelReviewInfo`](HotelReviewInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IHotelReviewInfo`](../interfaces/IHotelReviewInfo.md) |

#### Returns

[`HotelReviewInfo`](HotelReviewInfo.md)

#### Defined in

[main.ts:195937](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195937)

## Properties

### mentions

• `Optional` **mentions**: [`ReviewMentionInfo`](ReviewMentionInfo.md)[]

hotel mentions
information about hotel reviews by criteria

#### Implementation of

[IHotelReviewInfo](../interfaces/IHotelReviewInfo.md).[mentions](../interfaces/IHotelReviewInfo.md#mentions)

#### Defined in

[main.ts:195927](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195927)

___


### other\_sites\_reviews

• `Optional` **other\_sites\_reviews**: [`OtherSitesReviewsInfo`](OtherSitesReviewsInfo.md)[]

reviews on third-party sites
reviews from third-paty sites

#### Implementation of

[IHotelReviewInfo](../interfaces/IHotelReviewInfo.md).[other_sites_reviews](../interfaces/IHotelReviewInfo.md#other_sites_reviews)

#### Defined in

[main.ts:195933](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195933)

___


### rating\_distribution

• `Optional` **rating\_distribution**: `Object`

rating distribution by votes
the distribution of votes across the rating in the range from 1 to 5

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IHotelReviewInfo](../interfaces/IHotelReviewInfo.md).[rating_distribution](../interfaces/IHotelReviewInfo.md#rating_distribution)

#### Defined in

[main.ts:195930](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195930)

___


### value

• `Optional` **value**: `number`

overall hotel rating based on customer votes

#### Implementation of

[IHotelReviewInfo](../interfaces/IHotelReviewInfo.md).[value](../interfaces/IHotelReviewInfo.md#value)

#### Defined in

[main.ts:195921](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195921)

___


### votes\_count

• `Optional` **votes\_count**: `number`

number of customer votes
the number of customer votes included in the calculation of the hotel rating

#### Implementation of

[IHotelReviewInfo](../interfaces/IHotelReviewInfo.md).[votes_count](../interfaces/IHotelReviewInfo.md#votes_count)

#### Defined in

[main.ts:195924](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195924)

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

[main.ts:195946](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195946)

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

[main.ts:195981](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195981)

___


### fromJS

▸ **fromJS**(`data`): [`HotelReviewInfo`](HotelReviewInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`HotelReviewInfo`](HotelReviewInfo.md)

#### Defined in

[main.ts:195974](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L195974)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")