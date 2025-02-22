[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleSearchByImageTaskPostTaskInfo

# Class: SerpGoogleSearchByImageTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleSearchByImageTaskPostTaskInfo`**

## Implements

- [`ISerpGoogleSearchByImageTaskPostTaskInfo`](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleSearchByImageTaskPostTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleSearchByImageTaskPostTaskInfo.md#cost)
- [data](SerpGoogleSearchByImageTaskPostTaskInfo.md#data)
- [id](SerpGoogleSearchByImageTaskPostTaskInfo.md#id)
- [path](SerpGoogleSearchByImageTaskPostTaskInfo.md#path)
- [result](SerpGoogleSearchByImageTaskPostTaskInfo.md#result)
- [result\_count](SerpGoogleSearchByImageTaskPostTaskInfo.md#result_count)
- [status\_code](SerpGoogleSearchByImageTaskPostTaskInfo.md#status_code)
- [status\_message](SerpGoogleSearchByImageTaskPostTaskInfo.md#status_message)
- [time](SerpGoogleSearchByImageTaskPostTaskInfo.md#time)

### Methods

- [init](SerpGoogleSearchByImageTaskPostTaskInfo.md#init)
- [toJSON](SerpGoogleSearchByImageTaskPostTaskInfo.md#tojson)
- [fromJS](SerpGoogleSearchByImageTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleSearchByImageTaskPostTaskInfo**(`data?`): [`SerpGoogleSearchByImageTaskPostTaskInfo`](SerpGoogleSearchByImageTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleSearchByImageTaskPostTaskInfo`](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md) |

#### Returns

[`SerpGoogleSearchByImageTaskPostTaskInfo`](SerpGoogleSearchByImageTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:47493](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L47493)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[cost](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#cost)

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

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[data](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#data)

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

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[id](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[path](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: `any`

array of results
in this case, the value will be null

#### Implementation of

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[result](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:47489](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L47489)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[result_count](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#result_count)

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

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[status_code](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#status_code)

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

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[status_message](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleSearchByImageTaskPostTaskInfo](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md).[time](../interfaces/ISerpGoogleSearchByImageTaskPostTaskInfo.md#time)

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

[main.ts:47497](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L47497)

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

[main.ts:47515](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L47515)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleSearchByImageTaskPostTaskInfo`](SerpGoogleSearchByImageTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleSearchByImageTaskPostTaskInfo`](SerpGoogleSearchByImageTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:47508](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L47508)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")