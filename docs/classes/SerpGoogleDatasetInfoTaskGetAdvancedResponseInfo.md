[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo

# Class: SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`**

## Implements

- [`ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#cost)
- [status\_code](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#status_code)
- [status\_message](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#status_message)
- [tasks](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tasks_error)
- [time](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#time)
- [version](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#version)

### Methods

- [init](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#init)
- [toJSON](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tojson)
- [fromJS](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo**(`data?`): [`SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md) |

#### Returns

[`SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:52701](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52701)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[cost](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#cost)

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

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[status_code](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#status_code)

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

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[status_message](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleDatasetInfoTaskGetAdvancedTaskInfo`](SerpGoogleDatasetInfoTaskGetAdvancedTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[tasks](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tasks)

#### Defined in

[main.ts:52697](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52697)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[time](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md).[version](../interfaces/ISerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md#version)

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

[main.ts:52705](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52705)

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

[main.ts:52727](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52727)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo`](SerpGoogleDatasetInfoTaskGetAdvancedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:52720](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L52720)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")