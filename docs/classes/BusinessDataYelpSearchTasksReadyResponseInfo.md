[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataYelpSearchTasksReadyResponseInfo

# Class: BusinessDataYelpSearchTasksReadyResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataYelpSearchTasksReadyResponseInfo`**

## Implements

- [`IBusinessDataYelpSearchTasksReadyResponseInfo`](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataYelpSearchTasksReadyResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataYelpSearchTasksReadyResponseInfo.md#cost)
- [status\_code](BusinessDataYelpSearchTasksReadyResponseInfo.md#status_code)
- [status\_message](BusinessDataYelpSearchTasksReadyResponseInfo.md#status_message)
- [tasks](BusinessDataYelpSearchTasksReadyResponseInfo.md#tasks)
- [tasks\_count](BusinessDataYelpSearchTasksReadyResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataYelpSearchTasksReadyResponseInfo.md#tasks_error)
- [time](BusinessDataYelpSearchTasksReadyResponseInfo.md#time)
- [version](BusinessDataYelpSearchTasksReadyResponseInfo.md#version)

### Methods

- [init](BusinessDataYelpSearchTasksReadyResponseInfo.md#init)
- [toJSON](BusinessDataYelpSearchTasksReadyResponseInfo.md#tojson)
- [fromJS](BusinessDataYelpSearchTasksReadyResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataYelpSearchTasksReadyResponseInfo**(`data?`): [`BusinessDataYelpSearchTasksReadyResponseInfo`](BusinessDataYelpSearchTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataYelpSearchTasksReadyResponseInfo`](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md) |

#### Returns

[`BusinessDataYelpSearchTasksReadyResponseInfo`](BusinessDataYelpSearchTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:203821](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203821)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[cost](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#cost)

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

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[status_code](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#status_code)

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

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[status_message](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataYelpSearchTasksReadyTaskInfo`](BusinessDataYelpSearchTasksReadyTaskInfo.md)[]

array of tasks

#### Implementation of

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[tasks](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#tasks)

#### Defined in

[main.ts:203817](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203817)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[tasks_count](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[tasks_error](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[time](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataYelpSearchTasksReadyResponseInfo](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md).[version](../interfaces/IBusinessDataYelpSearchTasksReadyResponseInfo.md#version)

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

[main.ts:203825](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203825)

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

[main.ts:203847](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203847)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataYelpSearchTasksReadyResponseInfo`](BusinessDataYelpSearchTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataYelpSearchTasksReadyResponseInfo`](BusinessDataYelpSearchTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:203840](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L203840)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")