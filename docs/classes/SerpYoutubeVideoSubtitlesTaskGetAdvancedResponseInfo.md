[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo

# Class: SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`**

## Implements

- [`ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#time)
- [version](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#init)
- [toJSON](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo**(`data?`): [`SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md) |

#### Returns

[`SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:60535](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60535)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[cost](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#cost)

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

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#status_code)

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

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpYoutubeVideoSubtitlesTaskGetAdvancedTaskInfo`](SerpYoutubeVideoSubtitlesTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:60531](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60531)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[time](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md).[version](../interfaces/ISerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:60539](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60539)

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

[main.ts:60561](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60561)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo`](SerpYoutubeVideoSubtitlesTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:60554](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L60554)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")