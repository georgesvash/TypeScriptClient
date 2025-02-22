[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleImagesTasksFixedResponseInfo

# Class: SerpGoogleImagesTasksFixedResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`SerpGoogleImagesTasksFixedResponseInfo`**

## Implements

- [`ISerpGoogleImagesTasksFixedResponseInfo`](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleImagesTasksFixedResponseInfo.md#constructor)

### Properties

- [cost](SerpGoogleImagesTasksFixedResponseInfo.md#cost)
- [status\_code](SerpGoogleImagesTasksFixedResponseInfo.md#status_code)
- [status\_message](SerpGoogleImagesTasksFixedResponseInfo.md#status_message)
- [tasks](SerpGoogleImagesTasksFixedResponseInfo.md#tasks)
- [tasks\_count](SerpGoogleImagesTasksFixedResponseInfo.md#tasks_count)
- [tasks\_error](SerpGoogleImagesTasksFixedResponseInfo.md#tasks_error)
- [time](SerpGoogleImagesTasksFixedResponseInfo.md#time)
- [version](SerpGoogleImagesTasksFixedResponseInfo.md#version)

### Methods

- [init](SerpGoogleImagesTasksFixedResponseInfo.md#init)
- [toJSON](SerpGoogleImagesTasksFixedResponseInfo.md#tojson)
- [fromJS](SerpGoogleImagesTasksFixedResponseInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleImagesTasksFixedResponseInfo**(`data?`): [`SerpGoogleImagesTasksFixedResponseInfo`](SerpGoogleImagesTasksFixedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleImagesTasksFixedResponseInfo`](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md) |

#### Returns

[`SerpGoogleImagesTasksFixedResponseInfo`](SerpGoogleImagesTasksFixedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:46045](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46045)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[cost](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#cost)

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

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[status_code](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#status_code)

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

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[status_message](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`SerpGoogleImagesTasksFixedTaskInfo`](SerpGoogleImagesTasksFixedTaskInfo.md)[]

array of tasks

#### Implementation of

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[tasks](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#tasks)

#### Defined in

[main.ts:46041](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46041)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[tasks_count](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[tasks_error](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[time](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[ISerpGoogleImagesTasksFixedResponseInfo](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md).[version](../interfaces/ISerpGoogleImagesTasksFixedResponseInfo.md#version)

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

[main.ts:46049](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46049)

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

[main.ts:46071](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46071)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleImagesTasksFixedResponseInfo`](SerpGoogleImagesTasksFixedResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleImagesTasksFixedResponseInfo`](SerpGoogleImagesTasksFixedResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:46064](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L46064)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")