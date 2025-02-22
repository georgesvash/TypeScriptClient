[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AmazonAmazonReviewItemSerpElementItem

# Class: AmazonAmazonReviewItemSerpElementItem

## Hierarchy

- [`BaseAmazonSerpElementItem`](BaseAmazonSerpElementItem.md)
  
  ↳ **`AmazonAmazonReviewItemSerpElementItem`**

## Implements

- [`IAmazonAmazonReviewItemSerpElementItem`](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AmazonAmazonReviewItemSerpElementItem.md#constructor)

### Properties

- [\_discriminator](AmazonAmazonReviewItemSerpElementItem.md#_discriminator)
- [helpful\_votes](AmazonAmazonReviewItemSerpElementItem.md#helpful_votes)
- [images](AmazonAmazonReviewItemSerpElementItem.md#images)
- [position](AmazonAmazonReviewItemSerpElementItem.md#position)
- [publication\_date](AmazonAmazonReviewItemSerpElementItem.md#publication_date)
- [rank\_absolute](AmazonAmazonReviewItemSerpElementItem.md#rank_absolute)
- [rank\_group](AmazonAmazonReviewItemSerpElementItem.md#rank_group)
- [rating](AmazonAmazonReviewItemSerpElementItem.md#rating)
- [review\_text](AmazonAmazonReviewItemSerpElementItem.md#review_text)
- [subtitle](AmazonAmazonReviewItemSerpElementItem.md#subtitle)
- [title](AmazonAmazonReviewItemSerpElementItem.md#title)
- [url](AmazonAmazonReviewItemSerpElementItem.md#url)
- [user\_profile](AmazonAmazonReviewItemSerpElementItem.md#user_profile)
- [verified](AmazonAmazonReviewItemSerpElementItem.md#verified)
- [videos](AmazonAmazonReviewItemSerpElementItem.md#videos)
- [xpath](AmazonAmazonReviewItemSerpElementItem.md#xpath)

### Methods

- [init](AmazonAmazonReviewItemSerpElementItem.md#init)
- [toJSON](AmazonAmazonReviewItemSerpElementItem.md#tojson)
- [fromJS](AmazonAmazonReviewItemSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new AmazonAmazonReviewItemSerpElementItem**(`data?`): [`AmazonAmazonReviewItemSerpElementItem`](AmazonAmazonReviewItemSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAmazonAmazonReviewItemSerpElementItem`](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md) |

#### Returns

[`AmazonAmazonReviewItemSerpElementItem`](AmazonAmazonReviewItemSerpElementItem.md)

#### Overrides

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[constructor](BaseAmazonSerpElementItem.md#constructor)

#### Defined in

[main.ts:175655](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175655)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[_discriminator](BaseAmazonSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:20756](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L20756)

___


### helpful\_votes

• `Optional` **helpful\_votes**: `number`

helpful votes count
number of users who clicked on the ‘Helpful” button under the review text

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[helpful_votes](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#helpful_votes)

#### Defined in

[main.ts:175632](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175632)

___


### images

• `Optional` **images**: [`ImagesElement`](ImagesElement.md)[]

images of the product submitted by the reviewer

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[images](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#images)

#### Defined in

[main.ts:175634](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175634)

___


### position

• `Optional` **position**: `string`

the alignment of the review in SERP
can take the following values: right

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[position](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#position)

#### Defined in

[main.ts:175623](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175623)

___


### publication\_date

• `Optional` **publication\_date**: `string`

date and time when the review was published
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”;
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[publication_date](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#publication_date)

#### Defined in

[main.ts:175649](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175649)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank among all the listed reviews
absolute position among all reviews on the list

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[rank_absolute](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:175620](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175620)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[rank_group](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#rank_group)

#### Defined in

[main.ts:175617](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175617)

___


### rating

• `Optional` **rating**: [`RatingInfo`](RatingInfo.md)

the rating score submitted by the reviewer

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[rating](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#rating)

#### Defined in

[main.ts:175651](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175651)

___


### review\_text

• `Optional` **review\_text**: `string`

content of the review

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[review_text](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#review_text)

#### Defined in

[main.ts:175644](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175644)

___


### subtitle

• `Optional` **subtitle**: `string`

subtitle of the review

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[subtitle](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#subtitle)

#### Defined in

[main.ts:175629](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175629)

___


### title

• `Optional` **title**: `string`

title of the review

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[title](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#title)

#### Defined in

[main.ts:175640](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175640)

___


### url

• `Optional` **url**: `string`

URL to the review

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[url](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#url)

#### Defined in

[main.ts:175642](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175642)

___


### user\_profile

• `Optional` **user\_profile**: [`UserProfileInfo`](UserProfileInfo.md)

user profile of the reviewer

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[user_profile](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#user_profile)

#### Defined in

[main.ts:175638](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175638)

___


### verified

• `Optional` **verified**: `boolean`

indicates whether the review has the “Verified Purchase” mark

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[verified](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#verified)

#### Defined in

[main.ts:175627](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175627)

___


### videos

• `Optional` **videos**: [`VideoElement`](VideoElement.md)[]

videos of the product submitted by the reviewer

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[videos](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#videos)

#### Defined in

[main.ts:175636](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175636)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Implementation of

[IAmazonAmazonReviewItemSerpElementItem](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md).[xpath](../interfaces/IAmazonAmazonReviewItemSerpElementItem.md#xpath)

#### Defined in

[main.ts:175625](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175625)

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

[main.ts:175660](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175660)

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

[main.ts:175700](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175700)

___


### fromJS

▸ **fromJS**(`data`): [`AmazonAmazonReviewItemSerpElementItem`](AmazonAmazonReviewItemSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AmazonAmazonReviewItemSerpElementItem`](AmazonAmazonReviewItemSerpElementItem.md)

#### Overrides

[BaseAmazonSerpElementItem](BaseAmazonSerpElementItem.md).[fromJS](BaseAmazonSerpElementItem.md#fromjs)

#### Defined in

[main.ts:175693](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L175693)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")