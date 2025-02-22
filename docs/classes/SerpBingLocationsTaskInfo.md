[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBingLocationsTaskInfo

# Class: SerpBingLocationsTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpBingLocationsTaskInfo`**

## Implements

- [`ISerpBingLocationsTaskInfo`](../interfaces/ISerpBingLocationsTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBingLocationsTaskInfo.md#constructor)

### Properties

- [cost](SerpBingLocationsTaskInfo.md#cost)
- [data](SerpBingLocationsTaskInfo.md#data)
- [id](SerpBingLocationsTaskInfo.md#id)
- [path](SerpBingLocationsTaskInfo.md#path)
- [result](SerpBingLocationsTaskInfo.md#result)
- [result\_count](SerpBingLocationsTaskInfo.md#result_count)
- [status\_code](SerpBingLocationsTaskInfo.md#status_code)
- [status\_message](SerpBingLocationsTaskInfo.md#status_message)
- [time](SerpBingLocationsTaskInfo.md#time)

### Methods

- [init](SerpBingLocationsTaskInfo.md#init)
- [toJSON](SerpBingLocationsTaskInfo.md#tojson)
- [fromJS](SerpBingLocationsTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBingLocationsTaskInfo**(`data?`): [`SerpBingLocationsTaskInfo`](SerpBingLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBingLocationsTaskInfo`](../interfaces/ISerpBingLocationsTaskInfo.md) |

#### Returns

[`SerpBingLocationsTaskInfo`](SerpBingLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:53212](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L53212)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[cost](../interfaces/ISerpBingLocationsTaskInfo.md#cost)

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

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[data](../interfaces/ISerpBingLocationsTaskInfo.md#data)

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

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[id](../interfaces/ISerpBingLocationsTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[path](../interfaces/ISerpBingLocationsTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpBingLocationsResultInfo`](SerpBingLocationsResultInfo.md)[]

array of results

#### Implementation of

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[result](../interfaces/ISerpBingLocationsTaskInfo.md#result)

#### Defined in

[main.ts:53208](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L53208)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[result_count](../interfaces/ISerpBingLocationsTaskInfo.md#result_count)

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

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[status_code](../interfaces/ISerpBingLocationsTaskInfo.md#status_code)

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

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[status_message](../interfaces/ISerpBingLocationsTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpBingLocationsTaskInfo](../interfaces/ISerpBingLocationsTaskInfo.md).[time](../interfaces/ISerpBingLocationsTaskInfo.md#time)

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

[main.ts:53216](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L53216)

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

[main.ts:53238](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L53238)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBingLocationsTaskInfo`](SerpBingLocationsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBingLocationsTaskInfo`](SerpBingLocationsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:53231](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L53231)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")