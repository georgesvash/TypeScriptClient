[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsBingRankedKeywordsLiveRequestInfo

# Interface: IDataforseoLabsBingRankedKeywordsLiveRequestInfo

## Implemented by

- [`DataforseoLabsBingRankedKeywordsLiveRequestInfo`](../classes/DataforseoLabsBingRankedKeywordsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [filters](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#filters)
- [historical\_serp\_mode](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#historical_serp_mode)
- [ignore\_synonyms](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#ignore_synonyms)
- [item\_types](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#item_types)
- [language\_code](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#language_code)
- [language\_name](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#language_name)
- [limit](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#limit)
- [load\_rank\_absolute](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#load_rank_absolute)
- [location\_code](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#location_code)
- [location\_name](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#location_name)
- [offset](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#offset)
- [order\_by](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#order_by)
- [tag](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#tag)
- [target](IDataforseoLabsBingRankedKeywordsLiveRequestInfo.md#target)

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
["ranked_serp_element.serp_item.rank_group","<=",10]
[["ranked_serp_element.serp_item.rank_group","<=",10],
"and",
["ranked_serp_element.serp_item.type","<>","paid"]]
[["keyword_data.keyword_info.search_volume","<>",0],
"and",
[["ranked_serp_element.serp_item.type","<>","paid"],"or",["ranked_serp_element.serp_item.is_malicious","=",false]]]
if you want to get the keywords a particular webpage ranks for, specify the filter by the ranked_serp_element.serp_item.relative_url parameter
example:
["ranked_serp_element.serp_item.relative_url", "=", "/apis/rank-tracker-api"]
for more information about filters, please refer to Dataforseo Labs – Filters or this help center guide

#### Defined in

[main.ts:105283](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105283)

___


### historical\_serp\_mode

• `Optional` **historical\_serp\_mode**: `string`

data collection mode
optional field
you can use this field to filter the results;
possible types of filtering:
live — return keywords for which the specified target currently has ranking results in SERP;
lost — return keywords for which the specified target had previously had ranking results in SERP, but didn’t have them during the last check;
all — return both types of keywords.
default value: live

#### Defined in

[main.ts:105263](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105263)

___


### ignore\_synonyms

• `Optional` **ignore\_synonyms**: `boolean`

ignore highly similar keywords
optional field
if set to true only core keywords will be returned, all highly similar keywords will be excluded;
default value: false

#### Defined in

[main.ts:105239](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105239)

___


### item\_types

• `Optional` **item\_types**: `string`[]

display results by item type
optional field
indicates the type of search results included in the response
Note: if the item_types array contains item types that are different from organic, the results will be ordered by the first item type in the array; you will not be able to sort and filter results by the types of search results not included in the response;
possible values:
["organic", "paid", "featured_snippet", "local_pack"]
default value:
["organic", "paid", "featured_snippet", "local_pack"]

#### Defined in

[main.ts:105234](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105234)

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

#### Defined in

[main.ts:105225](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105225)

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

#### Defined in

[main.ts:105216](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105216)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned keywords
optional field
default value: 100
maximum value: 1000

#### Defined in

[main.ts:105244](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105244)

___


### load\_rank\_absolute

• `Optional` **load\_rank\_absolute**: `boolean`

return rankings distribution by rank_absolute
optional field
default value: false
if set to true, we will return the field metrics_absolute containing rankings distribution by the rank_absolute parameter that indicates the result’s position among all SERP elements

#### Defined in

[main.ts:105254](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105254)

___


### location\_code

• `Optional` **location\_code**: `number`

location code
optional field
if you use this field, you don’t need to specify location_name
you can receive the list of available locations with their location_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
ignore this field to get the results for all available locations;
Note: this endpoint currently supports the US location only;
example:
2840

#### Defined in

[main.ts:105207](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105207)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
optional field
if you use this field, you don’t need to specify location_code
you can receive the list of available locations with their location_name by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
ignore this field to get the results for all available locations;
Note: this endpoint currently supports the US location only;
example:
United States

#### Defined in

[main.ts:105197](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105197)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned keywords
optional field
default value: 0
if you specify the 10 value, the first ten keywords in the results array will be omitted and the data will be provided for the successive keywords

#### Defined in

[main.ts:105249](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105249)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
you can use the same values as in the filters array to sort the results
possible sorting types:
asc – results will be sorted in the ascending order
desc – results will be sorted in the descending order
you should use a comma to set up a sorting type
example:
["keyword_data.keyword_info.competition,desc"]
default rule:
["ranked_serp_element.serp_item.rank_group,asc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["keyword_data.keyword_info.search_volume,desc","keyword_data.keyword_info.cpc,desc"]

#### Defined in

[main.ts:105299](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105299)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:105305](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105305)

___


### target

• `Optional` **target**: `string`

domain
required field
the domain name of the target website
the domain should be specified without https:// or www.
if you want to get the keywords a particular webpage ranks for, specify the filter by the
ranked_serp_element.serp_item.relative_url parameter
example:
"filters":[
"ranked_serp_element.serp_item.relative_url", "=", "/apis/rank-tracker-api"]

#### Defined in

[main.ts:105187](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L105187)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")