[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYoutubeVideoInfoLiveAdvancedTaskInfo

# Class: SerpYoutubeVideoInfoLiveAdvancedTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpYoutubeVideoInfoLiveAdvancedTaskInfo`**

## Implements

- [`ISerpYoutubeVideoInfoLiveAdvancedTaskInfo`](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#constructor)

### Properties

- [cost](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#cost)
- [data](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#data)
- [id](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#id)
- [path](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#path)
- [result](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#result)
- [result\_count](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#result_count)
- [status\_code](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#status_code)
- [status\_message](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#status_message)
- [time](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#time)

### Methods

- [init](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#init)
- [toJSON](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#tojson)
- [fromJS](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYoutubeVideoInfoLiveAdvancedTaskInfo**(`data?`): [`SerpYoutubeVideoInfoLiveAdvancedTaskInfo`](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYoutubeVideoInfoLiveAdvancedTaskInfo`](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md) |

#### Returns

[`SerpYoutubeVideoInfoLiveAdvancedTaskInfo`](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:59334](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L59334)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[cost](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#cost)

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

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[data](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#data)

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

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[id](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[path](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpYoutubeVideoInfoLiveAdvancedResultInfo`](SerpYoutubeVideoInfoLiveAdvancedResultInfo.md)[]

array of results

#### Implementation of

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[result](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#result)

#### Defined in

[main.ts:59330](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L59330)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[result_count](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#result_count)

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

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[status_code](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#status_code)

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

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[status_message](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpYoutubeVideoInfoLiveAdvancedTaskInfo](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md).[time](../interfaces/ISerpYoutubeVideoInfoLiveAdvancedTaskInfo.md#time)

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

[main.ts:59338](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L59338)

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

[main.ts:59360](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L59360)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYoutubeVideoInfoLiveAdvancedTaskInfo`](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYoutubeVideoInfoLiveAdvancedTaskInfo`](SerpYoutubeVideoInfoLiveAdvancedTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:59353](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L59353)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")