[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantGoogleProductsTaskGetHtmlTaskInfo

# Class: MerchantGoogleProductsTaskGetHtmlTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantGoogleProductsTaskGetHtmlTaskInfo`**

## Implements

- [`IMerchantGoogleProductsTaskGetHtmlTaskInfo`](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#constructor)

### Properties

- [cost](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#cost)
- [data](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#data)
- [id](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#id)
- [path](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#path)
- [result](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#result)
- [result\_count](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#result_count)
- [status\_code](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#status_code)
- [status\_message](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#status_message)
- [time](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#time)

### Methods

- [init](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#init)
- [toJSON](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#tojson)
- [fromJS](MerchantGoogleProductsTaskGetHtmlTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantGoogleProductsTaskGetHtmlTaskInfo**(`data?`): [`MerchantGoogleProductsTaskGetHtmlTaskInfo`](MerchantGoogleProductsTaskGetHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantGoogleProductsTaskGetHtmlTaskInfo`](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md) |

#### Returns

[`MerchantGoogleProductsTaskGetHtmlTaskInfo`](MerchantGoogleProductsTaskGetHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:165741](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165741)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[cost](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#cost)

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

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[data](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#data)

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

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[id](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[path](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`MerchantGoogleProductsTaskGetHtmlResultInfo`](MerchantGoogleProductsTaskGetHtmlResultInfo.md)[]

array of results

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[result](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#result)

#### Defined in

[main.ts:165737](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165737)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[result_count](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#result_count)

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

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[status_code](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#status_code)

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

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[status_message](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantGoogleProductsTaskGetHtmlTaskInfo](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md).[time](../interfaces/IMerchantGoogleProductsTaskGetHtmlTaskInfo.md#time)

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

[main.ts:165745](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165745)

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

[main.ts:165767](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165767)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantGoogleProductsTaskGetHtmlTaskInfo`](MerchantGoogleProductsTaskGetHtmlTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantGoogleProductsTaskGetHtmlTaskInfo`](MerchantGoogleProductsTaskGetHtmlTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:165760](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L165760)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")