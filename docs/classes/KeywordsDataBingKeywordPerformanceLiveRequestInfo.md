[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataBingKeywordPerformanceLiveRequestInfo

# Class: KeywordsDataBingKeywordPerformanceLiveRequestInfo

## Implements

- [`IKeywordsDataBingKeywordPerformanceLiveRequestInfo`](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#constructor)

### Properties

- [device](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#device)
- [keywords](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#keywords)
- [language\_code](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#language_code)
- [language\_name](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#language_name)
- [location\_code](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#location_code)
- [location\_coordinate](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#location_coordinate)
- [location\_name](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#location_name)
- [match](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#match)
- [tag](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#tag)

### Methods

- [init](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#init)
- [toJSON](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#tojson)
- [fromJS](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataBingKeywordPerformanceLiveRequestInfo**(`data?`): [`KeywordsDataBingKeywordPerformanceLiveRequestInfo`](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataBingKeywordPerformanceLiveRequestInfo`](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md) |

#### Returns

[`KeywordsDataBingKeywordPerformanceLiveRequestInfo`](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md)

#### Defined in

[main.ts:127608](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127608)

## Properties

### device

• `Optional` **device**: `string`

device type
optional field
specify this field if you want to get the data for a particular device typepossible values: desktop, mobile, tablet, all
default value: all

#### Implementation of

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[device](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#device)

#### Defined in

[main.ts:127555](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127555)

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

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[keywords](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#keywords)

#### Defined in

[main.ts:127550](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127550)

___


### language\_code

• `Optional` **language\_code**: `string`

search engine language code
required field if you don’t specify language_name
you can receive the list of available locations and languages by making a separate request to https://api.dataforseo.com/v3/keywords_data/bing/keyword_performance/locations_and_languages
example:
"en"

#### Implementation of

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[language_code](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#language_code)

#### Defined in

[main.ts:127598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127598)

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

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[language_name](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#language_name)

#### Defined in

[main.ts:127592](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127592)

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

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[location_code](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#location_code)

#### Defined in

[main.ts:127577](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127577)

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

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[location_coordinate](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#location_coordinate)

#### Defined in

[main.ts:127585](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127585)

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

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[location_name](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#location_name)

#### Defined in

[main.ts:127570](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127570)

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

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[match](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#match)

#### Defined in

[main.ts:127563](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127563)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IKeywordsDataBingKeywordPerformanceLiveRequestInfo](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md).[tag](../interfaces/IKeywordsDataBingKeywordPerformanceLiveRequestInfo.md#tag)

#### Defined in

[main.ts:127604](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127604)

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

[main.ts:127617](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127617)

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

[main.ts:127646](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127646)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataBingKeywordPerformanceLiveRequestInfo`](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataBingKeywordPerformanceLiveRequestInfo`](KeywordsDataBingKeywordPerformanceLiveRequestInfo.md)

#### Defined in

[main.ts:127639](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L127639)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")