[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleAppListTaskPostTaskInfo

# Class: AppDataAppleAppListTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`AppDataAppleAppListTaskPostTaskInfo`**

## Implements

- [`IAppDataAppleAppListTaskPostTaskInfo`](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleAppListTaskPostTaskInfo.md#constructor)

### Properties

- [cost](AppDataAppleAppListTaskPostTaskInfo.md#cost)
- [data](AppDataAppleAppListTaskPostTaskInfo.md#data)
- [id](AppDataAppleAppListTaskPostTaskInfo.md#id)
- [path](AppDataAppleAppListTaskPostTaskInfo.md#path)
- [result](AppDataAppleAppListTaskPostTaskInfo.md#result)
- [result\_count](AppDataAppleAppListTaskPostTaskInfo.md#result_count)
- [status\_code](AppDataAppleAppListTaskPostTaskInfo.md#status_code)
- [status\_message](AppDataAppleAppListTaskPostTaskInfo.md#status_message)
- [time](AppDataAppleAppListTaskPostTaskInfo.md#time)

### Methods

- [init](AppDataAppleAppListTaskPostTaskInfo.md#init)
- [toJSON](AppDataAppleAppListTaskPostTaskInfo.md#tojson)
- [fromJS](AppDataAppleAppListTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleAppListTaskPostTaskInfo**(`data?`): [`AppDataAppleAppListTaskPostTaskInfo`](AppDataAppleAppListTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleAppListTaskPostTaskInfo`](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md) |

#### Returns

[`AppDataAppleAppListTaskPostTaskInfo`](AppDataAppleAppListTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:185133](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185133)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[cost](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#cost)

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

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[data](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#data)

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

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[id](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[path](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: `any`

array of results
in this case, the value will be null

#### Implementation of

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[result](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:185129](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185129)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[result_count](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#result_count)

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

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[status_code](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#status_code)

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

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[status_message](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IAppDataAppleAppListTaskPostTaskInfo](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md).[time](../interfaces/IAppDataAppleAppListTaskPostTaskInfo.md#time)

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

[main.ts:185137](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185137)

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

[main.ts:185155](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185155)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleAppListTaskPostTaskInfo`](AppDataAppleAppListTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleAppListTaskPostTaskInfo`](AppDataAppleAppListTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:185148](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L185148)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")