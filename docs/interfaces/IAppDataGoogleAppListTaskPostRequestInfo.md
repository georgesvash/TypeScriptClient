[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IAppDataGoogleAppListTaskPostRequestInfo

# Interface: IAppDataGoogleAppListTaskPostRequestInfo

## Implemented by

- [`AppDataGoogleAppListTaskPostRequestInfo`](../classes/AppDataGoogleAppListTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [age\_rating](IAppDataGoogleAppListTaskPostRequestInfo.md#age_rating)
- [app\_category](IAppDataGoogleAppListTaskPostRequestInfo.md#app_category)
- [app\_collection](IAppDataGoogleAppListTaskPostRequestInfo.md#app_collection)
- [depth](IAppDataGoogleAppListTaskPostRequestInfo.md#depth)
- [language\_code](IAppDataGoogleAppListTaskPostRequestInfo.md#language_code)
- [language\_name](IAppDataGoogleAppListTaskPostRequestInfo.md#language_name)
- [location\_code](IAppDataGoogleAppListTaskPostRequestInfo.md#location_code)
- [location\_name](IAppDataGoogleAppListTaskPostRequestInfo.md#location_name)
- [pingback\_url](IAppDataGoogleAppListTaskPostRequestInfo.md#pingback_url)
- [postback\_data](IAppDataGoogleAppListTaskPostRequestInfo.md#postback_data)
- [postback\_url](IAppDataGoogleAppListTaskPostRequestInfo.md#postback_url)
- [priority](IAppDataGoogleAppListTaskPostRequestInfo.md#priority)
- [tag](IAppDataGoogleAppListTaskPostRequestInfo.md#tag)

## Properties

### age\_rating

• `Optional` **age\_rating**: `string`

filter results by age rating
optional field
you can use this field to filter the results by age rating;
possible types of filtering:
ages_up_to_5 — return apps approved for children up to 5 years old;
ages_6_8 — return apps approved for children from 6 to 8 years old;
ages_9_12 — return apps approved for children from 9 to 12 years old;
by default, the API returns apps for all ages;
Note: this filter works only in conjunction with the "category": "family" parameter

#### Defined in

[main.ts:178467](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178467)

___


### app\_category

• `Optional` **app\_category**: `string`

application category on Google Play
optional field
you can filter the results by app category;
example:
family;
you can receive the full list of available categories by making a separate request to https://api.dataforseo.com/v3/app_data/google/categories
Note: app_category cannot be used if app_collection parameter is set to featured

#### Defined in

[main.ts:178457](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178457)

___


### app\_collection

• `Optional` **app\_collection**: `string`

app collection
required field
app collection on Google Play from which apps will be collected;
you can specify the following values:
featured, topselling_paid, topselling_free, topselling_new_free, topselling_new_paid, topgrossing, movers_shakers
Note: if featured is selected, the app_category parameter cannot be used

#### Defined in

[main.ts:178406](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178406)

___


### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of apps to be returned in the API response;
we strongly recommend setting the parsing depth in the multiples of 100, because our system processes 100 results in a row;
default value: 100;
maximum value: 200

#### Defined in

[main.ts:178449](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178449)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
optional field
if you use this field, you don’t need to specify language_name
you can receive the list of available languages with their language_code by making a separate request to https://api.dataforseo.com/v3/app_data/google/languages
example:
en

#### Defined in

[main.ts:178434](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178434)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
optional field
if you use this field, you don’t need to specify language_code
you can receive the list of available languages with language_name by making a separate request to https://api.dataforseo.com/v3/app_data/google/languages
example:
English

#### Defined in

[main.ts:178427](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178427)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name
if you use this field, you don’t need to specify location_name
you can receive the list of available locations of the search engine with their location_code by making a separate request to https://api.dataforseo.com/v3/app_data/google/locations
example:
9061121

#### Defined in

[main.ts:178420](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178420)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code
if you use this field, you don’t need to specify location_code
you can receive the list of available locations of the search engine with their location_name by making a separate request to https://api.dataforseo.com/v3/app_data/google/locations
example:
West Los Angeles,California,United States

#### Defined in

[main.ts:178413](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178413)

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

[main.ts:178499](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178499)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced, html

#### Defined in

[main.ts:178489](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178489)

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

[main.ts:178483](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178483)

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

[main.ts:178442](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178442)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:178473](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L178473)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")