[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleOrganicTasksFixedResponseInfo

# Class: SerpGoogleOrganicTasksFixedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleOrganicTasksFixedResponseInfo`**

## Implements

- [`ISerpGoogleOrganicTasksFixedResponseInfo`](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleOrganicTasksFixedResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleOrganicTasksFixedResponseInfo.md#cost)
- [status\_code](SerpGoogleOrganicTasksFixedResponseInfo.md#status_code)
- [status\_message](SerpGoogleOrganicTasksFixedResponseInfo.md#status_message)
- [tasks](SerpGoogleOrganicTasksFixedResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleOrganicTasksFixedResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleOrganicTasksFixedResponseInfo.md#tasks_error)
- [time](SerpGoogleOrganicTasksFixedResponseInfo.md#time)
- [version](SerpGoogleOrganicTasksFixedResponseInfo.md#version)

### Methods

- [init](SerpGoogleOrganicTasksFixedResponseInfo.md#init)
- [toJSON](SerpGoogleOrganicTasksFixedResponseInfo.md#tojson)
- [fromJS](SerpGoogleOrganicTasksFixedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleOrganicTasksFixedResponseInfo**(`data?`): [`SerpGoogleOrganicTasksFixedResponseInfo`](SerpGoogleOrganicTasksFixedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleOrganicTasksFixedResponseInfo`](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md) |

#### Returns

[`SerpGoogleOrganicTasksFixedResponseInfo`](SerpGoogleOrganicTasksFixedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:25099](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L25099)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[cost](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#cost)

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

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[status_code](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#status_code)

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

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[status_message](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleOrganicTasksFixedTaskInfo`](SerpGoogleOrganicTasksFixedTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[tasks](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#tasks)

#### Defined in

[main.ts:25095](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L25095)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[time](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleOrganicTasksFixedResponseInfo](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md).[version](../interfaces/ISerpGoogleOrganicTasksFixedResponseInfo.md#version)

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

[main.ts:25103](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L25103)

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

[main.ts:25125](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L25125)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleOrganicTasksFixedResponseInfo`](SerpGoogleOrganicTasksFixedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleOrganicTasksFixedResponseInfo`](SerpGoogleOrganicTasksFixedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:25118](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L25118)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")