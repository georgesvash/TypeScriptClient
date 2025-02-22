[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MapsSearchBusinessDataSerpElementItem

# Class: MapsSearchBusinessDataSerpElementItem

## Hierarchy

- [`BaseBusinessDataSerpElementItem`](BaseBusinessDataSerpElementItem.md)
  
  ↳ **`MapsSearchBusinessDataSerpElementItem`**

## Implements

- [`IMapsSearchBusinessDataSerpElementItem`](../interfaces/IMapsSearchBusinessDataSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MapsSearchBusinessDataSerpElementItem.md#constructor)

### Properties

- [\_discriminator](MapsSearchBusinessDataSerpElementItem.md#_discriminator)
- [additional\_categories](MapsSearchBusinessDataSerpElementItem.md#additional_categories)
- [address](MapsSearchBusinessDataSerpElementItem.md#address)
- [address\_info](MapsSearchBusinessDataSerpElementItem.md#address_info)
- [category](MapsSearchBusinessDataSerpElementItem.md#category)
- [category\_ids](MapsSearchBusinessDataSerpElementItem.md#category_ids)
- [cid](MapsSearchBusinessDataSerpElementItem.md#cid)
- [domain](MapsSearchBusinessDataSerpElementItem.md#domain)
- [feature\_id](MapsSearchBusinessDataSerpElementItem.md#feature_id)
- [hotel\_rating](MapsSearchBusinessDataSerpElementItem.md#hotel_rating)
- [is\_claimed](MapsSearchBusinessDataSerpElementItem.md#is_claimed)
- [is\_directory\_item](MapsSearchBusinessDataSerpElementItem.md#is_directory_item)
- [latitude](MapsSearchBusinessDataSerpElementItem.md#latitude)
- [local\_justifications](MapsSearchBusinessDataSerpElementItem.md#local_justifications)
- [longitude](MapsSearchBusinessDataSerpElementItem.md#longitude)
- [main\_image](MapsSearchBusinessDataSerpElementItem.md#main_image)
- [phone](MapsSearchBusinessDataSerpElementItem.md#phone)
- [place\_id](MapsSearchBusinessDataSerpElementItem.md#place_id)
- [price\_level](MapsSearchBusinessDataSerpElementItem.md#price_level)
- [rank\_absolute](MapsSearchBusinessDataSerpElementItem.md#rank_absolute)
- [rank\_group](MapsSearchBusinessDataSerpElementItem.md#rank_group)
- [rating](MapsSearchBusinessDataSerpElementItem.md#rating)
- [rating\_distribution](MapsSearchBusinessDataSerpElementItem.md#rating_distribution)
- [snippet](MapsSearchBusinessDataSerpElementItem.md#snippet)
- [title](MapsSearchBusinessDataSerpElementItem.md#title)
- [total\_photos](MapsSearchBusinessDataSerpElementItem.md#total_photos)
- [url](MapsSearchBusinessDataSerpElementItem.md#url)
- [work\_hours](MapsSearchBusinessDataSerpElementItem.md#work_hours)

### Methods

- [init](MapsSearchBusinessDataSerpElementItem.md#init)
- [toJSON](MapsSearchBusinessDataSerpElementItem.md#tojson)
- [fromJS](MapsSearchBusinessDataSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new MapsSearchBusinessDataSerpElementItem**(`data?`): [`MapsSearchBusinessDataSerpElementItem`](MapsSearchBusinessDataSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMapsSearchBusinessDataSerpElementItem`](../interfaces/IMapsSearchBusinessDataSerpElementItem.md) |

#### Returns

[`MapsSearchBusinessDataSerpElementItem`](MapsSearchBusinessDataSerpElementItem.md)

#### Overrides

[BaseBusinessDataSerpElementItem](BaseBusinessDataSerpElementItem.md).[constructor](BaseBusinessDataSerpElementItem.md#constructor)

#### Defined in

[main.ts:191094](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191094)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseBusinessDataSerpElementItem](BaseBusinessDataSerpElementItem.md).[_discriminator](BaseBusinessDataSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:20076](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L20076)

___


### additional\_categories

• `Optional` **additional\_categories**: `string`[]

additional business categories
additional Google My Business categories that describe the services provided by the business entity in more detail

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[additional_categories](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#additional_categories)

#### Defined in

[main.ts:191050](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191050)

___


### address

• `Optional` **address**: `string`

address of the business entity

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[address](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#address)

#### Defined in

[main.ts:191032](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191032)

___


### address\_info

• `Optional` **address\_info**: [`AddressInfo`](AddressInfo.md)

object containing address components of the business entity

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[address_info](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#address_info)

#### Defined in

[main.ts:191034](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191034)

___


### category

• `Optional` **category**: `string`

business category
Google My Business general category that best describes the services provided by the business entity

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[category](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#category)

#### Defined in

[main.ts:191047](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191047)

___


### category\_ids

• `Optional` **category\_ids**: `string`[]

global category IDs
universal category IDs that do not change based on the selected country

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[category_ids](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#category_ids)

#### Defined in

[main.ts:191061](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191061)

___


### cid

• `Optional` **cid**: `string`

google-defined client id
unique id of a local establishment;
can be used with Google Reviews API to get a full list of reviews
learn more about the identifier in this help center article

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[cid](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#cid)

#### Defined in

[main.ts:191072](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191072)

___


### domain

• `Optional` **domain**: `string`

domain of the business entity

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[domain](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#domain)

#### Defined in

[main.ts:191017](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191017)

___


### feature\_id

• `Optional` **feature\_id**: `string`

the unique identifier of the element in SERP
learn more about the identifier in this help center article

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[feature_id](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#feature_id)

#### Defined in

[main.ts:191067](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191067)

___


### hotel\_rating

• `Optional` **hotel\_rating**: `number`

hotel class rating
class ratings range between 1-5 stars, learn more
if there is no hotel class rating information, the value will be null

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[hotel_rating](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#hotel_rating)

#### Defined in

[main.ts:191058](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191058)

___


### is\_claimed

• `Optional` **is\_claimed**: `boolean`

shows whether the entity is verified by its owner on Google Maps

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[is_claimed](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#is_claimed)

#### Defined in

[main.ts:191082](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191082)

___


### is\_directory\_item

• `Optional` **is\_directory\_item**: `boolean`

business establishment is a part of the directory
indicates whether the business establishment is a part of the directory;
if true, the item is a part of the larger directory of businesses with the same address (e.g., a mall or a business centre);
note: if the business establishment is a parent item in the directory, the value will be null

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[is_directory_item](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#is_directory_item)

#### Defined in

[main.ts:191090](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191090)

___


### latitude

• `Optional` **latitude**: `number`

latitude coordinate of the local establishments in google maps
example:
"latitude": 51.584091

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[latitude](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#latitude)

#### Defined in

[main.ts:191076](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191076)

___


### local\_justifications

• `Optional` **local\_justifications**: `string`[]

Google local justifications
snippets of text that “justify” why the business is showing up for search query

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[local_justifications](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#local_justifications)

#### Defined in

[main.ts:191085](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191085)

___


### longitude

• `Optional` **longitude**: `number`

longitude coordinate of the local establishment in google maps
example:
"longitude": -0.31365919999999997

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[longitude](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#longitude)

#### Defined in

[main.ts:191080](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191080)

___


### main\_image

• `Optional` **main\_image**: `string`

URL of the main image featured in Google My Business profile

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[main_image](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#main_image)

#### Defined in

[main.ts:191042](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191042)

___


### phone

• `Optional` **phone**: `string`

phone number of the business entity

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[phone](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#phone)

#### Defined in

[main.ts:191040](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191040)

___


### place\_id

• `Optional` **place\_id**: `string`

unique place identifier
place id of the local establishment featured in the element
learn more about the identifier in this help center article

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[place_id](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#place_id)

#### Defined in

[main.ts:191038](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191038)

___


### price\_level

• `Optional` **price\_level**: `string`

property price level
can take values: inexpensive, moderate, expensive, very_expensive
if there is no price level information, the value will be null

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[price_level](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#price_level)

#### Defined in

[main.ts:191054](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191054)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank among all the elements

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[rank_absolute](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:191015](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191015)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from the rank_group

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[rank_group](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#rank_group)

#### Defined in

[main.ts:191013](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191013)

___


### rating

• `Optional` **rating**: [`RatingInfo`](RatingInfo.md)

the element’s rating
the popularity rate based on reviews and displayed in SERP

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[rating](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#rating)

#### Defined in

[main.ts:191025](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191025)

___


### rating\_distribution

• `Optional` **rating\_distribution**: `Object`

the distribution of ratings of the business entity
the object displays the number of 1-star to 5-star ratings, as reviewed by users

#### Index signature

▪ [key: `string`]: `number`

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[rating_distribution](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#rating_distribution)

#### Defined in

[main.ts:191028](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191028)

___


### snippet

• `Optional` **snippet**: `string`

additional information about the business entity

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[snippet](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#snippet)

#### Defined in

[main.ts:191030](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191030)

___


### title

• `Optional` **title**: `string`

directory title
can take the following values: At this place, Directory

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[title](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#title)

#### Defined in

[main.ts:191020](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191020)

___


### total\_photos

• `Optional` **total\_photos**: `number`

total count of images featured in Google My Business profile

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[total_photos](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#total_photos)

#### Defined in

[main.ts:191044](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191044)

___


### url

• `Optional` **url**: `string`

URL to view the menu

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[url](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#url)

#### Defined in

[main.ts:191022](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191022)

___


### work\_hours

• `Optional` **work\_hours**: [`WorkInfo`](WorkInfo.md)

open hours
information about work hours of the local establishment

#### Implementation of

[IMapsSearchBusinessDataSerpElementItem](../interfaces/IMapsSearchBusinessDataSerpElementItem.md).[work_hours](../interfaces/IMapsSearchBusinessDataSerpElementItem.md#work_hours)

#### Defined in

[main.ts:191064](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191064)

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

[BaseBusinessDataSerpElementItem](BaseBusinessDataSerpElementItem.md).[init](BaseBusinessDataSerpElementItem.md#init)

#### Defined in

[main.ts:191099](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191099)

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

[BaseBusinessDataSerpElementItem](BaseBusinessDataSerpElementItem.md).[toJSON](BaseBusinessDataSerpElementItem.md#tojson)

#### Defined in

[main.ts:191161](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191161)

___


### fromJS

▸ **fromJS**(`data`): [`MapsSearchBusinessDataSerpElementItem`](MapsSearchBusinessDataSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MapsSearchBusinessDataSerpElementItem`](MapsSearchBusinessDataSerpElementItem.md)

#### Overrides

[BaseBusinessDataSerpElementItem](BaseBusinessDataSerpElementItem.md).[fromJS](BaseBusinessDataSerpElementItem.md#fromjs)

#### Defined in

[main.ts:191154](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191154)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")