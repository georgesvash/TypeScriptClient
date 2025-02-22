[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ContentGenerationTextSummaryLanguagesResponseInfo

# Class: ContentGenerationTextSummaryLanguagesResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`ContentGenerationTextSummaryLanguagesResponseInfo`**

## Implements

- [`IContentGenerationTextSummaryLanguagesResponseInfo`](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](ContentGenerationTextSummaryLanguagesResponseInfo.md#constructor)

### Properties

- [cost](ContentGenerationTextSummaryLanguagesResponseInfo.md#cost)
- [status\_code](ContentGenerationTextSummaryLanguagesResponseInfo.md#status_code)
- [status\_message](ContentGenerationTextSummaryLanguagesResponseInfo.md#status_message)
- [tasks](ContentGenerationTextSummaryLanguagesResponseInfo.md#tasks)
- [tasks\_count](ContentGenerationTextSummaryLanguagesResponseInfo.md#tasks_count)
- [tasks\_error](ContentGenerationTextSummaryLanguagesResponseInfo.md#tasks_error)
- [time](ContentGenerationTextSummaryLanguagesResponseInfo.md#time)
- [version](ContentGenerationTextSummaryLanguagesResponseInfo.md#version)

### Methods

- [init](ContentGenerationTextSummaryLanguagesResponseInfo.md#init)
- [toJSON](ContentGenerationTextSummaryLanguagesResponseInfo.md#tojson)
- [fromJS](ContentGenerationTextSummaryLanguagesResponseInfo.md#fromjs)

## Constructors

### constructor

• **new ContentGenerationTextSummaryLanguagesResponseInfo**(`data?`): [`ContentGenerationTextSummaryLanguagesResponseInfo`](ContentGenerationTextSummaryLanguagesResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IContentGenerationTextSummaryLanguagesResponseInfo`](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md) |

#### Returns

[`ContentGenerationTextSummaryLanguagesResponseInfo`](ContentGenerationTextSummaryLanguagesResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:162602](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L162602)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[cost](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#cost)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[cost](BaseResponseInfo.md#cost)

#### Defined in

[main.ts:22510](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22510)

___


### status\_code

• `Optional` **status\_code**: `number`

general status code
you can find the full list of the response codes here

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[status_code](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#status_code)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_code](BaseResponseInfo.md#status_code)

#### Defined in

[main.ts:22503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22503)

___


### status\_message

• `Optional` **status\_message**: `string`

general informational message
you can find the full list of general informational messages here

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[status_message](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`ContentGenerationTextSummaryLanguagesTaskInfo`](ContentGenerationTextSummaryLanguagesTaskInfo.md)[]

array of tasks

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[tasks](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#tasks)

#### Defined in

[main.ts:162598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L162598)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[tasks_count](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[tasks_error](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[time](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IContentGenerationTextSummaryLanguagesResponseInfo](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md).[version](../interfaces/IContentGenerationTextSummaryLanguagesResponseInfo.md#version)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[version](BaseResponseInfo.md#version)

#### Defined in

[main.ts:22500](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22500)

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

[BaseResponseInfo](BaseResponseInfo.md).[init](BaseResponseInfo.md#init)

#### Defined in

[main.ts:162606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L162606)

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

[BaseResponseInfo](BaseResponseInfo.md).[toJSON](BaseResponseInfo.md#tojson)

#### Defined in

[main.ts:162628](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L162628)

___


### fromJS

▸ **fromJS**(`data`): [`ContentGenerationTextSummaryLanguagesResponseInfo`](ContentGenerationTextSummaryLanguagesResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`ContentGenerationTextSummaryLanguagesResponseInfo`](ContentGenerationTextSummaryLanguagesResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:162621](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L162621)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")