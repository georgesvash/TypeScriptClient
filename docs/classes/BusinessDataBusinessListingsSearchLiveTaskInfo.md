[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataBusinessListingsSearchLiveTaskInfo

# Class: BusinessDataBusinessListingsSearchLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataBusinessListingsSearchLiveTaskInfo`**

## Implements

- [`IBusinessDataBusinessListingsSearchLiveTaskInfo`](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataBusinessListingsSearchLiveTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataBusinessListingsSearchLiveTaskInfo.md#cost)
- [data](BusinessDataBusinessListingsSearchLiveTaskInfo.md#data)
- [id](BusinessDataBusinessListingsSearchLiveTaskInfo.md#id)
- [path](BusinessDataBusinessListingsSearchLiveTaskInfo.md#path)
- [result](BusinessDataBusinessListingsSearchLiveTaskInfo.md#result)
- [result\_count](BusinessDataBusinessListingsSearchLiveTaskInfo.md#result_count)
- [status\_code](BusinessDataBusinessListingsSearchLiveTaskInfo.md#status_code)
- [status\_message](BusinessDataBusinessListingsSearchLiveTaskInfo.md#status_message)
- [time](BusinessDataBusinessListingsSearchLiveTaskInfo.md#time)

### Methods

- [init](BusinessDataBusinessListingsSearchLiveTaskInfo.md#init)
- [toJSON](BusinessDataBusinessListingsSearchLiveTaskInfo.md#tojson)
- [fromJS](BusinessDataBusinessListingsSearchLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataBusinessListingsSearchLiveTaskInfo**(`data?`): [`BusinessDataBusinessListingsSearchLiveTaskInfo`](BusinessDataBusinessListingsSearchLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataBusinessListingsSearchLiveTaskInfo`](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md) |

#### Returns

[`BusinessDataBusinessListingsSearchLiveTaskInfo`](BusinessDataBusinessListingsSearchLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:189458](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L189458)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[cost](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#cost)

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

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[data](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#data)

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

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[id](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[path](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`BusinessDataBusinessListingsSearchLiveResultInfo`](BusinessDataBusinessListingsSearchLiveResultInfo.md)[]

array of results

#### Implementation of

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[result](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#result)

#### Defined in

[main.ts:189454](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L189454)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[result_count](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#result_count)

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

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[status_code](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#status_code)

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

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[status_message](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataBusinessListingsSearchLiveTaskInfo](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md).[time](../interfaces/IBusinessDataBusinessListingsSearchLiveTaskInfo.md#time)

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

[main.ts:189462](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L189462)

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

[main.ts:189484](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L189484)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataBusinessListingsSearchLiveTaskInfo`](BusinessDataBusinessListingsSearchLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataBusinessListingsSearchLiveTaskInfo`](BusinessDataBusinessListingsSearchLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:189477](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L189477)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")