[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageLighthouseTaskGetJsonTaskInfo

# Class: OnPageLighthouseTaskGetJsonTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`OnPageLighthouseTaskGetJsonTaskInfo`**

## Implements

- [`IOnPageLighthouseTaskGetJsonTaskInfo`](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageLighthouseTaskGetJsonTaskInfo.md#constructor)

### Properties

- [cost](OnPageLighthouseTaskGetJsonTaskInfo.md#cost)
- [data](OnPageLighthouseTaskGetJsonTaskInfo.md#data)
- [id](OnPageLighthouseTaskGetJsonTaskInfo.md#id)
- [path](OnPageLighthouseTaskGetJsonTaskInfo.md#path)
- [result](OnPageLighthouseTaskGetJsonTaskInfo.md#result)
- [result\_count](OnPageLighthouseTaskGetJsonTaskInfo.md#result_count)
- [status\_code](OnPageLighthouseTaskGetJsonTaskInfo.md#status_code)
- [status\_message](OnPageLighthouseTaskGetJsonTaskInfo.md#status_message)
- [time](OnPageLighthouseTaskGetJsonTaskInfo.md#time)

### Methods

- [init](OnPageLighthouseTaskGetJsonTaskInfo.md#init)
- [toJSON](OnPageLighthouseTaskGetJsonTaskInfo.md#tojson)
- [fromJS](OnPageLighthouseTaskGetJsonTaskInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageLighthouseTaskGetJsonTaskInfo**(`data?`): [`OnPageLighthouseTaskGetJsonTaskInfo`](OnPageLighthouseTaskGetJsonTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageLighthouseTaskGetJsonTaskInfo`](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md) |

#### Returns

[`OnPageLighthouseTaskGetJsonTaskInfo`](OnPageLighthouseTaskGetJsonTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:154597](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154597)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[cost](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#cost)

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

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[data](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#data)

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

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[id](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[path](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: \{ `[key: string]`: `any`;  }[]

results of Lighthouse audit
this array will include data according to the parameters specified in the POST request;
description of the fields in the result array is available in the official documentation

#### Implementation of

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[result](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#result)

#### Defined in

[main.ts:154593](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154593)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[result_count](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#result_count)

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

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[status_code](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#status_code)

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

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[status_message](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IOnPageLighthouseTaskGetJsonTaskInfo](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md).[time](../interfaces/IOnPageLighthouseTaskGetJsonTaskInfo.md#time)

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

[main.ts:154601](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154601)

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

[main.ts:154623](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154623)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageLighthouseTaskGetJsonTaskInfo`](OnPageLighthouseTaskGetJsonTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageLighthouseTaskGetJsonTaskInfo`](OnPageLighthouseTaskGetJsonTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:154616](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L154616)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")