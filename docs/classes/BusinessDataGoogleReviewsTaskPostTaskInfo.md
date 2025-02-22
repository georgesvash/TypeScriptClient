[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleReviewsTaskPostTaskInfo

# Class: BusinessDataGoogleReviewsTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataGoogleReviewsTaskPostTaskInfo`**

## Implements

- [`IBusinessDataGoogleReviewsTaskPostTaskInfo`](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleReviewsTaskPostTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataGoogleReviewsTaskPostTaskInfo.md#cost)
- [data](BusinessDataGoogleReviewsTaskPostTaskInfo.md#data)
- [id](BusinessDataGoogleReviewsTaskPostTaskInfo.md#id)
- [path](BusinessDataGoogleReviewsTaskPostTaskInfo.md#path)
- [result](BusinessDataGoogleReviewsTaskPostTaskInfo.md#result)
- [result\_count](BusinessDataGoogleReviewsTaskPostTaskInfo.md#result_count)
- [status\_code](BusinessDataGoogleReviewsTaskPostTaskInfo.md#status_code)
- [status\_message](BusinessDataGoogleReviewsTaskPostTaskInfo.md#status_message)
- [time](BusinessDataGoogleReviewsTaskPostTaskInfo.md#time)

### Methods

- [init](BusinessDataGoogleReviewsTaskPostTaskInfo.md#init)
- [toJSON](BusinessDataGoogleReviewsTaskPostTaskInfo.md#tojson)
- [fromJS](BusinessDataGoogleReviewsTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleReviewsTaskPostTaskInfo**(`data?`): [`BusinessDataGoogleReviewsTaskPostTaskInfo`](BusinessDataGoogleReviewsTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleReviewsTaskPostTaskInfo`](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md) |

#### Returns

[`BusinessDataGoogleReviewsTaskPostTaskInfo`](BusinessDataGoogleReviewsTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:197871](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L197871)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[cost](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#cost)

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

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[data](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#data)

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

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[id](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[path](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#path)

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

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[result](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:197867](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L197867)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[result_count](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#result_count)

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

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[status_code](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#status_code)

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

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[status_message](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataGoogleReviewsTaskPostTaskInfo](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md).[time](../interfaces/IBusinessDataGoogleReviewsTaskPostTaskInfo.md#time)

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

[main.ts:197875](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L197875)

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

[main.ts:197893](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L197893)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleReviewsTaskPostTaskInfo`](BusinessDataGoogleReviewsTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleReviewsTaskPostTaskInfo`](BusinessDataGoogleReviewsTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:197886](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L197886)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")