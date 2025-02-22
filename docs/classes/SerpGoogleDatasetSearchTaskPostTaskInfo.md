[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleDatasetSearchTaskPostTaskInfo

# Class: SerpGoogleDatasetSearchTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleDatasetSearchTaskPostTaskInfo`**

## Implements

- [`ISerpGoogleDatasetSearchTaskPostTaskInfo`](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleDatasetSearchTaskPostTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleDatasetSearchTaskPostTaskInfo.md#cost)
- [data](SerpGoogleDatasetSearchTaskPostTaskInfo.md#data)
- [id](SerpGoogleDatasetSearchTaskPostTaskInfo.md#id)
- [path](SerpGoogleDatasetSearchTaskPostTaskInfo.md#path)
- [result](SerpGoogleDatasetSearchTaskPostTaskInfo.md#result)
- [result\_count](SerpGoogleDatasetSearchTaskPostTaskInfo.md#result_count)
- [status\_code](SerpGoogleDatasetSearchTaskPostTaskInfo.md#status_code)
- [status\_message](SerpGoogleDatasetSearchTaskPostTaskInfo.md#status_message)
- [time](SerpGoogleDatasetSearchTaskPostTaskInfo.md#time)

### Methods

- [init](SerpGoogleDatasetSearchTaskPostTaskInfo.md#init)
- [toJSON](SerpGoogleDatasetSearchTaskPostTaskInfo.md#tojson)
- [fromJS](SerpGoogleDatasetSearchTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleDatasetSearchTaskPostTaskInfo**(`data?`): [`SerpGoogleDatasetSearchTaskPostTaskInfo`](SerpGoogleDatasetSearchTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleDatasetSearchTaskPostTaskInfo`](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md) |

#### Returns

[`SerpGoogleDatasetSearchTaskPostTaskInfo`](SerpGoogleDatasetSearchTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:50039](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L50039)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[cost](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#cost)

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

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[data](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#data)

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

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[id](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[path](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#path)

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

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[result](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:50035](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L50035)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[result_count](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#result_count)

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

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[status_code](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#status_code)

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

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[status_message](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleDatasetSearchTaskPostTaskInfo](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md).[time](../interfaces/ISerpGoogleDatasetSearchTaskPostTaskInfo.md#time)

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

[main.ts:50043](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L50043)

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

[main.ts:50061](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L50061)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleDatasetSearchTaskPostTaskInfo`](SerpGoogleDatasetSearchTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleDatasetSearchTaskPostTaskInfo`](SerpGoogleDatasetSearchTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:50054](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L50054)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")