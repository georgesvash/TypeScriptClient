[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ShopsListMerchantSerpElementItem

# Class: ShopsListMerchantSerpElementItem

## Hierarchy

- [`BaseMerchantSerpElementItem`](BaseMerchantSerpElementItem.md)
  
  ↳ **`ShopsListMerchantSerpElementItem`**

## Implements

- [`IShopsListMerchantSerpElementItem`](../interfaces/IShopsListMerchantSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ShopsListMerchantSerpElementItem.md#constructor)

### Properties

- [\_discriminator](ShopsListMerchantSerpElementItem.md#_discriminator)
- [base\_price](ShopsListMerchantSerpElementItem.md#base_price)
- [currency](ShopsListMerchantSerpElementItem.md#currency)
- [details](ShopsListMerchantSerpElementItem.md#details)
- [domain](ShopsListMerchantSerpElementItem.md#domain)
- [position](ShopsListMerchantSerpElementItem.md#position)
- [product\_annotation](ShopsListMerchantSerpElementItem.md#product_annotation)
- [product\_condition](ShopsListMerchantSerpElementItem.md#product_condition)
- [rank\_absolute](ShopsListMerchantSerpElementItem.md#rank_absolute)
- [rank\_group](ShopsListMerchantSerpElementItem.md#rank_group)
- [rating](ShopsListMerchantSerpElementItem.md#rating)
- [seller\_name](ShopsListMerchantSerpElementItem.md#seller_name)
- [shipping\_price](ShopsListMerchantSerpElementItem.md#shipping_price)
- [shop\_ad\_aclk](ShopsListMerchantSerpElementItem.md#shop_ad_aclk)
- [tax](ShopsListMerchantSerpElementItem.md#tax)
- [title](ShopsListMerchantSerpElementItem.md#title)
- [total\_price](ShopsListMerchantSerpElementItem.md#total_price)
- [url](ShopsListMerchantSerpElementItem.md#url)
- [xpath](ShopsListMerchantSerpElementItem.md#xpath)

### Methods

- [init](ShopsListMerchantSerpElementItem.md#init)
- [toJSON](ShopsListMerchantSerpElementItem.md#tojson)
- [fromJS](ShopsListMerchantSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new ShopsListMerchantSerpElementItem**(`data?`): [`ShopsListMerchantSerpElementItem`](ShopsListMerchantSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IShopsListMerchantSerpElementItem`](../interfaces/IShopsListMerchantSerpElementItem.md) |

#### Returns

[`ShopsListMerchantSerpElementItem`](ShopsListMerchantSerpElementItem.md)

#### Overrides

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[constructor](BaseMerchantSerpElementItem.md#constructor)

#### Defined in

[main.ts:166496](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166496)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[_discriminator](BaseMerchantSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:19988](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L19988)

___


### base\_price

• `Optional` **base\_price**: `number`

product price without tax and shipping

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[base_price](../interfaces/IShopsListMerchantSerpElementItem.md#base_price)

#### Defined in

[main.ts:166465](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166465)

___


### currency

• `Optional` **currency**: `string`

currency in the ISO format
example:
USD

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[currency](../interfaces/IShopsListMerchantSerpElementItem.md#currency)

#### Defined in

[main.ts:166476](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166476)

___


### details

• `Optional` **details**: `string`

details and special offers
if there are no details, the value will be null

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[details](../interfaces/IShopsListMerchantSerpElementItem.md#details)

#### Defined in

[main.ts:166463](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166463)

___


### domain

• `Optional` **domain**: `string`

domain in SERP

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[domain](../interfaces/IShopsListMerchantSerpElementItem.md#domain)

#### Defined in

[main.ts:166455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166455)

___


### position

• `Optional` **position**: `string`

the alignment of the element in Google Shopping SERP
possible values:
left, right

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[position](../interfaces/IShopsListMerchantSerpElementItem.md#position)

#### Defined in

[main.ts:166451](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166451)

___


### product\_annotation

• `Optional` **product\_annotation**: `string`

data from annotations and badges with special offers
if there is no annotation for this product, the value will be null
examples: LOW PRICE, SPECIAL OFFER, SALE, PRICE DROP

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[product_annotation](../interfaces/IShopsListMerchantSerpElementItem.md#product_annotation)

#### Defined in

[main.ts:166492](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166492)

___


### product\_condition

• `Optional` **product\_condition**: `string`

indicated condition of the product
possible values: Used, Refurbished, New, null

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[product_condition](../interfaces/IShopsListMerchantSerpElementItem.md#product_condition)

#### Defined in

[main.ts:166488](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166488)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements found in Google Shopping SERP

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[rank_absolute](../interfaces/IShopsListMerchantSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:166447](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166447)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[rank_group](../interfaces/IShopsListMerchantSerpElementItem.md#rank_group)

#### Defined in

[main.ts:166444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166444)

___


### rating

• `Optional` **rating**: [`RatingElement`](RatingElement.md)

shop rating
the shop popularity rate based on product reviews

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[rating](../interfaces/IShopsListMerchantSerpElementItem.md#rating)

#### Defined in

[main.ts:166482](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166482)

___


### seller\_name

• `Optional` **seller\_name**: `string`

name of the seller
the name of the company that placed a corresponding product on Google Shopping

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[seller_name](../interfaces/IShopsListMerchantSerpElementItem.md#seller_name)

#### Defined in

[main.ts:166479](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166479)

___


### shipping\_price

• `Optional` **shipping\_price**: `number`

product shipping price

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[shipping_price](../interfaces/IShopsListMerchantSerpElementItem.md#shipping_price)

#### Defined in

[main.ts:166470](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166470)

___


### shop\_ad\_aclk

• `Optional` **shop\_ad\_aclk**: `string`

unique ad click referral parameter
using this parameter you can get a URL of the advertisement in Google Shopping Sellers Ad URL

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[shop_ad_aclk](../interfaces/IShopsListMerchantSerpElementItem.md#shop_ad_aclk)

#### Defined in

[main.ts:166485](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166485)

___


### tax

• `Optional` **tax**: `number`

the amount of tax
tax is specified as the actual amount of money, not as the percentage

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[tax](../interfaces/IShopsListMerchantSerpElementItem.md#tax)

#### Defined in

[main.ts:166468](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166468)

___


### title

• `Optional` **title**: `string`

product title

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[title](../interfaces/IShopsListMerchantSerpElementItem.md#title)

#### Defined in

[main.ts:166457](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166457)

___


### total\_price

• `Optional` **total\_price**: `number`

product price including tax and shipping

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[total_price](../interfaces/IShopsListMerchantSerpElementItem.md#total_price)

#### Defined in

[main.ts:166472](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166472)

___


### url

• `Optional` **url**: `string`

Google Shopping URL forwarding to the product page on the seller’s website
if you want to obtain a URL of the advertisement forwarding to the product page on the seller’s website, please refer to the Google Shopping Sellers Ad URL endpoint

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[url](../interfaces/IShopsListMerchantSerpElementItem.md#url)

#### Defined in

[main.ts:166460](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166460)

___


### xpath

• `Optional` **xpath**: `string`

XPath of the element

#### Implementation of

[IShopsListMerchantSerpElementItem](../interfaces/IShopsListMerchantSerpElementItem.md).[xpath](../interfaces/IShopsListMerchantSerpElementItem.md#xpath)

#### Defined in

[main.ts:166453](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166453)

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

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[init](BaseMerchantSerpElementItem.md#init)

#### Defined in

[main.ts:166501](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166501)

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

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[toJSON](BaseMerchantSerpElementItem.md#tojson)

#### Defined in

[main.ts:166536](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166536)

___


### fromJS

▸ **fromJS**(`data`): [`ShopsListMerchantSerpElementItem`](ShopsListMerchantSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ShopsListMerchantSerpElementItem`](ShopsListMerchantSerpElementItem.md)

#### Overrides

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[fromJS](BaseMerchantSerpElementItem.md#fromjs)

#### Defined in

[main.ts:166529](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166529)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")