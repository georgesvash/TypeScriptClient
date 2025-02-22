[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBingOrganicLiveHtmlResponseInfo

# Class: SerpBingOrganicLiveHtmlResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpBingOrganicLiveHtmlResponseInfo`**

## Implements

- [`ISerpBingOrganicLiveHtmlResponseInfo`](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBingOrganicLiveHtmlResponseInfo.md#constructor)

### Properties

- [cost](SerpBingOrganicLiveHtmlResponseInfo.md#cost)
- [status\_code](SerpBingOrganicLiveHtmlResponseInfo.md#status_code)
- [status\_message](SerpBingOrganicLiveHtmlResponseInfo.md#status_message)
- [tasks](SerpBingOrganicLiveHtmlResponseInfo.md#tasks)
- [tasks\_count](SerpBingOrganicLiveHtmlResponseInfo.md#tasks_count)
- [tasks\_error](SerpBingOrganicLiveHtmlResponseInfo.md#tasks_error)
- [time](SerpBingOrganicLiveHtmlResponseInfo.md#time)
- [version](SerpBingOrganicLiveHtmlResponseInfo.md#version)

### Methods

- [init](SerpBingOrganicLiveHtmlResponseInfo.md#init)
- [toJSON](SerpBingOrganicLiveHtmlResponseInfo.md#tojson)
- [fromJS](SerpBingOrganicLiveHtmlResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBingOrganicLiveHtmlResponseInfo**(`data?`): [`SerpBingOrganicLiveHtmlResponseInfo`](SerpBingOrganicLiveHtmlResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBingOrganicLiveHtmlResponseInfo`](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md) |

#### Returns

[`SerpBingOrganicLiveHtmlResponseInfo`](SerpBingOrganicLiveHtmlResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:55637](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55637)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[cost](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#cost)

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

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[status_code](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#status_code)

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

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[status_message](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpBingOrganicLiveHtmlTaskInfo`](SerpBingOrganicLiveHtmlTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[tasks](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#tasks)

#### Defined in

[main.ts:55633](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55633)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[tasks_count](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[tasks_error](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[time](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpBingOrganicLiveHtmlResponseInfo](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md).[version](../interfaces/ISerpBingOrganicLiveHtmlResponseInfo.md#version)

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

[main.ts:55641](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55641)

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

[main.ts:55663](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55663)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBingOrganicLiveHtmlResponseInfo`](SerpBingOrganicLiveHtmlResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBingOrganicLiveHtmlResponseInfo`](SerpBingOrganicLiveHtmlResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:55656](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55656)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")