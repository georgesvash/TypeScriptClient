[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksBulkBacklinksLiveTaskInfo

# Class: BacklinksBulkBacklinksLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BacklinksBulkBacklinksLiveTaskInfo`**

## Implements

- [`IBacklinksBulkBacklinksLiveTaskInfo`](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksBulkBacklinksLiveTaskInfo.md#constructor)

### Properties

- [cost](BacklinksBulkBacklinksLiveTaskInfo.md#cost)
- [data](BacklinksBulkBacklinksLiveTaskInfo.md#data)
- [id](BacklinksBulkBacklinksLiveTaskInfo.md#id)
- [path](BacklinksBulkBacklinksLiveTaskInfo.md#path)
- [result](BacklinksBulkBacklinksLiveTaskInfo.md#result)
- [result\_count](BacklinksBulkBacklinksLiveTaskInfo.md#result_count)
- [status\_code](BacklinksBulkBacklinksLiveTaskInfo.md#status_code)
- [status\_message](BacklinksBulkBacklinksLiveTaskInfo.md#status_message)
- [time](BacklinksBulkBacklinksLiveTaskInfo.md#time)

### Methods

- [init](BacklinksBulkBacklinksLiveTaskInfo.md#init)
- [toJSON](BacklinksBulkBacklinksLiveTaskInfo.md#tojson)
- [fromJS](BacklinksBulkBacklinksLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksBulkBacklinksLiveTaskInfo**(`data?`): [`BacklinksBulkBacklinksLiveTaskInfo`](BacklinksBulkBacklinksLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksBulkBacklinksLiveTaskInfo`](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md) |

#### Returns

[`BacklinksBulkBacklinksLiveTaskInfo`](BacklinksBulkBacklinksLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:139869](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139869)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[cost](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#cost)

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

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[data](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#data)

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

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[id](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[path](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BacklinksBulkBacklinksLiveResultInfo`](BacklinksBulkBacklinksLiveResultInfo.md)[]

array of results

#### Implementation of

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[result](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#result)

#### Defined in

[main.ts:139865](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139865)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[result_count](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#result_count)

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

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[status_code](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#status_code)

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

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[status_message](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBacklinksBulkBacklinksLiveTaskInfo](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md).[time](../interfaces/IBacklinksBulkBacklinksLiveTaskInfo.md#time)

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

[main.ts:139873](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139873)

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

[main.ts:139895](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139895)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksBulkBacklinksLiveTaskInfo`](BacklinksBulkBacklinksLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksBulkBacklinksLiveTaskInfo`](BacklinksBulkBacklinksLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:139888](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L139888)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")