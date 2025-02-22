[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleEventsTaskPostResponseInfo

# Class: SerpGoogleEventsTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleEventsTaskPostResponseInfo`**

## Implements

- [`ISerpGoogleEventsTaskPostResponseInfo`](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleEventsTaskPostResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleEventsTaskPostResponseInfo.md#cost)
- [status\_code](SerpGoogleEventsTaskPostResponseInfo.md#status_code)
- [status\_message](SerpGoogleEventsTaskPostResponseInfo.md#status_message)
- [tasks](SerpGoogleEventsTaskPostResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleEventsTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleEventsTaskPostResponseInfo.md#tasks_error)
- [time](SerpGoogleEventsTaskPostResponseInfo.md#time)
- [version](SerpGoogleEventsTaskPostResponseInfo.md#version)

### Methods

- [init](SerpGoogleEventsTaskPostResponseInfo.md#init)
- [toJSON](SerpGoogleEventsTaskPostResponseInfo.md#tojson)
- [fromJS](SerpGoogleEventsTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleEventsTaskPostResponseInfo**(`data?`): [`SerpGoogleEventsTaskPostResponseInfo`](SerpGoogleEventsTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleEventsTaskPostResponseInfo`](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md) |

#### Returns

[`SerpGoogleEventsTaskPostResponseInfo`](SerpGoogleEventsTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:43947](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43947)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[cost](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#cost)

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

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[status_code](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#status_code)

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

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[status_message](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleEventsTaskPostTaskInfo`](SerpGoogleEventsTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[tasks](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:43943](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43943)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[time](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleEventsTaskPostResponseInfo](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md).[version](../interfaces/ISerpGoogleEventsTaskPostResponseInfo.md#version)

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

[main.ts:43951](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43951)

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

[main.ts:43973](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43973)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleEventsTaskPostResponseInfo`](SerpGoogleEventsTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleEventsTaskPostResponseInfo`](SerpGoogleEventsTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:43966](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L43966)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")