[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleLanguagesResponseInfo

# Class: AppDataAppleLanguagesResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`AppDataAppleLanguagesResponseInfo`**

## Implements

- [`IAppDataAppleLanguagesResponseInfo`](../interfaces/IAppDataAppleLanguagesResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleLanguagesResponseInfo.md#constructor)

### Properties

- [cost](AppDataAppleLanguagesResponseInfo.md#cost)
- [status\_code](AppDataAppleLanguagesResponseInfo.md#status_code)
- [status\_message](AppDataAppleLanguagesResponseInfo.md#status_message)
- [tasks](AppDataAppleLanguagesResponseInfo.md#tasks)
- [tasks\_count](AppDataAppleLanguagesResponseInfo.md#tasks_count)
- [tasks\_error](AppDataAppleLanguagesResponseInfo.md#tasks_error)
- [time](AppDataAppleLanguagesResponseInfo.md#time)
- [version](AppDataAppleLanguagesResponseInfo.md#version)

### Methods

- [init](AppDataAppleLanguagesResponseInfo.md#init)
- [toJSON](AppDataAppleLanguagesResponseInfo.md#tojson)
- [fromJS](AppDataAppleLanguagesResponseInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleLanguagesResponseInfo**(`data?`): [`AppDataAppleLanguagesResponseInfo`](AppDataAppleLanguagesResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleLanguagesResponseInfo`](../interfaces/IAppDataAppleLanguagesResponseInfo.md) |

#### Returns

[`AppDataAppleLanguagesResponseInfo`](AppDataAppleLanguagesResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:183045](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183045)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[cost](../interfaces/IAppDataAppleLanguagesResponseInfo.md#cost)

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

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[status_code](../interfaces/IAppDataAppleLanguagesResponseInfo.md#status_code)

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

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[status_message](../interfaces/IAppDataAppleLanguagesResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`AppDataAppleLanguagesTaskInfo`](AppDataAppleLanguagesTaskInfo.md)[]

array of tasks

#### Implementation of

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[tasks](../interfaces/IAppDataAppleLanguagesResponseInfo.md#tasks)

#### Defined in

[main.ts:183041](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183041)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[tasks_count](../interfaces/IAppDataAppleLanguagesResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[tasks_error](../interfaces/IAppDataAppleLanguagesResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[time](../interfaces/IAppDataAppleLanguagesResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IAppDataAppleLanguagesResponseInfo](../interfaces/IAppDataAppleLanguagesResponseInfo.md).[version](../interfaces/IAppDataAppleLanguagesResponseInfo.md#version)

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

[main.ts:183049](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183049)

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

[main.ts:183071](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183071)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleLanguagesResponseInfo`](AppDataAppleLanguagesResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleLanguagesResponseInfo`](AppDataAppleLanguagesResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:183064](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L183064)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")