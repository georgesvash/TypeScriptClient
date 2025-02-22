[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBaiduOrganicTaskPostResponseInfo

# Class: SerpBaiduOrganicTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpBaiduOrganicTaskPostResponseInfo`**

## Implements

- [`ISerpBaiduOrganicTaskPostResponseInfo`](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBaiduOrganicTaskPostResponseInfo.md#constructor)

### Properties

- [cost](SerpBaiduOrganicTaskPostResponseInfo.md#cost)
- [status\_code](SerpBaiduOrganicTaskPostResponseInfo.md#status_code)
- [status\_message](SerpBaiduOrganicTaskPostResponseInfo.md#status_message)
- [tasks](SerpBaiduOrganicTaskPostResponseInfo.md#tasks)
- [tasks\_count](SerpBaiduOrganicTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](SerpBaiduOrganicTaskPostResponseInfo.md#tasks_error)
- [time](SerpBaiduOrganicTaskPostResponseInfo.md#time)
- [version](SerpBaiduOrganicTaskPostResponseInfo.md#version)

### Methods

- [init](SerpBaiduOrganicTaskPostResponseInfo.md#init)
- [toJSON](SerpBaiduOrganicTaskPostResponseInfo.md#tojson)
- [fromJS](SerpBaiduOrganicTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBaiduOrganicTaskPostResponseInfo**(`data?`): [`SerpBaiduOrganicTaskPostResponseInfo`](SerpBaiduOrganicTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBaiduOrganicTaskPostResponseInfo`](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md) |

#### Returns

[`SerpBaiduOrganicTaskPostResponseInfo`](SerpBaiduOrganicTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:66119](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66119)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[cost](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#cost)

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

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[status_code](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#status_code)

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

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[status_message](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpBaiduOrganicTaskPostTaskInfo`](SerpBaiduOrganicTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[tasks](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:66115](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66115)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[tasks_count](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[tasks_error](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[time](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpBaiduOrganicTaskPostResponseInfo](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md).[version](../interfaces/ISerpBaiduOrganicTaskPostResponseInfo.md#version)

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

[main.ts:66123](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66123)

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

[main.ts:66145](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66145)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBaiduOrganicTaskPostResponseInfo`](SerpBaiduOrganicTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBaiduOrganicTaskPostResponseInfo`](SerpBaiduOrganicTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:66138](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66138)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")