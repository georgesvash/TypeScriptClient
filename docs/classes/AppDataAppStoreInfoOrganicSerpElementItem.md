[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppStoreInfoOrganicSerpElementItem

# Class: AppDataAppStoreInfoOrganicSerpElementItem

## Hierarchy

- [`BaseAppDataSerpElementItem`](BaseAppDataSerpElementItem.md)
  
  ↳ **`AppDataAppStoreInfoOrganicSerpElementItem`**

## Implements

- [`IAppDataAppStoreInfoOrganicSerpElementItem`](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppStoreInfoOrganicSerpElementItem.md#constructor)

### Properties

- [\_discriminator](AppDataAppStoreInfoOrganicSerpElementItem.md#_discriminator)
- [advisories](AppDataAppStoreInfoOrganicSerpElementItem.md#advisories)
- [app\_id](AppDataAppStoreInfoOrganicSerpElementItem.md#app_id)
- [categories](AppDataAppStoreInfoOrganicSerpElementItem.md#categories)
- [description](AppDataAppStoreInfoOrganicSerpElementItem.md#description)
- [developer](AppDataAppStoreInfoOrganicSerpElementItem.md#developer)
- [developer\_id](AppDataAppStoreInfoOrganicSerpElementItem.md#developer_id)
- [developer\_url](AppDataAppStoreInfoOrganicSerpElementItem.md#developer_url)
- [icon](AppDataAppStoreInfoOrganicSerpElementItem.md#icon)
- [images](AppDataAppStoreInfoOrganicSerpElementItem.md#images)
- [is\_free](AppDataAppStoreInfoOrganicSerpElementItem.md#is_free)
- [languages](AppDataAppStoreInfoOrganicSerpElementItem.md#languages)
- [last\_update\_date](AppDataAppStoreInfoOrganicSerpElementItem.md#last_update_date)
- [main\_category](AppDataAppStoreInfoOrganicSerpElementItem.md#main_category)
- [minimum\_os\_version](AppDataAppStoreInfoOrganicSerpElementItem.md#minimum_os_version)
- [more\_apps\_by\_developer](AppDataAppStoreInfoOrganicSerpElementItem.md#more_apps_by_developer)
- [position](AppDataAppStoreInfoOrganicSerpElementItem.md#position)
- [price](AppDataAppStoreInfoOrganicSerpElementItem.md#price)
- [rank\_absolute](AppDataAppStoreInfoOrganicSerpElementItem.md#rank_absolute)
- [rank\_group](AppDataAppStoreInfoOrganicSerpElementItem.md#rank_group)
- [rating](AppDataAppStoreInfoOrganicSerpElementItem.md#rating)
- [released\_date](AppDataAppStoreInfoOrganicSerpElementItem.md#released_date)
- [reviews\_count](AppDataAppStoreInfoOrganicSerpElementItem.md#reviews_count)
- [similar\_apps](AppDataAppStoreInfoOrganicSerpElementItem.md#similar_apps)
- [size](AppDataAppStoreInfoOrganicSerpElementItem.md#size)
- [title](AppDataAppStoreInfoOrganicSerpElementItem.md#title)
- [update\_notes](AppDataAppStoreInfoOrganicSerpElementItem.md#update_notes)
- [url](AppDataAppStoreInfoOrganicSerpElementItem.md#url)
- [version](AppDataAppStoreInfoOrganicSerpElementItem.md#version)

### Methods

- [init](AppDataAppStoreInfoOrganicSerpElementItem.md#init)
- [toJSON](AppDataAppStoreInfoOrganicSerpElementItem.md#tojson)
- [fromJS](AppDataAppStoreInfoOrganicSerpElementItem.md#fromjs)

## Constructors

### constructor

• **new AppDataAppStoreInfoOrganicSerpElementItem**(`data?`): [`AppDataAppStoreInfoOrganicSerpElementItem`](AppDataAppStoreInfoOrganicSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppStoreInfoOrganicSerpElementItem`](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md) |

#### Returns

[`AppDataAppStoreInfoOrganicSerpElementItem`](AppDataAppStoreInfoOrganicSerpElementItem.md)

#### Overrides

[BaseAppDataSerpElementItem](BaseAppDataSerpElementItem.md).[constructor](BaseAppDataSerpElementItem.md#constructor)

#### Defined in

[main.ts:184441](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184441)

## Properties

### \_discriminator

• `Protected` **\_discriminator**: `string`

#### Inherited from

[BaseAppDataSerpElementItem](BaseAppDataSerpElementItem.md).[_discriminator](BaseAppDataSerpElementItem.md#_discriminator)

#### Defined in

[main.ts:20450](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L20450)

___


### advisories

• `Optional` **advisories**: `string`[]

age rating and age-based content advisories

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[advisories](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#advisories)

#### Defined in

[main.ts:184403](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184403)

___


### app\_id

• `Optional` **app\_id**: `string`

ID of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[app_id](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#app_id)

#### Defined in

[main.ts:184379](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184379)

___


### categories

• `Optional` **categories**: `string`[]

all relevant categories/genres of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[categories](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#categories)

#### Defined in

[main.ts:184399](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184399)

___


### description

• `Optional` **description**: `string`

description of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[description](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#description)

#### Defined in

[main.ts:184387](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184387)

___


### developer

• `Optional` **developer**: `string`

name of the app developer

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[developer](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#developer)

#### Defined in

[main.ts:184405](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184405)

___


### developer\_id

• `Optional` **developer\_id**: `string`

ID of the app developer

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[developer_id](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#developer_id)

#### Defined in

[main.ts:184407](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184407)

___


### developer\_url

• `Optional` **developer\_url**: `string`

URL to the developer page on App Store

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[developer_url](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#developer_url)

#### Defined in

[main.ts:184409](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184409)

___


### icon

• `Optional` **icon**: `string`

URL to the app icon

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[icon](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#icon)

#### Defined in

[main.ts:184385](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184385)

___


### images

• `Optional` **images**: `string`[]

app images
contains URLs to the images used on the app page on App Store

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[images](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#images)

#### Defined in

[main.ts:184431](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184431)

___


### is\_free

• `Optional` **is\_free**: `boolean`

indicates whether the app is free

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[is_free](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#is_free)

#### Defined in

[main.ts:184395](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184395)

___


### languages

• `Optional` **languages**: `string`[]

languages supported in the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[languages](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#languages)

#### Defined in

[main.ts:184401](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184401)

___


### last\_update\_date

• `Optional` **last\_update\_date**: `string`

date and time when the app was last updated
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”;
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[last_update_date](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#last_update_date)

#### Defined in

[main.ts:184425](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184425)

___


### main\_category

• `Optional` **main\_category**: `string`

main category/genre of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[main_category](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#main_category)

#### Defined in

[main.ts:184397](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184397)

___


### minimum\_os\_version

• `Optional` **minimum\_os\_version**: `string`

minimum OS version required to install the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[minimum_os_version](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#minimum_os_version)

#### Defined in

[main.ts:184413](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184413)

___


### more\_apps\_by\_developer

• `Optional` **more\_apps\_by\_developer**: [`AppsInfo`](AppsInfo.md)[]

similar apps
information about apps built by the same developer

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[more_apps_by_developer](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#more_apps_by_developer)

#### Defined in

[main.ts:184437](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184437)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values: left

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[position](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#position)

#### Defined in

[main.ts:184377](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184377)

___


### price

• `Optional` **price**: [`PriceInfo`](PriceInfo.md)

price of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[price](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#price)

#### Defined in

[main.ts:184393](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184393)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank among all the listed apps
absolute position among all apps on the list

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[rank_absolute](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#rank_absolute)

#### Defined in

[main.ts:184374](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184374)

___


### rank\_group

• `Optional` **rank\_group**: `number`

position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[rank_group](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#rank_group)

#### Defined in

[main.ts:184371](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184371)

___


### rating

• `Optional` **rating**: [`RatingInfo`](RatingInfo.md)

average rating of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[rating](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#rating)

#### Defined in

[main.ts:184391](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184391)

___


### released\_date

• `Optional` **released\_date**: `string`

date and time when the app was released
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”;
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[released_date](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#released_date)

#### Defined in

[main.ts:184420](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184420)

___


### reviews\_count

• `Optional` **reviews\_count**: `number`

the total number of reviews of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[reviews_count](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#reviews_count)

#### Defined in

[main.ts:184389](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184389)

___


### similar\_apps

• `Optional` **similar\_apps**: [`AppsInfo`](AppsInfo.md)[]

similar apps
displays apps similar to the app in a POST request

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[similar_apps](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#similar_apps)

#### Defined in

[main.ts:184434](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184434)

___


### size

• `Optional` **size**: `string`

size of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[size](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#size)

#### Defined in

[main.ts:184415](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184415)

___


### title

• `Optional` **title**: `string`

title of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[title](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#title)

#### Defined in

[main.ts:184381](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184381)

___


### update\_notes

• `Optional` **update\_notes**: `string`

update notes
contains the latest update notes from the developer

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[update_notes](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#update_notes)

#### Defined in

[main.ts:184428](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184428)

___


### url

• `Optional` **url**: `string`

URL to the app page on App Store

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[url](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#url)

#### Defined in

[main.ts:184383](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184383)

___


### version

• `Optional` **version**: `string`

current version of the app

#### Implementation of

[IAppDataAppStoreInfoOrganicSerpElementItem](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md).[version](../interfaces/IAppDataAppStoreInfoOrganicSerpElementItem.md#version)

#### Defined in

[main.ts:184411](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184411)

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

[BaseAppDataSerpElementItem](BaseAppDataSerpElementItem.md).[init](BaseAppDataSerpElementItem.md#init)

#### Defined in

[main.ts:184446](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184446)

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

[BaseAppDataSerpElementItem](BaseAppDataSerpElementItem.md).[toJSON](BaseAppDataSerpElementItem.md#tojson)

#### Defined in

[main.ts:184515](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184515)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppStoreInfoOrganicSerpElementItem`](AppDataAppStoreInfoOrganicSerpElementItem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppStoreInfoOrganicSerpElementItem`](AppDataAppStoreInfoOrganicSerpElementItem.md)

#### Overrides

[BaseAppDataSerpElementItem](BaseAppDataSerpElementItem.md).[fromJS](BaseAppDataSerpElementItem.md#fromjs)

#### Defined in

[main.ts:184508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184508)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")