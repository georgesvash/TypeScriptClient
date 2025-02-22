[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo

# Class: KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`**

## Implements

- [`IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#cost)
- [data](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#data)
- [id](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#id)
- [path](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#path)
- [result](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#result)
- [result\_count](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#result_count)
- [status\_code](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#status_code)
- [status\_message](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#status_message)
- [time](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#time)

### Methods

- [init](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#init)
- [toJSON](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#tojson)
- [fromJS](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo**(`data?`): [`KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md) |

#### Returns

[`KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:118081](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118081)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[cost](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#cost)

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

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[data](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#data)

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

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[id](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[path](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyResultInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyResultInfo.md)[]

array of results

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[result](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#result)

#### Defined in

[main.ts:118077](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118077)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[result_count](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#result_count)

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

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[status_code](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#status_code)

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

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[status_message](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md).[time](../interfaces/IKeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md#time)

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

[main.ts:118085](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118085)

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

[main.ts:118107](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118107)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo`](KeywordsDataGoogleAdsAdTrafficByKeywordsTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:118100](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L118100)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")