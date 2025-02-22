[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BuyOnGoogleMerchantSerpElementItem

# Class: BuyOnGoogleMerchantSerpElementItem

## Hierarchy

- [`BaseMerchantSerpElementItem`](BaseMerchantSerpElementItem.md)
  
  ↳ **`BuyOnGoogleMerchantSerpElementItem`**

## Implements

- [`IBuyOnGoogleMerchantSerpElementItem`](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BuyOnGoogleMerchantSerpElementItem.md#constructor)

### Properties

- [\_discriminator](BuyOnGoogleMerchantSerpElementItem.md#_discriminator)
- [base\_price](BuyOnGoogleMerchantSerpElementItem.md#base_price)
- [currency](BuyOnGoogleMerchantSerpElementItem.md#currency)
- [details](BuyOnGoogleMerchantSerpElementItem.md#details)
- [domain](BuyOnGoogleMerchantSerpElementItem.md#domain)
- [position](BuyOnGoogleMerchantSerpElementItem.md#position)
- [product\_condition](BuyOnGoogleMerchantSerpElementItem.md#product_condition)
- [rank\_absolute](BuyOnGoogleMerchantSerpElementItem.md#rank_absolute)
- [rank\_group](BuyOnGoogleMerchantSerpElementItem.md#rank_group)
- [rating](BuyOnGoogleMerchantSerpElementItem.md#rating)
- [seller\_name](BuyOnGoogleMerchantSerpElementItem.md#seller_name)
- [shipping\_price](BuyOnGoogleMerchantSerpElementItem.md#shipping_price)
- [shop\_ad\_aclk](BuyOnGoogleMerchantSerpElementItem.md#shop_ad_aclk)
- [tax](BuyOnGoogleMerchantSerpElementItem.md#tax)
- [title](BuyOnGoogleMerchantSerpElementItem.md#title)
- [total\_price](BuyOnGoogleMerchantSerpElementItem.md#total_price)
- [url](BuyOnGoogleMerchantSerpElementItem.md#url)
- [xpath](BuyOnGoogleMerchantSerpElementItem.md#xpath)

### Methods

- [init](BuyOnGoogleMerchantSerpElementItem.md#init)
- [toJSON](BuyOnGoogleMerchantSerpElementItem.md#tojson)
- [fromJS](BuyOnGoogleMerchantSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new BuyOnGoogleMerchantSerpElementItem**(`data?`): [`BuyOnGoogleMerchantSerpElementItem`](BuyOnGoogleMerchantSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBuyOnGoogleMerchantSerpElementItem`](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md) |

#### Returns

[`BuyOnGoogleMerchantSerpElementItem`](BuyOnGoogleMerchantSerpElementItem.md)

#### Overrides

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[constructor](BaseMerchantSerpElementItem.md#constructor)

#### Defined in

[main.ts:166672](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166672)

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

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[base_price](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#base_price)

#### Defined in

[main.ts:166644](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166644)

___


### currency

• `Optional` **currency**: `string`

currency in the ISO format
example:
USD

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[currency](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#currency)

#### Defined in

[main.ts:166655](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166655)

___


### details

• `Optional` **details**: `string`

details and special offers
if there are no details, the value will be null

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[details](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#details)

#### Defined in

[main.ts:166642](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166642)

___


### domain

• `Optional` **domain**: `string`

domain in SERP

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[domain](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#domain)

#### Defined in

[main.ts:166635](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166635)

___


### position

• `Optional` **position**: `string`

the alignment of the element in Google Shopping SERP
possible values:
left, right

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[position](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#position)

#### Defined in

[main.ts:166631](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166631)

___


### product\_condition

• `Optional` **product\_condition**: `string`

indicated condition of the product
possible values: Used, Refurbished, New, null

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[product_condition](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#product_condition)

#### Defined in

[main.ts:166668](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166668)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements found in Google Shopping SERP

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[rank_absolute](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:166627](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166627)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[rank_group](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#rank_group)

#### Defined in

[main.ts:166624](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166624)

___


### rating

• `Optional` **rating**: [`RatingElement`](RatingElement.md)

shop rating
the shop popularity rate based on product reviews

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[rating](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#rating)

#### Defined in

[main.ts:166661](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166661)

___


### seller\_name

• `Optional` **seller\_name**: `string`

name of the seller
the name of the company that placed a corresponding product on Google Shopping

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[seller_name](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#seller_name)

#### Defined in

[main.ts:166658](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166658)

___


### shipping\_price

• `Optional` **shipping\_price**: `number`

product shipping price

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[shipping_price](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#shipping_price)

#### Defined in

[main.ts:166649](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166649)

___


### shop\_ad\_aclk

• `Optional` **shop\_ad\_aclk**: `string`

unique ad click referral parameter
using this parameter you can get a URL of the advertisement in Google Shopping Sellers Ad URL
in this case, the value equals null

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[shop_ad_aclk](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#shop_ad_aclk)

#### Defined in

[main.ts:166665](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166665)

___


### tax

• `Optional` **tax**: `number`

the amount of tax
tax is specified as the actual amount of money, not as the percentage

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[tax](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#tax)

#### Defined in

[main.ts:166647](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166647)

___


### title

• `Optional` **title**: `string`

product title

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[title](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#title)

#### Defined in

[main.ts:166637](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166637)

___


### total\_price

• `Optional` **total\_price**: `number`

product price including tax and shipping

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[total_price](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#total_price)

#### Defined in

[main.ts:166651](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166651)

___


### url

• `Optional` **url**: `string`

Google Shopping URL forwarding to the product page

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[url](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#url)

#### Defined in

[main.ts:166639](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166639)

___


### xpath

• `Optional` **xpath**: `string`

XPath of the element

#### Implementation of

[IBuyOnGoogleMerchantSerpElementItem](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md).[xpath](../interfaces/IBuyOnGoogleMerchantSerpElementItem.md#xpath)

#### Defined in

[main.ts:166633](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166633)

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

[main.ts:166677](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166677)

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

[main.ts:166711](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166711)

___


### fromJS

▸ **fromJS**(`data`): [`BuyOnGoogleMerchantSerpElementItem`](BuyOnGoogleMerchantSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BuyOnGoogleMerchantSerpElementItem`](BuyOnGoogleMerchantSerpElementItem.md)

#### Overrides

[BaseMerchantSerpElementItem](BaseMerchantSerpElementItem.md).[fromJS](BaseMerchantSerpElementItem.md#fromjs)

#### Defined in

[main.ts:166704](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L166704)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")