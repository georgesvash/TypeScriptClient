[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksPageIntersectionLiveResponseInfo

# Class: BacklinksPageIntersectionLiveResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BacklinksPageIntersectionLiveResponseInfo`**

## Implements

- [`IBacklinksPageIntersectionLiveResponseInfo`](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksPageIntersectionLiveResponseInfo.md#constructor)

### Properties

- [cost](BacklinksPageIntersectionLiveResponseInfo.md#cost)
- [status\_code](BacklinksPageIntersectionLiveResponseInfo.md#status_code)
- [status\_message](BacklinksPageIntersectionLiveResponseInfo.md#status_message)
- [tasks](BacklinksPageIntersectionLiveResponseInfo.md#tasks)
- [tasks\_count](BacklinksPageIntersectionLiveResponseInfo.md#tasks_count)
- [tasks\_error](BacklinksPageIntersectionLiveResponseInfo.md#tasks_error)
- [time](BacklinksPageIntersectionLiveResponseInfo.md#time)
- [version](BacklinksPageIntersectionLiveResponseInfo.md#version)

### Methods

- [init](BacklinksPageIntersectionLiveResponseInfo.md#init)
- [toJSON](BacklinksPageIntersectionLiveResponseInfo.md#tojson)
- [fromJS](BacklinksPageIntersectionLiveResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksPageIntersectionLiveResponseInfo**(`data?`): [`BacklinksPageIntersectionLiveResponseInfo`](BacklinksPageIntersectionLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksPageIntersectionLiveResponseInfo`](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md) |

#### Returns

[`BacklinksPageIntersectionLiveResponseInfo`](BacklinksPageIntersectionLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:138306](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L138306)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[cost](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#cost)

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

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[status_code](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#status_code)

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

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[status_message](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BacklinksPageIntersectionLiveTaskInfo`](BacklinksPageIntersectionLiveTaskInfo.md)[]

array of tasks

#### Implementation of

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[tasks](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#tasks)

#### Defined in

[main.ts:138302](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L138302)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[tasks_count](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[tasks_error](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[time](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBacklinksPageIntersectionLiveResponseInfo](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md).[version](../interfaces/IBacklinksPageIntersectionLiveResponseInfo.md#version)

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

[main.ts:138310](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L138310)

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

[main.ts:138332](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L138332)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksPageIntersectionLiveResponseInfo`](BacklinksPageIntersectionLiveResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksPageIntersectionLiveResponseInfo`](BacklinksPageIntersectionLiveResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:138325](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L138325)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")