[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataYelpSearchTaskGetTaskInfo

# Class: BusinessDataYelpSearchTaskGetTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataYelpSearchTaskGetTaskInfo`**

## Implements

- [`IBusinessDataYelpSearchTaskGetTaskInfo`](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataYelpSearchTaskGetTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataYelpSearchTaskGetTaskInfo.md#cost)
- [data](BusinessDataYelpSearchTaskGetTaskInfo.md#data)
- [id](BusinessDataYelpSearchTaskGetTaskInfo.md#id)
- [path](BusinessDataYelpSearchTaskGetTaskInfo.md#path)
- [result](BusinessDataYelpSearchTaskGetTaskInfo.md#result)
- [result\_count](BusinessDataYelpSearchTaskGetTaskInfo.md#result_count)
- [status\_code](BusinessDataYelpSearchTaskGetTaskInfo.md#status_code)
- [status\_message](BusinessDataYelpSearchTaskGetTaskInfo.md#status_message)
- [time](BusinessDataYelpSearchTaskGetTaskInfo.md#time)

### Methods

- [init](BusinessDataYelpSearchTaskGetTaskInfo.md#init)
- [toJSON](BusinessDataYelpSearchTaskGetTaskInfo.md#tojson)
- [fromJS](BusinessDataYelpSearchTaskGetTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataYelpSearchTaskGetTaskInfo**(`data?`): [`BusinessDataYelpSearchTaskGetTaskInfo`](BusinessDataYelpSearchTaskGetTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataYelpSearchTaskGetTaskInfo`](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md) |

#### Returns

[`BusinessDataYelpSearchTaskGetTaskInfo`](BusinessDataYelpSearchTaskGetTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:204568](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L204568)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[cost](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#cost)

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

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[data](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#data)

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

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[id](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[path](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BusinessDataYelpSearchTaskGetResultInfo`](BusinessDataYelpSearchTaskGetResultInfo.md)[]

array of results

#### Implementation of

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[result](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#result)

#### Defined in

[main.ts:204564](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L204564)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[result_count](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#result_count)

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

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[status_code](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#status_code)

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

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[status_message](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataYelpSearchTaskGetTaskInfo](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md).[time](../interfaces/IBusinessDataYelpSearchTaskGetTaskInfo.md#time)

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

[main.ts:204572](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L204572)

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

[main.ts:204594](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L204594)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataYelpSearchTaskGetTaskInfo`](BusinessDataYelpSearchTaskGetTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataYelpSearchTaskGetTaskInfo`](BusinessDataYelpSearchTaskGetTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:204587](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L204587)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")