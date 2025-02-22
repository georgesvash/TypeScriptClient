[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppListingsSearchLiveRequestInfo

# Class: AppDataGoogleAppListingsSearchLiveRequestInfo

## Implements

- [`IAppDataGoogleAppListingsSearchLiveRequestInfo`](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppListingsSearchLiveRequestInfo.md#constructor)

### Properties

- [categories](AppDataGoogleAppListingsSearchLiveRequestInfo.md#categories)
- [description](AppDataGoogleAppListingsSearchLiveRequestInfo.md#description)
- [filters](AppDataGoogleAppListingsSearchLiveRequestInfo.md#filters)
- [limit](AppDataGoogleAppListingsSearchLiveRequestInfo.md#limit)
- [offset](AppDataGoogleAppListingsSearchLiveRequestInfo.md#offset)
- [offset\_token](AppDataGoogleAppListingsSearchLiveRequestInfo.md#offset_token)
- [order\_by](AppDataGoogleAppListingsSearchLiveRequestInfo.md#order_by)
- [tag](AppDataGoogleAppListingsSearchLiveRequestInfo.md#tag)
- [title](AppDataGoogleAppListingsSearchLiveRequestInfo.md#title)

### Methods

- [init](AppDataGoogleAppListingsSearchLiveRequestInfo.md#init)
- [toJSON](AppDataGoogleAppListingsSearchLiveRequestInfo.md#tojson)
- [fromJS](AppDataGoogleAppListingsSearchLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppListingsSearchLiveRequestInfo**(`data?`): [`AppDataGoogleAppListingsSearchLiveRequestInfo`](AppDataGoogleAppListingsSearchLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppListingsSearchLiveRequestInfo`](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md) |

#### Returns

[`AppDataGoogleAppListingsSearchLiveRequestInfo`](AppDataGoogleAppListingsSearchLiveRequestInfo.md)

#### Defined in

[main.ts:182127](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182127)

## Properties

### categories

• `Optional` **categories**: `string`[]

app categories
optional field
the categories you specify are used to search for app listings;
you can get the full list of available app listing categories by this link
you can specify up to 10 categories

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[categories](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#categories)

#### Defined in

[main.ts:182064](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182064)

___


### description

• `Optional` **description**: `string`

keyword in the app’s description
optional field
keywords that occur in the description of the app;
can contain up to 200 symbols

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[description](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#description)

#### Defined in

[main.ts:182069](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182069)

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
["item.rating.value",">",3]
you can receive the list of available filters by making a separate request to https://api.dataforseo.com/v3/app_data/google/app_listings/available_filters

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[filters](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#filters)

#### Defined in

[main.ts:182085](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182085)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned apps
optional field
default value: 100
maximum value: 1000

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[limit](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#limit)

#### Defined in

[main.ts:182104](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182104)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned apps
optional field
default value: 0
if you specify the 10 value, the first ten entities in the results array will be omitted and the data will be provided for the successive entities

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[offset](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#offset)

#### Defined in

[main.ts:182109](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182109)

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

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[offset_token](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#offset_token)

#### Defined in

[main.ts:182117](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182117)

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
["item.installs_count,asc"]
note that you can set no more than three sorting rules in a single request
you should use a comma to separate several sorting rules
example:
["item.rating.value,desc","item.installs_count,asc"]

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[order_by](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#order_by)

#### Defined in

[main.ts:182099](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182099)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[tag](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#tag)

#### Defined in

[main.ts:182123](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182123)

___


### title

• `Optional` **title**: `string`

keyword in the app’s title
optional field
keywords that occur in the title of the app;
can contain up to 200 symbols

#### Implementation of

[IAppDataGoogleAppListingsSearchLiveRequestInfo](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md).[title](../interfaces/IAppDataGoogleAppListingsSearchLiveRequestInfo.md#title)

#### Defined in

[main.ts:182074](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182074)

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

[main.ts:182136](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182136)

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

[main.ts:182173](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182173)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppListingsSearchLiveRequestInfo`](AppDataGoogleAppListingsSearchLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppListingsSearchLiveRequestInfo`](AppDataGoogleAppListingsSearchLiveRequestInfo.md)

#### Defined in

[main.ts:182166](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L182166)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")