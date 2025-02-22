[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataTripadvisorLocationsResponseInfo

# Class: BusinessDataTripadvisorLocationsResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataTripadvisorLocationsResponseInfo`**

## Implements

- [`IBusinessDataTripadvisorLocationsResponseInfo`](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataTripadvisorLocationsResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataTripadvisorLocationsResponseInfo.md#cost)
- [status\_code](BusinessDataTripadvisorLocationsResponseInfo.md#status_code)
- [status\_message](BusinessDataTripadvisorLocationsResponseInfo.md#status_message)
- [tasks](BusinessDataTripadvisorLocationsResponseInfo.md#tasks)
- [tasks\_count](BusinessDataTripadvisorLocationsResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataTripadvisorLocationsResponseInfo.md#tasks_error)
- [time](BusinessDataTripadvisorLocationsResponseInfo.md#time)
- [version](BusinessDataTripadvisorLocationsResponseInfo.md#version)

### Methods

- [init](BusinessDataTripadvisorLocationsResponseInfo.md#init)
- [toJSON](BusinessDataTripadvisorLocationsResponseInfo.md#tojson)
- [fromJS](BusinessDataTripadvisorLocationsResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataTripadvisorLocationsResponseInfo**(`data?`): [`BusinessDataTripadvisorLocationsResponseInfo`](BusinessDataTripadvisorLocationsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataTripadvisorLocationsResponseInfo`](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md) |

#### Returns

[`BusinessDataTripadvisorLocationsResponseInfo`](BusinessDataTripadvisorLocationsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:200487](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200487)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[cost](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#cost)

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

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[status_code](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#status_code)

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

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[status_message](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataTripadvisorLocationsTaskInfo`](BusinessDataTripadvisorLocationsTaskInfo.md)[]

array of tasks

#### Implementation of

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[tasks](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#tasks)

#### Defined in

[main.ts:200483](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200483)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[tasks_count](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[tasks_error](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[time](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataTripadvisorLocationsResponseInfo](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md).[version](../interfaces/IBusinessDataTripadvisorLocationsResponseInfo.md#version)

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

[main.ts:200491](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200491)

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

[main.ts:200513](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200513)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataTripadvisorLocationsResponseInfo`](BusinessDataTripadvisorLocationsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataTripadvisorLocationsResponseInfo`](BusinessDataTripadvisorLocationsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:200506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L200506)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")