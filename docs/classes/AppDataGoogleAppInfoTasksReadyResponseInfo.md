[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppInfoTasksReadyResponseInfo

# Class: AppDataGoogleAppInfoTasksReadyResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataGoogleAppInfoTasksReadyResponseInfo`**

## Implements

- [`IAppDataGoogleAppInfoTasksReadyResponseInfo`](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppInfoTasksReadyResponseInfo.md#constructor)

### Properties

- [cost](AppDataGoogleAppInfoTasksReadyResponseInfo.md#cost)
- [status\_code](AppDataGoogleAppInfoTasksReadyResponseInfo.md#status_code)
- [status\_message](AppDataGoogleAppInfoTasksReadyResponseInfo.md#status_message)
- [tasks](AppDataGoogleAppInfoTasksReadyResponseInfo.md#tasks)
- [tasks\_count](AppDataGoogleAppInfoTasksReadyResponseInfo.md#tasks_count)
- [tasks\_error](AppDataGoogleAppInfoTasksReadyResponseInfo.md#tasks_error)
- [time](AppDataGoogleAppInfoTasksReadyResponseInfo.md#time)
- [version](AppDataGoogleAppInfoTasksReadyResponseInfo.md#version)

### Methods

- [init](AppDataGoogleAppInfoTasksReadyResponseInfo.md#init)
- [toJSON](AppDataGoogleAppInfoTasksReadyResponseInfo.md#tojson)
- [fromJS](AppDataGoogleAppInfoTasksReadyResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppInfoTasksReadyResponseInfo**(`data?`): [`AppDataGoogleAppInfoTasksReadyResponseInfo`](AppDataGoogleAppInfoTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppInfoTasksReadyResponseInfo`](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md) |

#### Returns

[`AppDataGoogleAppInfoTasksReadyResponseInfo`](AppDataGoogleAppInfoTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:179709](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L179709)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[cost](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#cost)

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

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[status_code](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#status_code)

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

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[status_message](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataGoogleAppInfoTasksReadyTaskInfo`](AppDataGoogleAppInfoTasksReadyTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[tasks](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#tasks)

#### Defined in

[main.ts:179705](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L179705)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[tasks_count](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[tasks_error](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[time](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataGoogleAppInfoTasksReadyResponseInfo](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md).[version](../interfaces/IAppDataGoogleAppInfoTasksReadyResponseInfo.md#version)

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

[main.ts:179713](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L179713)

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

[main.ts:179735](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L179735)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppInfoTasksReadyResponseInfo`](AppDataGoogleAppInfoTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppInfoTasksReadyResponseInfo`](AppDataGoogleAppInfoTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:179728](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L179728)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")