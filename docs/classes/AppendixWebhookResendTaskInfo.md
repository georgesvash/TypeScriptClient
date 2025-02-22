[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / AppendixWebhookResendTaskInfo

# Class: AppendixWebhookResendTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`AppendixWebhookResendTaskInfo`**

## Implements

- [`IAppendixWebhookResendTaskInfo`](../interfaces/IAppendixWebhookResendTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](AppendixWebhookResendTaskInfo.md#constructor)

### Properties

- [cost](AppendixWebhookResendTaskInfo.md#cost)
- [data](AppendixWebhookResendTaskInfo.md#data)
- [id](AppendixWebhookResendTaskInfo.md#id)
- [path](AppendixWebhookResendTaskInfo.md#path)
- [result](AppendixWebhookResendTaskInfo.md#result)
- [result\_count](AppendixWebhookResendTaskInfo.md#result_count)
- [status\_code](AppendixWebhookResendTaskInfo.md#status_code)
- [status\_message](AppendixWebhookResendTaskInfo.md#status_message)
- [time](AppendixWebhookResendTaskInfo.md#time)

### Methods

- [init](AppendixWebhookResendTaskInfo.md#init)
- [toJSON](AppendixWebhookResendTaskInfo.md#tojson)
- [fromJS](AppendixWebhookResendTaskInfo.md#fromjs)

## Constructors

### constructor

• **new AppendixWebhookResendTaskInfo**(`data?`): [`AppendixWebhookResendTaskInfo`](AppendixWebhookResendTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IAppendixWebhookResendTaskInfo`](../interfaces/IAppendixWebhookResendTaskInfo.md) |

#### Returns

[`AppendixWebhookResendTaskInfo`](AppendixWebhookResendTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:212578](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212578)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[cost](../interfaces/IAppendixWebhookResendTaskInfo.md#cost)

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

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[data](../interfaces/IAppendixWebhookResendTaskInfo.md#data)

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

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[id](../interfaces/IAppendixWebhookResendTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[path](../interfaces/IAppendixWebhookResendTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: `any`

array of results
the value of this array is always null;
you can get the results by the preferred method of results delivery (pingback or postback) you specified when setting a task

#### Implementation of

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[result](../interfaces/IAppendixWebhookResendTaskInfo.md#result)

#### Defined in

[main.ts:212574](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212574)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[result_count](../interfaces/IAppendixWebhookResendTaskInfo.md#result_count)

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

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[status_code](../interfaces/IAppendixWebhookResendTaskInfo.md#status_code)

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

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[status_message](../interfaces/IAppendixWebhookResendTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IAppendixWebhookResendTaskInfo](../interfaces/IAppendixWebhookResendTaskInfo.md).[time](../interfaces/IAppendixWebhookResendTaskInfo.md#time)

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

[main.ts:212582](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212582)

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

[main.ts:212600](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212600)

___


### fromJS

▸ **fromJS**(`data`): [`AppendixWebhookResendTaskInfo`](AppendixWebhookResendTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`AppendixWebhookResendTaskInfo`](AppendixWebhookResendTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:212593](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L212593)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")