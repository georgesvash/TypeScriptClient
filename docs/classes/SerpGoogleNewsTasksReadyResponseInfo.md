[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleNewsTasksReadyResponseInfo

# Class: SerpGoogleNewsTasksReadyResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleNewsTasksReadyResponseInfo`**

## Implements

- [`ISerpGoogleNewsTasksReadyResponseInfo`](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleNewsTasksReadyResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleNewsTasksReadyResponseInfo.md#cost)
- [status\_code](SerpGoogleNewsTasksReadyResponseInfo.md#status_code)
- [status\_message](SerpGoogleNewsTasksReadyResponseInfo.md#status_message)
- [tasks](SerpGoogleNewsTasksReadyResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleNewsTasksReadyResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleNewsTasksReadyResponseInfo.md#tasks_error)
- [time](SerpGoogleNewsTasksReadyResponseInfo.md#time)
- [version](SerpGoogleNewsTasksReadyResponseInfo.md#version)

### Methods

- [init](SerpGoogleNewsTasksReadyResponseInfo.md#init)
- [toJSON](SerpGoogleNewsTasksReadyResponseInfo.md#tojson)
- [fromJS](SerpGoogleNewsTasksReadyResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleNewsTasksReadyResponseInfo**(`data?`): [`SerpGoogleNewsTasksReadyResponseInfo`](SerpGoogleNewsTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleNewsTasksReadyResponseInfo`](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md) |

#### Returns

[`SerpGoogleNewsTasksReadyResponseInfo`](SerpGoogleNewsTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:42227](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42227)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[cost](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#cost)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[cost](BaseResponseInfo.md#cost)

#### Defined in

[main.ts:22510](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22510)

___


### status\_code

• `Optional` **status\_code**: `number`

general status code
you can find the full list of the response codes here

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[status_code](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#status_code)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_code](BaseResponseInfo.md#status_code)

#### Defined in

[main.ts:22503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22503)

___


### status\_message

• `Optional` **status\_message**: `string`

general informational message
you can find the full list of general informational messages here

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[status_message](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleNewsTasksReadyTaskInfo`](SerpGoogleNewsTasksReadyTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[tasks](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#tasks)

#### Defined in

[main.ts:42223](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42223)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[time](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleNewsTasksReadyResponseInfo](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md).[version](../interfaces/ISerpGoogleNewsTasksReadyResponseInfo.md#version)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[version](BaseResponseInfo.md#version)

#### Defined in

[main.ts:22500](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22500)

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

[BaseResponseInfo](BaseResponseInfo.md).[init](BaseResponseInfo.md#init)

#### Defined in

[main.ts:42231](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42231)

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

[BaseResponseInfo](BaseResponseInfo.md).[toJSON](BaseResponseInfo.md#tojson)

#### Defined in

[main.ts:42253](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42253)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleNewsTasksReadyResponseInfo`](SerpGoogleNewsTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleNewsTasksReadyResponseInfo`](SerpGoogleNewsTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:42246](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42246)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")