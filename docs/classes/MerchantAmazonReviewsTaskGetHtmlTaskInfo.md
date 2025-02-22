[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonReviewsTaskGetHtmlTaskInfo

# Class: MerchantAmazonReviewsTaskGetHtmlTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantAmazonReviewsTaskGetHtmlTaskInfo`**

## Implements

- [`IMerchantAmazonReviewsTaskGetHtmlTaskInfo`](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#constructor)

### Properties

- [cost](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#cost)
- [data](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#data)
- [id](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#id)
- [path](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#path)
- [result](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#result)
- [result\_count](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#result_count)
- [status\_code](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#status_code)
- [status\_message](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#status_message)
- [time](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#time)

### Methods

- [init](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#init)
- [toJSON](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#tojson)
- [fromJS](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonReviewsTaskGetHtmlTaskInfo**(`data?`): [`MerchantAmazonReviewsTaskGetHtmlTaskInfo`](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonReviewsTaskGetHtmlTaskInfo`](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md) |

#### Returns

[`MerchantAmazonReviewsTaskGetHtmlTaskInfo`](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:176172](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176172)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[cost](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#cost)

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

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[data](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#data)

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

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[id](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[path](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`MerchantAmazonReviewsTaskGetHtmlResultInfo`](MerchantAmazonReviewsTaskGetHtmlResultInfo.md)[]

array of results

#### Implementation of

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[result](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#result)

#### Defined in

[main.ts:176168](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176168)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[result_count](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#result_count)

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

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[status_code](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#status_code)

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

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[status_message](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantAmazonReviewsTaskGetHtmlTaskInfo](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md).[time](../interfaces/IMerchantAmazonReviewsTaskGetHtmlTaskInfo.md#time)

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

[main.ts:176176](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176176)

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

[main.ts:176198](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176198)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonReviewsTaskGetHtmlTaskInfo`](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonReviewsTaskGetHtmlTaskInfo`](MerchantAmazonReviewsTaskGetHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:176191](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L176191)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")