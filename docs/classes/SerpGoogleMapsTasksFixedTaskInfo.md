[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleMapsTasksFixedTaskInfo

# Class: SerpGoogleMapsTasksFixedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleMapsTasksFixedTaskInfo`**

## Implements

- [`ISerpGoogleMapsTasksFixedTaskInfo`](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleMapsTasksFixedTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleMapsTasksFixedTaskInfo.md#cost)
- [data](SerpGoogleMapsTasksFixedTaskInfo.md#data)
- [id](SerpGoogleMapsTasksFixedTaskInfo.md#id)
- [path](SerpGoogleMapsTasksFixedTaskInfo.md#path)
- [result](SerpGoogleMapsTasksFixedTaskInfo.md#result)
- [result\_count](SerpGoogleMapsTasksFixedTaskInfo.md#result_count)
- [status\_code](SerpGoogleMapsTasksFixedTaskInfo.md#status_code)
- [status\_message](SerpGoogleMapsTasksFixedTaskInfo.md#status_message)
- [time](SerpGoogleMapsTasksFixedTaskInfo.md#time)

### Methods

- [init](SerpGoogleMapsTasksFixedTaskInfo.md#init)
- [toJSON](SerpGoogleMapsTasksFixedTaskInfo.md#tojson)
- [fromJS](SerpGoogleMapsTasksFixedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleMapsTasksFixedTaskInfo**(`data?`): [`SerpGoogleMapsTasksFixedTaskInfo`](SerpGoogleMapsTasksFixedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleMapsTasksFixedTaskInfo`](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md) |

#### Returns

[`SerpGoogleMapsTasksFixedTaskInfo`](SerpGoogleMapsTasksFixedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:38104](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L38104)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[cost](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#cost)

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

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[data](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#data)

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

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[id](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[path](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpGoogleMapsTasksFixedResultInfo`](SerpGoogleMapsTasksFixedResultInfo.md)[]

array of results

#### Implementation of

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[result](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#result)

#### Defined in

[main.ts:38100](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L38100)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[result_count](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#result_count)

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

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[status_code](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#status_code)

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

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[status_message](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleMapsTasksFixedTaskInfo](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md).[time](../interfaces/ISerpGoogleMapsTasksFixedTaskInfo.md#time)

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

[main.ts:38108](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L38108)

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

[main.ts:38130](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L38130)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleMapsTasksFixedTaskInfo`](SerpGoogleMapsTasksFixedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleMapsTasksFixedTaskInfo`](SerpGoogleMapsTasksFixedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:38123](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L38123)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")