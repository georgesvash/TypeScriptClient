[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ContentAnalysisLocationsTaskInfo

# Class: ContentAnalysisLocationsTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`ContentAnalysisLocationsTaskInfo`**

## Implements

- [`IContentAnalysisLocationsTaskInfo`](../interfaces/IContentAnalysisLocationsTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ContentAnalysisLocationsTaskInfo.md#constructor)

### Properties

- [cost](ContentAnalysisLocationsTaskInfo.md#cost)
- [data](ContentAnalysisLocationsTaskInfo.md#data)
- [id](ContentAnalysisLocationsTaskInfo.md#id)
- [path](ContentAnalysisLocationsTaskInfo.md#path)
- [result](ContentAnalysisLocationsTaskInfo.md#result)
- [result\_count](ContentAnalysisLocationsTaskInfo.md#result_count)
- [status\_code](ContentAnalysisLocationsTaskInfo.md#status_code)
- [status\_message](ContentAnalysisLocationsTaskInfo.md#status_message)
- [time](ContentAnalysisLocationsTaskInfo.md#time)

### Methods

- [init](ContentAnalysisLocationsTaskInfo.md#init)
- [toJSON](ContentAnalysisLocationsTaskInfo.md#tojson)
- [fromJS](ContentAnalysisLocationsTaskInfo.md#fromjs)

## Constructors

### constructor

• **new ContentAnalysisLocationsTaskInfo**(`data?`): [`ContentAnalysisLocationsTaskInfo`](ContentAnalysisLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IContentAnalysisLocationsTaskInfo`](../interfaces/IContentAnalysisLocationsTaskInfo.md) |

#### Returns

[`ContentAnalysisLocationsTaskInfo`](ContentAnalysisLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:155581](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155581)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[cost](../interfaces/IContentAnalysisLocationsTaskInfo.md#cost)

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

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[data](../interfaces/IContentAnalysisLocationsTaskInfo.md#data)

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

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[id](../interfaces/IContentAnalysisLocationsTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[path](../interfaces/IContentAnalysisLocationsTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`ContentAnalysisLocationsResultInfo`](ContentAnalysisLocationsResultInfo.md)[]

array of results

#### Implementation of

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[result](../interfaces/IContentAnalysisLocationsTaskInfo.md#result)

#### Defined in

[main.ts:155577](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155577)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[result_count](../interfaces/IContentAnalysisLocationsTaskInfo.md#result_count)

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

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[status_code](../interfaces/IContentAnalysisLocationsTaskInfo.md#status_code)

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

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[status_message](../interfaces/IContentAnalysisLocationsTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IContentAnalysisLocationsTaskInfo](../interfaces/IContentAnalysisLocationsTaskInfo.md).[time](../interfaces/IContentAnalysisLocationsTaskInfo.md#time)

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

[main.ts:155585](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155585)

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

[main.ts:155607](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155607)

___


### fromJS

▸ **fromJS**(`data`): [`ContentAnalysisLocationsTaskInfo`](ContentAnalysisLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ContentAnalysisLocationsTaskInfo`](ContentAnalysisLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:155600](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155600)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")