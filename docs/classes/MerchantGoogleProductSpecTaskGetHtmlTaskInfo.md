[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantGoogleProductSpecTaskGetHtmlTaskInfo

# Class: MerchantGoogleProductSpecTaskGetHtmlTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantGoogleProductSpecTaskGetHtmlTaskInfo`**

## Implements

- [`IMerchantGoogleProductSpecTaskGetHtmlTaskInfo`](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#constructor)

### Properties

- [cost](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#cost)
- [data](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#data)
- [id](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#id)
- [path](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#path)
- [result](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#result)
- [result\_count](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#result_count)
- [status\_code](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#status_code)
- [status\_message](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#status_message)
- [time](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#time)

### Methods

- [init](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#init)
- [toJSON](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#tojson)
- [fromJS](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantGoogleProductSpecTaskGetHtmlTaskInfo**(`data?`): [`MerchantGoogleProductSpecTaskGetHtmlTaskInfo`](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantGoogleProductSpecTaskGetHtmlTaskInfo`](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md) |

#### Returns

[`MerchantGoogleProductSpecTaskGetHtmlTaskInfo`](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:168319](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L168319)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[cost](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#cost)

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

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[data](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#data)

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

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[id](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[path](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`MerchantGoogleProductSpecTaskGetHtmlResultInfo`](MerchantGoogleProductSpecTaskGetHtmlResultInfo.md)[]

array of results

#### Implementation of

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[result](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#result)

#### Defined in

[main.ts:168315](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L168315)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[result_count](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#result_count)

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

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[status_code](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#status_code)

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

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[status_message](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantGoogleProductSpecTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md).[time](../interfaces/IMerchantGoogleProductSpecTaskGetHtmlTaskInfo.md#time)

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

[main.ts:168323](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L168323)

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

[main.ts:168345](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L168345)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantGoogleProductSpecTaskGetHtmlTaskInfo`](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantGoogleProductSpecTaskGetHtmlTaskInfo`](MerchantGoogleProductSpecTaskGetHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:168338](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L168338)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")