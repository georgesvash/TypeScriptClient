[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonSellersTasksReadyTaskInfo

# Class: MerchantAmazonSellersTasksReadyTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantAmazonSellersTasksReadyTaskInfo`**

## Implements

- [`IMerchantAmazonSellersTasksReadyTaskInfo`](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonSellersTasksReadyTaskInfo.md#constructor)

### Properties

- [cost](MerchantAmazonSellersTasksReadyTaskInfo.md#cost)
- [data](MerchantAmazonSellersTasksReadyTaskInfo.md#data)
- [id](MerchantAmazonSellersTasksReadyTaskInfo.md#id)
- [path](MerchantAmazonSellersTasksReadyTaskInfo.md#path)
- [result](MerchantAmazonSellersTasksReadyTaskInfo.md#result)
- [result\_count](MerchantAmazonSellersTasksReadyTaskInfo.md#result_count)
- [status\_code](MerchantAmazonSellersTasksReadyTaskInfo.md#status_code)
- [status\_message](MerchantAmazonSellersTasksReadyTaskInfo.md#status_message)
- [time](MerchantAmazonSellersTasksReadyTaskInfo.md#time)

### Methods

- [init](MerchantAmazonSellersTasksReadyTaskInfo.md#init)
- [toJSON](MerchantAmazonSellersTasksReadyTaskInfo.md#tojson)
- [fromJS](MerchantAmazonSellersTasksReadyTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonSellersTasksReadyTaskInfo**(`data?`): [`MerchantAmazonSellersTasksReadyTaskInfo`](MerchantAmazonSellersTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonSellersTasksReadyTaskInfo`](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md) |

#### Returns

[`MerchantAmazonSellersTasksReadyTaskInfo`](MerchantAmazonSellersTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:174008](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L174008)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[cost](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#cost)

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

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[data](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#data)

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

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[id](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[path](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`MerchantAmazonSellersTasksReadyResultInfo`](MerchantAmazonSellersTasksReadyResultInfo.md)[]

array of results

#### Implementation of

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[result](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#result)

#### Defined in

[main.ts:174004](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L174004)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[result_count](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#result_count)

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

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[status_code](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#status_code)

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

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[status_message](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantAmazonSellersTasksReadyTaskInfo](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md).[time](../interfaces/IMerchantAmazonSellersTasksReadyTaskInfo.md#time)

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

[main.ts:174012](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L174012)

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

[main.ts:174034](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L174034)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonSellersTasksReadyTaskInfo`](MerchantAmazonSellersTasksReadyTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonSellersTasksReadyTaskInfo`](MerchantAmazonSellersTasksReadyTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:174027](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L174027)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")