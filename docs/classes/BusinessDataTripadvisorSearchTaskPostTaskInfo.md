[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataTripadvisorSearchTaskPostTaskInfo

# Class: BusinessDataTripadvisorSearchTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataTripadvisorSearchTaskPostTaskInfo`**

## Implements

- [`IBusinessDataTripadvisorSearchTaskPostTaskInfo`](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#cost)
- [data](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#data)
- [id](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#id)
- [path](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#path)
- [result](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#result)
- [result\_count](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#result_count)
- [status\_code](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#status_code)
- [status\_message](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#status_message)
- [time](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#time)

### Methods

- [init](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#init)
- [toJSON](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#tojson)
- [fromJS](BusinessDataTripadvisorSearchTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataTripadvisorSearchTaskPostTaskInfo**(`data?`): [`BusinessDataTripadvisorSearchTaskPostTaskInfo`](BusinessDataTripadvisorSearchTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataTripadvisorSearchTaskPostTaskInfo`](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md) |

#### Returns

[`BusinessDataTripadvisorSearchTaskPostTaskInfo`](BusinessDataTripadvisorSearchTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:201081](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201081)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[cost](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#cost)

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

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[data](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#data)

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

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[id](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[path](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#path)

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

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[result](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:201077](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201077)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[result_count](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#result_count)

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

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[status_code](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#status_code)

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

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[status_message](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataTripadvisorSearchTaskPostTaskInfo](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md).[time](../interfaces/IBusinessDataTripadvisorSearchTaskPostTaskInfo.md#time)

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

[main.ts:201085](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201085)

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

[main.ts:201103](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201103)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataTripadvisorSearchTaskPostTaskInfo`](BusinessDataTripadvisorSearchTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataTripadvisorSearchTaskPostTaskInfo`](BusinessDataTripadvisorSearchTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:201096](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L201096)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")