[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleJobsTasksReadyTaskInfo

# Class: SerpGoogleJobsTasksReadyTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleJobsTasksReadyTaskInfo`**

## Implements

- [`ISerpGoogleJobsTasksReadyTaskInfo`](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleJobsTasksReadyTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleJobsTasksReadyTaskInfo.md#cost)
- [data](SerpGoogleJobsTasksReadyTaskInfo.md#data)
- [id](SerpGoogleJobsTasksReadyTaskInfo.md#id)
- [path](SerpGoogleJobsTasksReadyTaskInfo.md#path)
- [result](SerpGoogleJobsTasksReadyTaskInfo.md#result)
- [result\_count](SerpGoogleJobsTasksReadyTaskInfo.md#result_count)
- [status\_code](SerpGoogleJobsTasksReadyTaskInfo.md#status_code)
- [status\_message](SerpGoogleJobsTasksReadyTaskInfo.md#status_message)
- [time](SerpGoogleJobsTasksReadyTaskInfo.md#time)

### Methods

- [init](SerpGoogleJobsTasksReadyTaskInfo.md#init)
- [toJSON](SerpGoogleJobsTasksReadyTaskInfo.md#tojson)
- [fromJS](SerpGoogleJobsTasksReadyTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleJobsTasksReadyTaskInfo**(`data?`): [`SerpGoogleJobsTasksReadyTaskInfo`](SerpGoogleJobsTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleJobsTasksReadyTaskInfo`](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md) |

#### Returns

[`SerpGoogleJobsTasksReadyTaskInfo`](SerpGoogleJobsTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:48790](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L48790)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[cost](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#cost)

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

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[data](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#data)

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

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[id](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[path](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpGoogleJobsTasksReadyResultInfo`](SerpGoogleJobsTasksReadyResultInfo.md)[]

array of results

#### Implementation of

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[result](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#result)

#### Defined in

[main.ts:48786](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L48786)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[result_count](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#result_count)

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

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[status_code](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#status_code)

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

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[status_message](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleJobsTasksReadyTaskInfo](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md).[time](../interfaces/ISerpGoogleJobsTasksReadyTaskInfo.md#time)

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

[main.ts:48794](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L48794)

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

[main.ts:48816](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L48816)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleJobsTasksReadyTaskInfo`](SerpGoogleJobsTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleJobsTasksReadyTaskInfo`](SerpGoogleJobsTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:48809](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L48809)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")