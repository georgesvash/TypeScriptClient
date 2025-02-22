[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPagePagesByResourceResponseInfo

# Class: OnPagePagesByResourceResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`OnPagePagesByResourceResponseInfo`**

## Implements

- [`IOnPagePagesByResourceResponseInfo`](../interfaces/IOnPagePagesByResourceResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPagePagesByResourceResponseInfo.md#constructor)

### Properties

- [cost](OnPagePagesByResourceResponseInfo.md#cost)
- [status\_code](OnPagePagesByResourceResponseInfo.md#status_code)
- [status\_message](OnPagePagesByResourceResponseInfo.md#status_message)
- [tasks](OnPagePagesByResourceResponseInfo.md#tasks)
- [tasks\_count](OnPagePagesByResourceResponseInfo.md#tasks_count)
- [tasks\_error](OnPagePagesByResourceResponseInfo.md#tasks_error)
- [time](OnPagePagesByResourceResponseInfo.md#time)
- [version](OnPagePagesByResourceResponseInfo.md#version)

### Methods

- [init](OnPagePagesByResourceResponseInfo.md#init)
- [toJSON](OnPagePagesByResourceResponseInfo.md#tojson)
- [fromJS](OnPagePagesByResourceResponseInfo.md#fromjs)

## Constructors

### constructor

• **new OnPagePagesByResourceResponseInfo**(`data?`): [`OnPagePagesByResourceResponseInfo`](OnPagePagesByResourceResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPagePagesByResourceResponseInfo`](../interfaces/IOnPagePagesByResourceResponseInfo.md) |

#### Returns

[`OnPagePagesByResourceResponseInfo`](OnPagePagesByResourceResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:145660](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L145660)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[cost](../interfaces/IOnPagePagesByResourceResponseInfo.md#cost)

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

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[status_code](../interfaces/IOnPagePagesByResourceResponseInfo.md#status_code)

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

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[status_message](../interfaces/IOnPagePagesByResourceResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`OnPagePagesByResourceTaskInfo`](OnPagePagesByResourceTaskInfo.md)[]

array of tasks

#### Implementation of

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[tasks](../interfaces/IOnPagePagesByResourceResponseInfo.md#tasks)

#### Defined in

[main.ts:145656](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L145656)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[tasks_count](../interfaces/IOnPagePagesByResourceResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[tasks_error](../interfaces/IOnPagePagesByResourceResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[time](../interfaces/IOnPagePagesByResourceResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IOnPagePagesByResourceResponseInfo](../interfaces/IOnPagePagesByResourceResponseInfo.md).[version](../interfaces/IOnPagePagesByResourceResponseInfo.md#version)

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

[main.ts:145664](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L145664)

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

[main.ts:145686](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L145686)

___


### fromJS

▸ **fromJS**(`data`): [`OnPagePagesByResourceResponseInfo`](OnPagePagesByResourceResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPagePagesByResourceResponseInfo`](OnPagePagesByResourceResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:145679](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L145679)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")