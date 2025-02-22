[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleAppReviewsTaskGetAdvancedResponseInfo

# Class: AppDataAppleAppReviewsTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataAppleAppReviewsTaskGetAdvancedResponseInfo`**

## Implements

- [`IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo`](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#time)
- [version](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#init)
- [toJSON](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleAppReviewsTaskGetAdvancedResponseInfo**(`data?`): [`AppDataAppleAppReviewsTaskGetAdvancedResponseInfo`](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo`](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md) |

#### Returns

[`AppDataAppleAppReviewsTaskGetAdvancedResponseInfo`](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:186517](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L186517)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[cost](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#cost)

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

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#status_code)

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

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataAppleAppReviewsTaskGetAdvancedTaskInfo`](AppDataAppleAppReviewsTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:186513](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L186513)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[time](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md).[version](../interfaces/IAppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:186521](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L186521)

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

[main.ts:186543](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L186543)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleAppReviewsTaskGetAdvancedResponseInfo`](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleAppReviewsTaskGetAdvancedResponseInfo`](AppDataAppleAppReviewsTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:186536](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L186536)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")