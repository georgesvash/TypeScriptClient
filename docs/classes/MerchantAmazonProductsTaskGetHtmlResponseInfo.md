[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonProductsTaskGetHtmlResponseInfo

# Class: MerchantAmazonProductsTaskGetHtmlResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`MerchantAmazonProductsTaskGetHtmlResponseInfo`**

## Implements

- [`IMerchantAmazonProductsTaskGetHtmlResponseInfo`](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#constructor)

### Properties

- [cost](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#cost)
- [status\_code](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#status_code)
- [status\_message](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#status_message)
- [tasks](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#tasks)
- [tasks\_count](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#tasks_count)
- [tasks\_error](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#tasks_error)
- [time](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#time)
- [version](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#version)

### Methods

- [init](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#init)
- [toJSON](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#tojson)
- [fromJS](MerchantAmazonProductsTaskGetHtmlResponseInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonProductsTaskGetHtmlResponseInfo**(`data?`): [`MerchantAmazonProductsTaskGetHtmlResponseInfo`](MerchantAmazonProductsTaskGetHtmlResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonProductsTaskGetHtmlResponseInfo`](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md) |

#### Returns

[`MerchantAmazonProductsTaskGetHtmlResponseInfo`](MerchantAmazonProductsTaskGetHtmlResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:171717](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171717)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[cost](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#cost)

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

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[status_code](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#status_code)

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

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[status_message](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`MerchantAmazonProductsTaskGetHtmlTaskInfo`](MerchantAmazonProductsTaskGetHtmlTaskInfo.md)[]

array of tasks

#### Implementation of

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[tasks](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#tasks)

#### Defined in

[main.ts:171713](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171713)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[tasks_count](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[tasks_error](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[time](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IMerchantAmazonProductsTaskGetHtmlResponseInfo](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md).[version](../interfaces/IMerchantAmazonProductsTaskGetHtmlResponseInfo.md#version)

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

[main.ts:171721](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171721)

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

[main.ts:171743](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171743)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonProductsTaskGetHtmlResponseInfo`](MerchantAmazonProductsTaskGetHtmlResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonProductsTaskGetHtmlResponseInfo`](MerchantAmazonProductsTaskGetHtmlResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:171736](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L171736)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")