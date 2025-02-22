[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IAppDataTaskRequestInfo

# Interface: IAppDataTaskRequestInfo

## Implemented by

- [`AppDataTaskRequestInfo`](../classes/AppDataTaskRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [depth](IAppDataTaskRequestInfo.md#depth)
- [keyword](IAppDataTaskRequestInfo.md#keyword)
- [language\_code](IAppDataTaskRequestInfo.md#language_code)
- [language\_name](IAppDataTaskRequestInfo.md#language_name)
- [location\_code](IAppDataTaskRequestInfo.md#location_code)
- [location\_name](IAppDataTaskRequestInfo.md#location_name)
- [pingback\_url](IAppDataTaskRequestInfo.md#pingback_url)
- [postback\_data](IAppDataTaskRequestInfo.md#postback_data)
- [postback\_url](IAppDataTaskRequestInfo.md#postback_url)
- [priority](IAppDataTaskRequestInfo.md#priority)
- [tag](IAppDataTaskRequestInfo.md#tag)

## Properties

### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of results to be returned to be returned from the Google Play SERP;
we strongly recommend setting the parsing depth in the multiples of 100, because our system processes 100 results in a row;
Note: your account will be billed per each SERP containing up to 100 results;
thus, setting a depth above 100 may result in additional charges if the search engine returns more than 100 results;
if the specified depth is higher than the number of results in the response, the difference will be refunded to your account balance automatically
default value: 100;
maximum value: 200

#### Defined in

[main.ts:164086](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164086)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
you can specify up to 700 symbols in the keyword field;
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character);
if you need to use the “%” symbol for your keyword, please specify it as “%25”;
if you need to use the “+” symbol for your keyword, please specify it as “%2B”

#### Defined in

[main.ts:164040](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164040)

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

[main.ts:164068](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164068)

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

[main.ts:164061](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164061)

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

[main.ts:164054](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164054)

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

[main.ts:164047](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164047)

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

[main.ts:164118](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164118)

___


### postback\_data

• `Optional` **postback\_data**: `string`

postback_url datatype
required field if you specify postback_url
corresponds to the datatype that will be sent to your server
possible values:
advanced, html

#### Defined in

[main.ts:164108](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164108)

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

[main.ts:164102](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164102)

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

[main.ts:164076](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164076)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:164092](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L164092)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")