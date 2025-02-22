[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageWaterfallTaskInfo

# Class: OnPageWaterfallTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`OnPageWaterfallTaskInfo`**

## Implements

- [`IOnPageWaterfallTaskInfo`](../interfaces/IOnPageWaterfallTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageWaterfallTaskInfo.md#constructor)

### Properties

- [cost](OnPageWaterfallTaskInfo.md#cost)
- [data](OnPageWaterfallTaskInfo.md#data)
- [id](OnPageWaterfallTaskInfo.md#id)
- [path](OnPageWaterfallTaskInfo.md#path)
- [result](OnPageWaterfallTaskInfo.md#result)
- [result\_count](OnPageWaterfallTaskInfo.md#result_count)
- [status\_code](OnPageWaterfallTaskInfo.md#status_code)
- [status\_message](OnPageWaterfallTaskInfo.md#status_message)
- [time](OnPageWaterfallTaskInfo.md#time)

### Methods

- [init](OnPageWaterfallTaskInfo.md#init)
- [toJSON](OnPageWaterfallTaskInfo.md#tojson)
- [fromJS](OnPageWaterfallTaskInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageWaterfallTaskInfo**(`data?`): [`OnPageWaterfallTaskInfo`](OnPageWaterfallTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageWaterfallTaskInfo`](../interfaces/IOnPageWaterfallTaskInfo.md) |

#### Returns

[`OnPageWaterfallTaskInfo`](OnPageWaterfallTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:149935](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149935)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[cost](../interfaces/IOnPageWaterfallTaskInfo.md#cost)

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

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[data](../interfaces/IOnPageWaterfallTaskInfo.md#data)

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

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[id](../interfaces/IOnPageWaterfallTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[path](../interfaces/IOnPageWaterfallTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`OnPageWaterfallResultInfo`](OnPageWaterfallResultInfo.md)[]

array of results

#### Implementation of

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[result](../interfaces/IOnPageWaterfallTaskInfo.md#result)

#### Defined in

[main.ts:149931](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149931)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[result_count](../interfaces/IOnPageWaterfallTaskInfo.md#result_count)

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

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[status_code](../interfaces/IOnPageWaterfallTaskInfo.md#status_code)

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

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[status_message](../interfaces/IOnPageWaterfallTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IOnPageWaterfallTaskInfo](../interfaces/IOnPageWaterfallTaskInfo.md).[time](../interfaces/IOnPageWaterfallTaskInfo.md#time)

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

[main.ts:149939](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149939)

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

[main.ts:149961](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149961)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageWaterfallTaskInfo`](OnPageWaterfallTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageWaterfallTaskInfo`](OnPageWaterfallTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:149954](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149954)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")