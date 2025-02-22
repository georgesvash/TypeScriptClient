[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo

# Class: KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`**

## Implements

- [`IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#constructor)

### Properties

- [cost](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#cost)
- [status\_code](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#status_code)
- [status\_message](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#status_message)
- [tasks](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tasks)
- [tasks\_count](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tasks_count)
- [tasks\_error](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tasks_error)
- [time](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#time)
- [version](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#version)

### Methods

- [init](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#init)
- [toJSON](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tojson)
- [fromJS](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#fromjs)

## Constructors

### constructor

• **new KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo**(`data?`): [`KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md) |

#### Returns

[`KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:115297](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L115297)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[cost](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#cost)

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

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[status_code](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#status_code)

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

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[status_message](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`KeywordsDataGoogleAdsKeywordsForSiteTaskGetTaskInfo`](KeywordsDataGoogleAdsKeywordsForSiteTaskGetTaskInfo.md)[]

array of tasks

#### Implementation of

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[tasks](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tasks)

#### Defined in

[main.ts:115293](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L115293)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[tasks_count](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[tasks_error](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[time](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md).[version](../interfaces/IKeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md#version)

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

[main.ts:115301](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L115301)

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

[main.ts:115323](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L115323)

___


### fromJS

▸ **fromJS**(`data`): [`KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo`](KeywordsDataGoogleAdsKeywordsForSiteTaskGetResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:115316](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L115316)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")