[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonAsinTaskPostTaskInfo

# Class: MerchantAmazonAsinTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantAmazonAsinTaskPostTaskInfo`**

## Implements

- [`IMerchantAmazonAsinTaskPostTaskInfo`](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonAsinTaskPostTaskInfo.md#constructor)

### Properties

- [cost](MerchantAmazonAsinTaskPostTaskInfo.md#cost)
- [data](MerchantAmazonAsinTaskPostTaskInfo.md#data)
- [id](MerchantAmazonAsinTaskPostTaskInfo.md#id)
- [path](MerchantAmazonAsinTaskPostTaskInfo.md#path)
- [result](MerchantAmazonAsinTaskPostTaskInfo.md#result)
- [result\_count](MerchantAmazonAsinTaskPostTaskInfo.md#result_count)
- [status\_code](MerchantAmazonAsinTaskPostTaskInfo.md#status_code)
- [status\_message](MerchantAmazonAsinTaskPostTaskInfo.md#status_message)
- [time](MerchantAmazonAsinTaskPostTaskInfo.md#time)

### Methods

- [init](MerchantAmazonAsinTaskPostTaskInfo.md#init)
- [toJSON](MerchantAmazonAsinTaskPostTaskInfo.md#tojson)
- [fromJS](MerchantAmazonAsinTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonAsinTaskPostTaskInfo**(`data?`): [`MerchantAmazonAsinTaskPostTaskInfo`](MerchantAmazonAsinTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonAsinTaskPostTaskInfo`](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md) |

#### Returns

[`MerchantAmazonAsinTaskPostTaskInfo`](MerchantAmazonAsinTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:172023](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L172023)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[cost](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#cost)

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

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[data](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#data)

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

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[id](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[path](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#path)

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

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[result](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:172019](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L172019)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[result_count](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#result_count)

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

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[status_code](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#status_code)

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

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[status_message](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantAmazonAsinTaskPostTaskInfo](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md).[time](../interfaces/IMerchantAmazonAsinTaskPostTaskInfo.md#time)

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

[main.ts:172027](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L172027)

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

[main.ts:172045](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L172045)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonAsinTaskPostTaskInfo`](MerchantAmazonAsinTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonAsinTaskPostTaskInfo`](MerchantAmazonAsinTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:172038](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L172038)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")