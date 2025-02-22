[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppDataAppleAppInfoTaskPostTaskInfo

# Class: AppDataAppleAppInfoTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`AppDataAppleAppInfoTaskPostTaskInfo`**

## Implements

- [`IAppDataAppleAppInfoTaskPostTaskInfo`](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppDataAppleAppInfoTaskPostTaskInfo.md#constructor)

### Properties

- [cost](AppDataAppleAppInfoTaskPostTaskInfo.md#cost)
- [data](AppDataAppleAppInfoTaskPostTaskInfo.md#data)
- [id](AppDataAppleAppInfoTaskPostTaskInfo.md#id)
- [path](AppDataAppleAppInfoTaskPostTaskInfo.md#path)
- [result](AppDataAppleAppInfoTaskPostTaskInfo.md#result)
- [result\_count](AppDataAppleAppInfoTaskPostTaskInfo.md#result_count)
- [status\_code](AppDataAppleAppInfoTaskPostTaskInfo.md#status_code)
- [status\_message](AppDataAppleAppInfoTaskPostTaskInfo.md#status_message)
- [time](AppDataAppleAppInfoTaskPostTaskInfo.md#time)

### Methods

- [init](AppDataAppleAppInfoTaskPostTaskInfo.md#init)
- [toJSON](AppDataAppleAppInfoTaskPostTaskInfo.md#tojson)
- [fromJS](AppDataAppleAppInfoTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new AppDataAppleAppInfoTaskPostTaskInfo**(`data?`): [`AppDataAppleAppInfoTaskPostTaskInfo`](AppDataAppleAppInfoTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppDataAppleAppInfoTaskPostTaskInfo`](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md) |

#### Returns

[`AppDataAppleAppInfoTaskPostTaskInfo`](AppDataAppleAppInfoTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:184077](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184077)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[cost](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#cost)

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

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[data](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#data)

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

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[id](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[path](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#path)

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

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[result](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:184073](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184073)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[result_count](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#result_count)

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

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[status_code](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#status_code)

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

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[status_message](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IAppDataAppleAppInfoTaskPostTaskInfo](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md).[time](../interfaces/IAppDataAppleAppInfoTaskPostTaskInfo.md#time)

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

[main.ts:184081](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184081)

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

[main.ts:184099](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184099)

___


### fromJS

▸ **fromJS**(`data`): [`AppDataAppleAppInfoTaskPostTaskInfo`](AppDataAppleAppInfoTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppDataAppleAppInfoTaskPostTaskInfo`](AppDataAppleAppInfoTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:184092](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L184092)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")