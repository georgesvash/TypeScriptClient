[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DomainAnalyticsTechnologiesLanguagesTaskInfo

# Class: DomainAnalyticsTechnologiesLanguagesTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`DomainAnalyticsTechnologiesLanguagesTaskInfo`**

## Implements

- [`IDomainAnalyticsTechnologiesLanguagesTaskInfo`](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#constructor)

### Properties

- [cost](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#cost)
- [data](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#data)
- [id](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#id)
- [path](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#path)
- [result](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#result)
- [result\_count](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#result_count)
- [status\_code](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#status_code)
- [status\_message](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#status_message)
- [time](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#time)

### Methods

- [init](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#init)
- [toJSON](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#tojson)
- [fromJS](DomainAnalyticsTechnologiesLanguagesTaskInfo.md#fromjs)

## Constructors

### constructor

• **new DomainAnalyticsTechnologiesLanguagesTaskInfo**(`data?`): [`DomainAnalyticsTechnologiesLanguagesTaskInfo`](DomainAnalyticsTechnologiesLanguagesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDomainAnalyticsTechnologiesLanguagesTaskInfo`](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md) |

#### Returns

[`DomainAnalyticsTechnologiesLanguagesTaskInfo`](DomainAnalyticsTechnologiesLanguagesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:71994](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71994)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[cost](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#cost)

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

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[data](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#data)

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

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[id](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[path](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`DomainAnalyticsTechnologiesLanguagesResultInfo`](DomainAnalyticsTechnologiesLanguagesResultInfo.md)[]

array of results

#### Implementation of

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[result](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#result)

#### Defined in

[main.ts:71990](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71990)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[result_count](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#result_count)

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

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[status_code](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#status_code)

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

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[status_message](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IDomainAnalyticsTechnologiesLanguagesTaskInfo](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md).[time](../interfaces/IDomainAnalyticsTechnologiesLanguagesTaskInfo.md#time)

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

[main.ts:71998](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L71998)

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

[main.ts:72020](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L72020)

___


### fromJS

▸ **fromJS**(`data`): [`DomainAnalyticsTechnologiesLanguagesTaskInfo`](DomainAnalyticsTechnologiesLanguagesTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DomainAnalyticsTechnologiesLanguagesTaskInfo`](DomainAnalyticsTechnologiesLanguagesTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:72013](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L72013)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")