[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksAvailableFiltersTaskInfo

# Class: BacklinksAvailableFiltersTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BacklinksAvailableFiltersTaskInfo`**

## Implements

- [`IBacklinksAvailableFiltersTaskInfo`](../interfaces/IBacklinksAvailableFiltersTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksAvailableFiltersTaskInfo.md#constructor)

### Properties

- [cost](BacklinksAvailableFiltersTaskInfo.md#cost)
- [data](BacklinksAvailableFiltersTaskInfo.md#data)
- [id](BacklinksAvailableFiltersTaskInfo.md#id)
- [path](BacklinksAvailableFiltersTaskInfo.md#path)
- [result](BacklinksAvailableFiltersTaskInfo.md#result)
- [result\_count](BacklinksAvailableFiltersTaskInfo.md#result_count)
- [status\_code](BacklinksAvailableFiltersTaskInfo.md#status_code)
- [status\_message](BacklinksAvailableFiltersTaskInfo.md#status_message)
- [time](BacklinksAvailableFiltersTaskInfo.md#time)

### Methods

- [init](BacklinksAvailableFiltersTaskInfo.md#init)
- [toJSON](BacklinksAvailableFiltersTaskInfo.md#tojson)
- [fromJS](BacklinksAvailableFiltersTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksAvailableFiltersTaskInfo**(`data?`): [`BacklinksAvailableFiltersTaskInfo`](BacklinksAvailableFiltersTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksAvailableFiltersTaskInfo`](../interfaces/IBacklinksAvailableFiltersTaskInfo.md) |

#### Returns

[`BacklinksAvailableFiltersTaskInfo`](BacklinksAvailableFiltersTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:128836](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128836)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[cost](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#cost)

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

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[data](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#data)

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

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[id](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[path](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BacklinksAvailableFiltersResultInfo`](BacklinksAvailableFiltersResultInfo.md)[]

#### Implementation of

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[result](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#result)

#### Defined in

[main.ts:128832](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128832)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[result_count](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#result_count)

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

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[status_code](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#status_code)

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

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[status_message](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBacklinksAvailableFiltersTaskInfo](../interfaces/IBacklinksAvailableFiltersTaskInfo.md).[time](../interfaces/IBacklinksAvailableFiltersTaskInfo.md#time)

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

[main.ts:128840](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128840)

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

[main.ts:128862](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128862)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksAvailableFiltersTaskInfo`](BacklinksAvailableFiltersTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksAvailableFiltersTaskInfo`](BacklinksAvailableFiltersTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:128855](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L128855)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")