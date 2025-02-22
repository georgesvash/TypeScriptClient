[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataTripadvisorSearchTaskGetResponseInfo

# Class: BusinessDataTripadvisorSearchTaskGetResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataTripadvisorSearchTaskGetResponseInfo`**

## Implements

- [`IBusinessDataTripadvisorSearchTaskGetResponseInfo`](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#cost)
- [status\_code](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#status_code)
- [status\_message](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#status_message)
- [tasks](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#tasks)
- [tasks\_count](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#tasks_error)
- [time](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#time)
- [version](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#version)

### Methods

- [init](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#init)
- [toJSON](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#tojson)
- [fromJS](BusinessDataTripadvisorSearchTaskGetResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataTripadvisorSearchTaskGetResponseInfo**(`data?`): [`BusinessDataTripadvisorSearchTaskGetResponseInfo`](BusinessDataTripadvisorSearchTaskGetResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataTripadvisorSearchTaskGetResponseInfo`](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md) |

#### Returns

[`BusinessDataTripadvisorSearchTaskGetResponseInfo`](BusinessDataTripadvisorSearchTaskGetResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:201669](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201669)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[cost](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#cost)

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

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[status_code](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#status_code)

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

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[status_message](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataTripadvisorSearchTaskGetTaskInfo`](BusinessDataTripadvisorSearchTaskGetTaskInfo.md)[]

array of tasks

#### Implementation of

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[tasks](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#tasks)

#### Defined in

[main.ts:201665](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201665)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[tasks_count](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[tasks_error](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[time](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataTripadvisorSearchTaskGetResponseInfo](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md).[version](../interfaces/IBusinessDataTripadvisorSearchTaskGetResponseInfo.md#version)

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

[main.ts:201673](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201673)

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

[main.ts:201695](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201695)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataTripadvisorSearchTaskGetResponseInfo`](BusinessDataTripadvisorSearchTaskGetResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataTripadvisorSearchTaskGetResponseInfo`](BusinessDataTripadvisorSearchTaskGetResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:201688](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201688)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")