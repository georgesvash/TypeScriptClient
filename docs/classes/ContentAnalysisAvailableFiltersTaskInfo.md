[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ContentAnalysisAvailableFiltersTaskInfo

# Class: ContentAnalysisAvailableFiltersTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`ContentAnalysisAvailableFiltersTaskInfo`**

## Implements

- [`IContentAnalysisAvailableFiltersTaskInfo`](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ContentAnalysisAvailableFiltersTaskInfo.md#constructor)

### Properties

- [cost](ContentAnalysisAvailableFiltersTaskInfo.md#cost)
- [data](ContentAnalysisAvailableFiltersTaskInfo.md#data)
- [id](ContentAnalysisAvailableFiltersTaskInfo.md#id)
- [path](ContentAnalysisAvailableFiltersTaskInfo.md#path)
- [result](ContentAnalysisAvailableFiltersTaskInfo.md#result)
- [result\_count](ContentAnalysisAvailableFiltersTaskInfo.md#result_count)
- [status\_code](ContentAnalysisAvailableFiltersTaskInfo.md#status_code)
- [status\_message](ContentAnalysisAvailableFiltersTaskInfo.md#status_message)
- [time](ContentAnalysisAvailableFiltersTaskInfo.md#time)

### Methods

- [init](ContentAnalysisAvailableFiltersTaskInfo.md#init)
- [toJSON](ContentAnalysisAvailableFiltersTaskInfo.md#tojson)
- [fromJS](ContentAnalysisAvailableFiltersTaskInfo.md#fromjs)

## Constructors

### constructor

• **new ContentAnalysisAvailableFiltersTaskInfo**(`data?`): [`ContentAnalysisAvailableFiltersTaskInfo`](ContentAnalysisAvailableFiltersTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IContentAnalysisAvailableFiltersTaskInfo`](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md) |

#### Returns

[`ContentAnalysisAvailableFiltersTaskInfo`](ContentAnalysisAvailableFiltersTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:155418](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155418)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[cost](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#cost)

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

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[data](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#data)

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

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[id](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[path](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`ContentAnalysisAvailableFiltersResultInfo`](ContentAnalysisAvailableFiltersResultInfo.md)[]

#### Implementation of

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[result](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#result)

#### Defined in

[main.ts:155414](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155414)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[result_count](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#result_count)

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

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[status_code](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#status_code)

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

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[status_message](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IContentAnalysisAvailableFiltersTaskInfo](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md).[time](../interfaces/IContentAnalysisAvailableFiltersTaskInfo.md#time)

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

[main.ts:155422](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155422)

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

[main.ts:155444](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155444)

___


### fromJS

▸ **fromJS**(`data`): [`ContentAnalysisAvailableFiltersTaskInfo`](ContentAnalysisAvailableFiltersTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ContentAnalysisAvailableFiltersTaskInfo`](ContentAnalysisAvailableFiltersTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:155437](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L155437)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")