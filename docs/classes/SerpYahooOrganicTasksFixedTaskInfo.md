[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYahooOrganicTasksFixedTaskInfo

# Class: SerpYahooOrganicTasksFixedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpYahooOrganicTasksFixedTaskInfo`**

## Implements

- [`ISerpYahooOrganicTasksFixedTaskInfo`](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYahooOrganicTasksFixedTaskInfo.md#constructor)

### Properties

- [cost](SerpYahooOrganicTasksFixedTaskInfo.md#cost)
- [data](SerpYahooOrganicTasksFixedTaskInfo.md#data)
- [id](SerpYahooOrganicTasksFixedTaskInfo.md#id)
- [path](SerpYahooOrganicTasksFixedTaskInfo.md#path)
- [result](SerpYahooOrganicTasksFixedTaskInfo.md#result)
- [result\_count](SerpYahooOrganicTasksFixedTaskInfo.md#result_count)
- [status\_code](SerpYahooOrganicTasksFixedTaskInfo.md#status_code)
- [status\_message](SerpYahooOrganicTasksFixedTaskInfo.md#status_message)
- [time](SerpYahooOrganicTasksFixedTaskInfo.md#time)

### Methods

- [init](SerpYahooOrganicTasksFixedTaskInfo.md#init)
- [toJSON](SerpYahooOrganicTasksFixedTaskInfo.md#tojson)
- [fromJS](SerpYahooOrganicTasksFixedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYahooOrganicTasksFixedTaskInfo**(`data?`): [`SerpYahooOrganicTasksFixedTaskInfo`](SerpYahooOrganicTasksFixedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYahooOrganicTasksFixedTaskInfo`](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md) |

#### Returns

[`SerpYahooOrganicTasksFixedTaskInfo`](SerpYahooOrganicTasksFixedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:63618](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63618)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[cost](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#cost)

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

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[data](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#data)

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

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[id](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[path](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpYahooOrganicTasksFixedResultInfo`](SerpYahooOrganicTasksFixedResultInfo.md)[]

array of results

#### Implementation of

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[result](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#result)

#### Defined in

[main.ts:63614](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63614)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[result_count](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#result_count)

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

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[status_code](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#status_code)

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

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[status_message](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpYahooOrganicTasksFixedTaskInfo](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md).[time](../interfaces/ISerpYahooOrganicTasksFixedTaskInfo.md#time)

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

[main.ts:63622](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63622)

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

[main.ts:63644](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63644)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYahooOrganicTasksFixedTaskInfo`](SerpYahooOrganicTasksFixedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYahooOrganicTasksFixedTaskInfo`](SerpYahooOrganicTasksFixedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:63637](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L63637)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")