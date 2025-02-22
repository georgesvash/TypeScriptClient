[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / MerchantAmazonLanguagesTaskInfo

# Class: MerchantAmazonLanguagesTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`MerchantAmazonLanguagesTaskInfo`**

## Implements

- [`IMerchantAmazonLanguagesTaskInfo`](../interfaces/IMerchantAmazonLanguagesTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](MerchantAmazonLanguagesTaskInfo.md#constructor)

### Properties

- [cost](MerchantAmazonLanguagesTaskInfo.md#cost)
- [data](MerchantAmazonLanguagesTaskInfo.md#data)
- [id](MerchantAmazonLanguagesTaskInfo.md#id)
- [path](MerchantAmazonLanguagesTaskInfo.md#path)
- [result](MerchantAmazonLanguagesTaskInfo.md#result)
- [result\_count](MerchantAmazonLanguagesTaskInfo.md#result_count)
- [status\_code](MerchantAmazonLanguagesTaskInfo.md#status_code)
- [status\_message](MerchantAmazonLanguagesTaskInfo.md#status_message)
- [time](MerchantAmazonLanguagesTaskInfo.md#time)

### Methods

- [init](MerchantAmazonLanguagesTaskInfo.md#init)
- [toJSON](MerchantAmazonLanguagesTaskInfo.md#tojson)
- [fromJS](MerchantAmazonLanguagesTaskInfo.md#fromjs)

## Constructors

### constructor

• **new MerchantAmazonLanguagesTaskInfo**(`data?`): [`MerchantAmazonLanguagesTaskInfo`](MerchantAmazonLanguagesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IMerchantAmazonLanguagesTaskInfo`](../interfaces/IMerchantAmazonLanguagesTaskInfo.md) |

#### Returns

[`MerchantAmazonLanguagesTaskInfo`](MerchantAmazonLanguagesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:170193](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L170193)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[cost](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#cost)

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

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[data](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#data)

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

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[id](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[path](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`MerchantAmazonLanguagesResultInfo`](MerchantAmazonLanguagesResultInfo.md)[]

array of results

#### Implementation of

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[result](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#result)

#### Defined in

[main.ts:170189](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L170189)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[result_count](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#result_count)

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

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[status_code](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#status_code)

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

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[status_message](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IMerchantAmazonLanguagesTaskInfo](../interfaces/IMerchantAmazonLanguagesTaskInfo.md).[time](../interfaces/IMerchantAmazonLanguagesTaskInfo.md#time)

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

[main.ts:170197](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L170197)

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

[main.ts:170219](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L170219)

___


### fromJS

▸ **fromJS**(`data`): [`MerchantAmazonLanguagesTaskInfo`](MerchantAmazonLanguagesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`MerchantAmazonLanguagesTaskInfo`](MerchantAmazonLanguagesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:170212](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L170212)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")