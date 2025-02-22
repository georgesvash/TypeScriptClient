[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksIndexResponseInfo

# Class: BacklinksIndexResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BacklinksIndexResponseInfo`**

## Implements

- [`IBacklinksIndexResponseInfo`](../interfaces/IBacklinksIndexResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksIndexResponseInfo.md#constructor)

### Properties

- [cost](BacklinksIndexResponseInfo.md#cost)
- [status\_code](BacklinksIndexResponseInfo.md#status_code)
- [status\_message](BacklinksIndexResponseInfo.md#status_message)
- [tasks](BacklinksIndexResponseInfo.md#tasks)
- [tasks\_count](BacklinksIndexResponseInfo.md#tasks_count)
- [tasks\_error](BacklinksIndexResponseInfo.md#tasks_error)
- [time](BacklinksIndexResponseInfo.md#time)
- [version](BacklinksIndexResponseInfo.md#version)

### Methods

- [init](BacklinksIndexResponseInfo.md#init)
- [toJSON](BacklinksIndexResponseInfo.md#tojson)
- [fromJS](BacklinksIndexResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksIndexResponseInfo**(`data?`): [`BacklinksIndexResponseInfo`](BacklinksIndexResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksIndexResponseInfo`](../interfaces/IBacklinksIndexResponseInfo.md) |

#### Returns

[`BacklinksIndexResponseInfo`](BacklinksIndexResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:129148](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129148)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[cost](../interfaces/IBacklinksIndexResponseInfo.md#cost)

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

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[status_code](../interfaces/IBacklinksIndexResponseInfo.md#status_code)

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

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[status_message](../interfaces/IBacklinksIndexResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BacklinksIndexTaskInfo`](BacklinksIndexTaskInfo.md)[]

array of tasks

#### Implementation of

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[tasks](../interfaces/IBacklinksIndexResponseInfo.md#tasks)

#### Defined in

[main.ts:129144](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129144)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[tasks_count](../interfaces/IBacklinksIndexResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[tasks_error](../interfaces/IBacklinksIndexResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[time](../interfaces/IBacklinksIndexResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBacklinksIndexResponseInfo](../interfaces/IBacklinksIndexResponseInfo.md).[version](../interfaces/IBacklinksIndexResponseInfo.md#version)

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

[main.ts:129152](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129152)

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

[main.ts:129174](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129174)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksIndexResponseInfo`](BacklinksIndexResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksIndexResponseInfo`](BacklinksIndexResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:129167](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L129167)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")