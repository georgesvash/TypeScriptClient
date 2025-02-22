[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo

# Interface: IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo

## Implemented by

- [`AppDataGoogleAppReviewsTaskGetAdvancedResultInfo`](../classes/AppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [app\_id](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#app_id)
- [check\_url](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#check_url)
- [datetime](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#datetime)
- [items](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#items)
- [items\_count](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#items_count)
- [language\_code](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#language_code)
- [location\_code](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#location_code)
- [rating](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#rating)
- [reviews\_count](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#reviews_count)
- [se\_domain](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#se_domain)
- [title](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#title)
- [type](IAppDataGoogleAppReviewsTaskGetAdvancedResultInfo.md#type)

## Properties

### app\_id

• `Optional` **app\_id**: `string`

application id received in a POST array

#### Defined in

[main.ts:181531](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181531)

___


### check\_url

• `Optional` **check\_url**: `string`

direct URL to search engine results
you can use it to make sure that we provided accurate results

#### Defined in

[main.ts:181542](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181542)

___


### datetime

• `Optional` **datetime**: `string`

date and time when the result was received
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Defined in

[main.ts:181547](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181547)

___


### items

• `Optional` **items**: [`BaseAppDataSerpElementItem`](../classes/BaseAppDataSerpElementItem.md)[]

found reviews
you can get more results by using the depth parameter when setting a task

#### Defined in

[main.ts:181561](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181561)

___


### items\_count

• `Optional` **items\_count**: `number`

the number of reviews items in the results array
you can get more results by using the depth parameter when setting a task

#### Defined in

[main.ts:181558](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181558)

___


### language\_code

• `Optional` **language\_code**: `string`

language code in a POST array

#### Defined in

[main.ts:181539](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181539)

___


### location\_code

• `Optional` **location\_code**: `number`

location code in a POST array

#### Defined in

[main.ts:181537](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181537)

___


### rating

• `Optional` **rating**: [`RatingInfo`](../classes/RatingInfo.md)

rating of the app
rating of the application for which the reviews are collected

#### Defined in

[main.ts:181553](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181553)

___


### reviews\_count

• `Optional` **reviews\_count**: `number`

the total number of reviews

#### Defined in

[main.ts:181555](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181555)

___


### se\_domain

• `Optional` **se\_domain**: `string`

search engine domain in a POST array

#### Defined in

[main.ts:181535](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181535)

___


### title

• `Optional` **title**: `string`

title of the app
title of the application for which the reviews are collected

#### Defined in

[main.ts:181550](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181550)

___


### type

• `Optional` **type**: `string`

type of element

#### Defined in

[main.ts:181533](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L181533)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")