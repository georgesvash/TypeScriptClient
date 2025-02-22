[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBingLocalPackTaskPostResponseInfo

# Class: SerpBingLocalPackTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpBingLocalPackTaskPostResponseInfo`**

## Implements

- [`ISerpBingLocalPackTaskPostResponseInfo`](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBingLocalPackTaskPostResponseInfo.md#constructor)

### Properties

- [cost](SerpBingLocalPackTaskPostResponseInfo.md#cost)
- [status\_code](SerpBingLocalPackTaskPostResponseInfo.md#status_code)
- [status\_message](SerpBingLocalPackTaskPostResponseInfo.md#status_message)
- [tasks](SerpBingLocalPackTaskPostResponseInfo.md#tasks)
- [tasks\_count](SerpBingLocalPackTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](SerpBingLocalPackTaskPostResponseInfo.md#tasks_error)
- [time](SerpBingLocalPackTaskPostResponseInfo.md#time)
- [version](SerpBingLocalPackTaskPostResponseInfo.md#version)

### Methods

- [init](SerpBingLocalPackTaskPostResponseInfo.md#init)
- [toJSON](SerpBingLocalPackTaskPostResponseInfo.md#tojson)
- [fromJS](SerpBingLocalPackTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBingLocalPackTaskPostResponseInfo**(`data?`): [`SerpBingLocalPackTaskPostResponseInfo`](SerpBingLocalPackTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBingLocalPackTaskPostResponseInfo`](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md) |

#### Returns

[`SerpBingLocalPackTaskPostResponseInfo`](SerpBingLocalPackTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:55741](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55741)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[cost](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#cost)

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

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[status_code](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#status_code)

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

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[status_message](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpBingLocalPackTaskPostTaskInfo`](SerpBingLocalPackTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[tasks](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:55737](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55737)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[tasks_count](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[tasks_error](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[time](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpBingLocalPackTaskPostResponseInfo](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md).[version](../interfaces/ISerpBingLocalPackTaskPostResponseInfo.md#version)

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

[main.ts:55745](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55745)

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

[main.ts:55767](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55767)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBingLocalPackTaskPostResponseInfo`](SerpBingLocalPackTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBingLocalPackTaskPostResponseInfo`](SerpBingLocalPackTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:55760](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L55760)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")