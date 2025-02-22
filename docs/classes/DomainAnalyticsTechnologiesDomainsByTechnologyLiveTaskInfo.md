[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo

# Class: DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`**

## Implements

- [`IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#constructor)

### Properties

- [cost](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#cost)
- [data](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#data)
- [id](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#id)
- [path](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#path)
- [result](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#result)
- [result\_count](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#result_count)
- [status\_code](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#status_code)
- [status\_message](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#status_message)
- [time](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#time)

### Methods

- [init](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#init)
- [toJSON](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#tojson)
- [fromJS](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#fromjs)

## Constructors

### constructor

• **new DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo**(`data?`): [`DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md) |

#### Returns

[`DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:74512](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74512)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[cost](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#cost)

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

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[data](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#data)

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

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[id](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[path](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`DomainAnalyticsTechnologiesDomainsByTechnologyLiveResultInfo`](DomainAnalyticsTechnologiesDomainsByTechnologyLiveResultInfo.md)[]

array of results

#### Implementation of

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[result](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#result)

#### Defined in

[main.ts:74508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74508)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[result_count](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#result_count)

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

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[status_code](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#status_code)

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

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[status_message](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md).[time](../interfaces/IDomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md#time)

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

[main.ts:74516](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74516)

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

[main.ts:74538](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74538)

___


### fromJS

▸ **fromJS**(`data`): [`DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo`](DomainAnalyticsTechnologiesDomainsByTechnologyLiveTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:74531](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L74531)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")