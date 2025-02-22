[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BusinessDataGoogleLocationsCountryResponseInfo

# Class: BusinessDataGoogleLocationsCountryResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`BusinessDataGoogleLocationsCountryResponseInfo`**

## Implements

- [`IBusinessDataGoogleLocationsCountryResponseInfo`](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BusinessDataGoogleLocationsCountryResponseInfo.md#constructor)

### Properties

- [cost](BusinessDataGoogleLocationsCountryResponseInfo.md#cost)
- [status\_code](BusinessDataGoogleLocationsCountryResponseInfo.md#status_code)
- [status\_message](BusinessDataGoogleLocationsCountryResponseInfo.md#status_message)
- [tasks](BusinessDataGoogleLocationsCountryResponseInfo.md#tasks)
- [tasks\_count](BusinessDataGoogleLocationsCountryResponseInfo.md#tasks_count)
- [tasks\_error](BusinessDataGoogleLocationsCountryResponseInfo.md#tasks_error)
- [time](BusinessDataGoogleLocationsCountryResponseInfo.md#time)
- [version](BusinessDataGoogleLocationsCountryResponseInfo.md#version)

### Methods

- [init](BusinessDataGoogleLocationsCountryResponseInfo.md#init)
- [toJSON](BusinessDataGoogleLocationsCountryResponseInfo.md#tojson)
- [fromJS](BusinessDataGoogleLocationsCountryResponseInfo.md#fromjs)

## Constructors

### constructor

• **new BusinessDataGoogleLocationsCountryResponseInfo**(`data?`): [`BusinessDataGoogleLocationsCountryResponseInfo`](BusinessDataGoogleLocationsCountryResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBusinessDataGoogleLocationsCountryResponseInfo`](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md) |

#### Returns

[`BusinessDataGoogleLocationsCountryResponseInfo`](BusinessDataGoogleLocationsCountryResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:190503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L190503)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[cost](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#cost)

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

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[status_code](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#status_code)

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

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[status_message](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`BusinessDataGoogleLocationsCountryTaskInfo`](BusinessDataGoogleLocationsCountryTaskInfo.md)[]

array of tasks

#### Implementation of

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[tasks](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#tasks)

#### Defined in

[main.ts:190499](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L190499)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[tasks_count](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[tasks_error](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[time](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IBusinessDataGoogleLocationsCountryResponseInfo](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md).[version](../interfaces/IBusinessDataGoogleLocationsCountryResponseInfo.md#version)

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

[main.ts:190507](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L190507)

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

[main.ts:190529](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L190529)

___


### fromJS

▸ **fromJS**(`data`): [`BusinessDataGoogleLocationsCountryResponseInfo`](BusinessDataGoogleLocationsCountryResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BusinessDataGoogleLocationsCountryResponseInfo`](BusinessDataGoogleLocationsCountryResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:190522](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L190522)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")