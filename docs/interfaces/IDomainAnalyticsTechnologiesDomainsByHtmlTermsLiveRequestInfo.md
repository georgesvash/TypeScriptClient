[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo

# Interface: IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo

## Implemented by

- [`DomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo`](../classes/DomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [filters](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#filters)
- [keywords](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#keywords)
- [limit](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#limit)
- [mode](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#mode)
- [offset](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#offset)
- [offset\_token](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#offset_token)
- [order\_by](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#order_by)
- [search\_terms](IDomainAnalyticsTechnologiesDomainsByHtmlTermsLiveRequestInfo.md#search_terms)

## Properties

### filters

• `Optional` **filters**: `any`[]

array of results filtering parameters
optional field
you can add several filters at once (8 filters maximum)
you should set a logical operator and, or between the conditions
the following operators are supported:
<, <=, >, >=, =, <>, in, not_in, like, not_like
you can use the % operator with like and not_like to match any string of zero or more characters
example:
["domain","like","%seo%"]
[["country_iso_code","=","US"],
"and",
["domain_rank",">",100]]
[["domain_rank",">",100],
"and",
[["country_iso_code","=","US"],"or",["country_iso_code","=","CA"]]]
for more information about filters, please refer to Domain Analytics Technologies API – Filters

#### Defined in

[main.ts:74820](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74820)

___


### keywords

• `Optional` **keywords**: `string`[]

target keywords in the domain’s title, description or meta keywords
optional field
UTF-8 encoding
each keyword should be at least 3 characters long
maximum number of keywords you can specify: 10
example:
["seo","software"]

#### Defined in

[main.ts:74796](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74796)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned domains
optional field
default value: 100
maximum value: 10000

#### Defined in

[main.ts:74842](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74842)

___


### mode

• `Optional` **mode**: `string`

search mode
optional field
possible search mode types:
strict_entry – search for results exactly matching the order, intervals and separators in the specified search terms
entry – search for results ignoring the order, intervals and separators in the specified search terms
default value: entry

#### Defined in

[main.ts:74803](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74803)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned domains
optional field
default value: 0
if you specify the 10 value, the first ten domains in the results array will be omitted and the data will be provided for the successive domains;
Note: the maximum value is 9999, the sum of limit and offset must not exceed 10000;
use the offset_token if you would like to offset more results

#### Defined in

[main.ts:74849](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74849)

___


### offset\_token

• `Optional` **offset\_token**: `string`

token for subsequent requests
optional field
provided in the identical filed of the response to each request;
use this parameter to avoid timeouts while trying to obtain over 100,000 results in a single request;
by specifying the unique offset_token value from the response array, you will get the subsequent results of the initial task;
offset_token values are unique for each subsequent task
Note: if the offset_token is specified in the request, all other parameters should be identical to the previous request

#### Defined in

[main.ts:74857](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74857)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
available fields:
domain_rank, domain, last_visited, country_iso_code, language_code, content_language_code
possible sorting types:
asc – results will be sorted in the ascending order
desc – results will be sorted in the descending order
you should use a comma to set up a sorting type
example:
["last_visited,desc"]
default rule:
["domain_rank,desc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["last_visited,desc","domain_rank,desc"]

#### Defined in

[main.ts:74837](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74837)

___


### search\_terms

• `Optional` **search\_terms**: `string`[]

target search terms
required field
specify target HTML elements, tags, attributes, their content or all of the above
if you specify more than one search term, you will receive only the domains containing all of the specified terms in the HTML code of their homepage
maximum number of search terms you can specify: 10
example:
["data-attrid"]

#### Defined in

[main.ts:74788](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74788)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")