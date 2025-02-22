[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataBusinessListingsLocationsResponseInfo

# Class: BusinessDataBusinessListingsLocationsResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataBusinessListingsLocationsResponseInfo`**

## Implements

- [`IBusinessDataBusinessListingsLocationsResponseInfo`](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataBusinessListingsLocationsResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataBusinessListingsLocationsResponseInfo.md#cost)
- [status\_code](BusinessDataBusinessListingsLocationsResponseInfo.md#status_code)
- [status\_message](BusinessDataBusinessListingsLocationsResponseInfo.md#status_message)
- [tasks](BusinessDataBusinessListingsLocationsResponseInfo.md#tasks)
- [tasks\_count](BusinessDataBusinessListingsLocationsResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataBusinessListingsLocationsResponseInfo.md#tasks_error)
- [time](BusinessDataBusinessListingsLocationsResponseInfo.md#time)
- [version](BusinessDataBusinessListingsLocationsResponseInfo.md#version)

### Methods

- [init](BusinessDataBusinessListingsLocationsResponseInfo.md#init)
- [toJSON](BusinessDataBusinessListingsLocationsResponseInfo.md#tojson)
- [fromJS](BusinessDataBusinessListingsLocationsResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataBusinessListingsLocationsResponseInfo**(`data?`): [`BusinessDataBusinessListingsLocationsResponseInfo`](BusinessDataBusinessListingsLocationsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataBusinessListingsLocationsResponseInfo`](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md) |

#### Returns

[`BusinessDataBusinessListingsLocationsResponseInfo`](BusinessDataBusinessListingsLocationsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:187955](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187955)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[cost](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#cost)

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

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[status_code](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#status_code)

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

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[status_message](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataBusinessListingsLocationsTaskInfo`](BusinessDataBusinessListingsLocationsTaskInfo.md)[]

array of tasks

#### Implementation of

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[tasks](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#tasks)

#### Defined in

[main.ts:187951](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187951)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[tasks_count](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[tasks_error](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[time](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataBusinessListingsLocationsResponseInfo](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md).[version](../interfaces/IBusinessDataBusinessListingsLocationsResponseInfo.md#version)

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

[main.ts:187959](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187959)

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

[main.ts:187981](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187981)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataBusinessListingsLocationsResponseInfo`](BusinessDataBusinessListingsLocationsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataBusinessListingsLocationsResponseInfo`](BusinessDataBusinessListingsLocationsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:187974](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L187974)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")