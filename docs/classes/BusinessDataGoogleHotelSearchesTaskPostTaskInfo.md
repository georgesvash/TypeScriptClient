[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleHotelSearchesTaskPostTaskInfo

# Class: BusinessDataGoogleHotelSearchesTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`BusinessDataGoogleHotelSearchesTaskPostTaskInfo`**

## Implements

- [`IBusinessDataGoogleHotelSearchesTaskPostTaskInfo`](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#constructor)

### Properties

- [cost](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#cost)
- [data](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#data)
- [id](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#id)
- [path](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#path)
- [result](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#result)
- [result\_count](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#result_count)
- [status\_code](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#status_code)
- [status\_message](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#status_message)
- [time](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#time)

### Methods

- [init](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#init)
- [toJSON](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#tojson)
- [fromJS](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleHotelSearchesTaskPostTaskInfo**(`data?`): [`BusinessDataGoogleHotelSearchesTaskPostTaskInfo`](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleHotelSearchesTaskPostTaskInfo`](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md) |

#### Returns

[`BusinessDataGoogleHotelSearchesTaskPostTaskInfo`](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:193103](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L193103)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[cost](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#cost)

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

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[data](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#data)

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

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[id](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[path](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#path)

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

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[result](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:193099](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L193099)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[result_count](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#result_count)

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

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[status_code](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#status_code)

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

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[status_message](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskPostTaskInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md).[time](../interfaces/IBusinessDataGoogleHotelSearchesTaskPostTaskInfo.md#time)

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

[main.ts:193107](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L193107)

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

[main.ts:193125](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L193125)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleHotelSearchesTaskPostTaskInfo`](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleHotelSearchesTaskPostTaskInfo`](BusinessDataGoogleHotelSearchesTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:193118](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L193118)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")