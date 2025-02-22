[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo

# Class: BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`**

## Implements

- [`IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#cost)
- [data](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#data)
- [id](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#id)
- [path](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#path)
- [result](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#result)
- [result\_count](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#result_count)
- [status\_code](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#status_code)
- [status\_message](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#status_message)
- [time](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#time)

### Methods

- [init](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#init)
- [toJSON](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#tojson)
- [fromJS](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo**(`data?`): [`BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md) |

#### Returns

[`BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:191894](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191894)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[cost](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#cost)

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

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[data](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#data)

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

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[id](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[path](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BusinessDataGoogleMyBusinessInfoTaskGetResultInfo`](BusinessDataGoogleMyBusinessInfoTaskGetResultInfo.md)[]

array of results

#### Implementation of

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[result](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#result)

#### Defined in

[main.ts:191890](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191890)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[result_count](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#result_count)

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

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[status_code](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#status_code)

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

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[status_message](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md).[time](../interfaces/IBusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md#time)

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

[main.ts:191898](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191898)

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

[main.ts:191920](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191920)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo`](BusinessDataGoogleMyBusinessInfoTaskGetTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:191913](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L191913)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")