[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo

# Interface: IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo

## Implemented by

- [`DataforseoLabsGoogleSerpCompetitorsLiveRequestInfo`](../classes/DataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [filters](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#filters)
- [include\_subdomains](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#include_subdomains)
- [item\_types](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#item_types)
- [keywords](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#keywords)
- [language\_code](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#language_code)
- [language\_name](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#language_name)
- [limit](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#limit)
- [location\_code](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#location_code)
- [location\_name](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#location_name)
- [offset](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#offset)
- [order\_by](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#order_by)
- [tag](IDataforseoLabsGoogleSerpCompetitorsLiveRequestInfo.md#tag)

## Properties

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
["median_position","in",[1,10]]
[["median_position","in",[1,10]],"and",["domain","not_like","%wikipedia.org%"]]
[["domain","not_like","%wikipedia.org%"],
"and",
[["relevant_serp_items",">",0],"or",["median_position","in",[1,10]]]]
for more information about filters, please refer to Dataforseo Labs – Filters or this help center guide

#### Defined in

[main.ts:87619](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87619)

___


### include\_subdomains

• `Optional` **include\_subdomains**: `boolean`

indicates if the subdomains will be included in the search
optional field
if set to false, the subdomains will be ignored
default value: true

#### Defined in

[main.ts:87586](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87586)

___


### item\_types

• `Optional` **item\_types**: `string`[]

search results type
indicates type of search results included in the response
optional field
possible values:
["organic", "paid", "featured_snippet", "local_pack"]
default value:
["organic", "paid", "featured_snippet", "local_pack"]

#### Defined in

[main.ts:87594](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87594)

___


### keywords

• `Optional` **keywords**: `string`[]

keywords array
required field
the results will be based on the keywords you specify in this array
UTF-8 encoding;
the keywords will be converted to lowercase format;
a keyword should be at least 3 characters long;
you can specify the maximum of 200 keywords

#### Defined in

[main.ts:87549](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87549)

___


### language\_code

• `Optional` **language\_code**: `string`

unique language identifier
required field if you don’t specify language_name
Note: it is required to specify either language_name or language_code
you can receive the list of available languages with their language_code parameters by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
en

#### Defined in

[main.ts:87581](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87581)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
required field if you don’t specify language_code
Note: it is required to specify either language_name or language_code
you can receive the list of available languages with their language_name parameters by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
English

#### Defined in

[main.ts:87573](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87573)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned domains
optional field
default value: 100
maximum value: 1000

#### Defined in

[main.ts:87599](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87599)

___


### location\_code

• `Optional` **location\_code**: `number`

unique location identifier
required field if you don’t specify location_name
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_code parameters by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
2840

#### Defined in

[main.ts:87565](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87565)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with location_name parameters by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
United Kingdom

#### Defined in

[main.ts:87557](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87557)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned domains
optional field
default value: 0
if you specify the 10 value, the first ten domains in the results array will be omitted and the data will be provided for the successive domains

#### Defined in

[main.ts:87604](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87604)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
you can use the same values as in the filters array to sort the results
possible sorting types:
asc – results will be sorted in the ascending order
desc – results will be sorted in the descending order
the comma is used as a separator
example:
["avg_position,asc"]
default rule:
["rating,desc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["avg_position,asc","etv,desc"]

#### Defined in

[main.ts:87635](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87635)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:87641](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L87641)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")