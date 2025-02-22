[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageKeywordDensityResponseInfo

# Class: OnPageKeywordDensityResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`OnPageKeywordDensityResponseInfo`**

## Implements

- [`IOnPageKeywordDensityResponseInfo`](../interfaces/IOnPageKeywordDensityResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageKeywordDensityResponseInfo.md#constructor)

### Properties

- [cost](OnPageKeywordDensityResponseInfo.md#cost)
- [status\_code](OnPageKeywordDensityResponseInfo.md#status_code)
- [status\_message](OnPageKeywordDensityResponseInfo.md#status_message)
- [tasks](OnPageKeywordDensityResponseInfo.md#tasks)
- [tasks\_count](OnPageKeywordDensityResponseInfo.md#tasks_count)
- [tasks\_error](OnPageKeywordDensityResponseInfo.md#tasks_error)
- [time](OnPageKeywordDensityResponseInfo.md#time)
- [version](OnPageKeywordDensityResponseInfo.md#version)

### Methods

- [init](OnPageKeywordDensityResponseInfo.md#init)
- [toJSON](OnPageKeywordDensityResponseInfo.md#tojson)
- [fromJS](OnPageKeywordDensityResponseInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageKeywordDensityResponseInfo**(`data?`): [`OnPageKeywordDensityResponseInfo`](OnPageKeywordDensityResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageKeywordDensityResponseInfo`](../interfaces/IOnPageKeywordDensityResponseInfo.md) |

#### Returns

[`OnPageKeywordDensityResponseInfo`](OnPageKeywordDensityResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:150444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150444)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[cost](../interfaces/IOnPageKeywordDensityResponseInfo.md#cost)

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

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[status_code](../interfaces/IOnPageKeywordDensityResponseInfo.md#status_code)

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

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[status_message](../interfaces/IOnPageKeywordDensityResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`OnPageKeywordDensityTaskInfo`](OnPageKeywordDensityTaskInfo.md)[]

array of tasks

#### Implementation of

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[tasks](../interfaces/IOnPageKeywordDensityResponseInfo.md#tasks)

#### Defined in

[main.ts:150440](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150440)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[tasks_count](../interfaces/IOnPageKeywordDensityResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[tasks_error](../interfaces/IOnPageKeywordDensityResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[time](../interfaces/IOnPageKeywordDensityResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IOnPageKeywordDensityResponseInfo](../interfaces/IOnPageKeywordDensityResponseInfo.md).[version](../interfaces/IOnPageKeywordDensityResponseInfo.md#version)

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

[main.ts:150448](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150448)

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

[main.ts:150470](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150470)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageKeywordDensityResponseInfo`](OnPageKeywordDensityResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageKeywordDensityResponseInfo`](OnPageKeywordDensityResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:150463](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L150463)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")