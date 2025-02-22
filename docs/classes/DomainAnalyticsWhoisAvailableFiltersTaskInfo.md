[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DomainAnalyticsWhoisAvailableFiltersTaskInfo

# Class: DomainAnalyticsWhoisAvailableFiltersTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`DomainAnalyticsWhoisAvailableFiltersTaskInfo`**

## Implements

- [`IDomainAnalyticsWhoisAvailableFiltersTaskInfo`](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#constructor)

### Properties

- [cost](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#cost)
- [data](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#data)
- [id](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#id)
- [path](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#path)
- [result](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#result)
- [result\_count](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#result_count)
- [status\_code](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#status_code)
- [status\_message](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#status_message)
- [time](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#time)

### Methods

- [init](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#init)
- [toJSON](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#tojson)
- [fromJS](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md#fromjs)

## Constructors

### constructor

• **new DomainAnalyticsWhoisAvailableFiltersTaskInfo**(`data?`): [`DomainAnalyticsWhoisAvailableFiltersTaskInfo`](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDomainAnalyticsWhoisAvailableFiltersTaskInfo`](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md) |

#### Returns

[`DomainAnalyticsWhoisAvailableFiltersTaskInfo`](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:75473](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75473)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[cost](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#cost)

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

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[data](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#data)

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

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[id](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[path](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`DomainAnalyticsWhoisAvailableFiltersResultInfo`](DomainAnalyticsWhoisAvailableFiltersResultInfo.md)[]

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[result](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#result)

#### Defined in

[main.ts:75469](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75469)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[result_count](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#result_count)

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

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[status_code](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#status_code)

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

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[status_message](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IDomainAnalyticsWhoisAvailableFiltersTaskInfo](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md).[time](../interfaces/IDomainAnalyticsWhoisAvailableFiltersTaskInfo.md#time)

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

[main.ts:75477](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75477)

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

[main.ts:75499](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75499)

___


### fromJS

▸ **fromJS**(`data`): [`DomainAnalyticsWhoisAvailableFiltersTaskInfo`](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DomainAnalyticsWhoisAvailableFiltersTaskInfo`](DomainAnalyticsWhoisAvailableFiltersTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:75492](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L75492)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")