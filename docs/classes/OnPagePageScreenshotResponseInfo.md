[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPagePageScreenshotResponseInfo

# Class: OnPagePageScreenshotResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`OnPagePageScreenshotResponseInfo`**

## Implements

- [`IOnPagePageScreenshotResponseInfo`](../interfaces/IOnPagePageScreenshotResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPagePageScreenshotResponseInfo.md#constructor)

### Properties

- [cost](OnPagePageScreenshotResponseInfo.md#cost)
- [status\_code](OnPagePageScreenshotResponseInfo.md#status_code)
- [status\_message](OnPagePageScreenshotResponseInfo.md#status_message)
- [tasks](OnPagePageScreenshotResponseInfo.md#tasks)
- [tasks\_count](OnPagePageScreenshotResponseInfo.md#tasks_count)
- [tasks\_error](OnPagePageScreenshotResponseInfo.md#tasks_error)
- [time](OnPagePageScreenshotResponseInfo.md#time)
- [version](OnPagePageScreenshotResponseInfo.md#version)

### Methods

- [init](OnPagePageScreenshotResponseInfo.md#init)
- [toJSON](OnPagePageScreenshotResponseInfo.md#tojson)
- [fromJS](OnPagePageScreenshotResponseInfo.md#fromjs)

## Constructors

### constructor

• **new OnPagePageScreenshotResponseInfo**(`data?`): [`OnPagePageScreenshotResponseInfo`](OnPagePageScreenshotResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPagePageScreenshotResponseInfo`](../interfaces/IOnPagePageScreenshotResponseInfo.md) |

#### Returns

[`OnPagePageScreenshotResponseInfo`](OnPagePageScreenshotResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:151830](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151830)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[cost](../interfaces/IOnPagePageScreenshotResponseInfo.md#cost)

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

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[status_code](../interfaces/IOnPagePageScreenshotResponseInfo.md#status_code)

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

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[status_message](../interfaces/IOnPagePageScreenshotResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`OnPagePageScreenshotTaskInfo`](OnPagePageScreenshotTaskInfo.md)[]

array of tasks

#### Implementation of

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[tasks](../interfaces/IOnPagePageScreenshotResponseInfo.md#tasks)

#### Defined in

[main.ts:151826](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151826)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[tasks_count](../interfaces/IOnPagePageScreenshotResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[tasks_error](../interfaces/IOnPagePageScreenshotResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[time](../interfaces/IOnPagePageScreenshotResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IOnPagePageScreenshotResponseInfo](../interfaces/IOnPagePageScreenshotResponseInfo.md).[version](../interfaces/IOnPagePageScreenshotResponseInfo.md#version)

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

[main.ts:151834](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151834)

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

[main.ts:151856](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151856)

___


### fromJS

▸ **fromJS**(`data`): [`OnPagePageScreenshotResponseInfo`](OnPagePageScreenshotResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPagePageScreenshotResponseInfo`](OnPagePageScreenshotResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:151849](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L151849)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")