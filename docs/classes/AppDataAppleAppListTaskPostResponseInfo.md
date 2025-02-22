[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleAppListTaskPostResponseInfo

# Class: AppDataAppleAppListTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataAppleAppListTaskPostResponseInfo`**

## Implements

- [`IAppDataAppleAppListTaskPostResponseInfo`](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleAppListTaskPostResponseInfo.md#constructor)

### Properties

- [cost](AppDataAppleAppListTaskPostResponseInfo.md#cost)
- [status\_code](AppDataAppleAppListTaskPostResponseInfo.md#status_code)
- [status\_message](AppDataAppleAppListTaskPostResponseInfo.md#status_message)
- [tasks](AppDataAppleAppListTaskPostResponseInfo.md#tasks)
- [tasks\_count](AppDataAppleAppListTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](AppDataAppleAppListTaskPostResponseInfo.md#tasks_error)
- [time](AppDataAppleAppListTaskPostResponseInfo.md#time)
- [version](AppDataAppleAppListTaskPostResponseInfo.md#version)

### Methods

- [init](AppDataAppleAppListTaskPostResponseInfo.md#init)
- [toJSON](AppDataAppleAppListTaskPostResponseInfo.md#tojson)
- [fromJS](AppDataAppleAppListTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleAppListTaskPostResponseInfo**(`data?`): [`AppDataAppleAppListTaskPostResponseInfo`](AppDataAppleAppListTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleAppListTaskPostResponseInfo`](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md) |

#### Returns

[`AppDataAppleAppListTaskPostResponseInfo`](AppDataAppleAppListTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:185181](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185181)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[cost](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#cost)

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

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[status_code](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#status_code)

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

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[status_message](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataAppleAppListTaskPostTaskInfo`](AppDataAppleAppListTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[tasks](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:185177](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185177)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[tasks_count](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[tasks_error](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[time](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataAppleAppListTaskPostResponseInfo](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md).[version](../interfaces/IAppDataAppleAppListTaskPostResponseInfo.md#version)

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

[main.ts:185185](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185185)

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

[main.ts:185207](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185207)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleAppListTaskPostResponseInfo`](AppDataAppleAppListTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleAppListTaskPostResponseInfo`](AppDataAppleAppListTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:185200](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185200)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")