[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksDomainPagesLiveTaskInfo

# Class: BacklinksDomainPagesLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BacklinksDomainPagesLiveTaskInfo`**

## Implements

- [`IBacklinksDomainPagesLiveTaskInfo`](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksDomainPagesLiveTaskInfo.md#constructor)

### Properties

- [cost](BacklinksDomainPagesLiveTaskInfo.md#cost)
- [data](BacklinksDomainPagesLiveTaskInfo.md#data)
- [id](BacklinksDomainPagesLiveTaskInfo.md#id)
- [path](BacklinksDomainPagesLiveTaskInfo.md#path)
- [result](BacklinksDomainPagesLiveTaskInfo.md#result)
- [result\_count](BacklinksDomainPagesLiveTaskInfo.md#result_count)
- [status\_code](BacklinksDomainPagesLiveTaskInfo.md#status_code)
- [status\_message](BacklinksDomainPagesLiveTaskInfo.md#status_message)
- [time](BacklinksDomainPagesLiveTaskInfo.md#time)

### Methods

- [init](BacklinksDomainPagesLiveTaskInfo.md#init)
- [toJSON](BacklinksDomainPagesLiveTaskInfo.md#tojson)
- [fromJS](BacklinksDomainPagesLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksDomainPagesLiveTaskInfo**(`data?`): [`BacklinksDomainPagesLiveTaskInfo`](BacklinksDomainPagesLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksDomainPagesLiveTaskInfo`](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md) |

#### Returns

[`BacklinksDomainPagesLiveTaskInfo`](BacklinksDomainPagesLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:133503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L133503)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[cost](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#cost)

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

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[data](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#data)

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

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[id](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[path](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BacklinksDomainPagesLiveResultInfo`](BacklinksDomainPagesLiveResultInfo.md)[]

array of results

#### Implementation of

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[result](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#result)

#### Defined in

[main.ts:133499](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L133499)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[result_count](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#result_count)

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

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[status_code](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#status_code)

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

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[status_message](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBacklinksDomainPagesLiveTaskInfo](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md).[time](../interfaces/IBacklinksDomainPagesLiveTaskInfo.md#time)

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

[main.ts:133507](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L133507)

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

[main.ts:133529](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L133529)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksDomainPagesLiveTaskInfo`](BacklinksDomainPagesLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksDomainPagesLiveTaskInfo`](BacklinksDomainPagesLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:133522](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L133522)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")