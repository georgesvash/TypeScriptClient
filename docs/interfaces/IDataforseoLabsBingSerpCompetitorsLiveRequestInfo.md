[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsBingSerpCompetitorsLiveRequestInfo

# Interface: IDataforseoLabsBingSerpCompetitorsLiveRequestInfo

## Implemented by

- [`DataforseoLabsBingSerpCompetitorsLiveRequestInfo`](../classes/DataforseoLabsBingSerpCompetitorsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [filters](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#filters)
- [include\_subdomains](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#include_subdomains)
- [item\_types](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#item_types)
- [keywords](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#keywords)
- [language\_code](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#language_code)
- [language\_name](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#language_name)
- [limit](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#limit)
- [location\_code](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#location_code)
- [location\_name](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#location_name)
- [offset](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#offset)
- [order\_by](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#order_by)
- [tag](IDataforseoLabsBingSerpCompetitorsLiveRequestInfo.md#tag)

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

[main.ts:107027](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107027)

___


### include\_subdomains

• `Optional` **include\_subdomains**: `boolean`

indicates if the subdomains will be included in the search
optional field
if set to false, the subdomains will be ignored
default value: true

#### Defined in

[main.ts:106994](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106994)

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

[main.ts:107002](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107002)

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

[main.ts:106955](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106955)

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

[main.ts:106989](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106989)

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

[main.ts:106981](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106981)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned domains
optional field
default value: 100
maximum value: 1000

#### Defined in

[main.ts:107007](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107007)

___


### location\_code

• `Optional` **location\_code**: `number`

unique location identifier
required field if you don’t specify location_name
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_code parameters by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
Note: this endpoint currently supports the US location only;
example:
2840

#### Defined in

[main.ts:106973](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106973)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with location_name parameters by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
Note: this endpoint currently supports the US location only;
example:
United States

#### Defined in

[main.ts:106964](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106964)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned domains
optional field
default value: 0
if you specify the 10 value, the first ten domains in the results array will be omitted and the data will be provided for the successive domains

#### Defined in

[main.ts:107012](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107012)

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

[main.ts:107043](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107043)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:107049](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L107049)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")