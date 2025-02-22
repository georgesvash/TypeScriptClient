[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo

# Class: SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`**

## Implements

- [`ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#cost)
- [data](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#data)
- [id](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#id)
- [path](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#path)
- [result](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#result)
- [result\_count](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#result_count)
- [status\_code](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#status_code)
- [status\_message](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#status_message)
- [time](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#time)

### Methods

- [init](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#init)
- [toJSON](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#tojson)
- [fromJS](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo**(`data?`): [`SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md) |

#### Returns

[`SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:51220](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51220)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[cost](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#cost)

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

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[data](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#data)

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

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[id](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[path](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpGoogleDatasetSearchTaskGetAdvancedResultInfo`](SerpGoogleDatasetSearchTaskGetAdvancedResultInfo.md)[]

array of results

#### Implementation of

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[result](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#result)

#### Defined in

[main.ts:51216](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51216)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[result_count](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#result_count)

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

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[status_code](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#status_code)

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

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[status_message](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md).[time](../interfaces/ISerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md#time)

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

[main.ts:51224](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51224)

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

[main.ts:51246](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51246)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo`](SerpGoogleDatasetSearchTaskGetAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:51239](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51239)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")