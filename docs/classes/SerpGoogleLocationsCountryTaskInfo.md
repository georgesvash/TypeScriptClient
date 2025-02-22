[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleLocationsCountryTaskInfo

# Class: SerpGoogleLocationsCountryTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleLocationsCountryTaskInfo`**

## Implements

- [`ISerpGoogleLocationsCountryTaskInfo`](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleLocationsCountryTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleLocationsCountryTaskInfo.md#cost)
- [data](SerpGoogleLocationsCountryTaskInfo.md#data)
- [id](SerpGoogleLocationsCountryTaskInfo.md#id)
- [path](SerpGoogleLocationsCountryTaskInfo.md#path)
- [result](SerpGoogleLocationsCountryTaskInfo.md#result)
- [result\_count](SerpGoogleLocationsCountryTaskInfo.md#result_count)
- [status\_code](SerpGoogleLocationsCountryTaskInfo.md#status_code)
- [status\_message](SerpGoogleLocationsCountryTaskInfo.md#status_message)
- [time](SerpGoogleLocationsCountryTaskInfo.md#time)

### Methods

- [init](SerpGoogleLocationsCountryTaskInfo.md#init)
- [toJSON](SerpGoogleLocationsCountryTaskInfo.md#tojson)
- [fromJS](SerpGoogleLocationsCountryTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleLocationsCountryTaskInfo**(`data?`): [`SerpGoogleLocationsCountryTaskInfo`](SerpGoogleLocationsCountryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleLocationsCountryTaskInfo`](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md) |

#### Returns

[`SerpGoogleLocationsCountryTaskInfo`](SerpGoogleLocationsCountryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:24350](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L24350)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[cost](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#cost)

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

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[data](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#data)

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

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[id](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[path](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpGoogleLocationsCountryResultInfo`](SerpGoogleLocationsCountryResultInfo.md)[]

array of results

#### Implementation of

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[result](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#result)

#### Defined in

[main.ts:24346](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L24346)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[result_count](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#result_count)

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

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[status_code](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#status_code)

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

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[status_message](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleLocationsCountryTaskInfo](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md).[time](../interfaces/ISerpGoogleLocationsCountryTaskInfo.md#time)

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

[main.ts:24354](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L24354)

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

[main.ts:24376](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L24376)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleLocationsCountryTaskInfo`](SerpGoogleLocationsCountryTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleLocationsCountryTaskInfo`](SerpGoogleLocationsCountryTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:24369](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L24369)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")