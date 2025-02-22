[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo

# Class: DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo

## Implements

- [`IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo`](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#constructor)

### Properties

- [exact\_match](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#exact_match)
- [filters](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#filters)
- [ignore\_synonyms](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#ignore_synonyms)
- [include\_seed\_keyword](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#include_seed_keyword)
- [include\_serp\_info](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#include_serp_info)
- [keyword](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#keyword)
- [language\_code](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#language_code)
- [language\_name](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#language_name)
- [limit](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#limit)
- [location\_code](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#location_code)
- [location\_name](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#location_name)
- [offset](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#offset)
- [offset\_token](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#offset_token)
- [order\_by](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#order_by)
- [tag](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#tag)

### Methods

- [init](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#init)
- [toJSON](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo**(`data?`): [`DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo`](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md) |

#### Returns

[`DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md)

#### Defined in

[main.ts:80728](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80728)

## Properties

### exact\_match

• `Optional` **exact\_match**: `boolean`

search for the exact phrase
optional field
if set to true, the returned keywords will include the exact keyword phrase you specified, with potentially other words before or after that phrase
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[exact_match](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#exact_match)

#### Defined in

[main.ts:80661](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80661)

___


### filters

• `Optional` **filters**: `any`[]

array of results filtering parameters
optional field
you can add several filters at once (8 filters maximum)
you should set a logical operator and, or between the conditions
the following operators are supported:
regex, <, <=, >, >=, =, <>, in, not_in, like, not_like
you can use the % operator with like and not_like to match any string of zero or more characters
example:
["keyword_info.search_volume",">",0]
[["keyword_info.search_volume","in",[0,1000]],
"and",
["keyword_info.competition_level","=","LOW"]][["keyword_info.search_volume",">",100],
"and",
[["keyword_info.cpc","<",0.5],
"or",
["keyword_info.high_top_of_page_bid","<=",0.5]]]
for more information about filters, please refer to Dataforseo Labs – Filters or this help center guide

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[filters](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#filters)

#### Defined in

[main.ts:80684](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80684)

___


### ignore\_synonyms

• `Optional` **ignore\_synonyms**: `boolean`

ignore highly similar keywords
optional field
if set to true only core keywords will be returned, all highly similar keywords will be excluded;
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[ignore_synonyms](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#ignore_synonyms)

#### Defined in

[main.ts:80666](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80666)

___


### include\_seed\_keyword

• `Optional` **include\_seed\_keyword**: `boolean`

include data for the seed keyword
optional field
if set to true, data for the seed keyword specified in the keyword field will be provided in the seed_keyword_data array of the response
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[include_seed_keyword](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#include_seed_keyword)

#### Defined in

[main.ts:80651](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80651)

___


### include\_serp\_info

• `Optional` **include\_serp\_info**: `boolean`

include data from SERP for each keyword
optional field
if set to true, we will return a serp_info array containing SERP data (number of search results, relevant URL, and SERP features) for every keyword in the response
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[include_serp_info](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#include_serp_info)

#### Defined in

[main.ts:80656](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80656)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
UTF-8 encoding
a keyword should be at least 3 characters long;
the keywords will be converted to lowercase format

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[keyword](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#keyword)

#### Defined in

[main.ts:80610](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80610)

___


### language\_code

• `Optional` **language\_code**: `string`

language code
optional field
if you use this field, you don’t need to specify language_name
you can receive the list of available languages with their language_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
ignore this field to get the results for all available languages
example:
en

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[language_code](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#language_code)

#### Defined in

[main.ts:80646](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80646)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
optional field
if you use this field, you don’t need to specify language_code
you can receive the list of available languages with their language_name by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
ignore this field to get the results for all available languages
example:
English

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[language_name](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#language_name)

#### Defined in

[main.ts:80637](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80637)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned keywords
optional field
default value: 100
maximum value: 1000

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[limit](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#limit)

#### Defined in

[main.ts:80705](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80705)

___


### location\_code

• `Optional` **location\_code**: `number`

location code
optional field
if you use this field, you don’t need to specify location_name
you can receive the list of available locations with their location_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
ignore this field to get the results for all available locations
example:
2840

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[location_code](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#location_code)

#### Defined in

[main.ts:80628](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80628)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
optional field
if you use this field, you don’t need to specify location_code
you can receive the list of available locations with their location_name by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
ignore this field to get the results for all available locations
example:
United Kingdom

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[location_name](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#location_name)

#### Defined in

[main.ts:80619](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80619)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned keywords
optional field
default value: 0
if you specify the 10 value, the first ten keywords in the results array will be omitted and the data will be provided for the successive keywords

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[offset](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#offset)

#### Defined in

[main.ts:80710](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80710)

___


### offset\_token

• `Optional` **offset\_token**: `string`

offset token for subsequent requests
optional field
provided in the identical filed of the response to each request;
use this parameter to avoid timeouts while trying to obtain over 10,000 results in a single request;
by specifying the unique offset_token value from the response array, you will get the subsequent results of the initial task;
offset_token values are unique for each subsequent task
Note: if the offset_token is specified in the request, all other parameters except limit will not be taken into account when processing a task.

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[offset_token](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#offset_token)

#### Defined in

[main.ts:80718](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80718)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
you can use the same values as in the filters array to sort the results
possible sorting types:
asc – results will be sorted in the ascending order
desc – results will be sorted in the descending order
a comma is used as a separator
example:
["keyword_info.competition,desc"]
default rule:
["keyword_info.search_volume,desc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["keyword_info.search_volume,desc","keyword_info.cpc,desc"]

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[order_by](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#order_by)

#### Defined in

[main.ts:80700](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80700)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md).[tag](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md#tag)

#### Defined in

[main.ts:80724](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80724)

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

[main.ts:80737](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80737)

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

[main.ts:80776](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80776)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveRequestInfo.md)

#### Defined in

[main.ts:80769](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L80769)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")