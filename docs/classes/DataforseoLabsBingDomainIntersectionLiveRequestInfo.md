[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsBingDomainIntersectionLiveRequestInfo

# Class: DataforseoLabsBingDomainIntersectionLiveRequestInfo

## Implements

- [`IDataforseoLabsBingDomainIntersectionLiveRequestInfo`](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#constructor)

### Properties

- [filters](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#filters)
- [include\_serp\_info](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#include_serp_info)
- [intersections](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#intersections)
- [item\_types](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#item_types)
- [language\_code](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#language_code)
- [language\_name](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#language_name)
- [limit](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#limit)
- [location\_code](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#location_code)
- [location\_name](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#location_name)
- [offset](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#offset)
- [order\_by](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#order_by)
- [tag](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#tag)
- [target1](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#target1)
- [target2](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#target2)

### Methods

- [init](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#init)
- [toJSON](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#tojson)
- [fromJS](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsBingDomainIntersectionLiveRequestInfo**(`data?`): [`DataforseoLabsBingDomainIntersectionLiveRequestInfo`](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsBingDomainIntersectionLiveRequestInfo`](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md) |

#### Returns

[`DataforseoLabsBingDomainIntersectionLiveRequestInfo`](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md)

#### Defined in

[main.ts:103502](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103502)

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
["keyword_data.keyword_info.search_volume","in",[100,1000]]
[["first_domain_serp_element.etv",">",0],"and",["first_domain_serp_element.description","like","%goat%"]]
[["keyword_data.keyword_info.search_volume",">",100],
"and",
[["first_domain_serp_element.description","like","%goat%"],
"or",
["second_domain_serp_element.type","=","organic"]]]
for more information about filters, please refer to Dataforseo Labs – Filters or this help center guide

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[filters](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#filters)

#### Defined in

[main.ts:103476](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103476)

___


### include\_serp\_info

• `Optional` **include\_serp\_info**: `boolean`

include data from SERP for each keyword
optional field
if set to true, we will return a serp_info array containing SERP data (number of search results, relevant URL, and SERP features) for every keyword in the response
default value: false

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[include_serp_info](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#include_serp_info)

#### Defined in

[main.ts:103449](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103449)

___


### intersections

• `Optional` **intersections**: `boolean`

domain intersections in SERP
optional field
if you set intersections to true, you will get the keywords for which both target domains specified as target1 and target2 have results within the same SERP; the corresponding SERP elements for both domains will be provided in the results array
Note: this endpoint will not provide results if the number of intersecting keywords exceeds 10 million
if you specify intersections: false, you will get the keywords for which the domain specified as target1 has results in SERP, and the domain specified as target2 doesn’t;
thus, the corresponding SERP elements and other data will be provided for the domain specified as target1only
default value: true

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[intersections](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#intersections)

#### Defined in

[main.ts:103436](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103436)

___


### item\_types

• `Optional` **item\_types**: `string`[]

search results type
indicates type of search results included in the response
optional field
possible values:
["organic", "paid", "featured_snippet", "local_pack"]
default value:
["organic", "paid"]

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[item_types](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#item_types)

#### Defined in

[main.ts:103444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103444)

___


### language\_code

• `Optional` **language\_code**: `string`

language code
required field if you don’t specify language_name
Note: it is required to specify either language_name or language_code
you can receive the list of available languages with their language_code by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
en

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[language_code](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#language_code)

#### Defined in

[main.ts:103428](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103428)

___


### language\_name

• `Optional` **language\_name**: `string`

full name of the language
required field if you don’t specify language_code
Note: it is required to specify either language_name or language_code
you can receive the list of available languages with their language_name by making a separate request to the
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages
example:
English

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[language_name](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#language_name)

#### Defined in

[main.ts:103420](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103420)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned keywords
optional field
default value: 100
maximum value: 1000

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[limit](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#limit)

#### Defined in

[main.ts:103454](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103454)

___


### location\_code

• `Optional` **location\_code**: `number`

location code
required field if you don’t specify location_name
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_code by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
Note: this endpoint currently supports the US location only;
example:
2840

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[location_code](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#location_code)

#### Defined in

[main.ts:103412](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103412)

___


### location\_name

• `Optional` **location\_name**: `string`

full name of the location
required field if you don’t specify location_code
Note: it is required to specify either location_name or location_code
you can receive the list of available locations with their location_name by making a separate request to
https://api.dataforseo.com/v3/dataforseo_labs/locations_and_languages;
Note: this endpoint currently supports the US location only;
example:
United States

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[location_name](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#location_name)

#### Defined in

[main.ts:103403](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103403)

___


### offset

• `Optional` **offset**: `number`

offset in the items array of returned keywords
optional field
default value: 0
if you specify the 10 value, the first ten keywords in the results array will be omitted and the data will be provided for the successive keywords

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[offset](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#offset)

#### Defined in

[main.ts:103459](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103459)

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
["keyword_data.keyword_info.competition,desc"]
default rule:
["keyword_data.keyword_info.search_volume,desc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["keyword_data.keyword_info.search_volume,desc","keyword_data.keyword_info.cpc,desc"]

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[order_by](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#order_by)

#### Defined in

[main.ts:103492](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103492)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[tag](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#tag)

#### Defined in

[main.ts:103498](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103498)

___


### target1

• `Optional` **target1**: `string`

domain
required field
the domain name of the first target website
the domain should be specified without https:// and www.

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[target1](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#target1)

#### Defined in

[main.ts:103389](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103389)

___


### target2

• `Optional` **target2**: `string`

domain
required field
the domain name of the second target website
the domain should be specified without https:// and www.

#### Implementation of

[IDataforseoLabsBingDomainIntersectionLiveRequestInfo](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md).[target2](../interfaces/IDataforseoLabsBingDomainIntersectionLiveRequestInfo.md#target2)

#### Defined in

[main.ts:103394](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103394)

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

[main.ts:103511](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103511)

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

[main.ts:103553](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103553)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsBingDomainIntersectionLiveRequestInfo`](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsBingDomainIntersectionLiveRequestInfo`](DataforseoLabsBingDomainIntersectionLiveRequestInfo.md)

#### Defined in

[main.ts:103546](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L103546)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")