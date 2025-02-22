[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYahooOrganicTasksReadyTaskInfo

# Class: SerpYahooOrganicTasksReadyTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpYahooOrganicTasksReadyTaskInfo`**

## Implements

- [`ISerpYahooOrganicTasksReadyTaskInfo`](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYahooOrganicTasksReadyTaskInfo.md#constructor)

### Properties

- [cost](SerpYahooOrganicTasksReadyTaskInfo.md#cost)
- [data](SerpYahooOrganicTasksReadyTaskInfo.md#data)
- [id](SerpYahooOrganicTasksReadyTaskInfo.md#id)
- [path](SerpYahooOrganicTasksReadyTaskInfo.md#path)
- [result](SerpYahooOrganicTasksReadyTaskInfo.md#result)
- [result\_count](SerpYahooOrganicTasksReadyTaskInfo.md#result_count)
- [status\_code](SerpYahooOrganicTasksReadyTaskInfo.md#status_code)
- [status\_message](SerpYahooOrganicTasksReadyTaskInfo.md#status_message)
- [time](SerpYahooOrganicTasksReadyTaskInfo.md#time)

### Methods

- [init](SerpYahooOrganicTasksReadyTaskInfo.md#init)
- [toJSON](SerpYahooOrganicTasksReadyTaskInfo.md#tojson)
- [fromJS](SerpYahooOrganicTasksReadyTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYahooOrganicTasksReadyTaskInfo**(`data?`): [`SerpYahooOrganicTasksReadyTaskInfo`](SerpYahooOrganicTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYahooOrganicTasksReadyTaskInfo`](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md) |

#### Returns

[`SerpYahooOrganicTasksReadyTaskInfo`](SerpYahooOrganicTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:63406](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63406)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[cost](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#cost)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[cost](BaseResponseTaskInfo.md#cost)

#### Defined in

[main.ts:22602](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22602)

___


### data

• `Optional` **data**: `Object`

contains the same parameters that you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[data](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#data)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[data](BaseResponseTaskInfo.md#data)

#### Defined in

[main.ts:22608](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22608)

___


### id

• `Optional` **id**: `string`

task identifier
unique task identifier in our system in the UUID format

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[id](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[path](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpYahooOrganicTasksReadyResultInfo`](SerpYahooOrganicTasksReadyResultInfo.md)[]

array of results

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[result](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#result)

#### Defined in

[main.ts:63402](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63402)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[result_count](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#result_count)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[result_count](BaseResponseTaskInfo.md#result_count)

#### Defined in

[main.ts:22604](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22604)

___


### status\_code

• `Optional` **status\_code**: `number`

status code of the task
generated by DataForSEO, can be within the following range: 10000-60000
you can find the full list of the response codes here

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[status_code](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#status_code)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_code](BaseResponseTaskInfo.md#status_code)

#### Defined in

[main.ts:22595](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22595)

___


### status\_message

• `Optional` **status\_message**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[status_message](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpYahooOrganicTasksReadyTaskInfo](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md).[time](../interfaces/ISerpYahooOrganicTasksReadyTaskInfo.md#time)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[time](BaseResponseTaskInfo.md#time)

#### Defined in

[main.ts:22600](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22600)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[init](BaseResponseTaskInfo.md#init)

#### Defined in

[main.ts:63410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63410)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[toJSON](BaseResponseTaskInfo.md#tojson)

#### Defined in

[main.ts:63432](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63432)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYahooOrganicTasksReadyTaskInfo`](SerpYahooOrganicTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYahooOrganicTasksReadyTaskInfo`](SerpYahooOrganicTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:63425](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63425)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")