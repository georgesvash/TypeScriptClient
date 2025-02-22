[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataBingKeywordsForKeywordsLiveResponseInfo

# Class: KeywordsDataBingKeywordsForKeywordsLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`KeywordsDataBingKeywordsForKeywordsLiveResponseInfo`**

## Implements

- [`IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo`](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#constructor)

### Properties

- [cost](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#cost)
- [status\_code](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#status_code)
- [status\_message](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#status_message)
- [tasks](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tasks)
- [tasks\_count](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tasks_count)
- [tasks\_error](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tasks_error)
- [time](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#time)
- [version](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#version)

### Methods

- [init](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#init)
- [toJSON](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tojson)
- [fromJS](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataBingKeywordsForKeywordsLiveResponseInfo**(`data?`): [`KeywordsDataBingKeywordsForKeywordsLiveResponseInfo`](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo`](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md) |

#### Returns

[`KeywordsDataBingKeywordsForKeywordsLiveResponseInfo`](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:126286](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126286)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[cost](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#cost)

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

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[status_code](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#status_code)

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

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[status_message](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`KeywordsDataBingKeywordsForKeywordsLiveTaskInfo`](KeywordsDataBingKeywordsForKeywordsLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[tasks](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:126282](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126282)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[tasks_count](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[tasks_error](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[time](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md).[version](../interfaces/IKeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md#version)

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

[main.ts:126290](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126290)

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

[main.ts:126312](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126312)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataBingKeywordsForKeywordsLiveResponseInfo`](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataBingKeywordsForKeywordsLiveResponseInfo`](KeywordsDataBingKeywordsForKeywordsLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:126305](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L126305)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")