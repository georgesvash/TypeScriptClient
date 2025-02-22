[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppendixErrorsResponseInfo

# Class: AppendixErrorsResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppendixErrorsResponseInfo`**

## Implements

- [`IAppendixErrorsResponseInfo`](../interfaces/IAppendixErrorsResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppendixErrorsResponseInfo.md#constructor)

### Properties

- [cost](AppendixErrorsResponseInfo.md#cost)
- [status\_code](AppendixErrorsResponseInfo.md#status_code)
- [status\_message](AppendixErrorsResponseInfo.md#status_message)
- [tasks](AppendixErrorsResponseInfo.md#tasks)
- [tasks\_count](AppendixErrorsResponseInfo.md#tasks_count)
- [tasks\_error](AppendixErrorsResponseInfo.md#tasks_error)
- [time](AppendixErrorsResponseInfo.md#time)
- [version](AppendixErrorsResponseInfo.md#version)

### Methods

- [init](AppendixErrorsResponseInfo.md#init)
- [toJSON](AppendixErrorsResponseInfo.md#tojson)
- [fromJS](AppendixErrorsResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppendixErrorsResponseInfo**(`data?`): [`AppendixErrorsResponseInfo`](AppendixErrorsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppendixErrorsResponseInfo`](../interfaces/IAppendixErrorsResponseInfo.md) |

#### Returns

[`AppendixErrorsResponseInfo`](AppendixErrorsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:212465](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212465)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[cost](../interfaces/IAppendixErrorsResponseInfo.md#cost)

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

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[status_code](../interfaces/IAppendixErrorsResponseInfo.md#status_code)

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

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[status_message](../interfaces/IAppendixErrorsResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppendixErrorsTaskInfo`](AppendixErrorsTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[tasks](../interfaces/IAppendixErrorsResponseInfo.md#tasks)

#### Defined in

[main.ts:212461](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212461)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[tasks_count](../interfaces/IAppendixErrorsResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[tasks_error](../interfaces/IAppendixErrorsResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[time](../interfaces/IAppendixErrorsResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppendixErrorsResponseInfo](../interfaces/IAppendixErrorsResponseInfo.md).[version](../interfaces/IAppendixErrorsResponseInfo.md#version)

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

[main.ts:212469](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212469)

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

[main.ts:212491](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212491)

___


### fromJS

▸ **fromJS**(`data`): [`AppendixErrorsResponseInfo`](AppendixErrorsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppendixErrorsResponseInfo`](AppendixErrorsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:212484](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212484)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")