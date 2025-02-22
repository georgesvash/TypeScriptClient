[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpSeznamOrganicTasksReadyResponseInfo

# Class: SerpSeznamOrganicTasksReadyResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpSeznamOrganicTasksReadyResponseInfo`**

## Implements

- [`ISerpSeznamOrganicTasksReadyResponseInfo`](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpSeznamOrganicTasksReadyResponseInfo.md#constructor)

### Properties

- [cost](SerpSeznamOrganicTasksReadyResponseInfo.md#cost)
- [status\_code](SerpSeznamOrganicTasksReadyResponseInfo.md#status_code)
- [status\_message](SerpSeznamOrganicTasksReadyResponseInfo.md#status_message)
- [tasks](SerpSeznamOrganicTasksReadyResponseInfo.md#tasks)
- [tasks\_count](SerpSeznamOrganicTasksReadyResponseInfo.md#tasks_count)
- [tasks\_error](SerpSeznamOrganicTasksReadyResponseInfo.md#tasks_error)
- [time](SerpSeznamOrganicTasksReadyResponseInfo.md#time)
- [version](SerpSeznamOrganicTasksReadyResponseInfo.md#version)

### Methods

- [init](SerpSeznamOrganicTasksReadyResponseInfo.md#init)
- [toJSON](SerpSeznamOrganicTasksReadyResponseInfo.md#tojson)
- [fromJS](SerpSeznamOrganicTasksReadyResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpSeznamOrganicTasksReadyResponseInfo**(`data?`): [`SerpSeznamOrganicTasksReadyResponseInfo`](SerpSeznamOrganicTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpSeznamOrganicTasksReadyResponseInfo`](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md) |

#### Returns

[`SerpSeznamOrganicTasksReadyResponseInfo`](SerpSeznamOrganicTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:69855](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69855)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[cost](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#cost)

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

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[status_code](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#status_code)

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

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[status_message](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpSeznamOrganicTasksReadyTaskInfo`](SerpSeznamOrganicTasksReadyTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[tasks](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#tasks)

#### Defined in

[main.ts:69851](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69851)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[tasks_count](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[tasks_error](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[time](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpSeznamOrganicTasksReadyResponseInfo](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md).[version](../interfaces/ISerpSeznamOrganicTasksReadyResponseInfo.md#version)

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

[main.ts:69859](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69859)

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

[main.ts:69881](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69881)

___


### fromJS

▸ **fromJS**(`data`): [`SerpSeznamOrganicTasksReadyResponseInfo`](SerpSeznamOrganicTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpSeznamOrganicTasksReadyResponseInfo`](SerpSeznamOrganicTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:69874](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69874)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")