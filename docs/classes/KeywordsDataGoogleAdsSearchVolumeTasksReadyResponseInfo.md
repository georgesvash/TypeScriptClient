[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo

# Class: KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`**

## Implements

- [`IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#cost)
- [status\_code](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#status_code)
- [status\_message](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#status_message)
- [tasks](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tasks)
- [tasks\_count](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tasks_count)
- [tasks\_error](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tasks_error)
- [time](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#time)
- [version](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#version)

### Methods

- [init](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#init)
- [toJSON](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tojson)
- [fromJS](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo**(`data?`): [`KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md) |

#### Returns

[`KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:113711](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L113711)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[cost](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#cost)

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

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[status_code](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#status_code)

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

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[status_message](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`KeywordsDataGoogleAdsSearchVolumeTasksReadyTaskInfo`](KeywordsDataGoogleAdsSearchVolumeTasksReadyTaskInfo.md)[]

array of tasks

#### Implementation of

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[tasks](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tasks)

#### Defined in

[main.ts:113707](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L113707)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[tasks_count](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[tasks_error](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[time](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md).[version](../interfaces/IKeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md#version)

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

[main.ts:113715](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L113715)

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

[main.ts:113737](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L113737)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo`](KeywordsDataGoogleAdsSearchVolumeTasksReadyResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:113730](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L113730)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")