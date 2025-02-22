[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / OnPageRedirectChainsTaskInfo

# Class: OnPageRedirectChainsTaskInfo

## Hierarchy

- [`BaseResponseTaskInfo`](BaseResponseTaskInfo.md)
  
  ↳ **`OnPageRedirectChainsTaskInfo`**

## Implements

- [`IOnPageRedirectChainsTaskInfo`](../interfaces/IOnPageRedirectChainsTaskInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](OnPageRedirectChainsTaskInfo.md#constructor)

### Properties

- [cost](OnPageRedirectChainsTaskInfo.md#cost)
- [data](OnPageRedirectChainsTaskInfo.md#data)
- [id](OnPageRedirectChainsTaskInfo.md#id)
- [path](OnPageRedirectChainsTaskInfo.md#path)
- [result](OnPageRedirectChainsTaskInfo.md#result)
- [result\_count](OnPageRedirectChainsTaskInfo.md#result_count)
- [status\_code](OnPageRedirectChainsTaskInfo.md#status_code)
- [status\_message](OnPageRedirectChainsTaskInfo.md#status_message)
- [time](OnPageRedirectChainsTaskInfo.md#time)

### Methods

- [init](OnPageRedirectChainsTaskInfo.md#init)
- [toJSON](OnPageRedirectChainsTaskInfo.md#tojson)
- [fromJS](OnPageRedirectChainsTaskInfo.md#fromjs)

## Constructors

### constructor

• **new OnPageRedirectChainsTaskInfo**(`data?`): [`OnPageRedirectChainsTaskInfo`](OnPageRedirectChainsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IOnPageRedirectChainsTaskInfo`](../interfaces/IOnPageRedirectChainsTaskInfo.md) |

#### Returns

[`OnPageRedirectChainsTaskInfo`](OnPageRedirectChainsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[constructor](BaseResponseTaskInfo.md#constructor)

#### Defined in

[main.ts:149149](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149149)

## Properties

### cost

• `Optional` **cost**: `number`

total tasks cost, USD

#### Implementation of

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[cost](../interfaces/IOnPageRedirectChainsTaskInfo.md#cost)

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

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[data](../interfaces/IOnPageRedirectChainsTaskInfo.md#data)

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

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[id](../interfaces/IOnPageRedirectChainsTaskInfo.md#id)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[id](BaseResponseTaskInfo.md#id)

#### Defined in

[main.ts:22591](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22591)

___


### path

• `Optional` **path**: `string`[]

URL path

#### Implementation of

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[path](../interfaces/IOnPageRedirectChainsTaskInfo.md#path)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[path](BaseResponseTaskInfo.md#path)

#### Defined in

[main.ts:22606](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22606)

___


### result

• `Optional` **result**: [`OnPageRedirectChainsResultInfo`](OnPageRedirectChainsResultInfo.md)[]

array of results

#### Implementation of

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[result](../interfaces/IOnPageRedirectChainsTaskInfo.md#result)

#### Defined in

[main.ts:149145](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149145)

___


### result\_count

• `Optional` **result\_count**: `number`

number of elements in the result array

#### Implementation of

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[result_count](../interfaces/IOnPageRedirectChainsTaskInfo.md#result_count)

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

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[status_code](../interfaces/IOnPageRedirectChainsTaskInfo.md#status_code)

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

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[status_message](../interfaces/IOnPageRedirectChainsTaskInfo.md#status_message)

#### Inherited from

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[status_message](BaseResponseTaskInfo.md#status_message)

#### Defined in

[main.ts:22598](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L22598)

___


### time

• `Optional` **time**: `string`

execution time, seconds

#### Implementation of

[IOnPageRedirectChainsTaskInfo](../interfaces/IOnPageRedirectChainsTaskInfo.md).[time](../interfaces/IOnPageRedirectChainsTaskInfo.md#time)

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

[main.ts:149153](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149153)

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

[main.ts:149175](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149175)

___


### fromJS

▸ **fromJS**(`data`): [`OnPageRedirectChainsTaskInfo`](OnPageRedirectChainsTaskInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`OnPageRedirectChainsTaskInfo`](OnPageRedirectChainsTaskInfo.md)

#### Overrides

[BaseResponseTaskInfo](BaseResponseTaskInfo.md).[fromJS](BaseResponseTaskInfo.md#fromjs)

#### Defined in

[main.ts:149168](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149168)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")