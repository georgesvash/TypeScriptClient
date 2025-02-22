[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleTrendsLocationsTaskInfo

# Class: KeywordsDataGoogleTrendsLocationsTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`KeywordsDataGoogleTrendsLocationsTaskInfo`**

## Implements

- [`IKeywordsDataGoogleTrendsLocationsTaskInfo`](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleTrendsLocationsTaskInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleTrendsLocationsTaskInfo.md#cost)
- [data](KeywordsDataGoogleTrendsLocationsTaskInfo.md#data)
- [id](KeywordsDataGoogleTrendsLocationsTaskInfo.md#id)
- [path](KeywordsDataGoogleTrendsLocationsTaskInfo.md#path)
- [result](KeywordsDataGoogleTrendsLocationsTaskInfo.md#result)
- [result\_count](KeywordsDataGoogleTrendsLocationsTaskInfo.md#result_count)
- [status\_code](KeywordsDataGoogleTrendsLocationsTaskInfo.md#status_code)
- [status\_message](KeywordsDataGoogleTrendsLocationsTaskInfo.md#status_message)
- [time](KeywordsDataGoogleTrendsLocationsTaskInfo.md#time)

### Methods

- [init](KeywordsDataGoogleTrendsLocationsTaskInfo.md#init)
- [toJSON](KeywordsDataGoogleTrendsLocationsTaskInfo.md#tojson)
- [fromJS](KeywordsDataGoogleTrendsLocationsTaskInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleTrendsLocationsTaskInfo**(`data?`): [`KeywordsDataGoogleTrendsLocationsTaskInfo`](KeywordsDataGoogleTrendsLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleTrendsLocationsTaskInfo`](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md) |

#### Returns

[`KeywordsDataGoogleTrendsLocationsTaskInfo`](KeywordsDataGoogleTrendsLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:119113](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119113)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[cost](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#cost)

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

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[data](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#data)

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

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[id](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[path](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`KeywordsDataGoogleTrendsLocationsResultInfo`](KeywordsDataGoogleTrendsLocationsResultInfo.md)[]

array of results

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[result](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#result)

#### Defined in

[main.ts:119109](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119109)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[result_count](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#result_count)

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

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[status_code](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#status_code)

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

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[status_message](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IKeywordsDataGoogleTrendsLocationsTaskInfo](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md).[time](../interfaces/IKeywordsDataGoogleTrendsLocationsTaskInfo.md#time)

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

[main.ts:119117](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119117)

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

[main.ts:119139](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119139)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleTrendsLocationsTaskInfo`](KeywordsDataGoogleTrendsLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleTrendsLocationsTaskInfo`](KeywordsDataGoogleTrendsLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:119132](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L119132)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")