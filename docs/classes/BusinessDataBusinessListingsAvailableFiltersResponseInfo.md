[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataBusinessListingsAvailableFiltersResponseInfo

# Class: BusinessDataBusinessListingsAvailableFiltersResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataBusinessListingsAvailableFiltersResponseInfo`**

## Implements

- [`IBusinessDataBusinessListingsAvailableFiltersResponseInfo`](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#cost)
- [status\_code](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#status_code)
- [status\_message](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#status_message)
- [tasks](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tasks)
- [tasks\_count](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tasks_error)
- [time](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#time)
- [version](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#version)

### Methods

- [init](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#init)
- [toJSON](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tojson)
- [fromJS](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataBusinessListingsAvailableFiltersResponseInfo**(`data?`): [`BusinessDataBusinessListingsAvailableFiltersResponseInfo`](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataBusinessListingsAvailableFiltersResponseInfo`](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md) |

#### Returns

[`BusinessDataBusinessListingsAvailableFiltersResponseInfo`](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:188304](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188304)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[cost](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#cost)

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

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[status_code](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#status_code)

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

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[status_message](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataBusinessListingsAvailableFiltersTaskInfo`](BusinessDataBusinessListingsAvailableFiltersTaskInfo.md)[]

#### Implementation of

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[tasks](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tasks)

#### Defined in

[main.ts:188300](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188300)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[tasks_count](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[tasks_error](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[time](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataBusinessListingsAvailableFiltersResponseInfo](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md).[version](../interfaces/IBusinessDataBusinessListingsAvailableFiltersResponseInfo.md#version)

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

[main.ts:188308](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188308)

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

[main.ts:188330](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188330)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataBusinessListingsAvailableFiltersResponseInfo`](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataBusinessListingsAvailableFiltersResponseInfo`](BusinessDataBusinessListingsAvailableFiltersResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:188323](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188323)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")