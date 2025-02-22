[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpSeznamLocationsCountryTaskInfo

# Class: SerpSeznamLocationsCountryTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpSeznamLocationsCountryTaskInfo`**

## Implements

- [`ISerpSeznamLocationsCountryTaskInfo`](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpSeznamLocationsCountryTaskInfo.md#constructor)

### Properties

- [cost](SerpSeznamLocationsCountryTaskInfo.md#cost)
- [data](SerpSeznamLocationsCountryTaskInfo.md#data)
- [id](SerpSeznamLocationsCountryTaskInfo.md#id)
- [path](SerpSeznamLocationsCountryTaskInfo.md#path)
- [result](SerpSeznamLocationsCountryTaskInfo.md#result)
- [result\_count](SerpSeznamLocationsCountryTaskInfo.md#result_count)
- [status\_code](SerpSeznamLocationsCountryTaskInfo.md#status_code)
- [status\_message](SerpSeznamLocationsCountryTaskInfo.md#status_message)
- [time](SerpSeznamLocationsCountryTaskInfo.md#time)

### Methods

- [init](SerpSeznamLocationsCountryTaskInfo.md#init)
- [toJSON](SerpSeznamLocationsCountryTaskInfo.md#tojson)
- [fromJS](SerpSeznamLocationsCountryTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpSeznamLocationsCountryTaskInfo**(`data?`): [`SerpSeznamLocationsCountryTaskInfo`](SerpSeznamLocationsCountryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpSeznamLocationsCountryTaskInfo`](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md) |

#### Returns

[`SerpSeznamLocationsCountryTaskInfo`](SerpSeznamLocationsCountryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:69024](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69024)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[cost](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#cost)

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

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[data](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#data)

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

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[id](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[path](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpSeznamLocationsCountryResultInfo`](SerpSeznamLocationsCountryResultInfo.md)[]

array of results

#### Implementation of

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[result](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#result)

#### Defined in

[main.ts:69020](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69020)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[result_count](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#result_count)

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

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[status_code](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#status_code)

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

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[status_message](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpSeznamLocationsCountryTaskInfo](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md).[time](../interfaces/ISerpSeznamLocationsCountryTaskInfo.md#time)

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

[main.ts:69028](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69028)

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

[main.ts:69050](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69050)

___


### fromJS

▸ **fromJS**(`data`): [`SerpSeznamLocationsCountryTaskInfo`](SerpSeznamLocationsCountryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpSeznamLocationsCountryTaskInfo`](SerpSeznamLocationsCountryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:69043](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L69043)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")