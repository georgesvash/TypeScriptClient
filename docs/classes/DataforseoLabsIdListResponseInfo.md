[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsIdListResponseInfo

# Class: DataforseoLabsIdListResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`DataforseoLabsIdListResponseInfo`**

## Implements

- [`IDataforseoLabsIdListResponseInfo`](../interfaces/IDataforseoLabsIdListResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsIdListResponseInfo.md#constructor)

### Properties

- [cost](DataforseoLabsIdListResponseInfo.md#cost)
- [status\_code](DataforseoLabsIdListResponseInfo.md#status_code)
- [status\_message](DataforseoLabsIdListResponseInfo.md#status_message)
- [tasks](DataforseoLabsIdListResponseInfo.md#tasks)
- [tasks\_count](DataforseoLabsIdListResponseInfo.md#tasks_count)
- [tasks\_error](DataforseoLabsIdListResponseInfo.md#tasks_error)
- [time](DataforseoLabsIdListResponseInfo.md#time)
- [version](DataforseoLabsIdListResponseInfo.md#version)

### Methods

- [init](DataforseoLabsIdListResponseInfo.md#init)
- [toJSON](DataforseoLabsIdListResponseInfo.md#tojson)
- [fromJS](DataforseoLabsIdListResponseInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsIdListResponseInfo**(`data?`): [`DataforseoLabsIdListResponseInfo`](DataforseoLabsIdListResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsIdListResponseInfo`](../interfaces/IDataforseoLabsIdListResponseInfo.md) |

#### Returns

[`DataforseoLabsIdListResponseInfo`](DataforseoLabsIdListResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:76721](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76721)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[cost](../interfaces/IDataforseoLabsIdListResponseInfo.md#cost)

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

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[status_code](../interfaces/IDataforseoLabsIdListResponseInfo.md#status_code)

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

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[status_message](../interfaces/IDataforseoLabsIdListResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`DataforseoLabsIdListTaskInfo`](DataforseoLabsIdListTaskInfo.md)[]

array of tasks

#### Implementation of

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[tasks](../interfaces/IDataforseoLabsIdListResponseInfo.md#tasks)

#### Defined in

[main.ts:76717](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76717)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[tasks_count](../interfaces/IDataforseoLabsIdListResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[tasks_error](../interfaces/IDataforseoLabsIdListResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[time](../interfaces/IDataforseoLabsIdListResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IDataforseoLabsIdListResponseInfo](../interfaces/IDataforseoLabsIdListResponseInfo.md).[version](../interfaces/IDataforseoLabsIdListResponseInfo.md#version)

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

[main.ts:76725](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76725)

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

[main.ts:76747](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76747)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsIdListResponseInfo`](DataforseoLabsIdListResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsIdListResponseInfo`](DataforseoLabsIdListResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:76740](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L76740)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")