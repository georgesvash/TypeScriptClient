[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo

# Class: DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`**

## Implements

- [`IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#constructor)

### Properties

- [cost](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#cost)
- [status\_code](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#status_code)
- [status\_message](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#status_message)
- [tasks](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tasks)
- [tasks\_count](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tasks_count)
- [tasks\_error](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tasks_error)
- [time](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#time)
- [version](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#version)

### Methods

- [init](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#init)
- [toJSON](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tojson)
- [fromJS](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo**(`data?`): [`DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md) |

#### Returns

[`DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:102391](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L102391)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[cost](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#cost)

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

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[status_code](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#status_code)

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

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[status_message](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`DataforseoLabsBingBulkKeywordDifficultyLiveTaskInfo`](DataforseoLabsBingBulkKeywordDifficultyLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[tasks](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:102387](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L102387)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[tasks_count](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[tasks_error](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[time](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md).[version](../interfaces/IDataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md#version)

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

[main.ts:102395](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L102395)

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

[main.ts:102417](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L102417)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo`](DataforseoLabsBingBulkKeywordDifficultyLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:102410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L102410)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")