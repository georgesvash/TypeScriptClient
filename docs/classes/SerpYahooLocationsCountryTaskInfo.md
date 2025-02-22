[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpYahooLocationsCountryTaskInfo

# Class: SerpYahooLocationsCountryTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpYahooLocationsCountryTaskInfo`**

## Implements

- [`ISerpYahooLocationsCountryTaskInfo`](../interfaces/ISerpYahooLocationsCountryTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpYahooLocationsCountryTaskInfo.md#constructor)

### Properties

- [cost](SerpYahooLocationsCountryTaskInfo.md#cost)
- [data](SerpYahooLocationsCountryTaskInfo.md#data)
- [id](SerpYahooLocationsCountryTaskInfo.md#id)
- [path](SerpYahooLocationsCountryTaskInfo.md#path)
- [result](SerpYahooLocationsCountryTaskInfo.md#result)
- [result\_count](SerpYahooLocationsCountryTaskInfo.md#result_count)
- [status\_code](SerpYahooLocationsCountryTaskInfo.md#status_code)
- [status\_message](SerpYahooLocationsCountryTaskInfo.md#status_message)
- [time](SerpYahooLocationsCountryTaskInfo.md#time)

### Methods

- [init](SerpYahooLocationsCountryTaskInfo.md#init)
- [toJSON](SerpYahooLocationsCountryTaskInfo.md#tojson)
- [fromJS](SerpYahooLocationsCountryTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpYahooLocationsCountryTaskInfo**(`data?`): [`SerpYahooLocationsCountryTaskInfo`](SerpYahooLocationsCountryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpYahooLocationsCountryTaskInfo`](../interfaces/ISerpYahooLocationsCountryTaskInfo.md) |

#### Returns

[`SerpYahooLocationsCountryTaskInfo`](SerpYahooLocationsCountryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:62924](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62924)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[cost](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#cost)

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

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[data](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#data)

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

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[id](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[path](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpYahooLocationsCountryResultInfo`](SerpYahooLocationsCountryResultInfo.md)[]

array of results

#### Implementation of

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[result](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#result)

#### Defined in

[main.ts:62920](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62920)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[result_count](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#result_count)

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

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[status_code](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#status_code)

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

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[status_message](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpYahooLocationsCountryTaskInfo](../interfaces/ISerpYahooLocationsCountryTaskInfo.md).[time](../interfaces/ISerpYahooLocationsCountryTaskInfo.md#time)

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

[main.ts:62928](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62928)

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

[main.ts:62950](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62950)

___


### fromJS

▸ **fromJS**(`data`): [`SerpYahooLocationsCountryTaskInfo`](SerpYahooLocationsCountryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpYahooLocationsCountryTaskInfo`](SerpYahooLocationsCountryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:62943](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L62943)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")