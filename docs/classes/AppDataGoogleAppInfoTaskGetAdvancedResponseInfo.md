[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppInfoTaskGetAdvancedResponseInfo

# Class: AppDataGoogleAppInfoTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataGoogleAppInfoTaskGetAdvancedResponseInfo`**

## Implements

- [`IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo`](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#time)
- [version](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#init)
- [toJSON](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppInfoTaskGetAdvancedResponseInfo**(`data?`): [`AppDataGoogleAppInfoTaskGetAdvancedResponseInfo`](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo`](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md) |

#### Returns

[`AppDataGoogleAppInfoTaskGetAdvancedResponseInfo`](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:180319](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L180319)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[cost](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#cost)

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

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#status_code)

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

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataGoogleAppInfoTaskGetAdvancedTaskInfo`](AppDataGoogleAppInfoTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:180315](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L180315)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[time](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md).[version](../interfaces/IAppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:180323](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L180323)

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

[main.ts:180345](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L180345)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppInfoTaskGetAdvancedResponseInfo`](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppInfoTaskGetAdvancedResponseInfo`](AppDataGoogleAppInfoTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:180338](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L180338)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")