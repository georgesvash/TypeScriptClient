[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleNewsTasksFixedTaskInfo

# Class: SerpGoogleNewsTasksFixedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleNewsTasksFixedTaskInfo`**

## Implements

- [`ISerpGoogleNewsTasksFixedTaskInfo`](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleNewsTasksFixedTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleNewsTasksFixedTaskInfo.md#cost)
- [data](SerpGoogleNewsTasksFixedTaskInfo.md#data)
- [id](SerpGoogleNewsTasksFixedTaskInfo.md#id)
- [path](SerpGoogleNewsTasksFixedTaskInfo.md#path)
- [result](SerpGoogleNewsTasksFixedTaskInfo.md#result)
- [result\_count](SerpGoogleNewsTasksFixedTaskInfo.md#result_count)
- [status\_code](SerpGoogleNewsTasksFixedTaskInfo.md#status_code)
- [status\_message](SerpGoogleNewsTasksFixedTaskInfo.md#status_message)
- [time](SerpGoogleNewsTasksFixedTaskInfo.md#time)

### Methods

- [init](SerpGoogleNewsTasksFixedTaskInfo.md#init)
- [toJSON](SerpGoogleNewsTasksFixedTaskInfo.md#tojson)
- [fromJS](SerpGoogleNewsTasksFixedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleNewsTasksFixedTaskInfo**(`data?`): [`SerpGoogleNewsTasksFixedTaskInfo`](SerpGoogleNewsTasksFixedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleNewsTasksFixedTaskInfo`](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md) |

#### Returns

[`SerpGoogleNewsTasksFixedTaskInfo`](SerpGoogleNewsTasksFixedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:42384](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42384)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[cost](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#cost)

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

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[data](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#data)

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

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[id](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[path](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpGoogleNewsTasksFixedResultInfo`](SerpGoogleNewsTasksFixedResultInfo.md)[]

array of results

#### Implementation of

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[result](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#result)

#### Defined in

[main.ts:42380](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42380)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[result_count](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#result_count)

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

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[status_code](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#status_code)

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

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[status_message](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleNewsTasksFixedTaskInfo](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md).[time](../interfaces/ISerpGoogleNewsTasksFixedTaskInfo.md#time)

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

[main.ts:42388](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42388)

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

[main.ts:42410](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42410)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleNewsTasksFixedTaskInfo`](SerpGoogleNewsTasksFixedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleNewsTasksFixedTaskInfo`](SerpGoogleNewsTasksFixedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:42403](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L42403)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")