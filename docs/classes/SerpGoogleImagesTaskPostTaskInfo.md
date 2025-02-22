[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / SerpGoogleImagesTaskPostTaskInfo

# Class: SerpGoogleImagesTaskPostTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`SerpGoogleImagesTaskPostTaskInfo`**

## Implements

- [`ISerpGoogleImagesTaskPostTaskInfo`](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](SerpGoogleImagesTaskPostTaskInfo.md#constructor)

### Properties

- [cost](SerpGoogleImagesTaskPostTaskInfo.md#cost)
- [data](SerpGoogleImagesTaskPostTaskInfo.md#data)
- [id](SerpGoogleImagesTaskPostTaskInfo.md#id)
- [path](SerpGoogleImagesTaskPostTaskInfo.md#path)
- [result](SerpGoogleImagesTaskPostTaskInfo.md#result)
- [result\_count](SerpGoogleImagesTaskPostTaskInfo.md#result_count)
- [status\_code](SerpGoogleImagesTaskPostTaskInfo.md#status_code)
- [status\_message](SerpGoogleImagesTaskPostTaskInfo.md#status_message)
- [time](SerpGoogleImagesTaskPostTaskInfo.md#time)

### Methods

- [init](SerpGoogleImagesTaskPostTaskInfo.md#init)
- [toJSON](SerpGoogleImagesTaskPostTaskInfo.md#tojson)
- [fromJS](SerpGoogleImagesTaskPostTaskInfo.md#fromjs)

## Constructors

### constructor

• **new SerpGoogleImagesTaskPostTaskInfo**(`data?`): [`SerpGoogleImagesTaskPostTaskInfo`](SerpGoogleImagesTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`ISerpGoogleImagesTaskPostTaskInfo`](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md) |

#### Returns

[`SerpGoogleImagesTaskPostTaskInfo`](SerpGoogleImagesTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:45573](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L45573)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[cost](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#cost)

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

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[data](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#data)

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

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[id](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[path](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#path)

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

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[result](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#result)

#### Defined in

[main.ts:45569](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L45569)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[result_count](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#result_count)

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

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[status_code](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#status_code)

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

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[status_message](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[ISerpGoogleImagesTaskPostTaskInfo](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md).[time](../interfaces/ISerpGoogleImagesTaskPostTaskInfo.md#time)

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

[main.ts:45577](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L45577)

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

[main.ts:45595](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L45595)

___


### fromJS

▸ **fromJS**(`data`): [`SerpGoogleImagesTaskPostTaskInfo`](SerpGoogleImagesTaskPostTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`SerpGoogleImagesTaskPostTaskInfo`](SerpGoogleImagesTaskPostTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:45588](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L45588)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")