[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataBingKeywordsForSiteLiveResponseInfo

# Class: KeywordsDataBingKeywordsForSiteLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`KeywordsDataBingKeywordsForSiteLiveResponseInfo`**

## Implements

- [`IKeywordsDataBingKeywordsForSiteLiveResponseInfo`](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#constructor)

### Properties

- [cost](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#cost)
- [status\_code](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#status_code)
- [status\_message](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#status_message)
- [tasks](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tasks)
- [tasks\_count](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tasks_count)
- [tasks\_error](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tasks_error)
- [time](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#time)
- [version](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#version)

### Methods

- [init](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#init)
- [toJSON](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tojson)
- [fromJS](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataBingKeywordsForSiteLiveResponseInfo**(`data?`): [`KeywordsDataBingKeywordsForSiteLiveResponseInfo`](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataBingKeywordsForSiteLiveResponseInfo`](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md) |

#### Returns

[`KeywordsDataBingKeywordsForSiteLiveResponseInfo`](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:124910](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L124910)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[cost](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#cost)

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

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[status_code](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#status_code)

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

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[status_message](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`KeywordsDataBingKeywordsForSiteLiveTaskInfo`](KeywordsDataBingKeywordsForSiteLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[tasks](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:124906](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L124906)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[tasks_count](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[tasks_error](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[time](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IKeywordsDataBingKeywordsForSiteLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md).[version](../interfaces/IKeywordsDataBingKeywordsForSiteLiveResponseInfo.md#version)

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

[main.ts:124914](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L124914)

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

[main.ts:124936](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L124936)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataBingKeywordsForSiteLiveResponseInfo`](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataBingKeywordsForSiteLiveResponseInfo`](KeywordsDataBingKeywordsForSiteLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:124929](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L124929)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")