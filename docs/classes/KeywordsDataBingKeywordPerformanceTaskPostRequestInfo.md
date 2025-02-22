[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataBingKeywordPerformanceTaskPostRequestInfo

# Class: KeywordsDataBingKeywordPerformanceTaskPostRequestInfo

## Implements

- [`IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo`](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#constructor)

### Properties

- [device](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#device)
- [keywords](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#keywords)
- [language\_code](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#language_code)
- [language\_name](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#language_name)
- [location\_code](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#location_code)
- [location\_coordinate](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#location_coordinate)
- [location\_name](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#location_name)
- [match](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#match)
- [pingback\_url](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#pingback_url)
- [postback\_url](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#postback_url)
- [tag](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#tag)

### Methods

- [init](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#init)
- [toJSON](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#tojson)
- [fromJS](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataBingKeywordPerformanceTaskPostRequestInfo**(`data?`): [`KeywordsDataBingKeywordPerformanceTaskPostRequestInfo`](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo`](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md) |

#### Returns

[`KeywordsDataBingKeywordPerformanceTaskPostRequestInfo`](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md)

#### Defined in

[main.ts:126674](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126674)

## Properties

### device

• `Optional` **device**: `string`

device type
optional field
specify this field if you want to get the data for a particular device typepossible values: desktop, mobile, tablet, all
default value: all

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[device](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#device)

#### Defined in

[main.ts:126601](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126601)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords
required field
The maximum number of keywords you can specify: 2500.
The maximum number of characters for each keyword: 80.
The maximum number of words for each keyword phrase: 10.
the specified keywords will be converted to lowercase, data will be provided in a separate array

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[keywords](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#keywords)

#### Defined in

[main.ts:126596](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126596)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
you can receive the list of available locations and languages by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/keyword_performance/locations_and_languages
example:
"en"

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[language_code](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#language_code)

#### Defined in

[main.ts:126644](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126644)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of search engine language
required field if you don’t specify language_code
if you use this field, you don’t need to specify language_code
you can receive the list of available locations and languages by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/keyword_performance/locations_and_languages
example:
English

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[language_name](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#language_name)

#### Defined in

[main.ts:126638](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126638)

___


### location\_code

• `Optional` **location\_code**: `number`

search engine location code
required field if you don’t specify location_name or location_coordinate
if you use this field, you don’t need to specify location_name or location_coordinate
you can receive the list of available locations and languages by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/keyword_performance/locations_and_languages
example:
2840

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[location_code](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#location_code)

#### Defined in

[main.ts:126623](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126623)

___


### location\_coordinate

• `Optional` **location\_coordinate**: `string`

GPS coordinates of a location
required field if you don’t specify location_name or location_code
if you use this field, you don’t need to specify location_name or location_code
location_coordinate parameter should be specified in the “latitude,longitude” format
the data will be provided for the country the specified coordinates belong to
example:
52.6178549,-155.352142

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[location_coordinate](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#location_coordinate)

#### Defined in

[main.ts:126631](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126631)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of search engine location
required field if you don’t specify location_code or location_coordinate
if you use this field, you don’t need to specify location_code or location_coordinate
you can receive the list of available locations and languages by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/keyword_performance/locations_and_languages
example:
"United States"

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[location_name](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#location_name)

#### Defined in

[main.ts:126616](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126616)

___


### match

• `Optional` **match**: `string`

keywords match type
optional field
can take the following values:
aggregate returns data across all match types;
broad returns data for all user queries containing the specified keyword with varying word order;
phrase returns data for all user queries containing the specified keyword with identical word order;
exact returns data for user query that matches the specified keyword;Note: the aggregate match type is applied by default

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[match](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#match)

#### Defined in

[main.ts:126609](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126609)

___


### pingback\_url

• `Optional` **pingback\_url**: `string`

notification URL of a completed task
optional field
when a task is completed we will notify you by GET request sent to the URL you have specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request
example:
http://your-server.com/pingscript?id=$id
http://your-server.com/pingscript?id=$id&tag=$tag
Note: special symbols in pingback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[pingback_url](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#pingback_url)

#### Defined in

[main.ts:126664](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126664)

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

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[postback_url](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#postback_url)

#### Defined in

[main.ts:126654](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126654)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md).[tag](../interfaces/IKeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md#tag)

#### Defined in

[main.ts:126670](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126670)

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

[main.ts:126683](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126683)

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

[main.ts:126714](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126714)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataBingKeywordPerformanceTaskPostRequestInfo`](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataBingKeywordPerformanceTaskPostRequestInfo`](KeywordsDataBingKeywordPerformanceTaskPostRequestInfo.md)

#### Defined in

[main.ts:126707](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126707)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")