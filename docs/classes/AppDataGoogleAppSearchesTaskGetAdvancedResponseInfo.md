[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo

# Class: AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`**

## Implements

- [`IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#time)
- [version](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#init)
- [toJSON](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo**(`data?`): [`AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md) |

#### Returns

[`AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:177969](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177969)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[cost](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#cost)

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

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#status_code)

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

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataGoogleAppSearchesTaskGetAdvancedTaskInfo`](AppDataGoogleAppSearchesTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:177965](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177965)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[time](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md).[version](../interfaces/IAppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:177973](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177973)

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

[main.ts:177995](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177995)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo`](AppDataGoogleAppSearchesTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:177988](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177988)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")