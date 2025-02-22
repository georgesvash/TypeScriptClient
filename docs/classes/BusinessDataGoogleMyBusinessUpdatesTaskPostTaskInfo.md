[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo

# Class: BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`**

## Implements

- [`IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#cost)
- [data](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#data)
- [id](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#id)
- [path](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#path)
- [result](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#result)
- [result\_count](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#result_count)
- [status\_code](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#status_code)
- [status\_message](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#status_message)
- [time](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#time)

### Methods

- [init](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#init)
- [toJSON](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#tojson)
- [fromJS](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo**(`data?`): [`BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md) |

#### Returns

[`BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:192062](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L192062)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[cost](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#cost)

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

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[data](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#data)

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

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[id](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[path](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#path)

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

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[result](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:192058](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L192058)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[result_count](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#result_count)

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

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[status_code](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#status_code)

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

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[status_message](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md).[time](../interfaces/IBusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md#time)

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

[main.ts:192066](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L192066)

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

[main.ts:192084](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L192084)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo`](BusinessDataGoogleMyBusinessUpdatesTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:192077](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L192077)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")