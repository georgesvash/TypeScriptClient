[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBaiduOrganicTaskGetAdvancedTaskInfo

# Class: SerpBaiduOrganicTaskGetAdvancedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpBaiduOrganicTaskGetAdvancedTaskInfo`**

## Implements

- [`ISerpBaiduOrganicTaskGetAdvancedTaskInfo`](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#constructor)

### Properties

- [cost](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#cost)
- [data](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#data)
- [id](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#id)
- [path](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#path)
- [result](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#result)
- [result\_count](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#result_count)
- [status\_code](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#status_code)
- [status\_message](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#status_message)
- [time](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#time)

### Methods

- [init](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#init)
- [toJSON](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#tojson)
- [fromJS](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBaiduOrganicTaskGetAdvancedTaskInfo**(`data?`): [`SerpBaiduOrganicTaskGetAdvancedTaskInfo`](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBaiduOrganicTaskGetAdvancedTaskInfo`](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md) |

#### Returns

[`SerpBaiduOrganicTaskGetAdvancedTaskInfo`](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:67156](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L67156)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[cost](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#cost)

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

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[data](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#data)

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

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[id](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[path](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpBaiduOrganicTaskGetAdvancedResultInfo`](SerpBaiduOrganicTaskGetAdvancedResultInfo.md)[]

array of results

#### Implementation of

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[result](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#result)

#### Defined in

[main.ts:67152](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L67152)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[result_count](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#result_count)

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

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[status_code](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#status_code)

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

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[status_message](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpBaiduOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md).[time](../interfaces/ISerpBaiduOrganicTaskGetAdvancedTaskInfo.md#time)

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

[main.ts:67160](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L67160)

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

[main.ts:67182](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L67182)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBaiduOrganicTaskGetAdvancedTaskInfo`](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBaiduOrganicTaskGetAdvancedTaskInfo`](SerpBaiduOrganicTaskGetAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:67175](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L67175)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")