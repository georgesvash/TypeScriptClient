[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageLighthouseVersionsTaskInfo

# Class: OnPageLighthouseVersionsTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`OnPageLighthouseVersionsTaskInfo`**

## Implements

- [`IOnPageLighthouseVersionsTaskInfo`](../interfaces/IOnPageLighthouseVersionsTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageLighthouseVersionsTaskInfo.md#constructor)

### Properties

- [cost](OnPageLighthouseVersionsTaskInfo.md#cost)
- [data](OnPageLighthouseVersionsTaskInfo.md#data)
- [id](OnPageLighthouseVersionsTaskInfo.md#id)
- [path](OnPageLighthouseVersionsTaskInfo.md#path)
- [result](OnPageLighthouseVersionsTaskInfo.md#result)
- [result\_count](OnPageLighthouseVersionsTaskInfo.md#result_count)
- [status\_code](OnPageLighthouseVersionsTaskInfo.md#status_code)
- [status\_message](OnPageLighthouseVersionsTaskInfo.md#status_message)
- [time](OnPageLighthouseVersionsTaskInfo.md#time)

### Methods

- [init](OnPageLighthouseVersionsTaskInfo.md#init)
- [toJSON](OnPageLighthouseVersionsTaskInfo.md#tojson)
- [fromJS](OnPageLighthouseVersionsTaskInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageLighthouseVersionsTaskInfo**(`data?`): [`OnPageLighthouseVersionsTaskInfo`](OnPageLighthouseVersionsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageLighthouseVersionsTaskInfo`](../interfaces/IOnPageLighthouseVersionsTaskInfo.md) |

#### Returns

[`OnPageLighthouseVersionsTaskInfo`](OnPageLighthouseVersionsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:153967](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L153967)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[cost](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#cost)

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

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[data](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#data)

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

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[id](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[path](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`OnPageLighthouseVersionsResultInfo`](OnPageLighthouseVersionsResultInfo.md)[]

array of results

#### Implementation of

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[result](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#result)

#### Defined in

[main.ts:153963](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L153963)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[result_count](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#result_count)

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

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[status_code](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#status_code)

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

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[status_message](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IOnPageLighthouseVersionsTaskInfo](../interfaces/IOnPageLighthouseVersionsTaskInfo.md).[time](../interfaces/IOnPageLighthouseVersionsTaskInfo.md#time)

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

[main.ts:153971](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L153971)

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

[main.ts:153993](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L153993)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageLighthouseVersionsTaskInfo`](OnPageLighthouseVersionsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageLighthouseVersionsTaskInfo`](OnPageLighthouseVersionsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:153986](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L153986)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")