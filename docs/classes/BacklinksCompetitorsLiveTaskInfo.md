[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksCompetitorsLiveTaskInfo

# Class: BacklinksCompetitorsLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BacklinksCompetitorsLiveTaskInfo`**

## Implements

- [`IBacklinksCompetitorsLiveTaskInfo`](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksCompetitorsLiveTaskInfo.md#constructor)

### Properties

- [cost](BacklinksCompetitorsLiveTaskInfo.md#cost)
- [data](BacklinksCompetitorsLiveTaskInfo.md#data)
- [id](BacklinksCompetitorsLiveTaskInfo.md#id)
- [path](BacklinksCompetitorsLiveTaskInfo.md#path)
- [result](BacklinksCompetitorsLiveTaskInfo.md#result)
- [result\_count](BacklinksCompetitorsLiveTaskInfo.md#result_count)
- [status\_code](BacklinksCompetitorsLiveTaskInfo.md#status_code)
- [status\_message](BacklinksCompetitorsLiveTaskInfo.md#status_message)
- [time](BacklinksCompetitorsLiveTaskInfo.md#time)

### Methods

- [init](BacklinksCompetitorsLiveTaskInfo.md#init)
- [toJSON](BacklinksCompetitorsLiveTaskInfo.md#tojson)
- [fromJS](BacklinksCompetitorsLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksCompetitorsLiveTaskInfo**(`data?`): [`BacklinksCompetitorsLiveTaskInfo`](BacklinksCompetitorsLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksCompetitorsLiveTaskInfo`](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md) |

#### Returns

[`BacklinksCompetitorsLiveTaskInfo`](BacklinksCompetitorsLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:136269](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L136269)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[cost](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#cost)

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

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[data](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#data)

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

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[id](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[path](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BacklinksCompetitorsLiveResultInfo`](BacklinksCompetitorsLiveResultInfo.md)[]

array of results

#### Implementation of

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[result](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#result)

#### Defined in

[main.ts:136265](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L136265)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[result_count](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#result_count)

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

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[status_code](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#status_code)

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

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[status_message](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBacklinksCompetitorsLiveTaskInfo](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md).[time](../interfaces/IBacklinksCompetitorsLiveTaskInfo.md#time)

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

[main.ts:136273](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L136273)

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

[main.ts:136295](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L136295)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksCompetitorsLiveTaskInfo`](BacklinksCompetitorsLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksCompetitorsLiveTaskInfo`](BacklinksCompetitorsLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:136288](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L136288)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")