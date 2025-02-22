[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DomainAnalyticsWhoisOverviewLiveRequestInfo

# Class: DomainAnalyticsWhoisOverviewLiveRequestInfo

## Implements

- [`IDomainAnalyticsWhoisOverviewLiveRequestInfo`](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#constructor)

### Properties

- [filters](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#filters)
- [limit](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#limit)
- [offset](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#offset)
- [order\_by](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#order_by)
- [tag](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#tag)

### Methods

- [init](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#init)
- [toJSON](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#tojson)
- [fromJS](DomainAnalyticsWhoisOverviewLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new DomainAnalyticsWhoisOverviewLiveRequestInfo**(`data?`): [`DomainAnalyticsWhoisOverviewLiveRequestInfo`](DomainAnalyticsWhoisOverviewLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDomainAnalyticsWhoisOverviewLiveRequestInfo`](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md) |

#### Returns

[`DomainAnalyticsWhoisOverviewLiveRequestInfo`](DomainAnalyticsWhoisOverviewLiveRequestInfo.md)

#### Defined in

[main.ts:75625](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75625)

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
examples:
["expiration_datetime", "<", "2021-02-15 01:00:00 +00:00"]
[["expiration_datetime", "<", "2021-02-15 01:00:00 +00:00"],
"and",
["domain", "like", "%seo%"]]

for more information about filters, please refer to Filters Page or this help center guide

#### Implementation of

[IDomainAnalyticsWhoisOverviewLiveRequestInfo](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md).[filters](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md#filters)

#### Defined in

[main.ts:75599](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75599)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned domains
optional field
default value: 100
maximum value: 1000

#### Implementation of

[IDomainAnalyticsWhoisOverviewLiveRequestInfo](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md).[limit](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md#limit)

#### Defined in

[main.ts:75579](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75579)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned items
optional field
default value: 0
if you specify the 10 value, the first ten items in the results array will be omitted and the data will be provided for the successive items

#### Implementation of

[IDomainAnalyticsWhoisOverviewLiveRequestInfo](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md).[offset](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md#offset)

#### Defined in

[main.ts:75584](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75584)

___


### order\_by

• `Optional` **order\_by**: `string`[]

results sorting rules
optional field
you can use the same values as in the filters array to sort the results
possible sorting types:
asc - results will be sorted in the ascending order
desc - results will be sorted in the descending order
the comma is used as a separator
example:
["metrics.organic.pos_1,desc"]
default rule:
["metrics.organic.count,desc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["expiration_datetime,asc","metrics.organic.etv,desc","metrics.organic.pos_1,desc"]

#### Implementation of

[IDomainAnalyticsWhoisOverviewLiveRequestInfo](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md).[order_by](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md#order_by)

#### Defined in

[main.ts:75615](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75615)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IDomainAnalyticsWhoisOverviewLiveRequestInfo](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md).[tag](../interfaces/IDomainAnalyticsWhoisOverviewLiveRequestInfo.md#tag)

#### Defined in

[main.ts:75621](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75621)

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

[main.ts:75634](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75634)

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

[main.ts:75663](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75663)

___


### fromJS

▸ **fromJS**(`data`): [`DomainAnalyticsWhoisOverviewLiveRequestInfo`](DomainAnalyticsWhoisOverviewLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DomainAnalyticsWhoisOverviewLiveRequestInfo`](DomainAnalyticsWhoisOverviewLiveRequestInfo.md)

#### Defined in

[main.ts:75656](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75656)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")