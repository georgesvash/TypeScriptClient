[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleMapsTaskPostResponseInfo

# Class: SerpGoogleMapsTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleMapsTaskPostResponseInfo`**

## Implements

- [`ISerpGoogleMapsTaskPostResponseInfo`](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleMapsTaskPostResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleMapsTaskPostResponseInfo.md#cost)
- [status\_code](SerpGoogleMapsTaskPostResponseInfo.md#status_code)
- [status\_message](SerpGoogleMapsTaskPostResponseInfo.md#status_message)
- [tasks](SerpGoogleMapsTaskPostResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleMapsTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleMapsTaskPostResponseInfo.md#tasks_error)
- [time](SerpGoogleMapsTaskPostResponseInfo.md#time)
- [version](SerpGoogleMapsTaskPostResponseInfo.md#version)

### Methods

- [init](SerpGoogleMapsTaskPostResponseInfo.md#init)
- [toJSON](SerpGoogleMapsTaskPostResponseInfo.md#tojson)
- [fromJS](SerpGoogleMapsTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleMapsTaskPostResponseInfo**(`data?`): [`SerpGoogleMapsTaskPostResponseInfo`](SerpGoogleMapsTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleMapsTaskPostResponseInfo`](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md) |

#### Returns

[`SerpGoogleMapsTaskPostResponseInfo`](SerpGoogleMapsTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:37735](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37735)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[cost](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#cost)

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

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[status_code](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#status_code)

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

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[status_message](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleMapsTaskPostTaskInfo`](SerpGoogleMapsTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[tasks](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:37731](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37731)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[time](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleMapsTaskPostResponseInfo](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md).[version](../interfaces/ISerpGoogleMapsTaskPostResponseInfo.md#version)

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

[main.ts:37739](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37739)

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

[main.ts:37761](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37761)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleMapsTaskPostResponseInfo`](SerpGoogleMapsTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleMapsTaskPostResponseInfo`](SerpGoogleMapsTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:37754](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L37754)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")