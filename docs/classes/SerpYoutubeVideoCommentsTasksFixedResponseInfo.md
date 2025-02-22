[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYoutubeVideoCommentsTasksFixedResponseInfo

# Class: SerpYoutubeVideoCommentsTasksFixedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpYoutubeVideoCommentsTasksFixedResponseInfo`**

## Implements

- [`ISerpYoutubeVideoCommentsTasksFixedResponseInfo`](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#constructor)

### Properties

- [cost](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#cost)
- [status\_code](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#status_code)
- [status\_message](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#status_message)
- [tasks](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tasks)
- [tasks\_count](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tasks_count)
- [tasks\_error](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tasks_error)
- [time](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#time)
- [version](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#version)

### Methods

- [init](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#init)
- [toJSON](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tojson)
- [fromJS](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYoutubeVideoCommentsTasksFixedResponseInfo**(`data?`): [`SerpYoutubeVideoCommentsTasksFixedResponseInfo`](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYoutubeVideoCommentsTasksFixedResponseInfo`](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md) |

#### Returns

[`SerpYoutubeVideoCommentsTasksFixedResponseInfo`](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:61775](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L61775)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[cost](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#cost)

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

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[status_code](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#status_code)

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

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[status_message](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpYoutubeVideoCommentsTasksFixedTaskInfo`](SerpYoutubeVideoCommentsTasksFixedTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[tasks](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tasks)

#### Defined in

[main.ts:61771](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L61771)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[tasks_count](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[tasks_error](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[time](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpYoutubeVideoCommentsTasksFixedResponseInfo](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md).[version](../interfaces/ISerpYoutubeVideoCommentsTasksFixedResponseInfo.md#version)

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

[main.ts:61779](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L61779)

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

[main.ts:61801](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L61801)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYoutubeVideoCommentsTasksFixedResponseInfo`](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYoutubeVideoCommentsTasksFixedResponseInfo`](SerpYoutubeVideoCommentsTasksFixedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:61794](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L61794)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")