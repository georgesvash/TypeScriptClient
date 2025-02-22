[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageSummaryTaskInfo

# Class: OnPageSummaryTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`OnPageSummaryTaskInfo`**

## Implements

- [`IOnPageSummaryTaskInfo`](../interfaces/IOnPageSummaryTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageSummaryTaskInfo.md#constructor)

### Properties

- [cost](OnPageSummaryTaskInfo.md#cost)
- [data](OnPageSummaryTaskInfo.md#data)
- [id](OnPageSummaryTaskInfo.md#id)
- [path](OnPageSummaryTaskInfo.md#path)
- [result](OnPageSummaryTaskInfo.md#result)
- [result\_count](OnPageSummaryTaskInfo.md#result_count)
- [status\_code](OnPageSummaryTaskInfo.md#status_code)
- [status\_message](OnPageSummaryTaskInfo.md#status_message)
- [time](OnPageSummaryTaskInfo.md#time)

### Methods

- [init](OnPageSummaryTaskInfo.md#init)
- [toJSON](OnPageSummaryTaskInfo.md#tojson)
- [fromJS](OnPageSummaryTaskInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageSummaryTaskInfo**(`data?`): [`OnPageSummaryTaskInfo`](OnPageSummaryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageSummaryTaskInfo`](../interfaces/IOnPageSummaryTaskInfo.md) |

#### Returns

[`OnPageSummaryTaskInfo`](OnPageSummaryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:143775](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L143775)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[cost](../interfaces/IOnPageSummaryTaskInfo.md#cost)

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

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[data](../interfaces/IOnPageSummaryTaskInfo.md#data)

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

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[id](../interfaces/IOnPageSummaryTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[path](../interfaces/IOnPageSummaryTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`OnPageSummaryResultInfo`](OnPageSummaryResultInfo.md)[]

array of results

#### Implementation of

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[result](../interfaces/IOnPageSummaryTaskInfo.md#result)

#### Defined in

[main.ts:143771](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L143771)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[result_count](../interfaces/IOnPageSummaryTaskInfo.md#result_count)

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

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[status_code](../interfaces/IOnPageSummaryTaskInfo.md#status_code)

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

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[status_message](../interfaces/IOnPageSummaryTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IOnPageSummaryTaskInfo](../interfaces/IOnPageSummaryTaskInfo.md).[time](../interfaces/IOnPageSummaryTaskInfo.md#time)

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

[main.ts:143779](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L143779)

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

[main.ts:143801](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L143801)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageSummaryTaskInfo`](OnPageSummaryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageSummaryTaskInfo`](OnPageSummaryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:143794](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L143794)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")