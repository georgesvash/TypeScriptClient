[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleAppReviewsTaskPostRequestInfo

# Class: AppDataAppleAppReviewsTaskPostRequestInfo

## Implements

- [`IAppDataAppleAppReviewsTaskPostRequestInfo`](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleAppReviewsTaskPostRequestInfo.md#constructor)

### Properties

- [app\_id](AppDataAppleAppReviewsTaskPostRequestInfo.md#app_id)
- [depth](AppDataAppleAppReviewsTaskPostRequestInfo.md#depth)
- [language\_code](AppDataAppleAppReviewsTaskPostRequestInfo.md#language_code)
- [language\_name](AppDataAppleAppReviewsTaskPostRequestInfo.md#language_name)
- [location\_code](AppDataAppleAppReviewsTaskPostRequestInfo.md#location_code)
- [location\_name](AppDataAppleAppReviewsTaskPostRequestInfo.md#location_name)
- [pingback\_url](AppDataAppleAppReviewsTaskPostRequestInfo.md#pingback_url)
- [postback\_data](AppDataAppleAppReviewsTaskPostRequestInfo.md#postback_data)
- [postback\_url](AppDataAppleAppReviewsTaskPostRequestInfo.md#postback_url)
- [priority](AppDataAppleAppReviewsTaskPostRequestInfo.md#priority)
- [sort\_by](AppDataAppleAppReviewsTaskPostRequestInfo.md#sort_by)
- [tag](AppDataAppleAppReviewsTaskPostRequestInfo.md#tag)

### Methods

- [init](AppDataAppleAppReviewsTaskPostRequestInfo.md#init)
- [toJSON](AppDataAppleAppReviewsTaskPostRequestInfo.md#tojson)
- [fromJS](AppDataAppleAppReviewsTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleAppReviewsTaskPostRequestInfo**(`data?`): [`AppDataAppleAppReviewsTaskPostRequestInfo`](AppDataAppleAppReviewsTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleAppReviewsTaskPostRequestInfo`](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md) |

#### Returns

[`AppDataAppleAppReviewsTaskPostRequestInfo`](AppDataAppleAppReviewsTaskPostRequestInfo.md)

#### Defined in

[main.ts:185747](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185747)

## Properties

### app\_id

• `Optional` **app\_id**: `string`

id of the app
required field
ID of the mobile application on App Store;
you can find the ID in the URL of every app listed on App Store;
example:
in the URL https://apps.apple.com/us/app/id835599320
the id is 835599320

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[app_id](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#app_id)

#### Defined in

[main.ts:185660](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185660)

___


### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of reviews to be returned in the API response;
we strongly recommend setting the parsing depth in the multiples of 50, because our system processes 50 reviews in a row;
default value: 50;
maximum value: 500

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[depth](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#depth)

#### Defined in

[main.ts:185703](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185703)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
optional field
if you use this field, you don’t need to specify language_name
you can receive the list of available languages with their language_code by making a separate request to https://api.dataforseo.com/v3/app_data/apple/languages
example:
en

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[language_code](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#language_code)

#### Defined in

[main.ts:185688](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185688)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
optional field
if you use this field, you don’t need to specify language_code
you can receive the list of available languages with language_name by making a separate request to https://api.dataforseo.com/v3/app_data/apple/languages
example:
English

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[language_name](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#language_name)

#### Defined in

[main.ts:185681](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185681)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name
if you use this field, you don’t need to specify location_name
you can receive the list of available locations of the search engine with their location_code by making a separate request to https://api.dataforseo.com/v3/app_data/apple/locations
example:
9061121

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[location_code](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#location_code)

#### Defined in

[main.ts:185674](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185674)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code
if you use this field, you don’t need to specify location_code
you can receive the list of available locations of the search engine with their location_name by making a separate request to https://api.dataforseo.com/v3/app_data/apple/locations
example:
West Los Angeles,California,United States

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[location_name](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#location_name)

#### Defined in

[main.ts:185667](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185667)

___


### pingback\_url

• `Optional` **pingback\_url**: `string`

notification URL of a completed task
optional field
when a task is completed we will notify you by GET request sent to the URL you have specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/pingscript?id=$id
http://your-server.com/pingscript?id=$id&tag=$tag
Note: special symbols in pingback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[pingback_url](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:185743](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185743)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[postback_data](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#postback_data)

#### Defined in

[main.ts:185733](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185733)

___


### postback\_url

• `Optional` **postback\_url**: `string`

return URL for sending task results
optional field
once the task is completed, we will send a POST request with its results compressed in the gzip format to the postback_url you specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/postbackscript?id=$id
http://your-server.com/postbackscript?id=$id&tag=$tag
Note: special symbols in postback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[postback_url](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:185727](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185727)

___


### priority

• `Optional` **priority**: `number`

task priority
optional field
can take the following values:
1 – normal execution priority (set by default)
2 – high execution priority
You will be additionally charged for the tasks with high execution priority.
The cost can be calculated on the Pricing page.

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[priority](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#priority)

#### Defined in

[main.ts:185696](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185696)

___


### sort\_by

• `Optional` **sort\_by**: `string`

results sorting parameters
optional field
you can use this field to sort the results;
possible types of sorting:
most_recent — sort by the most recent reviews;
most_helpful — sort by the most relevant reviews;
default rule: most_helpful

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[sort_by](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#sort_by)

#### Defined in

[main.ts:185711](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185711)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IAppDataAppleAppReviewsTaskPostRequestInfo](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md).[tag](../interfaces/IAppDataAppleAppReviewsTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:185717](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185717)

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

[main.ts:185756](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185756)

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

[main.ts:185784](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185784)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleAppReviewsTaskPostRequestInfo`](AppDataAppleAppReviewsTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleAppReviewsTaskPostRequestInfo`](AppDataAppleAppReviewsTaskPostRequestInfo.md)

#### Defined in

[main.ts:185777](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185777)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")