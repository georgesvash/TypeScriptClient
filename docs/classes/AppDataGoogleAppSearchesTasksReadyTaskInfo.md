[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataGoogleAppSearchesTasksReadyTaskInfo

# Class: AppDataGoogleAppSearchesTasksReadyTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`AppDataGoogleAppSearchesTasksReadyTaskInfo`**

## Implements

- [`IAppDataGoogleAppSearchesTasksReadyTaskInfo`](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#constructor)

### Properties

- [cost](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#cost)
- [data](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#data)
- [id](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#id)
- [path](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#path)
- [result](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#result)
- [result\_count](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#result_count)
- [status\_code](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#status_code)
- [status\_message](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#status_message)
- [time](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#time)

### Methods

- [init](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#init)
- [toJSON](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#tojson)
- [fromJS](AppDataGoogleAppSearchesTasksReadyTaskInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataGoogleAppSearchesTasksReadyTaskInfo**(`data?`): [`AppDataGoogleAppSearchesTasksReadyTaskInfo`](AppDataGoogleAppSearchesTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataGoogleAppSearchesTasksReadyTaskInfo`](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md) |

#### Returns

[`AppDataGoogleAppSearchesTasksReadyTaskInfo`](AppDataGoogleAppSearchesTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:177690](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177690)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[cost](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#cost)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[cost](BaseResponseTaskInfo.md#cost)

#### Defined in

[main.ts:22602](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22602)

___


### data

• `Optional` **data**: `Object`

contains the same parameters that you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[data](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#data)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[data](BaseResponseTaskInfo.md#data)

#### Defined in

[main.ts:22608](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22608)

___


### id

• `Optional` **id**: `string`

task identifier
unique task identifier in our system in the UUID format

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[id](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[path](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`AppDataGoogleAppSearchesTasksReadyResultInfo`](AppDataGoogleAppSearchesTasksReadyResultInfo.md)[]

array of results

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[result](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#result)

#### Defined in

[main.ts:177686](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177686)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[result_count](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#result_count)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[result_count](BaseResponseTaskInfo.md#result_count)

#### Defined in

[main.ts:22604](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22604)

___


### status\_code

• `Optional` **status\_code**: `number`

status code of the task
generated by DataForSEO, can be within the following range: 10000-60000
you can find the full list of the response codes here

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[status_code](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#status_code)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_code](BaseResponseTaskInfo.md#status_code)

#### Defined in

[main.ts:22595](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22595)

___


### status\_message

• `Optional` **status\_message**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[status_message](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IAppDataGoogleAppSearchesTasksReadyTaskInfo](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md).[time](../interfaces/IAppDataGoogleAppSearchesTasksReadyTaskInfo.md#time)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[time](BaseResponseTaskInfo.md#time)

#### Defined in

[main.ts:22600](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22600)

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

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[init](BaseResponseTaskInfo.md#init)

#### Defined in

[main.ts:177694](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177694)

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

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[toJSON](BaseResponseTaskInfo.md#tojson)

#### Defined in

[main.ts:177716](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177716)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataGoogleAppSearchesTasksReadyTaskInfo`](AppDataGoogleAppSearchesTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataGoogleAppSearchesTasksReadyTaskInfo`](AppDataGoogleAppSearchesTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:177709](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L177709)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")