[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleKeywordIdeasLiveRequestInfo

# Class: DataforseoLabsGoogleKeywordIdeasLiveRequestInfo

## Implements

- [`IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo`](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#constructor)

### Properties

- [closely\_variants](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#closely_variants)
- [filters](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#filters)
- [ignore\_synonyms](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#ignore_synonyms)
- [include\_serp\_info](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#include_serp_info)
- [keywords](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#keywords)
- [language\_code](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#language_code)
- [language\_name](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#language_name)
- [limit](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#limit)
- [location\_code](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#location_code)
- [location\_name](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#location_name)
- [offset](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#offset)
- [offset\_token](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#offset_token)
- [order\_by](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#order_by)
- [tag](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#tag)

### Methods

- [init](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#init)
- [toJSON](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleKeywordIdeasLiveRequestInfo**(`data?`): [`DataforseoLabsGoogleKeywordIdeasLiveRequestInfo`](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo`](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md) |

#### Returns

[`DataforseoLabsGoogleKeywordIdeasLiveRequestInfo`](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md)

#### Defined in

[main.ts:81296](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81296)

## Properties

### closely\_variants

• `Optional` **closely\_variants**: `boolean`

search mode
optional field
if set to true the results will be based on the phrase-match search algorithm
if set to false the results will be based on the broad-match search algorithm
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[closely_variants](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#closely_variants)

#### Defined in

[main.ts:81221](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81221)

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
note that you can not filter the results by relevance
example:
["keyword_info.search_volume",">",0]
[["keyword_info.search_volume","in",[0,1000]],
"and",
["keyword_info.competition_level","=","LOW"]]
[["keyword_info.search_volume",">",100],
"and",
[["keyword_info.cpc","<",0.5],
"or",
["keyword_info.high_top_of_page_bid","<=",0.5]]]
for more information about filters, please refer to Dataforseo Labs – Filters or this help center guide

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[filters](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#filters)

#### Defined in

[main.ts:81269](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81269)

___


### ignore\_synonyms

• `Optional` **ignore\_synonyms**: `boolean`

ignore highly similar keywords
optional field
if set to true only core keywords will be returned, all highly similar keywords will be excluded;
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[ignore_synonyms](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#ignore_synonyms)

#### Defined in

[main.ts:81226](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81226)

___


### include\_serp\_info

• `Optional` **include\_serp\_info**: `boolean`

include data from SERP for each keyword
optional field
if set to true, we will return a serp_info array containing SERP data (number of search results, relevant URL, and SERP features) for every keyword in the response
default value: false

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[include_serp_info](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#include_serp_info)

#### Defined in

[main.ts:81231](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81231)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords
required field
UTF-8 encoding
The maximum number of keywords you can specify: 200.
The minimum number of characters for each keyword: 3.
The keywords will be converted to lowercase format

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[keywords](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#keywords)

#### Defined in

[main.ts:81181](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81181)

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

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[language_code](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#language_code)

#### Defined in

[main.ts:81215](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81215)

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

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[language_name](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#language_name)

#### Defined in

[main.ts:81206](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81206)

___


### limit

• `Optional` **limit**: `number`

the maximum number of keywords in the results array
optional field
default value: 700
maximum value: 1000

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[limit](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#limit)

#### Defined in

[main.ts:81236](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81236)

___


### location\_code

• `Optional` **location\_code**: `number`

unique location identifier
required field if you don’t specify location_name
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
2840

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[location_code](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#location_code)

#### Defined in

[main.ts:81197](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81197)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_name by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
United Kingdom

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[location_name](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#location_name)

#### Defined in

[main.ts:81189](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81189)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned keywords
optional field
default value: 0
if you specify the 10 value, the first ten keywords in the results array will be omitted and the data will be provided for the successive keywords

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[offset](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#offset)

#### Defined in

[main.ts:81241](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81241)

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

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[offset_token](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#offset_token)

#### Defined in

[main.ts:81249](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81249)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
you can use the same values as in the filters array to sort the results
possible sorting types:
asc – results will be sorted in the ascending order
desc – results will be sorted in the descending order
you should use a comma to set up a sorting parameter
example:
["keyword_info.competition,desc"]
default rule:
["relevance,desc"]
relevance is used as the default sorting rule to provide you with the closest keyword ideas. We recommend using this sorting rule to get highly-relevant search terms. Note that relevance is only our internal system identifier, so it can not be used as a filter, and you will not find this field in the result array. The relevance score is based on a similar principle as used in the Keywords For Keywords endpoint.
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["keyword_info.search_volume,desc","keyword_info.cpc,desc"]

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[order_by](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#order_by)

#### Defined in

[main.ts:81286](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81286)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md).[tag](../interfaces/IDataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md#tag)

#### Defined in

[main.ts:81292](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81292)

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

[main.ts:81305](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81305)

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

[main.ts:81347](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81347)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleKeywordIdeasLiveRequestInfo`](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleKeywordIdeasLiveRequestInfo`](DataforseoLabsGoogleKeywordIdeasLiveRequestInfo.md)

#### Defined in

[main.ts:81340](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81340)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")