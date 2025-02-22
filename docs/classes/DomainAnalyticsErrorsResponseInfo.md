[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DomainAnalyticsErrorsResponseInfo

# Class: DomainAnalyticsErrorsResponseInfo

## Hierarchy

- [`BaseResponseInfo`](BaseResponseInfo.md)
  
  ↳ **`DomainAnalyticsErrorsResponseInfo`**

## Implements

- [`IDomainAnalyticsErrorsResponseInfo`](../interfaces/IDomainAnalyticsErrorsResponseInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DomainAnalyticsErrorsResponseInfo.md#constructor)

### Properties

- [cost](DomainAnalyticsErrorsResponseInfo.md#cost)
- [status\_code](DomainAnalyticsErrorsResponseInfo.md#status_code)
- [status\_message](DomainAnalyticsErrorsResponseInfo.md#status_message)
- [tasks](DomainAnalyticsErrorsResponseInfo.md#tasks)
- [tasks\_count](DomainAnalyticsErrorsResponseInfo.md#tasks_count)
- [tasks\_error](DomainAnalyticsErrorsResponseInfo.md#tasks_error)
- [time](DomainAnalyticsErrorsResponseInfo.md#time)
- [version](DomainAnalyticsErrorsResponseInfo.md#version)

### Methods

- [init](DomainAnalyticsErrorsResponseInfo.md#init)
- [toJSON](DomainAnalyticsErrorsResponseInfo.md#tojson)
- [fromJS](DomainAnalyticsErrorsResponseInfo.md#fromjs)

## Constructors

### constructor

• **new DomainAnalyticsErrorsResponseInfo**(`data?`): [`DomainAnalyticsErrorsResponseInfo`](DomainAnalyticsErrorsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDomainAnalyticsErrorsResponseInfo`](../interfaces/IDomainAnalyticsErrorsResponseInfo.md) |

#### Returns

[`DomainAnalyticsErrorsResponseInfo`](DomainAnalyticsErrorsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[constructor](BaseResponseInfo.md#constructor)

#### Defined in

[main.ts:71503](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71503)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[cost](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#cost)

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

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[status_code](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#status_code)

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

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[status_message](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#status_message)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[status_message](BaseResponseInfo.md#status_message)

#### Defined in

[main.ts:22506](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22506)

___


### tasks

• `Optional` **tasks**: [`DomainAnalyticsErrorsTaskInfo`](DomainAnalyticsErrorsTaskInfo.md)[]

array of tasks

#### Implementation of

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[tasks](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#tasks)

#### Defined in

[main.ts:71499](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71499)

___


### tasks\_count

• `Optional` **tasks\_count**: `number`

the number of tasks in the tasks array

#### Implementation of

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[tasks_count](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#tasks_count)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_count](BaseResponseInfo.md#tasks_count)

#### Defined in

[main.ts:22512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22512)

___


### tasks\_error

• `Optional` **tasks\_error**: `number`

the number of tasks in the tasks array returned with an error

#### Implementation of

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[tasks_error](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#tasks_error)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[tasks_error](BaseResponseInfo.md#tasks_error)

#### Defined in

[main.ts:22514](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22514)

___


### time

• `Optional` **time**: `string`

total execution time, seconds

#### Implementation of

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[time](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#time)

#### Inherited from

[BaseResponseInfo](BaseResponseInfo.md).[time](BaseResponseInfo.md#time)

#### Defined in

[main.ts:22508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22508)

___


### version

• `Optional` **version**: `string`

the current version of the API

#### Implementation of

[IDomainAnalyticsErrorsResponseInfo](../interfaces/IDomainAnalyticsErrorsResponseInfo.md).[version](../interfaces/IDomainAnalyticsErrorsResponseInfo.md#version)

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

[main.ts:71507](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71507)

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

[main.ts:71529](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71529)

___


### fromJS

▸ **fromJS**(`data`): [`DomainAnalyticsErrorsResponseInfo`](DomainAnalyticsErrorsResponseInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DomainAnalyticsErrorsResponseInfo`](DomainAnalyticsErrorsResponseInfo.md)

#### Overrides

[BaseResponseInfo](BaseResponseInfo.md).[fromJS](BaseResponseInfo.md#fromjs)

#### Defined in

[main.ts:71522](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71522)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")