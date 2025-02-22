[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsBingRelevantPagesLiveTaskInfo

# Class: DataforseoLabsBingRelevantPagesLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`DataforseoLabsBingRelevantPagesLiveTaskInfo`**

## Implements

- [`IDataforseoLabsBingRelevantPagesLiveTaskInfo`](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#constructor)

### Properties

- [cost](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#cost)
- [data](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#data)
- [id](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#id)
- [path](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#path)
- [result](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#result)
- [result\_count](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#result_count)
- [status\_code](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#status_code)
- [status\_message](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#status_message)
- [time](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#time)

### Methods

- [init](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#init)
- [toJSON](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#tojson)
- [fromJS](DataforseoLabsBingRelevantPagesLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsBingRelevantPagesLiveTaskInfo**(`data?`): [`DataforseoLabsBingRelevantPagesLiveTaskInfo`](DataforseoLabsBingRelevantPagesLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsBingRelevantPagesLiveTaskInfo`](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md) |

#### Returns

[`DataforseoLabsBingRelevantPagesLiveTaskInfo`](DataforseoLabsBingRelevantPagesLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:106646](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106646)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[cost](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#cost)

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

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[data](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#data)

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

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[id](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[path](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`DataforseoLabsBingRelevantPagesLiveResultInfo`](DataforseoLabsBingRelevantPagesLiveResultInfo.md)[]

array of results

#### Implementation of

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[result](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#result)

#### Defined in

[main.ts:106642](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106642)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[result_count](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#result_count)

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

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[status_code](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#status_code)

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

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[status_message](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IDataforseoLabsBingRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md).[time](../interfaces/IDataforseoLabsBingRelevantPagesLiveTaskInfo.md#time)

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

[main.ts:106650](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106650)

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

[main.ts:106672](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106672)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsBingRelevantPagesLiveTaskInfo`](DataforseoLabsBingRelevantPagesLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsBingRelevantPagesLiveTaskInfo`](DataforseoLabsBingRelevantPagesLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:106665](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L106665)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")