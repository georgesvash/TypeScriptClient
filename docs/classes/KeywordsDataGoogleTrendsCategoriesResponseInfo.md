[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleTrendsCategoriesResponseInfo

# Class: KeywordsDataGoogleTrendsCategoriesResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`KeywordsDataGoogleTrendsCategoriesResponseInfo`**

## Implements

- [`IKeywordsDataGoogleTrendsCategoriesResponseInfo`](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#cost)
- [status\_code](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#status_code)
- [status\_message](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#status_message)
- [tasks](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#tasks)
- [tasks\_count](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#tasks_count)
- [tasks\_error](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#tasks_error)
- [time](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#time)
- [version](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#version)

### Methods

- [init](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#init)
- [toJSON](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#tojson)
- [fromJS](KeywordsDataGoogleTrendsCategoriesResponseInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleTrendsCategoriesResponseInfo**(`data?`): [`KeywordsDataGoogleTrendsCategoriesResponseInfo`](KeywordsDataGoogleTrendsCategoriesResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleTrendsCategoriesResponseInfo`](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md) |

#### Returns

[`KeywordsDataGoogleTrendsCategoriesResponseInfo`](KeywordsDataGoogleTrendsCategoriesResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:119736](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119736)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[cost](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#cost)

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

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[status_code](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#status_code)

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

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[status_message](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`KeywordsDataGoogleTrendsCategoriesTaskInfo`](KeywordsDataGoogleTrendsCategoriesTaskInfo.md)[]

array of tasks

#### Implementation of

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[tasks](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#tasks)

#### Defined in

[main.ts:119732](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119732)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[tasks_count](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[tasks_error](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[time](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IKeywordsDataGoogleTrendsCategoriesResponseInfo](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md).[version](../interfaces/IKeywordsDataGoogleTrendsCategoriesResponseInfo.md#version)

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

[main.ts:119740](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119740)

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

[main.ts:119762](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119762)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleTrendsCategoriesResponseInfo`](KeywordsDataGoogleTrendsCategoriesResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleTrendsCategoriesResponseInfo`](KeywordsDataGoogleTrendsCategoriesResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:119755](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119755)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")