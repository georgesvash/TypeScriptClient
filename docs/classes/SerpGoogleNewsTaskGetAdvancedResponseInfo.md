[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleNewsTaskGetAdvancedResponseInfo

# Class: SerpGoogleNewsTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleNewsTaskGetAdvancedResponseInfo`**

## Implements

- [`ISerpGoogleNewsTaskGetAdvancedResponseInfo`](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#time)
- [version](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#init)
- [toJSON](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](SerpGoogleNewsTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleNewsTaskGetAdvancedResponseInfo**(`data?`): [`SerpGoogleNewsTaskGetAdvancedResponseInfo`](SerpGoogleNewsTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleNewsTaskGetAdvancedResponseInfo`](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md) |

#### Returns

[`SerpGoogleNewsTaskGetAdvancedResponseInfo`](SerpGoogleNewsTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:42827](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42827)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[cost](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#cost)

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

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#status_code)

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

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleNewsTaskGetAdvancedTaskInfo`](SerpGoogleNewsTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:42823](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42823)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[time](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleNewsTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md).[version](../interfaces/ISerpGoogleNewsTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:42831](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42831)

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

[main.ts:42853](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42853)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleNewsTaskGetAdvancedResponseInfo`](SerpGoogleNewsTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleNewsTaskGetAdvancedResponseInfo`](SerpGoogleNewsTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:42846](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42846)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")