[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksBacklinksLiveRequestInfo

# Class: BacklinksBacklinksLiveRequestInfo

## Implements

- [`IBacklinksBacklinksLiveRequestInfo`](../interfaces/IBacklinksBacklinksLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksBacklinksLiveRequestInfo.md#constructor)

### Properties

- [backlinks\_status\_type](BacklinksBacklinksLiveRequestInfo.md#backlinks_status_type)
- [custom\_mode](BacklinksBacklinksLiveRequestInfo.md#custom_mode)
- [field](BacklinksBacklinksLiveRequestInfo.md#field)
- [filters](BacklinksBacklinksLiveRequestInfo.md#filters)
- [include\_indirect\_links](BacklinksBacklinksLiveRequestInfo.md#include_indirect_links)
- [include\_subdomains](BacklinksBacklinksLiveRequestInfo.md#include_subdomains)
- [limit](BacklinksBacklinksLiveRequestInfo.md#limit)
- [mode](BacklinksBacklinksLiveRequestInfo.md#mode)
- [offset](BacklinksBacklinksLiveRequestInfo.md#offset)
- [order\_by](BacklinksBacklinksLiveRequestInfo.md#order_by)
- [search\_after\_token](BacklinksBacklinksLiveRequestInfo.md#search_after_token)
- [tag](BacklinksBacklinksLiveRequestInfo.md#tag)
- [target](BacklinksBacklinksLiveRequestInfo.md#target)
- [value](BacklinksBacklinksLiveRequestInfo.md#value)

### Methods

- [init](BacklinksBacklinksLiveRequestInfo.md#init)
- [toJSON](BacklinksBacklinksLiveRequestInfo.md#tojson)
- [fromJS](BacklinksBacklinksLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksBacklinksLiveRequestInfo**(`data?`): [`BacklinksBacklinksLiveRequestInfo`](BacklinksBacklinksLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksBacklinksLiveRequestInfo`](../interfaces/IBacklinksBacklinksLiveRequestInfo.md) |

#### Returns

[`BacklinksBacklinksLiveRequestInfo`](BacklinksBacklinksLiveRequestInfo.md)

#### Defined in

[main.ts:130674](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130674)

## Properties

### backlinks\_status\_type

• `Optional` **backlinks\_status\_type**: `string`

set what backlinks to return and count
optional field
you can use this field to choose what backlinks will be returned and used for aggregated metrics for your target;
possible values:
all – all backlinks will be returned and counted;
live – backlinks found during the last check will be returned and counted;
lost – lost backlinks will be returned and counted;
default value: live

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[backlinks_status_type](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#backlinks_status_type)

#### Defined in

[main.ts:130653](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130653)

___


### custom\_mode

• `Optional` **custom\_mode**: `Object`

detailed results grouping type
optional field
use this object to get a specific number of backlinks per field
if you use custom_mode, then mode will be ignored
example:
"custom_mode": {"field": "domain", "value": 100}

#### Index signature

▪ [key: `string`]: `any`

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[custom_mode](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#custom_mode)

#### Defined in

[main.ts:130577](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130577)

___


### field

• `Optional` **field**: `string`

response field
required field if you choose to specify custom_mode
possible values:
anchor
domain_from
domain_from_country
tld_from
page_from_encoding
page_from_language
item_type
page_from_status_code
semantic_location

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[field](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#field)

#### Defined in

[main.ts:130590](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130590)

___


### filters

• `Optional` **filters**: `any`[]

array of results filtering parameters
optional field
you can add several filters at once (8 filters maximum)
you should set a logical operator and, or between the conditions
the following operators are supported:
regex, =, <>, in, not_in, like, not_like, ilike, not_ilike
you can use the % operator with like and not_like to match any string of zero or more characters
example:
["rank",">","80"]
[["page_from_rank",">","55"],
"and",
["dofollow","=",true]]
[["first_seen",">","2017-10-23 11:31:45 +00:00"],
"and",
[["anchor","like","%seo%"],"or",["text_pre","like","%seo%"]]]
The full list of possible filters is available here.

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[filters](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#filters)

#### Defined in

[main.ts:130611](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130611)

___


### include\_indirect\_links

• `Optional` **include\_indirect\_links**: `boolean`

indicates if indirect links to the target will be included in the results
optional field
if set to true, the results will include data on indirect links pointing to a page that either redirects to the target, or points to a canonical page
if set to false, indirect links will be ignored
default value: true

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[include_indirect_links](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#include_indirect_links)

#### Defined in

[main.ts:130664](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130664)

___


### include\_subdomains

• `Optional` **include\_subdomains**: `boolean`

indicates if the subdomains of the target will be included in the search
optional field
if set to false, the subdomains will be ignored
default value: true

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[include_subdomains](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#include_subdomains)

#### Defined in

[main.ts:130658](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130658)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned backlinks
optional field
default value: 100
maximum value: 1000

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[limit](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#limit)

#### Defined in

[main.ts:130644](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130644)

___


### mode

• `Optional` **mode**: `string`

results grouping type
optional field
possible grouping types:
as_is – returns all backlinks
one_per_domain – returns one backlink per domain
one_per_anchor – returns one backlink per anchor
default value: as_is

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[mode](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#mode)

#### Defined in

[main.ts:130570](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130570)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of the returned backlinks
optional field
default value: 0
if you specify the 10 value, the first ten backlinks in the results array will be omitted and the data will be provided for the successive backlinks;
Note: the maximum value is 20,000, use the search_after_token if you would like to offset more results

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[offset](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#offset)

#### Defined in

[main.ts:130631](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130631)

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
["rank,desc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["domain_from_rank,desc","page_from_rank,asc"]

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[order_by](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#order_by)

#### Defined in

[main.ts:130625](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130625)

___


### search\_after\_token

• `Optional` **search\_after\_token**: `string`

token for subsequent requests
optional field
provided in the identical filed of the response to each request;
use this parameter to avoid timeouts while trying to obtain over 100,000 results in a single request;
by specifying the unique search_after_token value from the response array, you will get the subsequent results of the initial task;
search_after_token values are unique for each subsequent task
Note: if the search_after_token is specified in the request, all other parameters should be identical to the previous request

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[search_after_token](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#search_after_token)

#### Defined in

[main.ts:130639](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130639)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[tag](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#tag)

#### Defined in

[main.ts:130670](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130670)

___


### target

• `Optional` **target**: `string`

domain, subdomain or webpage to get backlinks for
required field
a domain or a subdomain should be specified without https:// and www.
a page should be specified with absolute URL (including http:// or https://)

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[target](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#target)

#### Defined in

[main.ts:130562](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130562)

___


### value

• `Optional` **value**: `number`

number of backlinks to return per field
required field if you choose to specify custom_mode
can be set from 1 to 1000

#### Implementation of

[IBacklinksBacklinksLiveRequestInfo](../interfaces/IBacklinksBacklinksLiveRequestInfo.md).[value](../interfaces/IBacklinksBacklinksLiveRequestInfo.md#value)

#### Defined in

[main.ts:130594](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130594)

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

[main.ts:130683](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130683)

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

[main.ts:130727](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130727)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksBacklinksLiveRequestInfo`](BacklinksBacklinksLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksBacklinksLiveRequestInfo`](BacklinksBacklinksLiveRequestInfo.md)

#### Defined in

[main.ts:130720](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L130720)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")