[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataBusinessListingsCategoriesTaskInfo

# Class: BusinessDataBusinessListingsCategoriesTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataBusinessListingsCategoriesTaskInfo`**

## Implements

- [`IBusinessDataBusinessListingsCategoriesTaskInfo`](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataBusinessListingsCategoriesTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataBusinessListingsCategoriesTaskInfo.md#cost)
- [data](BusinessDataBusinessListingsCategoriesTaskInfo.md#data)
- [id](BusinessDataBusinessListingsCategoriesTaskInfo.md#id)
- [path](BusinessDataBusinessListingsCategoriesTaskInfo.md#path)
- [result](BusinessDataBusinessListingsCategoriesTaskInfo.md#result)
- [result\_count](BusinessDataBusinessListingsCategoriesTaskInfo.md#result_count)
- [status\_code](BusinessDataBusinessListingsCategoriesTaskInfo.md#status_code)
- [status\_message](BusinessDataBusinessListingsCategoriesTaskInfo.md#status_message)
- [time](BusinessDataBusinessListingsCategoriesTaskInfo.md#time)

### Methods

- [init](BusinessDataBusinessListingsCategoriesTaskInfo.md#init)
- [toJSON](BusinessDataBusinessListingsCategoriesTaskInfo.md#tojson)
- [fromJS](BusinessDataBusinessListingsCategoriesTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataBusinessListingsCategoriesTaskInfo**(`data?`): [`BusinessDataBusinessListingsCategoriesTaskInfo`](BusinessDataBusinessListingsCategoriesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataBusinessListingsCategoriesTaskInfo`](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md) |

#### Returns

[`BusinessDataBusinessListingsCategoriesTaskInfo`](BusinessDataBusinessListingsCategoriesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:188066](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188066)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[cost](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#cost)

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

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[data](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#data)

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

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[id](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[path](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BusinessDataBusinessListingsCategoriesResultInfo`](BusinessDataBusinessListingsCategoriesResultInfo.md)[]

array of results

#### Implementation of

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[result](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#result)

#### Defined in

[main.ts:188062](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188062)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[result_count](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#result_count)

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

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[status_code](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#status_code)

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

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[status_message](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataBusinessListingsCategoriesTaskInfo](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md).[time](../interfaces/IBusinessDataBusinessListingsCategoriesTaskInfo.md#time)

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

[main.ts:188070](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188070)

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

[main.ts:188092](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188092)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataBusinessListingsCategoriesTaskInfo`](BusinessDataBusinessListingsCategoriesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataBusinessListingsCategoriesTaskInfo`](BusinessDataBusinessListingsCategoriesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:188085](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L188085)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")