[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppSearchesTaskPostResponseInfo

# Class: AppDataGoogleAppSearchesTaskPostResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataGoogleAppSearchesTaskPostResponseInfo`**

## Implements

- [`IAppDataGoogleAppSearchesTaskPostResponseInfo`](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppSearchesTaskPostResponseInfo.md#constructor)

### Properties

- [cost](AppDataGoogleAppSearchesTaskPostResponseInfo.md#cost)
- [status\_code](AppDataGoogleAppSearchesTaskPostResponseInfo.md#status_code)
- [status\_message](AppDataGoogleAppSearchesTaskPostResponseInfo.md#status_message)
- [tasks](AppDataGoogleAppSearchesTaskPostResponseInfo.md#tasks)
- [tasks\_count](AppDataGoogleAppSearchesTaskPostResponseInfo.md#tasks_count)
- [tasks\_error](AppDataGoogleAppSearchesTaskPostResponseInfo.md#tasks_error)
- [time](AppDataGoogleAppSearchesTaskPostResponseInfo.md#time)
- [version](AppDataGoogleAppSearchesTaskPostResponseInfo.md#version)

### Methods

- [init](AppDataGoogleAppSearchesTaskPostResponseInfo.md#init)
- [toJSON](AppDataGoogleAppSearchesTaskPostResponseInfo.md#tojson)
- [fromJS](AppDataGoogleAppSearchesTaskPostResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppSearchesTaskPostResponseInfo**(`data?`): [`AppDataGoogleAppSearchesTaskPostResponseInfo`](AppDataGoogleAppSearchesTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppSearchesTaskPostResponseInfo`](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md) |

#### Returns

[`AppDataGoogleAppSearchesTaskPostResponseInfo`](AppDataGoogleAppSearchesTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:177551](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177551)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[cost](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#cost)

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

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[status_code](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#status_code)

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

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[status_message](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataGoogleAppSearchesTaskPostTaskInfo`](AppDataGoogleAppSearchesTaskPostTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[tasks](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#tasks)

#### Defined in

[main.ts:177547](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177547)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[tasks_count](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[tasks_error](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[time](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataGoogleAppSearchesTaskPostResponseInfo](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md).[version](../interfaces/IAppDataGoogleAppSearchesTaskPostResponseInfo.md#version)

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

[main.ts:177555](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177555)

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

[main.ts:177577](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177577)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppSearchesTaskPostResponseInfo`](AppDataGoogleAppSearchesTaskPostResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppSearchesTaskPostResponseInfo`](AppDataGoogleAppSearchesTaskPostResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:177570](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177570)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")