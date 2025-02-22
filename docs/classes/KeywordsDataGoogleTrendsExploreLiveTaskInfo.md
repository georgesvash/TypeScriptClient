[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleTrendsExploreLiveTaskInfo

# Class: KeywordsDataGoogleTrendsExploreLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`KeywordsDataGoogleTrendsExploreLiveTaskInfo`**

## Implements

- [`IKeywordsDataGoogleTrendsExploreLiveTaskInfo`](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#cost)
- [data](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#data)
- [id](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#id)
- [path](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#path)
- [result](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#result)
- [result\_count](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#result_count)
- [status\_code](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#status_code)
- [status\_message](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#status_message)
- [time](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#time)

### Methods

- [init](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#init)
- [toJSON](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#tojson)
- [fromJS](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleTrendsExploreLiveTaskInfo**(`data?`): [`KeywordsDataGoogleTrendsExploreLiveTaskInfo`](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleTrendsExploreLiveTaskInfo`](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md) |

#### Returns

[`KeywordsDataGoogleTrendsExploreLiveTaskInfo`](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:121819](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121819)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[cost](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#cost)

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

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[data](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#data)

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

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[id](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[path](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`KeywordsDataGoogleTrendsExploreLiveResultInfo`](KeywordsDataGoogleTrendsExploreLiveResultInfo.md)[]

array of results

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[result](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#result)

#### Defined in

[main.ts:121815](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121815)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[result_count](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#result_count)

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

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[status_code](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#status_code)

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

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[status_message](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IKeywordsDataGoogleTrendsExploreLiveTaskInfo](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md).[time](../interfaces/IKeywordsDataGoogleTrendsExploreLiveTaskInfo.md#time)

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

[main.ts:121823](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121823)

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

[main.ts:121845](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121845)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleTrendsExploreLiveTaskInfo`](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleTrendsExploreLiveTaskInfo`](KeywordsDataGoogleTrendsExploreLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:121838](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L121838)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")