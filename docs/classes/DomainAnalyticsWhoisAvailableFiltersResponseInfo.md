[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DomainAnalyticsWhoisAvailableFiltersResponseInfo

# Class: DomainAnalyticsWhoisAvailableFiltersResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`DomainAnalyticsWhoisAvailableFiltersResponseInfo`**

## Implements

- [`IDomainAnalyticsWhoisAvailableFiltersResponseInfo`](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#constructor)

### Properties

- [cost](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#cost)
- [status\_code](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#status_code)
- [status\_message](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#status_message)
- [tasks](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tasks)
- [tasks\_count](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tasks_count)
- [tasks\_error](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tasks_error)
- [time](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#time)
- [version](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#version)

### Methods

- [init](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#init)
- [toJSON](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tojson)
- [fromJS](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md#fromjs)

## Constructors

### constructor

• **new DomainAnalyticsWhoisAvailableFiltersResponseInfo**(`data?`): [`DomainAnalyticsWhoisAvailableFiltersResponseInfo`](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDomainAnalyticsWhoisAvailableFiltersResponseInfo`](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md) |

#### Returns

[`DomainAnalyticsWhoisAvailableFiltersResponseInfo`](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:75526](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75526)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[cost](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#cost)

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

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[status_code](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#status_code)

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

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[status_message](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`DomainAnalyticsWhoisAvailableFiltersTaskInfo`](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md)[]

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[tasks](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tasks)

#### Defined in

[main.ts:75522](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75522)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[tasks_count](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[tasks_error](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[time](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersResponseInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md).[version](../interfaces/IDomainAnalyticsWhoisAvailableFiltersResponseInfo.md#version)

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

[main.ts:75530](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75530)

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

[main.ts:75552](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75552)

___


### fromJS

▸ **fromJS**(`data`): [`DomainAnalyticsWhoisAvailableFiltersResponseInfo`](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DomainAnalyticsWhoisAvailableFiltersResponseInfo`](DomainAnalyticsWhoisAvailableFiltersResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:75545](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75545)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")