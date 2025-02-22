[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IAppDataAppleAppReviewsTaskPostRequestInfo

# Interface: IAppDataAppleAppReviewsTaskPostRequestInfo

## Implemented by

- [`AppDataAppleAppReviewsTaskPostRequestInfo`](../classes/AppDataAppleAppReviewsTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [app\_id](IAppDataAppleAppReviewsTaskPostRequestInfo.md#app_id)
- [depth](IAppDataAppleAppReviewsTaskPostRequestInfo.md#depth)
- [language\_code](IAppDataAppleAppReviewsTaskPostRequestInfo.md#language_code)
- [language\_name](IAppDataAppleAppReviewsTaskPostRequestInfo.md#language_name)
- [location\_code](IAppDataAppleAppReviewsTaskPostRequestInfo.md#location_code)
- [location\_name](IAppDataAppleAppReviewsTaskPostRequestInfo.md#location_name)
- [pingback\_url](IAppDataAppleAppReviewsTaskPostRequestInfo.md#pingback_url)
- [postback\_data](IAppDataAppleAppReviewsTaskPostRequestInfo.md#postback_data)
- [postback\_url](IAppDataAppleAppReviewsTaskPostRequestInfo.md#postback_url)
- [priority](IAppDataAppleAppReviewsTaskPostRequestInfo.md#priority)
- [sort\_by](IAppDataAppleAppReviewsTaskPostRequestInfo.md#sort_by)
- [tag](IAppDataAppleAppReviewsTaskPostRequestInfo.md#tag)

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

#### Defined in

[main.ts:185814](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185814)

___


### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of reviews to be returned in the API response;
we strongly recommend setting the parsing depth in the multiples of 50, because our system processes 50 reviews in a row;
default value: 50;
maximum value: 500

#### Defined in

[main.ts:185857](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185857)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
optional field
if you use this field, you don’t need to specify language_name
you can receive the list of available languages with their language_code by making a separate request to https://api.dataforseo.com/v3/app_data/apple/languages
example:
en

#### Defined in

[main.ts:185842](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185842)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
optional field
if you use this field, you don’t need to specify language_code
you can receive the list of available languages with language_name by making a separate request to https://api.dataforseo.com/v3/app_data/apple/languages
example:
English

#### Defined in

[main.ts:185835](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185835)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name
if you use this field, you don’t need to specify location_name
you can receive the list of available locations of the search engine with their location_code by making a separate request to https://api.dataforseo.com/v3/app_data/apple/locations
example:
9061121

#### Defined in

[main.ts:185828](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185828)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code
if you use this field, you don’t need to specify location_code
you can receive the list of available locations of the search engine with their location_name by making a separate request to https://api.dataforseo.com/v3/app_data/apple/locations
example:
West Los Angeles,California,United States

#### Defined in

[main.ts:185821](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185821)

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

#### Defined in

[main.ts:185897](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185897)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced

#### Defined in

[main.ts:185887](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185887)

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

#### Defined in

[main.ts:185881](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185881)

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

#### Defined in

[main.ts:185850](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185850)

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

#### Defined in

[main.ts:185865](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185865)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:185871](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185871)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")