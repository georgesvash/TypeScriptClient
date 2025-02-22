[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo

# Interface: IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo

## Implemented by

- [`DataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo`](../classes/DataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [category\_codes](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#category_codes)
- [correlate](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#correlate)
- [etv\_max](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#etv_max)
- [etv\_min](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#etv_min)
- [filters](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#filters)
- [first\_date](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#first_date)
- [include\_subdomains](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#include_subdomains)
- [item\_types](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#item_types)
- [language\_code](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#language_code)
- [language\_name](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#language_name)
- [limit](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#limit)
- [location\_code](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#location_code)
- [location\_name](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#location_name)
- [offset](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#offset)
- [order\_by](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#order_by)
- [second\_date](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#second_date)
- [tag](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#tag)
- [top\_categories\_count](IDataforseoLabsGoogleDomainMetricsByCategoriesLiveRequestInfo.md#top_categories_count)

## Properties

### category\_codes

• `Optional` **category\_codes**: `string`[]

product and service categories
required field
The maximum number of categories you can specify: 5
you can download the full list of possible categories

#### Defined in

[main.ts:84484](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84484)

___


### correlate

• `Optional` **correlate**: `boolean`

correlate data with previously obtained datasets
optional field
default value: true;
if you use this parameter, our system will correlate data you obtain now with previously obtained datasets;
this parameter is intended to mitigate any inconsistencies that may result from changes to our database;
Note: we do not recommend setting correlate to false

#### Defined in

[main.ts:84575](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84575)

___


### etv\_max

• `Optional` **etv\_max**: `number`

maximum current organic ETV of the domain
optional field
if specified, the API will return only domains with organic_etv lesser than the specified value

#### Defined in

[main.ts:84568](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84568)

___


### etv\_min

• `Optional` **etv\_min**: `number`

minimum current organic ETV of the domain
optional field
if specified, the API will return only domains with organic_etv greater than the specified value

#### Defined in

[main.ts:84564](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84564)

___


### filters

• `Optional` **filters**: `any`[]

array of results filtering parameters
optional field
you can add several filters at once (8 filters maximum);
you should set a logical operator and, or between the conditions
the following operators are supported:
regex, <, <=, >, >=, =, <>, in, not_in, like, not_like;
you can use the % operator with like and not_like to match any string of zero or more characters;
example:
["metrics_history.202110.organic.pos_1", ">", 15];
for more information about filters, please refer to Dataforseo Labs – Filters or this help center guide

#### Defined in

[main.ts:84596](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84596)

___


### first\_date

• `Optional` **first\_date**: `string`

first date of comparison period
required field
first date for which domain metrics will be provided;
date format: "yyyy-mm-dd";
example: "2021-06-01";
the list available dates is available through the available history endpoint;
Note: first_date cannot be greater than today’s date;
Also note: the dates specified in first_date and second_date cannot point to the same month of the same year;
you can specify the dates in any order: first_date can be greater than second_date and vice versa;
minimum date: "2020-10-01"

#### Defined in

[main.ts:84495](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84495)

___


### include\_subdomains

• `Optional` **include\_subdomains**: `boolean`

return subdomains in the API response
optional field
if false, the API response will contain main_domain only;
if true, the API will return main_domain plus its subdomains (if available);
default value: true

#### Defined in

[main.ts:84560](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84560)

___


### item\_types

• `Optional` **item\_types**: `string`[]

display results by item type
optional field
indicates the type of search results included in the response;
Note: if the item_types array contains item types that are different from the organic object, the results will be ordered by the first item type in the array; you will not be able to sort and filter results by the types of search results not included in the response;
possible values:
["organic", "paid", "featured_snippet", "local_pack"];
default value:
["organic", "paid"]

#### Defined in

[main.ts:84546](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84546)

___


### language\_code

• `Optional` **language\_code**: `string`

unique language identifier
required field if you don’t specify language_name
Note: it is required to specify either language_name or language_code;
you can receive the list of available languages with their language_code by making a separate request to https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
example:
en

#### Defined in

[main.ts:84537](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84537)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
required field if you don’t specify language_code
Note: it is required to specify either language_name or language_code;
you can receive the list of available languages with their language_name by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
example:
English

#### Defined in

[main.ts:84530](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84530)

___


### limit

• `Optional` **limit**: `number`

the maximum number of domains in the results array
optional field
default value: 100;
maximum value: 1000

#### Defined in

[main.ts:84580](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84580)

___


### location\_code

• `Optional` **location\_code**: `number`

unique location identifier
required field if you don’t specify location_name
Note: it is required to specify either location_name or location_code;
you can receive the list of available locations with their location_code by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
example:
2840

#### Defined in

[main.ts:84522](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84522)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code
Note: it is required to specify either location_name or location_code;
you can receive the list of available locations with their location_name by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
example:
United Kingdom

#### Defined in

[main.ts:84514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84514)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned domains
optional field
default value: 0;
if you specify the 10 value, the first ten domains in the results array will be omitted and the data will be provided for the successive domains

#### Defined in

[main.ts:84585](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84585)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
you can use the same values as in the filters array to sort the results;
default rule: ["organic_etv,desc"];
possible sorting types:
asc – results will be sorted in ascending order
desc – results will be sorted in descending order;
you should use a comma to set up a sorting type;
example:
["organic_count,desc"];
note that you can set no more than three sorting rules in a single request;
you should use a comma to separate several sorting rules;
example:
["organic_etv,desc","organic_count,asc"]

#### Defined in

[main.ts:84611](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84611)

___


### second\_date

• `Optional` **second\_date**: `string`

second date of comparison period
required field
second date for which domain metrics will be provided;
date format: "yyyy-mm-dd";
example: "2021-10-01";
the list available dates is available through the available history endpoint;
Note: second_date cannot be greater than today’s date;
Also note: the dates specified in first_date and second_date cannot point to the same month of the same year;
you can specify the dates in any order: second_date can be greater than first_date and vice versa;
minimum date: "2020-10-01"

#### Defined in

[main.ts:84506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84506)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255;
you can use this parameter to identify the task and match it with the result;
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:84617](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84617)

___


### top\_categories\_count

• `Optional` **top\_categories\_count**: `number`

number of additional domain categories
optional field
by using this parameter, you can receive domains relevant to additional categories that are not specified in category_codes above;
to learn more about the parameter, please refer to this help center article;
by default, top_categories_count is equal to the number of categories specified in the category_codes array;
Note: top_categories_count cannot be less than the number of categories in the category_codes array;
maximum value: 5

#### Defined in

[main.ts:84554](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L84554)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")