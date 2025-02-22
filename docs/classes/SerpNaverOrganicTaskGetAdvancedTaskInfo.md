[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpNaverOrganicTaskGetAdvancedTaskInfo

# Class: SerpNaverOrganicTaskGetAdvancedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpNaverOrganicTaskGetAdvancedTaskInfo`**

## Implements

- [`ISerpNaverOrganicTaskGetAdvancedTaskInfo`](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#constructor)

### Properties

- [cost](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#cost)
- [data](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#data)
- [id](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#id)
- [path](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#path)
- [result](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#result)
- [result\_count](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#result_count)
- [status\_code](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#status_code)
- [status\_message](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#status_message)
- [time](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#time)

### Methods

- [init](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#init)
- [toJSON](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#tojson)
- [fromJS](SerpNaverOrganicTaskGetAdvancedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpNaverOrganicTaskGetAdvancedTaskInfo**(`data?`): [`SerpNaverOrganicTaskGetAdvancedTaskInfo`](SerpNaverOrganicTaskGetAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpNaverOrganicTaskGetAdvancedTaskInfo`](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md) |

#### Returns

[`SerpNaverOrganicTaskGetAdvancedTaskInfo`](SerpNaverOrganicTaskGetAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:68430](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L68430)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[cost](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#cost)

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

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[data](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#data)

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

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[id](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[path](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpNaverOrganicTaskGetAdvancedResultInfo`](SerpNaverOrganicTaskGetAdvancedResultInfo.md)[]

array of results

#### Implementation of

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[result](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#result)

#### Defined in

[main.ts:68426](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L68426)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[result_count](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#result_count)

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

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[status_code](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#status_code)

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

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[status_message](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpNaverOrganicTaskGetAdvancedTaskInfo](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md).[time](../interfaces/ISerpNaverOrganicTaskGetAdvancedTaskInfo.md#time)

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

[main.ts:68434](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L68434)

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

[main.ts:68456](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L68456)

___


### fromJS

▸ **fromJS**(`data`): [`SerpNaverOrganicTaskGetAdvancedTaskInfo`](SerpNaverOrganicTaskGetAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpNaverOrganicTaskGetAdvancedTaskInfo`](SerpNaverOrganicTaskGetAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:68449](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L68449)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")