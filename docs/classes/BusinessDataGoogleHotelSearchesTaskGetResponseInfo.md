[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleHotelSearchesTaskGetResponseInfo

# Class: BusinessDataGoogleHotelSearchesTaskGetResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataGoogleHotelSearchesTaskGetResponseInfo`**

## Implements

- [`IBusinessDataGoogleHotelSearchesTaskGetResponseInfo`](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#cost)
- [status\_code](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#status_code)
- [status\_message](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#status_message)
- [tasks](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tasks)
- [tasks\_count](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tasks_error)
- [time](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#time)
- [version](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#version)

### Methods

- [init](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#init)
- [toJSON](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tojson)
- [fromJS](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleHotelSearchesTaskGetResponseInfo**(`data?`): [`BusinessDataGoogleHotelSearchesTaskGetResponseInfo`](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleHotelSearchesTaskGetResponseInfo`](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md) |

#### Returns

[`BusinessDataGoogleHotelSearchesTaskGetResponseInfo`](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:194091](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194091)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[cost](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#cost)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[cost](BaseResponseInfo.md#cost)

#### Defined in

[main.ts:22510](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22510)

___


### status\_code

• `Optional` **status\_code**: `number`

general status code
you can find the full list of the response codes here

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[status_code](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#status_code)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_code](BaseResponseInfo.md#status_code)

#### Defined in

[main.ts:22503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22503)

___


### status\_message

• `Optional` **status\_message**: `string`

general informational message
you can find the full list of general informational messages here

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[status_message](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataGoogleHotelSearchesTaskGetTaskInfo`](BusinessDataGoogleHotelSearchesTaskGetTaskInfo.md)[]

array of tasks

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[tasks](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tasks)

#### Defined in

[main.ts:194087](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194087)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[tasks_count](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[tasks_error](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[time](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataGoogleHotelSearchesTaskGetResponseInfo](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md).[version](../interfaces/IBusinessDataGoogleHotelSearchesTaskGetResponseInfo.md#version)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[version](BaseResponseInfo.md#version)

#### Defined in

[main.ts:22500](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22500)

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

[BaseResponseInfo](BaseResponseInfo.md).[init](BaseResponseInfo.md#init)

#### Defined in

[main.ts:194095](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194095)

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

[BaseResponseInfo](BaseResponseInfo.md).[toJSON](BaseResponseInfo.md#tojson)

#### Defined in

[main.ts:194117](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194117)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleHotelSearchesTaskGetResponseInfo`](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleHotelSearchesTaskGetResponseInfo`](BusinessDataGoogleHotelSearchesTaskGetResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:194110](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L194110)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")