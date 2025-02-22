[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleAppInfoTaskGetAdvancedResponseInfo

# Class: AppDataAppleAppInfoTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataAppleAppInfoTaskGetAdvancedResponseInfo`**

## Implements

- [`IAppDataAppleAppInfoTaskGetAdvancedResponseInfo`](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#time)
- [version](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#init)
- [toJSON](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleAppInfoTaskGetAdvancedResponseInfo**(`data?`): [`AppDataAppleAppInfoTaskGetAdvancedResponseInfo`](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleAppInfoTaskGetAdvancedResponseInfo`](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md) |

#### Returns

[`AppDataAppleAppInfoTaskGetAdvancedResponseInfo`](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:184827](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184827)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[cost](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#cost)

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

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#status_code)

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

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataAppleAppInfoTaskGetAdvancedTaskInfo`](AppDataAppleAppInfoTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:184823](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184823)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[time](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataAppleAppInfoTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md).[version](../interfaces/IAppDataAppleAppInfoTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:184831](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184831)

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

[main.ts:184853](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184853)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleAppInfoTaskGetAdvancedResponseInfo`](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleAppInfoTaskGetAdvancedResponseInfo`](AppDataAppleAppInfoTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:184846](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184846)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")