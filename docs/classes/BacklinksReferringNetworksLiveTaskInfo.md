[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksReferringNetworksLiveTaskInfo

# Class: BacklinksReferringNetworksLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BacklinksReferringNetworksLiveTaskInfo`**

## Implements

- [`IBacklinksReferringNetworksLiveTaskInfo`](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksReferringNetworksLiveTaskInfo.md#constructor)

### Properties

- [cost](BacklinksReferringNetworksLiveTaskInfo.md#cost)
- [data](BacklinksReferringNetworksLiveTaskInfo.md#data)
- [id](BacklinksReferringNetworksLiveTaskInfo.md#id)
- [path](BacklinksReferringNetworksLiveTaskInfo.md#path)
- [result](BacklinksReferringNetworksLiveTaskInfo.md#result)
- [result\_count](BacklinksReferringNetworksLiveTaskInfo.md#result_count)
- [status\_code](BacklinksReferringNetworksLiveTaskInfo.md#status_code)
- [status\_message](BacklinksReferringNetworksLiveTaskInfo.md#status_message)
- [time](BacklinksReferringNetworksLiveTaskInfo.md#time)

### Methods

- [init](BacklinksReferringNetworksLiveTaskInfo.md#init)
- [toJSON](BacklinksReferringNetworksLiveTaskInfo.md#tojson)
- [fromJS](BacklinksReferringNetworksLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksReferringNetworksLiveTaskInfo**(`data?`): [`BacklinksReferringNetworksLiveTaskInfo`](BacklinksReferringNetworksLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksReferringNetworksLiveTaskInfo`](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md) |

#### Returns

[`BacklinksReferringNetworksLiveTaskInfo`](BacklinksReferringNetworksLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:135821](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135821)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[cost](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#cost)

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

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[data](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#data)

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

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[id](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[path](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BacklinksReferringNetworksLiveResultInfo`](BacklinksReferringNetworksLiveResultInfo.md)[]

array of results

#### Implementation of

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[result](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#result)

#### Defined in

[main.ts:135817](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135817)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[result_count](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#result_count)

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

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[status_code](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#status_code)

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

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[status_message](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBacklinksReferringNetworksLiveTaskInfo](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md).[time](../interfaces/IBacklinksReferringNetworksLiveTaskInfo.md#time)

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

[main.ts:135825](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135825)

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

[main.ts:135847](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135847)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksReferringNetworksLiveTaskInfo`](BacklinksReferringNetworksLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksReferringNetworksLiveTaskInfo`](BacklinksReferringNetworksLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:135840](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L135840)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")