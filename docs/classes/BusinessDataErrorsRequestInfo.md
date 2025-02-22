[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataErrorsRequestInfo

# Class: BusinessDataErrorsRequestInfo

## Implements

- [`IBusinessDataErrorsRequestInfo`](../interfaces/IBusinessDataErrorsRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataErrorsRequestInfo.md#constructor)

### Properties

- [datetime\_from](BusinessDataErrorsRequestInfo.md#datetime_from)
- [datetime\_to](BusinessDataErrorsRequestInfo.md#datetime_to)
- [filtered\_function](BusinessDataErrorsRequestInfo.md#filtered_function)
- [limit](BusinessDataErrorsRequestInfo.md#limit)
- [offset](BusinessDataErrorsRequestInfo.md#offset)

### Methods

- [init](BusinessDataErrorsRequestInfo.md#init)
- [toJSON](BusinessDataErrorsRequestInfo.md#tojson)
- [fromJS](BusinessDataErrorsRequestInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataErrorsRequestInfo**(`data?`): [`BusinessDataErrorsRequestInfo`](BusinessDataErrorsRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataErrorsRequestInfo`](../interfaces/IBusinessDataErrorsRequestInfo.md) |

#### Returns

[`BusinessDataErrorsRequestInfo`](BusinessDataErrorsRequestInfo.md)

#### Defined in

[main.ts:187524](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187524)

## Properties

### datetime\_from

• `Optional` **datetime\_from**: `string`

start time for filtering results
optional field
allows filtering results by the datetime parameter within the range of the last 24 hours;
must be specified in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2021-11-15 12:57:46 +00:00

#### Implementation of

[IBusinessDataErrorsRequestInfo](../interfaces/IBusinessDataErrorsRequestInfo.md).[datetime_from](../interfaces/IBusinessDataErrorsRequestInfo.md#datetime_from)

#### Defined in

[main.ts:187513](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187513)

___


### datetime\_to

• `Optional` **datetime\_to**: `string`

finish time for filtering results
optional field
allows filtering results by the datetime parameter within the range of the last 24 hours;
must be specified in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2021-11-15 13:57:46 +00:00

#### Implementation of

[IBusinessDataErrorsRequestInfo](../interfaces/IBusinessDataErrorsRequestInfo.md).[datetime_to](../interfaces/IBusinessDataErrorsRequestInfo.md#datetime_to)

#### Defined in

[main.ts:187520](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187520)

___


### filtered\_function

• `Optional` **filtered\_function**: `string`

return tasks with a certain function
use this field to obtain a list of tasks that returned an error filtered by a certain function
you can filter the results by the values you receive in the function fields of the API response
i.e., once you receive unfiltered results, you can call this API again to filter them by function
example: hotel_searches/task_post, postback_url, pingback_url

#### Implementation of

[IBusinessDataErrorsRequestInfo](../interfaces/IBusinessDataErrorsRequestInfo.md).[filtered_function](../interfaces/IBusinessDataErrorsRequestInfo.md#filtered_function)

#### Defined in

[main.ts:187506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187506)

___


### limit

• `Optional` **limit**: `number`

the maximum number of returned tasks that responded with an error
optional field
default value: 1000
maximum value: 1000

#### Implementation of

[IBusinessDataErrorsRequestInfo](../interfaces/IBusinessDataErrorsRequestInfo.md).[limit](../interfaces/IBusinessDataErrorsRequestInfo.md#limit)

#### Defined in

[main.ts:187495](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187495)

___


### offset

• `Optional` **offset**: `number`

offset in the results array of returned tasks
optional field
default value: 0
if you specify the 10 value, the first ten tasks in the results array will be omitted and the data will be provided for the successive tasks

#### Implementation of

[IBusinessDataErrorsRequestInfo](../interfaces/IBusinessDataErrorsRequestInfo.md).[offset](../interfaces/IBusinessDataErrorsRequestInfo.md#offset)

#### Defined in

[main.ts:187500](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187500)

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

[main.ts:187533](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187533)

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

[main.ts:187554](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187554)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataErrorsRequestInfo`](BusinessDataErrorsRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataErrorsRequestInfo`](BusinessDataErrorsRequestInfo.md)

#### Defined in

[main.ts:187547](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187547)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")