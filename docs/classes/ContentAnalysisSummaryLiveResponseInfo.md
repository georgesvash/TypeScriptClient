[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ContentAnalysisSummaryLiveResponseInfo

# Class: ContentAnalysisSummaryLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`ContentAnalysisSummaryLiveResponseInfo`**

## Implements

- [`IContentAnalysisSummaryLiveResponseInfo`](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ContentAnalysisSummaryLiveResponseInfo.md#constructor)

### Properties

- [cost](ContentAnalysisSummaryLiveResponseInfo.md#cost)
- [status\_code](ContentAnalysisSummaryLiveResponseInfo.md#status_code)
- [status\_message](ContentAnalysisSummaryLiveResponseInfo.md#status_message)
- [tasks](ContentAnalysisSummaryLiveResponseInfo.md#tasks)
- [tasks\_count](ContentAnalysisSummaryLiveResponseInfo.md#tasks_count)
- [tasks\_error](ContentAnalysisSummaryLiveResponseInfo.md#tasks_error)
- [time](ContentAnalysisSummaryLiveResponseInfo.md#time)
- [version](ContentAnalysisSummaryLiveResponseInfo.md#version)

### Methods

- [init](ContentAnalysisSummaryLiveResponseInfo.md#init)
- [toJSON](ContentAnalysisSummaryLiveResponseInfo.md#tojson)
- [fromJS](ContentAnalysisSummaryLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new ContentAnalysisSummaryLiveResponseInfo**(`data?`): [`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IContentAnalysisSummaryLiveResponseInfo`](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md) |

#### Returns

[`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:157560](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L157560)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[cost](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#cost)

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

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[status_code](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#status_code)

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

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[status_message](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`ContentAnalysisSummaryLiveTaskInfo`](ContentAnalysisSummaryLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[tasks](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:157556](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L157556)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[tasks_count](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[tasks_error](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[time](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IContentAnalysisSummaryLiveResponseInfo](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md).[version](../interfaces/IContentAnalysisSummaryLiveResponseInfo.md#version)

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

[main.ts:157564](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L157564)

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

[main.ts:157586](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L157586)

___


### fromJS

▸ **fromJS**(`data`): [`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ContentAnalysisSummaryLiveResponseInfo`](ContentAnalysisSummaryLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:157579](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L157579)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")