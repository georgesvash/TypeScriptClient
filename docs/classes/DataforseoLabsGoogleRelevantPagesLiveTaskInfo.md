[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsGoogleRelevantPagesLiveTaskInfo

# Class: DataforseoLabsGoogleRelevantPagesLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`DataforseoLabsGoogleRelevantPagesLiveTaskInfo`**

## Implements

- [`IDataforseoLabsGoogleRelevantPagesLiveTaskInfo`](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#constructor)

### Properties

- [cost](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#cost)
- [data](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#data)
- [id](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#id)
- [path](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#path)
- [result](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#result)
- [result\_count](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#result_count)
- [status\_code](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#status_code)
- [status\_message](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#status_message)
- [time](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#time)

### Methods

- [init](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#init)
- [toJSON](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#tojson)
- [fromJS](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsGoogleRelevantPagesLiveTaskInfo**(`data?`): [`DataforseoLabsGoogleRelevantPagesLiveTaskInfo`](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsGoogleRelevantPagesLiveTaskInfo`](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md) |

#### Returns

[`DataforseoLabsGoogleRelevantPagesLiveTaskInfo`](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:90378](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L90378)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[cost](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#cost)

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

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[data](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#data)

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

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[id](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[path](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`DataforseoLabsGoogleRelevantPagesLiveResultInfo`](DataforseoLabsGoogleRelevantPagesLiveResultInfo.md)[]

array of results

#### Implementation of

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[result](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#result)

#### Defined in

[main.ts:90374](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L90374)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[result_count](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#result_count)

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

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[status_code](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#status_code)

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

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[status_message](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IDataforseoLabsGoogleRelevantPagesLiveTaskInfo](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md).[time](../interfaces/IDataforseoLabsGoogleRelevantPagesLiveTaskInfo.md#time)

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

[main.ts:90382](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L90382)

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

[main.ts:90404](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L90404)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsGoogleRelevantPagesLiveTaskInfo`](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsGoogleRelevantPagesLiveTaskInfo`](DataforseoLabsGoogleRelevantPagesLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:90397](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L90397)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")