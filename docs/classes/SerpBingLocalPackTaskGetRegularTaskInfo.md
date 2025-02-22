[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpBingLocalPackTaskGetRegularTaskInfo

# Class: SerpBingLocalPackTaskGetRegularTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpBingLocalPackTaskGetRegularTaskInfo`**

## Implements

- [`ISerpBingLocalPackTaskGetRegularTaskInfo`](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpBingLocalPackTaskGetRegularTaskInfo.md#constructor)

### Properties

- [cost](SerpBingLocalPackTaskGetRegularTaskInfo.md#cost)
- [data](SerpBingLocalPackTaskGetRegularTaskInfo.md#data)
- [id](SerpBingLocalPackTaskGetRegularTaskInfo.md#id)
- [path](SerpBingLocalPackTaskGetRegularTaskInfo.md#path)
- [result](SerpBingLocalPackTaskGetRegularTaskInfo.md#result)
- [result\_count](SerpBingLocalPackTaskGetRegularTaskInfo.md#result_count)
- [status\_code](SerpBingLocalPackTaskGetRegularTaskInfo.md#status_code)
- [status\_message](SerpBingLocalPackTaskGetRegularTaskInfo.md#status_message)
- [time](SerpBingLocalPackTaskGetRegularTaskInfo.md#time)

### Methods

- [init](SerpBingLocalPackTaskGetRegularTaskInfo.md#init)
- [toJSON](SerpBingLocalPackTaskGetRegularTaskInfo.md#tojson)
- [fromJS](SerpBingLocalPackTaskGetRegularTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpBingLocalPackTaskGetRegularTaskInfo**(`data?`): [`SerpBingLocalPackTaskGetRegularTaskInfo`](SerpBingLocalPackTaskGetRegularTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpBingLocalPackTaskGetRegularTaskInfo`](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md) |

#### Returns

[`SerpBingLocalPackTaskGetRegularTaskInfo`](SerpBingLocalPackTaskGetRegularTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:56370](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56370)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[cost](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#cost)

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

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[data](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#data)

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

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[id](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[path](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`SerpBingLocalPackTaskGetRegularResultInfo`](SerpBingLocalPackTaskGetRegularResultInfo.md)[]

array of results

#### Implementation of

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[result](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#result)

#### Defined in

[main.ts:56366](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56366)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[result_count](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#result_count)

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

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[status_code](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#status_code)

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

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[status_message](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpBingLocalPackTaskGetRegularTaskInfo](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md).[time](../interfaces/ISerpBingLocalPackTaskGetRegularTaskInfo.md#time)

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

[main.ts:56374](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56374)

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

[main.ts:56396](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56396)

___


### fromJS

▸ **fromJS**(`data`): [`SerpBingLocalPackTaskGetRegularTaskInfo`](SerpBingLocalPackTaskGetRegularTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpBingLocalPackTaskGetRegularTaskInfo`](SerpBingLocalPackTaskGetRegularTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:56389](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L56389)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")