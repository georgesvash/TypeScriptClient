[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo

# Class: DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`**

## Implements

- [`IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#constructor)

### Properties

- [cost](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#cost)
- [status\_code](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#status_code)
- [status\_message](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#status_message)
- [tasks](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tasks)
- [tasks\_count](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tasks_count)
- [tasks\_error](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tasks_error)
- [time](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#time)
- [version](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#version)

### Methods

- [init](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#init)
- [toJSON](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo**(`data?`): [`DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md) |

#### Returns

[`DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:81125](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81125)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[cost](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#cost)

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

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[status_code](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#status_code)

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

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[status_message](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`DataforseoLabsGoogleKeywordSuggestionsLiveTaskInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[tasks](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:81121](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81121)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[tasks_count](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[tasks_error](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[time](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md).[version](../interfaces/IDataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md#version)

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

[main.ts:81129](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81129)

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

[main.ts:81151](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81151)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo`](DataforseoLabsGoogleKeywordSuggestionsLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:81144](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L81144)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")