[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo

# Interface: IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo

## Hierarchy

- [`IBaseResponseTaskInfo`](IBaseResponseTaskInfo.md)
  
  ↳ **`IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo`**

## Implemented by

- [`KeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo`](../classes/KeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [cost](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#cost)
- [data](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#data)
- [id](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#id)
- [path](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#path)
- [result](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#result)
- [result\_count](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#result_count)
- [status\_code](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#status_code)
- [status\_message](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#status_message)
- [time](IKeywordsDataGoogleAdsSearchVolumeTaskGetTaskInfo.md#time)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[cost](IBaseResponseTaskInfo.md#cost)

#### Defined in

[main.ts:22697](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22697)

___


### data

• `Optional` **data**: `Object`

contains the same parameters that you specified in the POST request

#### Index signature

▪ [key: `string`]: `any`

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[data](IBaseResponseTaskInfo.md#data)

#### Defined in

[main.ts:22703](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22703)

___


### id

• `Optional` **id**: `string`

task identifier
unique task identifier in our system in the UUID format

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[id](IBaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22686](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22686)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[path](IBaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22701](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22701)

___


### result

• `Optional` **result**: [`KeywordsDataGoogleAdsSearchVolumeTaskGetResultInfo`](../classes/KeywordsDataGoogleAdsSearchVolumeTaskGetResultInfo.md)[]

array of results

#### Defined in

[main.ts:113976](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L113976)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[result_count](IBaseResponseTaskInfo.md#result_count)

#### Defined in

[main.ts:22699](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22699)

___


### status\_code

• `Optional` **status\_code**: `number`

status code of the task
generated by DataForSEO, can be within the following range: 10000-60000
you can find the full list of the response codes here

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[status_code](IBaseResponseTaskInfo.md#status_code)

#### Defined in

[main.ts:22690](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22690)

___


### status\_message

• `Optional` **status\_message**: `string`

informational message of the task
you can find the full list of general informational messages here

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[status_message](IBaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22693](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22693)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Inherited from

[IBaseResponseTaskInfo](IBaseResponseTaskInfo.md).[time](IBaseResponseTaskInfo.md#time)

#### Defined in

[main.ts:22695](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22695)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")