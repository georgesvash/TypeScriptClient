[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBaiduOrganicTasksReadyTaskInfo

# Class: SerpBaiduOrganicTasksReadyTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpBaiduOrganicTasksReadyTaskInfo`**

## Implements

- [`ISerpBaiduOrganicTasksReadyTaskInfo`](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBaiduOrganicTasksReadyTaskInfo.md#constructor)

### Properties

- [cost](SerpBaiduOrganicTasksReadyTaskInfo.md#cost)
- [data](SerpBaiduOrganicTasksReadyTaskInfo.md#data)
- [id](SerpBaiduOrganicTasksReadyTaskInfo.md#id)
- [path](SerpBaiduOrganicTasksReadyTaskInfo.md#path)
- [result](SerpBaiduOrganicTasksReadyTaskInfo.md#result)
- [result\_count](SerpBaiduOrganicTasksReadyTaskInfo.md#result_count)
- [status\_code](SerpBaiduOrganicTasksReadyTaskInfo.md#status_code)
- [status\_message](SerpBaiduOrganicTasksReadyTaskInfo.md#status_message)
- [time](SerpBaiduOrganicTasksReadyTaskInfo.md#time)

### Methods

- [init](SerpBaiduOrganicTasksReadyTaskInfo.md#init)
- [toJSON](SerpBaiduOrganicTasksReadyTaskInfo.md#tojson)
- [fromJS](SerpBaiduOrganicTasksReadyTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBaiduOrganicTasksReadyTaskInfo**(`data?`): [`SerpBaiduOrganicTasksReadyTaskInfo`](SerpBaiduOrganicTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBaiduOrganicTasksReadyTaskInfo`](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md) |

#### Returns

[`SerpBaiduOrganicTasksReadyTaskInfo`](SerpBaiduOrganicTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:66276](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66276)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[cost](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#cost)

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

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[data](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#data)

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

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[id](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[path](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpBaiduOrganicTasksReadyResultInfo`](SerpBaiduOrganicTasksReadyResultInfo.md)[]

array of results

#### Implementation of

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[result](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#result)

#### Defined in

[main.ts:66272](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66272)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[result_count](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#result_count)

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

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[status_code](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#status_code)

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

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[status_message](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpBaiduOrganicTasksReadyTaskInfo](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md).[time](../interfaces/ISerpBaiduOrganicTasksReadyTaskInfo.md#time)

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

[main.ts:66280](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66280)

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

[main.ts:66302](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66302)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBaiduOrganicTasksReadyTaskInfo`](SerpBaiduOrganicTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBaiduOrganicTasksReadyTaskInfo`](SerpBaiduOrganicTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:66295](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L66295)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")