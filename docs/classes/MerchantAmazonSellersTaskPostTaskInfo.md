[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonSellersTaskPostTaskInfo

# Class: MerchantAmazonSellersTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantAmazonSellersTaskPostTaskInfo`**

## Implements

- [`IMerchantAmazonSellersTaskPostTaskInfo`](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonSellersTaskPostTaskInfo.md#constructor)

### Properties

- [cost](MerchantAmazonSellersTaskPostTaskInfo.md#cost)
- [data](MerchantAmazonSellersTaskPostTaskInfo.md#data)
- [id](MerchantAmazonSellersTaskPostTaskInfo.md#id)
- [path](MerchantAmazonSellersTaskPostTaskInfo.md#path)
- [result](MerchantAmazonSellersTaskPostTaskInfo.md#result)
- [result\_count](MerchantAmazonSellersTaskPostTaskInfo.md#result_count)
- [status\_code](MerchantAmazonSellersTaskPostTaskInfo.md#status_code)
- [status\_message](MerchantAmazonSellersTaskPostTaskInfo.md#status_message)
- [time](MerchantAmazonSellersTaskPostTaskInfo.md#time)

### Methods

- [init](MerchantAmazonSellersTaskPostTaskInfo.md#init)
- [toJSON](MerchantAmazonSellersTaskPostTaskInfo.md#tojson)
- [fromJS](MerchantAmazonSellersTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonSellersTaskPostTaskInfo**(`data?`): [`MerchantAmazonSellersTaskPostTaskInfo`](MerchantAmazonSellersTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonSellersTaskPostTaskInfo`](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md) |

#### Returns

[`MerchantAmazonSellersTaskPostTaskInfo`](MerchantAmazonSellersTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:173815](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173815)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[cost](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#cost)

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

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[data](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#data)

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

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[id](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[path](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: `any`

array of results
in this case, the value will be null

#### Implementation of

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[result](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:173811](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173811)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[result_count](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#result_count)

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

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[status_code](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#status_code)

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

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[status_message](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantAmazonSellersTaskPostTaskInfo](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md).[time](../interfaces/IMerchantAmazonSellersTaskPostTaskInfo.md#time)

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

[main.ts:173819](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173819)

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

[main.ts:173837](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173837)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonSellersTaskPostTaskInfo`](MerchantAmazonSellersTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonSellersTaskPostTaskInfo`](MerchantAmazonSellersTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:173830](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L173830)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")