[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYoutubeVideoInfoTasksReadyResponseInfo

# Class: SerpYoutubeVideoInfoTasksReadyResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpYoutubeVideoInfoTasksReadyResponseInfo`**

## Implements

- [`ISerpYoutubeVideoInfoTasksReadyResponseInfo`](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#constructor)

### Properties

- [cost](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#cost)
- [status\_code](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#status_code)
- [status\_message](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#status_message)
- [tasks](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#tasks)
- [tasks\_count](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#tasks_count)
- [tasks\_error](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#tasks_error)
- [time](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#time)
- [version](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#version)

### Methods

- [init](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#init)
- [toJSON](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#tojson)
- [fromJS](SerpYoutubeVideoInfoTasksReadyResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYoutubeVideoInfoTasksReadyResponseInfo**(`data?`): [`SerpYoutubeVideoInfoTasksReadyResponseInfo`](SerpYoutubeVideoInfoTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYoutubeVideoInfoTasksReadyResponseInfo`](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md) |

#### Returns

[`SerpYoutubeVideoInfoTasksReadyResponseInfo`](SerpYoutubeVideoInfoTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:58233](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58233)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[cost](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#cost)

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

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[status_code](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#status_code)

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

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[status_message](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpYoutubeVideoInfoTasksReadyTaskInfo`](SerpYoutubeVideoInfoTasksReadyTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[tasks](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#tasks)

#### Defined in

[main.ts:58229](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58229)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[tasks_count](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[tasks_error](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[time](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpYoutubeVideoInfoTasksReadyResponseInfo](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md).[version](../interfaces/ISerpYoutubeVideoInfoTasksReadyResponseInfo.md#version)

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

[main.ts:58237](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58237)

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

[main.ts:58259](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58259)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYoutubeVideoInfoTasksReadyResponseInfo`](SerpYoutubeVideoInfoTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYoutubeVideoInfoTasksReadyResponseInfo`](SerpYoutubeVideoInfoTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:58252](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L58252)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")