[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleTrendsExploreTaskPostResponseInfo

# Class: KeywordsDataGoogleTrendsExploreTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`KeywordsDataGoogleTrendsExploreTaskPostResponseInfo`**

## Implements

- [`IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo`](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#cost)
- [status\_code](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#status_code)
- [status\_message](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#status_message)
- [tasks](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tasks)
- [tasks\_count](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tasks_error)
- [time](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#time)
- [version](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#version)

### Methods

- [init](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#init)
- [toJSON](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tojson)
- [fromJS](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleTrendsExploreTaskPostResponseInfo**(`data?`): [`KeywordsDataGoogleTrendsExploreTaskPostResponseInfo`](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo`](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md) |

#### Returns

[`KeywordsDataGoogleTrendsExploreTaskPostResponseInfo`](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:120144](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L120144)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[cost](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#cost)

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

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[status_code](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#status_code)

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

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[status_message](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`KeywordsDataGoogleTrendsExploreTaskPostTaskInfo`](KeywordsDataGoogleTrendsExploreTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[tasks](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:120140](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L120140)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[tasks_count](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[tasks_error](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[time](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md).[version](../interfaces/IKeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md#version)

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

[main.ts:120148](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L120148)

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

[main.ts:120170](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L120170)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleTrendsExploreTaskPostResponseInfo`](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleTrendsExploreTaskPostResponseInfo`](KeywordsDataGoogleTrendsExploreTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:120163](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L120163)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")