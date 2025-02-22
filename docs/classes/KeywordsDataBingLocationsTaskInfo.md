[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataBingLocationsTaskInfo

# Class: KeywordsDataBingLocationsTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`KeywordsDataBingLocationsTaskInfo`**

## Implements

- [`IKeywordsDataBingLocationsTaskInfo`](../interfaces/IKeywordsDataBingLocationsTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataBingLocationsTaskInfo.md#constructor)

### Properties

- [cost](KeywordsDataBingLocationsTaskInfo.md#cost)
- [data](KeywordsDataBingLocationsTaskInfo.md#data)
- [id](KeywordsDataBingLocationsTaskInfo.md#id)
- [path](KeywordsDataBingLocationsTaskInfo.md#path)
- [result](KeywordsDataBingLocationsTaskInfo.md#result)
- [result\_count](KeywordsDataBingLocationsTaskInfo.md#result_count)
- [status\_code](KeywordsDataBingLocationsTaskInfo.md#status_code)
- [status\_message](KeywordsDataBingLocationsTaskInfo.md#status_message)
- [time](KeywordsDataBingLocationsTaskInfo.md#time)

### Methods

- [init](KeywordsDataBingLocationsTaskInfo.md#init)
- [toJSON](KeywordsDataBingLocationsTaskInfo.md#tojson)
- [fromJS](KeywordsDataBingLocationsTaskInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataBingLocationsTaskInfo**(`data?`): [`KeywordsDataBingLocationsTaskInfo`](KeywordsDataBingLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataBingLocationsTaskInfo`](../interfaces/IKeywordsDataBingLocationsTaskInfo.md) |

#### Returns

[`KeywordsDataBingLocationsTaskInfo`](KeywordsDataBingLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:122015](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L122015)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[cost](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#cost)

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

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[data](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#data)

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

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[id](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[path](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`KeywordsDataBingLocationsResultInfo`](KeywordsDataBingLocationsResultInfo.md)[]

array of results

#### Implementation of

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[result](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#result)

#### Defined in

[main.ts:122011](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L122011)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[result_count](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#result_count)

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

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[status_code](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#status_code)

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

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[status_message](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IKeywordsDataBingLocationsTaskInfo](../interfaces/IKeywordsDataBingLocationsTaskInfo.md).[time](../interfaces/IKeywordsDataBingLocationsTaskInfo.md#time)

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

[main.ts:122019](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L122019)

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

[main.ts:122041](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L122041)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataBingLocationsTaskInfo`](KeywordsDataBingLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataBingLocationsTaskInfo`](KeywordsDataBingLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:122034](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L122034)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")